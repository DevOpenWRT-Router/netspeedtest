[![If some pictures cannot be displayed normally, please browse through the airport or click here to see the repair tutorial](https://visitor-badge.glitch.me/badge?page_id=sirpdboy-visitor-badge)](# Solve the problem that the picture on the github-webpage fails to display) [![](https://img.shields.io/badge/TG group-click to join-FFFFFF.svg)](https://t.me/joinchat /AAAAAEpRF88NfOK5vBXGBQ)
<a href="#readme">
    <img src="https://img.vim-cn.com/a1/8713845a4aa922ac96619b0d2fb3d6919d37fc.png" alt="The picture is flying😂" title="NetSpeedTest" align="right" height="180" />
</a>

Welcome to the source code repository of sirpdboy!
=
Welcome to sirpdboy's git source of packages
-
[luci-app-NetSpeedTest — Network Speed ​​Test 1.5 full version](https://github.com/sirpdboy/NetSpeedTest)
======================

[![](https://img.shields.io/badge/-directory: -696969.svg)](#readme) [![](https://img.shields.io/badge/-written in Front-F5F5F5.svg)](#Write in front-) [![](https://img.shields.io/badge/-Compilation Instructions-F5F5F5.svg)](#Compilation Instructions-) [![] (https://img.shields.io/badge/-instruction-F5F5F5.svg)](#instruction-) [![](https://img.shields.io/badge/-donation-F5F5F5.svg) ](#Donation-)

Please **read carefully** this page, this page contains precautions and how to use it.

a new NetSpeedTest luci app bese luci-app-NetSpeedTest
-

## Write in front: [![](https://img.shields.io/badge/-Write in front-F5F5F5.svg)](#Write in front-)

 I have been looking for a plug-in to test the speed on OPENWRT, but I couldn't find it, so I have it!
This plug-in can carry out internal, external and external network speed tests.

1. The internal network speed test is based on the iperf3 plug-in. If the server router is not installed, please install this ipk plug-in first.

2. The terminal using the speed measurement machine must be in the same local area network as the speed measurement server!

3. Client use steps:
  Start the speed test server -> download the test client -> run the speed test client -> enter the server IP address -> view the results.

5. The client is running. There is "iperf3 speed test client" in the domestic download. Just run it and enter the server IP.
  For the original foreign version, you need to manually enter the CMD command mode, and then enter the command: iperf3.exe -c server IP

6. Network speed test iperf3 client download address: https://sipdboy.lanzoui.com/b01c3esih Password: cpd6

8. Use speedtest.net speed test kernel for external network speed measurement, and need to rely on speedtest. In addition, thanks to superspeed and user1121114685 for borrowing your inspiration!

9. The final test stage of the external network speed test thanks to Zuo Dai: Sasuo Test and check the problem!

10. New plugins will inevitably have bugs, please don't make a fuss. Welcome to submit bugs.

## Compilation Instructions [![](https://img.shields.io/badge/-Compilation Instructions-F5F5F5.svg)](#Compilation Instructions-)

How to add NetSpeedTest theme to LEDE/OpenWRT source code.

## Download source code Method 1:
Edit the root directory feeds.conf.default of the source folder and add the following content:

```Brach
    # feedsGet the source code:
    src-git NetSpeedTest https://github.com/sirpdboy/NetSpeedTest
 ```
  ```Brach
   # Update feeds and install themes:
    scripts/feeds update NetSpeedTest
scripts/feeds install luci-app-NetSpeedTest
 ```

## Download source code method two:
 ```Brach
    # Download source code

    git clone https://github.com/sirpdboy/NetSpeedTest package/NetSpeedTest

    make menuconfig
 ```
## Configuration menu
 ```Brach
    make menuconfig
# Find LuCI -> Applications, select luci-app-NetSpeedTest, save and exit.
 ```
## Compile
 ```Brach
    # Compile the firmware
    make package/NetSpeedTest/luci-app-NetSpeedTest/{clean,compile} V=s
```

## Description [![](https://img.shields.io/badge/-instruction-F5F5F5.svg)](#instruction-)

Source: https://github.com/sirpdboy/NetSpeedTest/luci-app-NetSpeedTest


You can use the source code at will, but please indicate the source.
============================

# My other project
Network speed test: https://github.com/sirpdboy/NetSpeedTest

Scheduled shutdown and restart: https://github.com/sirpdboy/luci-app-autopoweroff

Shutdown function plugin: https://github.com/sirpdboy/luci-app-poweroffdevice

opentopd theme: https://github.com/sirpdboy/luci-theme-opentopd

opentoks theme: https://github.com/sirpdboy/luci-theme-opentoks [Imitation KOOLSAHRE theme]

btmob theme: https://github.com/sirpdboy/luci-theme-btmob

System advanced settings: https://github.com/sirpdboy/luci-app-advanced

## Donate [![](https://img.shields.io/badge/-donate-F5F5F5.svg)](# donate-)

**If you think this project is helpful to you, please donate to us so that the project can continue to develop and become more complete. ··The author has a cup of coffee~~~**

**Your support is my motivation! **

### Donation method

| <img src="https://img.shields.io/badge/-Alipay-F5F5F5.svg" href="#Sponsor to support this project-" height="25" alt="The picture is flying😂"/> | <img src="https://img.shields.io/badge/-WeChat-F5F5F5.svg" height="25" alt="The picture is flying 😂" href="#Sponsor the project-"/> |
| :-----------------: | :-------------: |
|<img src="https://img.vim-cn.com/fd/8e2793362ac3510094961b04407beec569b2b4.png" width="150" height="150" alt="Pictures fly away😂" href="#Sponsored to support this project -"/>|<img src="https://img.vim-cn.com/c7/675730a88accebf37a97d9e84e33529322b6e9.png" width="150" height="150" alt="The picture is flying😂" href="# Sponsor to support this project-"/>|

<a href="#readme">
    <img src="https://img.shields.io/badge/-back to top-orange.svg" alt="the picture is flying 😂" title="back to top" align="right"/>
</a>

###### [Solve the problem of failure to display pictures on Github webpage](https://blog.csdn.net/qq_38232598/article/details/91346392)

[![](https://img.shields.io/badge/TG group-click to join-FFFFFF.svg)](https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ)
