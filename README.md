<h1 align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTFapV2IYgXmzHqM3oQTnzQwBDolmiehF9BLQ&usqp=CAU" alt="Reverse Engineering Logo" width="120">
  <br>
  Android Reverse Engineering Resources
</h1>

<p align="center">
  <a href="https://github.com/OshekharO/Reverse-Engineering/stargazers">
    <img src="https://img.shields.io/github/stars/OshekharO/Reverse-Engineering?style=flat-square&color=yellow" alt="Stars">
  </a>
  <a href="https://github.com/OshekharO/Reverse-Engineering/forks">
    <img src="https://img.shields.io/github/forks/OshekharO/Reverse-Engineering?style=flat-square&color=blue" alt="Forks">
  </a>
  <a href="https://github.com/OshekharO/Reverse-Engineering/issues">
    <img src="https://img.shields.io/github/issues/OshekharO/Reverse-Engineering?style=flat-square&color=red" alt="Issues">
  </a>
  <a href="https://saksham.thedev.id/Reverse-Engineering/">
    <img src="https://img.shields.io/badge/Website-Live-brightgreen?style=flat-square" alt="Website">
  </a>
</p>

<p align="center">
  A curated collection of Android reverse engineering tools, emulators, and learning resources.<br>
  Contributions and suggestions are heartily welcome! (✿◕‿◕)
</p>

---

## 📖 Table of Contents

