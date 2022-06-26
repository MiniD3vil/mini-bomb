<h1 align="center">
  <br>
  <a href="https://github.com/MiniD3vil/mini-bomb"></a>
  <br>
  mini-bomb v2.1b
  <br>
</h1>


<p align="center">A free and open-source SMS/Call bombing application</p>

## NOTE:


> **Due to the overuse of script, a bunch of APIs have been taken offline. It is okay if you do not receive all the messages.**


- The application requires active internet connection to contact the APIs
- You would not be charged for any SMS/calls dispatched as a consequence of this script
- For best performance, use single thread with considerable delay time
- Always ensure that you are using the latest version of mini-bomb and have Python 3
- This application must not be used to cause harm/discomfort/trouble to others
- By using this, you agree that you cannot hold the contributors responsible for any misuse

## Compatibility
Check your Python version by typing in
```shell script
$ python --version
```
If you get the following
```shell script
Python 3.8.3
```
or any version greater than or equal to 3.4, this script has been tested and confirmed to be supported. For obsolete versions of Python (eg 2.7), use discretion while executing the script as it has not been tested there.

## Features

- Over 15 integrated messaging and calling APIs included with JSON
- Unlimited (with abuse protection) and super-fast bombing with multithreading
- Possibility of international API support (APIs are offline)
- Flexible with addition of newer APIs with the help of JSON documents
- Actively supported by the developers with frequent updates and bug-fixes
- Intuitive auto-update feature and notification fetch feature included
- Recently made free and open-source for community contributions
- Modular codebase and snippets can be easily embedded in other program


## Usage:

### Install by PIP (Recommended)

Before continuing make sure following requirements are satisfied:

- Python version greater than or equal to 3.4 is installed
- pip is installed for Python 3

Install `mini-bomb` package by running:

```shell script
pip3 install mini-bomb
```

Run mini-bomb by just typing:
```shell script
mini-bomb
```

### Install from GIT

#### NOTE 

Git installation methods are not universal and are likely to differ between distributions so installing Git as per the given instructions below may not work. Please check out how to install Git for your Linux distribution [here](https://git-scm.com/). Commands below provide instructions for Debian-based systems.

>Running `mini-bomb.sh` as sudo miscofigures files ownership. It is recommended not to run it as sudo

Run these commands to clone and run mini-bomb.

#### For Termux

To use the bomber type the following commands in Termux:
```shell script
pkg install git -y 
pkg install python -y 
git clone https://github.com/MiniD3vil/mini-bomb.git
cd mini-bomb
./mini-bomb.sh
```

#### For iSH

To use the application, type in the following commands in iSH.
```shell script
apk add git
apk add python3
apk add py3-pip
apk add ruby
gem install toilet
git clone https://github.com/MiniD3vil/mini-bomb.git
cd mini-bomb
pip3 install -r requirements.txt
chmod +x mini-bomb.sh
./mini-bomb.sh
```

#### For Debian-based GNU/Linux distributions

To use the application, type in the following commands in GNU/Linux terminal.
```shell script
sudo apt install git
git clone https://github.com/MiniD3vil/mini-bomb.git
cd mini-bomb
bash mini-bomb.sh
```

#### For MacOS

To use the application, type in the following commands in MacOS terminal:

##### Install Brew

```shell script
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
````

##### Install dependencies:

```shell script
brew install git
brew install python3
sudo easy_install pip
sudo pip install --upgrade pip
git clone https://github.com/MiniD3vil/mini-bomb.git
cd mini-bomb
bash mini-bomb.sh
```


##### Missing Tools on MacOS

The package `toilet` cannot be installed yet on macOS. But mini-bomb does still work.



### Donators:

- **MiniD3vil**
- **[34D30Y](34db0y@protonmail.com)**
- **SC AMAN**

### TODO:

- [x] Make Code More Readable and Extensible
- [x] Add Mail Spam Module
- [x] Add Mail Spam APIs
- [x] Add Update Feature using git
- [x] Add Update Feature without git (download zip and extract)
- [x] Split code into multiple files (after Deprecation)


### Contact US  

For Queries: [Telegram Group](https://t.me/Mini_D3vil_333)  
[Check Out My YouTube Channel](https://youtube.com/channel/UCKtsYPhsmbdpHmRPrNHRCDA)

## FAQ

- Poor internet connection:

```Check your internet connection and try pinging any remote address to confirm.```

- Do you support "X" Country?

```Most Countries are supported for SMS and only India for calls. The SMS delivery rate might be different for different countries.```

- Can you add support for "X" Country?

```We do what we can, but we cannot promise. Please stay tuned for future support. If you are ready to help then maybe we can do faster.```

- Why is the limit so low?

```Due the amount of requests, the APIs can die. To prevent a bigger outtake of mini-bomb, it has been limited.``` 

- Help, i got the error that the requirements aren't installed, even when the installer has successfully reached the main menu

The Easy Method:

```pip3 install mini-bomb```

Then execute by simply running

```mini-bomb```

The Git Method:  
Clone the repo and Switch to the mini-bomb Directory and execute this command:  
```pip3 install -r requirements.txt```

- Help, i can't execute mini-bomb.sh!

Run mini-bomb Directly with
```python3 mini-bomb.py```

- VPN? Proxy's? 

```No, mini-bomb can fail due the high response time or API restrictions.```

- Protection ?

```Use OTP Blockers and activate DND.```

- Call Bombing does not work!

``` It does only work for indian numbers. Other Country's are not supported yet.```


Last Update: 15.05.2021
