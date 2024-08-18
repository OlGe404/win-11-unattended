# Win-11-unattended
Config files for unattended Windows 11 installations

## Sources

YouTube:
* https://www.youtube.com/watch?v=JUTdRZNqODY

Web:
* https://www.microsoft.com/de-de/software-download/windows11
* https://schneegans.de/windows/unattend-generator/

# How to
A generic autounattend.xml file was generated with the help of [schneegans.de](https://schneegans.de/windows/unattend-generator/).
Some values were not provided in clear text, but placeholders. Search for the placeholders and overwrite them with the value to use before using the autounattend.xml file.

| Placeholder          | Purpose |
| -------------------- | ------- |
| AdminAccountName     | Windows account to create during installation. |
| AdminAccountPassword | Password for the windows account. |
| WifiSid              | WLAN SID to automatically connect to. |
| WifiPassword         | Password for the WLAN to connect to. |
