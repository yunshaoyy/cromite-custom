# I suggest using cromite or ungoogled-chromium.
## Resign.
### Resign chromium android system webview with AOSP's testkey.
### Download chromium android system webview apk and rename it to input.apk.
### Then use this in cmd
```
apksigner sign --key testkey.pk8 --cert testkey.x509.pem --out output_signed.apk input.apk
```
## Proxy.
### Put chrome in a folder.
### Then run this file.
```
start-use-proxy.bat
```