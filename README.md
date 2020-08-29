## SF Mono
Source: https://developer.apple.com/fonts/

Direct download: https://apple.box.com/shared/static/obqoann24digvuoicmplk65onas3tz20.dmg
```
UniqueID: SF Mono Regular; 16.0d1e1; 2020-06-10
Version: Version 16.0d1e1
Last modified date: 2020 22 Jun 21:28
```

---

The vanilla fonts for Apple's SF Mono. These fonts don't have changelogs but still change.

Steps to extract on Linux:

```
wget https://apple.box.com/shared/static/obqoann24digvuoicmplk65onas3tz20.dmg
7z x obqoann24digvuoicmplk65onas3tz20.dmg
cd SFMonoFonts
7z x 'SF Mono Fonts.pkg'
7z x 'Payload-'
```
Fonts are located in Library/Fonts. To install to system:
```
...
sudo mv Library/Fonts /usr/share/SF-Mono
```
