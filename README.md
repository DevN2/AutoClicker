# Auto-Clicker By Devn

## Mekanisme
Mekanismenya :

- monitor the screen at a constant rate by taking screenshots using  
  `/system/bin/screencap -p /sdcard/autoClicker/img.png`
- then examinate a certain pixel of the taken screenshot. 
- If that very pixel is the desired color, then do a rapid click at a certain point using  
  `/system/bin/input tap x y` (where x y being the coordinates).

Even the idea of making this app into an auto-clicker is cannot be implimented due to the performance issue mentioned above.

-  this code can be used to run adb shell commands on a rooted android device:
  `Process sh = Runtime.getRuntime().exec("su", null, null);`  
  `OutputStream os = sh.getOutputStream();`  
  `os.write((/* command */).getBytes("ASCII"));`  
  `os.flush();`  
  `os.close();`  
  `sh.waitFor();`
- mechanism behind floating window

-  how to include .jar file/library in Android Studio:

```
android {
...
}

dependencies {
    compile fileTree(dir: 'libs', include: '*.jar')
}
```

- also this app prompted me to start learning android from coursera
