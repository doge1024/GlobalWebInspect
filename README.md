# GlobalWebinspect

Enable WebView inspector for all iOS apps, requires jailbreak

## 直接使用
deb 文件在 [./packages](./packages) 目录下

## Usage

* Enable WebInspector in Preferences
* Build and install the tweak `THEOS_DEVICE_IP=localhost THEOS_DEVICE_PORT=2222 make package install`
* Re-plug the USB cable and restart target app
* **Note:** if you are using iOS9, please switch to iOS9 branch

