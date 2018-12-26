#### Bug fixes:
* `visitorActivity`: Use of _**downloadUri**_ instead of _**filePath**_ of `storageReference` of the photos stored in Firebase to facilitate display of photos on Admin end.
* `adminActivity`: Registration/Unregistration of `refEventListener` on `onStart()` and `onStop()` respectively, to prevent duplication of visitorList data on restart of `adminActivity`

( Sorry to not include Unit Tests. I was trying to test individual activities with their seperate Test classes but somehow, `AndroidJUnitRunner` dependencies were not working even after being downloaded. AndroidX dependencies brought same results.)
