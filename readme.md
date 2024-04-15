## Video Call UIBizBundle

**Please integrate the [Video Call SDK](https://developer.tuya.com/en/docs/app-development/videoCall?id=Kdfiplyi9iyin) firstly.**

### Integrate with the UIBizBundle
step1: add the below code in Podfile

`source 'https://github.com/tuya/screen-ipc-call-private-spec-ios.git'`

`pod 'ThingSmartCameraPanelBizBundle', '~> 5.11.0'`
`pod 'ThingSmartCameraRNPanelBizBundle', '~> 5.11.0'`
`pod 'ThingSmartCameraSettingBizBundle', '~> 5.11.0'`
`pod 'ThingSmartCloudServiceBizBundle', '~> 5.11.0'`

step2: run `pod update`.

### Note
if you need other UIBizBundles, please upgrade the versions of other UIBizBundles to `5.11.0`

### Features
- add audio/video call
- fix bugs


## Demo
[UIBizBundle Demo](https://github.com/tuya/tuya-bizbundle-ios-sdk-sample-objc)

[SDK Demo](https://github.com/tuya/tuya-home-ios-sdk-sample-objc/tree/v5.x_ipc)
