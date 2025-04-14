#### Turn OFF Developer options to improved battery life!

`adb` commands to remove Samsung bloatware.

#### Facebook

```bash
adb shell pm uninstall --user 0 com.facebook.services
adb shell pm uninstall --user 0 com.facebook.katana
adb shell pm uninstall --user 0 com.facebook.system
adb shell pm uninstall --user 0 com.facebook.appmanager
```

#### Microsoft OneDrive

```bash
adb shell pm uninstall --user 0 com.microsoft.skydrive
```

#### Samsung Free / Samsung Daily

```bash
adb shell pm uninstall --user 0 com.samsung.android.app.spage
```

#### Bixby

```bash
adb shell pm uninstall --user 0 com.samsung.android.bixby.service
adb shell pm uninstall --user 0 com.samsung.android.bixby.agent
adb shell pm uninstall --user 0 com.samsung.android.bixby.wakeup
adb shell pm uninstall --user 0 com.samsung.android.bixby.agent.dummy
adb shell pm uninstall --user 0 com.samsung.android.bixbyvision.framework
adb shell pm uninstall --user 0 com.samsung.android.app.settings.bixby
adb shell pm uninstall --user 0 com.samsung.android.app.routines
adb shell pm uninstall --user 0 com.samsung.android.visionintelligence
adb shell pm uninstall --user 0 com.samsung.systemui.bixby2
```
