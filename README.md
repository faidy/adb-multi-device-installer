adb-multi-device-installer
==========================

A bash script that allows you to install an apk on more than one device connected to the mac at the same time.

#### Prerequisites:
1. Android SDK is installed with platform-tools directory added to the path
2. Debugging is enabled on your android device from the developer options.
3. The connected device trusts the mac.

#### Steps:
1. Download the script
2. Execute the following from the same path of the script
```bash
chmod +x adbinstall
sudo cp adbinstall /usr/local/bin
```
Now you can take install the apk you want on multiple devices conneced at the same time to the mac by executing.
```bash
adbinstall "/path/to/apk/file.apk"
```
