# NoPrivacyIndicatorPadding
Remove Status Bar Privacy Indicator Padding On PHH-AOSP Based ROMs
### What's the "Privacy Indicator"?
With Android 12, Google added an indicator that lets users know when the phone's camera or microphone is being used by an app. The indicator appears in the form of a tiny green dot at the top-right corner of the display and is activated when an app accesses the camera/mic.
### What does this module do?
For the green dot to show properly, there needs to be space in the top-right corner and therefore there's padding applied to elements on the status bar. This might cause issue on some devices running PHH GSIs and the green dot might not show up at all, but the padding will still be visible. This module removes the padding using an overlay.