# xDrip-WatchMaker
This walk-through is intended to help you connect xDrip+ to your Tizen (Samsung) or WearOS (Android Wear) smart watch. After completing this walk-through, you will be able to create your own custom watch faces that integrate your blood glucose (BG) readings, insulin on-board (IOB), and more.

If you find this useful, [buy me a coffee](https://www.buymeacoffee.com/jdanl89) to show your gratitude!

If you have any issues or suggestions, please check the [issues](https://github.com/jdanl89/xDrip-WatchMaker/issues) section to see if anyone has had the same issue, and if not, feel free to add your issue & I'll get back to you.

All of these instructions were created by walking through the process on my Pixel 4. The experience on your phone may differ slightly.

## Download apps from Google Play Store onto Android phone (Approximate price after tax as of 12/22/2020)
[WatchMaker Premium](https://play.google.com/store/apps/details?id=slide.watchFrenzy) ($8.55) - Create/download custom watch faces

[Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) ($3.73) - Run scheduled tasks on your phone (for transferring data to your watch face)

[AutoApps](https://play.google.com/store/apps/details?id=com.joaomgcd.autoappshub&hl=en_US&gl=US) - Connects AutoTools to Tasker

## Download AutoTools from wiwthin the AutoApps application 
Once AutoApps is downloaded, click on AutoTools. This will send you to download AutoTools and connect it to Tasker.

[AutoTools](https://play.google.com/store/apps/details?id=com.joaomgcd.autotools) ($3.19) - Retrieve information from xDrip+ to utilize in Tasker

## Download apps from the app store on your phone
WatchMaker Companion ($3.15)

## Grant Permissions to the downloaded applications
WatchMaker, Tasker, AutoApps and AutoTools musts be given special permission to run in the background.

Go to: Settings > Apps and Notifications > Special App Access

The following is a list of special privileges and the apps they must be granted to:

- Device Admin App
  - Tasker
  
- Display Over Other Apps
  - AutoTools
  - Tasker

- Do Not Disturb Access
  - Tasker
  
- Notification Access
  - Tasker

- Unrestricted Data
  - AutoApps
  - AutoTools
  - Tasker
  - WatchMaker

- Usage Acces
