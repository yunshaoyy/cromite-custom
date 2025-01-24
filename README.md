# cromite-testkey
## Resign cromite with AOSP's testkey
```
download arm64_SystemWebView64.apk from https://github.com/uazo/cromite/releases
```
```
apksigner sign --key testkey.pk8 --cert testkey.x509.pem --out arm64_SystemWebView64.apk_signed.apk arm64_SystemWebView64.apk
```
# cromite-proxy
## put cromite-win in a folder with start-use-proxy.bat
```
run start-use-proxy.bat
```
