#Zordon Automation

#####READ THIS BEFORE RUNNING YOUR PROJECT

#####How to setup before running project:

1. Install HomeBrew

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
2. Install JDK [here](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

```bash
check JDK already installed :
$javac -version
```
3. Install npm/node

```bash
install :
$brew install node
```
```bash
check node & npm installed on your machine :
$node -v
$npm -v
```
4. Install Android-SDK

```bash
install :
$brew install android-sdk
```
5. Install Build-tools & Platform-tools

```bash
To Open SDK manager:
$android sdk
```
```bash
Check on :

Android SDK Platform-tools
Android SDK Build-tools
Google Web Driver

uncheck the other file and install it
```

6. Install Appium

```bash
install :
$npm install -g appium
```
```bash
check appium installed on your machine :
$appium -v
```

7. Write on your .bash_profile

```bash
open your bash profile using nano or vim :
$nano .bash_profile
```

```bash
Copy to your bash profile :

export ANDROID_HOME=/usr/local/Cellar/android-sdk/24.4.1_1
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
export JAVA_HOME=$(/usr/libexec/java_home)
```

####Now you're DONE and then proceed to [Run Section](Run.md)

If you have any specific queries reach out to me at [Github](https://github.com/raixa) or [E-Mail](mailto:khalif.rinaldi@gmail.com)