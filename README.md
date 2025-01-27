# testkey
## Resign chromium android system webview with AOSP's testkey
## download chromium android system webview apk and rename it to input.apk
### then use this in cmd
```
apksigner sign --key testkey.pk8 --cert testkey.x509.pem --out output_signed.apk input.apk
```
# proxy
## put chrome in a folder
### then run this file
```
start-use-proxy.bat
```