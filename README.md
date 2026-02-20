# alshobaki-downloads
contain installation files for website

macos dmg creator code via creat-dmg

```
create-dmg \
  --volname "AL-Shobaki Academy Installer" \
  --volicon "app_icon_1024.icns" \
  --window-pos 200 120 \
  --window-size 800 400 \
  --icon-size 100 \
  --icon "AL-Shobaki Academy.app" 200 190 \
  --hide-extension "AL-Shobaki Academy.app" \
  "./shobaki_dmg/AL-Installer.dmg" \
  "/Users/mohamed/projects/shobaki_academy/build/macos/Build/Products/Release/Al-Shobaki Academy.app"
```