- [About](#-about)
- [Android Emulators](#-android-emulators)
- [Tools for Android](#-tools-for-android)
- [Tools for PC](#-tools-for-pc)
- [Tutorials & Learning Resources](#-tutorials--learning-resources)
- [Community](#-community)
- [Disclaimer](#-disclaimer)
- [Contributing](#-contributing)

---

## 🔍 About

**Reverse Engineering** is the process of analyzing software to understand its internal structure, functionality, and behavior — without access to the original source code. In the context of Android, it typically involves:

- Decompiling APK files to inspect Smali/Java code
- Modifying app behavior using patching tools
- Analyzing network traffic and app resources
- Understanding and bypassing signature verification

This repository aggregates the best tools, emulators, and learning materials for Android reverse engineering in one place.

---

## 📱 Android Emulators

Android emulators create a sandboxed virtual Android environment — ideal for safely testing and analyzing apps without affecting your primary device.

| Name | Platform | Status |
|------|----------|--------|
| [Virtual Android](https://play.google.com/store/apps/details?id=com.pspace.vandroid) | Android | ✅ Active |
| [VPhoneGaGa](https://drive.google.com/uc?id=18uy6qDK7kJKPbTgsguOpBMm9Q2HnDn4B&export=download) | Android | ✅ Active |
| [RedFinger](https://play.google.com/store/apps/details?id=com.redfinger.global) | Android | ✅ Active |
| [DualMeta](https://github.com/FSpaceCore/SpaceCore/releases) | Android | ✅ Active |
| [Vmos Pro](https://4pda.to/forum/index.php?showtopic=961828) | Android | ✅ Active |
| [X8 Sandbox](https://4pda.to/forum/index.php?showtopic=1004655) | Android | ✅ Active |
| [F1 VM](https://4pda.to/forum/index.php?showtopic=1004655) | Android | ✅ Active |
| [Twoyi](https://4pda.to/forum/index.php?showtopic=1041895) | Android | ❌ Dead |

---

## 🛠️ Tools for Android

Mobile-based tools for decompiling, patching, analyzing, and recompiling APKs directly on your Android device.

### APK Editors & Patchers

| Tool | Description |
|------|-------------|
| [ApkEditor Pro](https://github.com/timscriptov/ApkEditor) | Feature-rich APK editor for Android |
| [AXML Editor](https://github.com/AbdurazaaqMohammed/AXML-Editor) | Binary XML editor for Android manifest files |
| [XML Editor](https://gofile.io/d/YLU7pP) | General-purpose XML editing tool |
| [MT Manager](https://4pda.to/forum/index.php?showtopic=548542) | Dual-pane file manager with APK editing capabilities |
| [NP Manager](https://4pda.to/forum/index.php?showtopic=966965) | APK editor with signature patching support |
| [APKTOOL M](https://maximoff.su/apktool/?lang=en) | Mobile port of the popular Apktool |
| [AEPatcher](https://github.com/Maximoff/AEPatcher) | Patch scripts for APK Editor |
| [M-Patcher](https://maximoff.su/mpatcher/) | Pattern-based APK patcher |
| [ApkToolPatcher](https://4pda.to/forum/index.php?showtopic=882654) | Automated APK patching utility |
| [Anti-Split](https://github.com/AbdurazaaqMohammed/AntiSplit-M) | Merge split APKs into a single APK |

### Smali & Java Tools

| Tool | Description |
|------|-------------|
| [Smali Helper](https://smalihelper.blogspot.com/) | Helper utilities for Smali code editing |
| [Java2Smali](https://gofile.io/d/HDln2J) | Convert Java source to Smali bytecode |
| [Android IDE](http://androidide.com) | Full-featured IDE for Android development on-device |

### Analysis & Debugging

| Tool | Description |
|------|-------------|
| [Apkanalyzer](https://4pda.to/forum/index.php?showtopic=1037391) | APK analysis and inspection tool |
| [Developer Assistant](https://4pda.to/forum/index.php?showtopic=897774) | Developer-oriented diagnostic tool |
| [Dev Tools Pro](https://4pda.to/forum/index.php?showtopic=958291) | Advanced developer utilities |
| [BlackDex](https://github.com/CodingGay/BlackDex) | On-device DEX dumping tool (unpack protected apps) |
| [Http Canary](https://4pda.to/forum/index.php?showtopic=957572&st=60#entry92625117) | HTTP/HTTPS traffic capture and analysis |
| [Reqable](https://play.google.com/store/apps/details?id=com.reqable.android) | Modern API debugging & traffic analysis tool |

### Patchers & Misc

| Tool | Description |
|------|-------------|
| [Jasi Patcher](https://jasi2169.com/jasi-patcher/) | Universal patcher for Android apps |
| [Lucky Patcher](https://4pda.to/forum/index.php?showtopic=298302) | App patcher for modifying permissions and purchases |
| [Ads Regex](https://www.pling.com/p/2175692) | Regex-based ad removal patterns |
| [Patches](https://4pda.to/forum/index.php?showtopic=575450&view=findpost&p=62744086) | Community patch collection |

---

## 💻 Tools for PC

Desktop tools for advanced APK analysis, decompilation, and reverse engineering on Windows, macOS, and Linux.

| Tool | Description |
|------|-------------|
| [APKEditor](https://github.com/REAndroid/APKEditor) | Powerful cross-platform APK editor |
| [Apktool](https://ibotpeaches.github.io/Apktool/) | Industry-standard tool for decoding and rebuilding APKs |
| [DEX2JAR](https://github.com/pxb1988/dex2jar) | Convert Android DEX files to JAR for Java decompilation |
| [Bytecode Viewer](https://github.com/Konloch/bytecode-viewer) | Java/Android bytecode viewer and decompiler |
| [Cutter](https://github.com/rizinorg/cutter) | Free and open-source reverse engineering platform (powered by Rizin) |
| [Apk Studio](https://github.com/vaibhavpandeyvpz/apkstudio) | Cross-platform IDE for decompiling and rebuilding APKs |
| [APK Easy Tool](https://forum.xda-developers.com/t/tool-windows-apk-easy-tool-v1-59-2-2021-04-03.3333960/) | User-friendly GUI wrapper for Apktool (Windows) |
| [ApkRepacker](https://github.com/MrIkso/ApkRepacker) | Simple GUI tool for unpacking and repacking APKs |
| [ArscEditor](https://github.com/MrIkso/ArscEditor) | Editor for Android binary resource (`.arsc`) files |
| [DTL-X](https://github.com/Gameye98/DTL-X) | Dalvik tool for analyzing and patching DEX files |

---

## 📚 Tutorials & Learning Resources

Resources to help you learn Android reverse engineering — from Smali basics to advanced binary analysis.

| Resource | Author | Description |
|----------|--------|-------------|
| [Understand Smali](https://github.com/OshekharO/Reverse-Engineering/wiki) | AbhiTheModder | A beginner-friendly guide to reading and writing Smali code |
| [Practical Reverse Engineering](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118787315.html) | Bruce Dang et al. (2014) | Comprehensive book covering x86, x64, ARM, and kernel-mode debugging |
| [Reverse Engineering for Beginners](http://beginners.re/) | Dennis Yurichev | Free book covering assembly language and RE fundamentals |
| [The IDA Pro Book](https://nostarch.com/idapro2.htm) | Chris Eagle (2011) | In-depth guide to using IDA Pro for binary analysis |
| [Malware Gems](https://github.com/0x4143/malware-gems) | 0x4143 | Curated collection of malware analysis and RE references |

---

## 🌐 Community

Connect with the reverse engineering community, ask questions, and share your work.

- **[4PDA Forums](https://4pda.to/)** — Large Russian-language community with extensive Android modding and RE discussions

---

## ⚠️ Disclaimer

> The tools and resources listed in this repository are collected from publicly available sources for **educational purposes only**.
> 
> - These applications were **not created by the repository maintainer**.
> - The maintainer is **not liable** for any misuse, damages, or legal issues arising from the use of these tools.
> - Always ensure you have **proper authorization** before reverse engineering any application.
> - Reverse engineering proprietary software may violate the application's Terms of Service or applicable laws in your jurisdiction.

---

## 🤝 Contributing

Contributions are welcome! If you know of a great tool, resource, or tutorial that belongs here:

1. Fork the repository
2. Add your resource to the appropriate section
3. Submit a Pull Request with a brief description

Please ensure any added resources are publicly available, relevant, and not malicious.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/OshekharO">OshekharO</a>
</p>
