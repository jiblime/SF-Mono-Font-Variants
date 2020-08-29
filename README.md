## SF Mono
Source: https://developer.apple.com/fonts/

Direct download: https://apple.box.com/shared/static/obqoann24digvuoicmplk65onas3tz20.dmg

Last modified date: 2020 22 Jun 21:28

SHA1 sums:

```
d4788bed587b83c36f47706a29947a1a0ad4160a  SF-Mono-BoldItalic.otf
3e884ce50e420db3e45b33cb2122f23a68c91e03  SF-Mono-Bold.otf
5e3b9c5028b5cd9ff6627147b5515f857a057f75  SF-Mono-HeavyItalic.otf
32ba88167f6007a9ce5307e5506ad96f12876b25  SF-Mono-Heavy.otf
801aa0e7b29fa01b89f3cdce039a307a332633a8  SF-Mono-LightItalic.otf
52f8fcdab8904a9180c16161f896cda47651fa58  SF-Mono-Light.otf
878df6de16e105d64b6ad8c208f5e1e131f0250c  SF-Mono-MediumItalic.otf
8ec05d6ce98dcb8698c01488ea6acd0cd1755dfa  SF-Mono-Medium.otf
e5d86bfc174b4e259c1acdaf716c8b71f624605d  SF-Mono-RegularItalic.otf
1946acea4f06e6c5dbd94f71c14bf6937c8be5a0  SF-Mono-Regular.otf
97b4c6faa3093b0d5ed05e98b55afe6166cf03a0  SF-Mono-SemiboldItalic.otf
8690b3990d68c04218abf221208ed15283b9e536  SF-Mono-Semibold.otf
```

---

The vanilla fonts for Apple's SF Mono. These fonts don't have changelogs but still change, so it would be best to document dates provided.

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
