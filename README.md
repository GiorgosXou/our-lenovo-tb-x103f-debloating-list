`2024-09-21 01:34:16 PM`

# 📱 Lenovo TB-X103F
A Basic ["Lenovo TB-X103F"](https://www.gsmchoice.com/en/catalogue/lenovo/tab10/) debloating list, for use within the [Hexapterygon](https://github.com/GiorgosXou/hexapterygon) *(disclaimer: I am not responsible for google play apps that may not work after :P)*


# ⚙️ Configure
Before running `hexapterygon` make sure you go-to:

- ***Settings:***
- - About tablet > tap repeatedly "Build number" to enable "Developer mode"
- - Enable: `Developer options > USB debugging`
- - Disable: `Developer options > Verify apps over USB`
- - Disable all under: `Security > Device administrators`

And afterwords open:

- ***Mull Browser:***
- - Goto `about:config` &
- - True `gfx.webrender.all`
- - True `network.process.enabled`
- - False `gfx.webrender.fallback.software`
- - False `toolkit.scrollbox.smoothScroll`
- - False `full-screen-api.transition-duration.`
- ***OpenLauncher:***
- - *(First download [openlauncher_20240923T171757.zip](./openlauncher_20240923T171757.zip))*
- - `Advanced > Restore > openlauncher_20240923T171757.zip`


# 🌐 Research
- ***Device [SAR](https://en.wikipedia.org/wiki/Specific_absorption_rate):***
- - HEAD SAR: `0.446 W/kg`
- - BODY SAR: `0.319 W/kg`
- - source: `am start -a android.intent.action.MAIN -n com.yep.setprop/.SARshowActivity`
- ***Usefull:***
- - [Can I use adb to change the default launcher program?](https://stackoverflow.com/questions/14816780)
- - [How can I run an installed system application that doesn't appear in the app list?](https://android.stackexchange.com/a/110812/384395)
- - [Old Android - How to install / get back uninstalled Apps (APKs) with ADB.](https://xdaforums.com/t/how-to-install-get-back-uninstalled-apps-apks-with-adb.3894235/post-84291287)
- - [Android: get all installed packages using ADB](https://stackoverflow.com/questions/53634246)
- ***Firefox ([Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/)):***
- - [Fixing performance problems in Firefox on Android.](https://www.reddit.com/r/firefox/comments/11shvus/fixing_performance_problems_in_firefox_on_android/)
- - [Improving performance in Firefox Android part II](https://www.reddit.com/r/browsers/comments/1278zp5/improving_performance_in_firefox_android_part_ii/)
- ***Random:***
- - [TWRP Root Guide - Lenovo P8 (TB-8703F and TB-8703X)](https://xdaforums.com/t/twrp-root-guide-lenovo-p8-tb-8703f-and-tb-8703x.3689442/page-4)
- - [Q: what is Galaxy4.apk (solved)](https://xdaforums.com/t/q-what-is-galaxy4-apk-solved.2256813/)
- - [Question - LenovoServices is running](https://xdaforums.com/t/lenovoservices-is-running.4344689/)
- - [Samsung Galaxy One UI - Optimization Guide](https://xdaforums.com/t/samsung-galaxy-one-ui-optimization-guide.4376755/post-88058593)


[<sup>See also</sup>](https://github.com/GiorgosXou/Our-Xiaomi-Redmi-5A-riva-debloating-list/?tab=readme-ov-file#-research)

<details><summary>Apps I haven't uninstalled +etc.</summary>

```
pm uninstall -k --user 0 com.qualcomm.qti.extsettings                    # ext filesystem something?
pm uninstall -k --user 0 com.google.android.marvin.talkback              # Android Accessibility Suite (Improtant for some people)
pm uninstall -k --user 0 com.qualcomm.fastdormancy                       # https://en.wikipedia.org/wiki/Fast_Dormancy
pm uninstall -k --user 0 org.codeaurora.ims                              # IMS - "handles wireless functions" (experience says it's not so critical for this device)
pm uninstall -k --user 0 com.android.facelock                            # Maybe remove
pm uninstall -k --user 0 com.android.managedprovisioning                 # NFC shit?
pm uninstall -k --user 0 com.android.captiveportallogin                  # That stupid thing that hotel-networks popup i think
pm uninstall -k --user 0 com.google.android.configupdater                # seems safe to uninstall
pm uninstall -k --user 0 com.android.defcontainer                        # Maybe
pm uninstall -k --user 0 com.android.noisefield
pm uninstall -k --user 0 com.qualcomm.qti.carrierconfigure
pm uninstall -k --user 0 com.android.smspush
pm uninstall -k --user 0 com.dolby
pm uninstall -k --user 0 com.qualcomm.qti.telephony.vodafonepack
pm uninstall -k --user 0 com.google.android.backuptransport
pm uninstall -k --user 0 com.qualcomm.qti.accesscache
pm uninstall -k --user 0 com.android.bookmarkprovider
pm uninstall -k --user 0 com.android.settings
pm uninstall -k --user 0 com.qualcomm.qti.ims
pm uninstall -k --user 0 com.qualcomm.simcontacts
pm uninstall -k --user 0 com.qualcomm.qti.qs
pm uninstall -k --user 0 com.qualcomm.qti.tetherservice
pm uninstall -k --user 0 com.caf.fmradio
pm uninstall -k --user 0 com.android.vpndialogs
pm uninstall -k --user 0 com.android.phone
pm uninstall -k --user 0 com.android.shell
pm uninstall -k --user 0 com.android.providers.userdictionary
pm uninstall -k --user 0 com.android.location.fused
pm uninstall -k --user 0 com.android.systemui
pm uninstall -k --user 0 com.android.bluetoothmidiservice
pm uninstall -k --user 0 com.qualcomm.qti.networksetting
pm uninstall -k --user 0 com.android.bluetooth
pm uninstall -k --user 0 com.qualcomm.timeservice
pm uninstall -k --user 0 com.android.providers.contacts
pm uninstall -k --user 0 com.goodix.rawdata
pm uninstall -k --user 0 com.android.wallpaper
pm uninstall -k --user 0 com.android.wallpapercropper
pm uninstall -k --user 0 com.android.providers.media
pm uninstall -k --user 0 com.android.browser.overlay.swe
pm uninstall -k --user 0 com.android.protips
pm uninstall -k --user 0 com.android.externalstorage
pm uninstall -k --user 0 com.android.htmlviewer
pm uninstall -k --user 0 com.qualcomm.shutdownlistner
pm uninstall -k --user 0 com.qualcomm.qti.phonefeature
pm uninstall -k --user 0 com.qualcomm.qti.auth.sampleauthenticatorservice
pm uninstall -k --user 0 com.qualcomm.qti.notificationservice
pm uninstall -k --user 0 com.qualcomm.qti.telephonyservice
pm uninstall -k --user 0 com.qualcomm.qti.auth.fidocryptoservice
pm uninstall -k --user 0 com.qualcomm.qti.auth.securesampleauthservice
pm uninstall -k --user 0 com.qualcomm.qti.loadcarrier
pm uninstall -k --user 0 com.qualcomm.qcrilmsgtunnel
pm uninstall -k --user 0 com.qualcomm.wfd.service
pm uninstall -k --user 0 com.qualcomm.sta
pm uninstall -k --user 0 com.qualcomm.svi
pm uninstall -k --user 0 com.qualcomm.cabl
pm uninstall -k --user 0 com.qti.qualcomm.datastatusnotification
pm uninstall -k --user 0 com.qti.primarycardcontroller
pm uninstall -k --user 0 com.android.documentsui
pm uninstall -k --user 0 com.qapp.secprotect
pm uninstall -k --user 0 com.android.pacprocessor
pm uninstall -k --user 0 com.android.certinstaller
pm uninstall -k --user 0 com.android.carrierconfig
pm uninstall -k --user 0 android
pm uninstall -k --user 0 com.android.backupconfirm
pm uninstall -k --user 0 com.android.statementservice
pm uninstall -k --user 0 com.android.providers.settings
pm uninstall -k --user 0 com.android.sharedstoragebackup
pm uninstall -k --user 0 com.android.printspooler
pm uninstall -k --user 0 com.android.frameworks.telresources
pm uninstall -k --user 0 com.lenovo.acttab
pm uninstall -k --user 0 com.android.inputdevices
pm uninstall -k --user 0 com.android.musicfx
pm uninstall -k --user 0 com.android.poweroffhandlerapp
pm uninstall -k --user 0 com.android.keychain
pm uninstall -k --user 0 com.google.android.packageinstaller
pm uninstall -k --user 0 com.android.calllogbackup
pm uninstall -k --user 0 com.huaqin.countrylist
pm uninstall -k --user 0 org.codeaurora.btmultisim
pm uninstall -k --user 0 com.android.keyguard.wallpaper
pm uninstall -k --user 0 com.android.proxyhandler
```
```
am start -a android.intent.action.MAIN -n com.benny.openlauncher/.activity.HomeActivity # Starting Home Activity
```

</details>
