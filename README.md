# anmy-launcher-updates

Host OTA cho **anmy-launcher** (repo private). App đọc `update.json` rồi tải `anmy-launcher.apk`.

- `update.json` — manifest cập nhật (versionCode/versionName/apkUrl/sha256/changelog)
- `anmy-launcher.apk` — APK bản mới

Để phát hành bản mới: thay 2 file này bằng bản build mới (cập nhật `versionCode`/`versionName` > bản hiện tại) rồi push lên `main`.
