# Homepage Panda releases

This repository holds the downloadable builds of [Homepage Panda](https://homepagepanda.com), the Mac app that lets you rearrange your iPhone home screen with drag and drop and push the layout back to your phone over USB.

It contains no source code. Each [release](https://github.com/superfacto/homepage-panda-releases/releases) carries two files:

- `HomepagePanda.dmg`: the installer. Open it and drag Homepage Panda to Applications.
- `Homepage_Panda_<version>_universal.app.tar.gz`: the update package the app downloads by itself when you click "Update & Restart". You do not need to download it.

The DMG is signed with Apple Developer ID, and the app inside it is notarized by Apple, so macOS opens it without warnings. Update packages are also signed with the app's own update key, and the app refuses any update whose signature does not match.

Get the latest version from [homepagepanda.com](https://homepagepanda.com) or directly from the [latest release](https://github.com/superfacto/homepage-panda-releases/releases/latest).

Questions or problems: email support@homepagepanda.com.
