# KeyCastOW
keystroke visualizer for Windows, lets you easily display your keystrokes while recording screencasts.

* small footprint (one 100kb executable file)
* green and portable, only depends on windows system dlls
* prenty of settings for keystroke display
* hotkey to turn on/off


## build

  msbuild /p:platform=win32 /p:Configuration=Release /p:PlatformToolset=v140
  
  - You can find the PlatformToolset by run:
  - msbuild /version
  - Actually , I use Visual C++ 2015 MSBuild Command Prompt , the PlatformToolset is v140 , maybe your is v141 , v120 and other.

## License

MIT License
