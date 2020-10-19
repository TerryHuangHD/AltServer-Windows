# AltServerPlus-Windows
AltServerPlus is an iOS app installer for non-jailbroken devices. Supports 3rd IPA files by config file.

### Current Status
* Fix build config for VS 2019
* Enable iDevice lookup over network
* Add external IPA source config mechanism
* Disable WinSparkle

### In Coming
* Auto-Renew Mechanism
* WinSparkle

# Config File "ipa.config"
```
URL_TO_IPA_FILE HASH_OF_URL
```

# Customize Installer
* [MSI2XML / XML2MSI](https://msi2xml.sourceforge.io/) used to modify "ipa.config" in installer

# Release
Go [Release Page](https://github.com/TerryHuangHD/AltServerPlus-Windows/releases)
