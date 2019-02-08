# try-react-native

> 8 Feb 2019

A react native based project for mobile apps 


| Technology | Version |
| --- | --- | 
| node | v11.5.0 | 
| npm  | 6.4.1 | 

+ `sudo npm install create-react-nativea-app` |

+ `sudo npm install --global expo-cli`

+ `sudo npm install git -g`

+ Make sure you have XCode (https://itunes.apple.com/us/app/xcode/id497799835?mt=12, otherwise the following command will not work)

```markdown
Go to Apple store
Search and install
Once finished, click on Open
Then click on 'agree', wait for installation on system

Finally

/usr/bin/xcodebuild

+ `sudo create-react-native-app MyReactApp`

+ Install JDK 8 (https://docs.oracle.com/javase/8/docs/technotes/guides/install/mac_jdk.html#A1096855)

> `/Library/Java/JavaVirtualMachines`
>
> https://docs.oracle.com/javase/8/

```bash
Rishikeshs-MacBook-Air:try-react-native hygull$ ls /Library/Java/JavaVirtualMachines/
jdk1.8.0_202.jdk
Rishikeshs-MacBook-Air:try-react-native hygull$ ls -al /Library/Java/JavaVirtualMachines/
total 0
drwxr-xr-x  3 root  wheel   96 Feb  8 12:50 .
drwxr-xr-x  4 root  wheel  128 Feb  8 12:50 ..
drwxr-xr-x  3 root  wheel   96 Feb  8 12:50 jdk1.8.0_202.jdk
Rishikeshs-MacBook-Air:try-react-native hygull$ 
```
	
Configure => SDK tools, check Google play services

### Errors

> Very very nice solution: https://stackoverflow.com/questions/39778607/error-running-react-native-app-from-terminal-ios

Just set the version of XCode (basically, it is for the first time)
```
xcrun: error: unable to find utility "instruments", not a developer tool or in PATH
```

### Quick start

+ https://www.christianengvall.se/install-react-native/

> brew install node 
> brew install watchman
> npm install react-native-cli
> react-native init MyReactApp
> cd MyReactApp
> react-native run-ios
> react-native run-android

**Note:** 

+ XCode should be already installed in your system

+ Android studio should be also installed (Download, drap it to Applications, db click, install)

https://docs.expo.io/versions/latest/workflow/android-studio-emulator/

Aslo make sure you can run `adb` from terminal. ()


https://medium.com/pvtl/react-native-android-development-on-mac-ef7481f65e47

```bash
Rishikeshs-MacBook-Air:sdk hygull$ pwd
/Users/hygull/Library/Android/sdk
Rishikeshs-MacBook-Air:sdk hygull$ 
Rishikeshs-MacBook-Air:sdk hygull$ ls
build-tools	extras		platform-tools	sources
emulator	patcher		platforms	tools
Rishikeshs-MacBook-Air:sdk hygull$ 
```

```bash
ANDROID_HOME=/Users/hygull/Library/Android/sdk
PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
```


+ https://facebook.github.io/react-native/docs/getting-started.html
	
### TODO 

+ https://docs.expo.io/versions/latest/workflow/configuration

+ Expo CLI 