In General: 

1) Put 'Superpowered' folder in the same directory as the SuperpoweredExamples_Android repo

2) Build -> Build Bundles / APKs -> Build APK

3) Deleted 'desktop.cfg' file from numerous directories to get anything to run


SuperpoweredCrossExample
-Crashes:
	-Output:
03/31 16:15:17: Launching app
$ adb shell am start -n "com.superpowered.crossexample/com.superpowered.crossexample.MainActivity" -a android.intent.action.MAIN -c android.intent.category.LAUNCHER
Client not ready yet..Waiting for process to come online
Waiting for process to come online


SuperpoweredEffect
-Working fine


SuperpoweredFrequencyDomain
-Working fine


SuperpoweredHLS
-Working fine


SuperpoweredPlayer
-Crashes:
	-Output:
A/libc: Fatal signal 7 (SIGBUS), code 2 (BUS_ADRERR), fault addr 0xc67a8000 in tid 5634 (AudioFile Read), pid 5608 (d.playerexample)
D/: HostConnection::get() New Host Connection established 0xdbb9d5c0, tid 5637
I/ConfigStore: android::hardware::configstore::V1_0::ISurfaceFlingerConfigs::hasWideColorDisplay retrieved: 0
I/ConfigStore: android::hardware::configstore::V1_0::ISurfaceFlingerConfigs::hasHDRDisplay retrieved: 0
I/OpenGLRenderer: Initialized EGL, version 1.4
D/OpenGLRenderer: Swap behavior 1
W/OpenGLRenderer: Failed to choose config with EGL_SWAP_BEHAVIOR_PRESERVED, retrying without...
D/OpenGLRenderer: Swap behavior 0
D/EGL_emulation: eglCreateContext: 0xc8d77420: maj 3 min 0 rcv 3
D/EGL_emulation: eglMakeCurrent: 0xc8d77420: ver 3 0 (tinfo 0xdf7a5ff0)
D/EGL_emulation: eglMakeCurrent: 0xc8d77420: ver 3 0 (tinfo 0xdf7a5ff0)
Application terminated.


SuperpoweredRecorder
-Working fine


SuperpoweredUSBExample
-Working fine


