# Android Common Issues & Solution

## 1) Android Adb connection error

The best and working solution is:
  1. Close Android Studio
  2. Open task manager
  3. Kill the process adb.exe
  4. Open android studio again
  5. Problem solved

You can see all the status using cmd. Most of the time adb's home directory ais also available in own PC home director. Such as
'C:\Users\USER_NAME\AppData\Local\Android\Sdk\platform-tools\adb.exe start-server'

->What you have to do is first check the availability of adb. Just type and enter adb service OR adb in your cmd
->Then you can see adb version, where it's installed and global option and much more info. If those info doesn't appear you should install Android Studio correctly.
->Then you can kill the adb server and start the adb serveer

  1.to kill--->> adb kill-server
  
  2.to start-->> adb start-server
  
  3. All done



