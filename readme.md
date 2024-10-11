cd presentation && npm run start



tunnel: `ssh -L 4724:192.168.0.123:4723 -L 3389:192.168.0.123:3389 pi@10.8.1.27`


## Practical demos

iOS

````
{
"platformName": "ios",
"appium:automationName": "xcuitest"
}
````


Android

`npx appium`

```
{
  "platformName": "Android",
  "appium:automationName": "UiAutomator2",
  "appium:deviceName": "Android",
  "appium:appPackage": "com.android.settings",
  "appium:appActivity": ".Settings",
  "appium:udid": "aee96db7d150",
  "appium:noReset": true
}
```


Windows


tunnel: `ssh -L 4724:192.168.0.123:4723 -L 3389:192.168.0.123:3389 pi@10.8.1.27`

````
{
"platformName": "windows",
"appium:automationName": "windows",
"appium:app": "Microsoft.WindowsCalculator_8wekyb3d8bbwe!App"
}
````
