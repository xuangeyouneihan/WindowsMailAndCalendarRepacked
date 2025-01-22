[简体中文](README.md)

# WindowsMailAndCalendarRepacked

**Note: The English contents are translated by GitHub Copilot, and there might be some errors. If there is any conflict between the Chinese text and the English text, the Chinese text shall prevail.**

## Introduction

**Windows Mail and Calendar** repacked client, with modified version number and signature, will not auto-update.

- It's just the original software simply repacked and the version number and signature modified to avoid auto-updating. No program code except the version number has been modified or added, please use it with confidence.

> [!IMPORTANT]
> All content resources _(including but not limited to applications, audio, images, etc.)_ are copyrighted by Microsoft.  
> This software is for learning and communication purposes only, and should not be used for commercial purposes. If there is any infringement, please raise an Issue.  
> By using this application, you agree to the [Microsoft Software License Terms](https://go.microsoft.com/fwlink/?LinkID=524989) and the [Microsoft Privacy Policy](https://go.microsoft.com/fwlink/?LinkID=521839).

## Download

Click to download: [16005.14326.21464.0](https://github.com/xuangeyouneihan/WindowsMailAndCalendarRepacked/releases/download/16005.14326.21464.0/windows-mail-and-calendar-16005-14326-21464-0.appxbundle)

## Installation

Since Windows only allows the installation of appx/msix packages from the **Microsoft Store** or **enterprise developers**, we need to install a **self-signed certificate** to disguise as an enterprise developer before we can install third-party packages.

1. Download the [certificate file](https://github.com/xuangeyouneihan/WindowsMailAndCalendarRepacked/releases/download/16005.14326.21464.0/windows-mail-and-calendar-repacked.cer) and open it directly.
2. Click `Install Certificate`, which will enter the "Certificate Import Wizard".
3. Select `Local Machine` for "Store Location", and click Next (you need to agree to the administrator permission request).
4. Choose `Place all certificates in the following store`, click `Browse`, select `Trusted Root Certification Authorities`, confirm, click Next, and complete the certificate import.
5. Download the `appxbundle` package and double-click to install.

> [!NOTE]
> Some antivirus software may falsely report the certificate installation tool as a virus.  
> You may need to temporarily disable the antivirus software or add it to the whitelist to use it.  
> *This project and its accompanying tools do not contain any viruses or malicious operations, feel free to check.*

## Known Issues and Solutions

#### Cannot sign in to an email account using OAuth

The solution is unknown. If you know the solution, I'll appreciate if you could send an issue.

#### "Cannot install the related item" error when installing appx

Usually, Windows' "App Installer" will automatically download and complete the missing dependency packages. However, in some system environments, or when the network connection to Microsoft's servers is not smooth, the installation may still prompt "Cannot install the related item". Please refer to the [detailed solution](Dependencies_en.md) for this issue.

## Special Thanks

#### [Windows Mail and Calendar](https://apps.microsoft.com/detail/9WZDNCRFHVQM) & [Microsoft Developers](https://developer.microsoft.com)

Undoubtedly deserves to be in the first place.

#### [exp-3/CloudMusic.UWP-Repacked](https://github.com/exp-3/CloudMusic.UWP-Repacked)

Provided the most contents for this README and solutions for some common issues.

#### [Microsoft Developers](https://developer.microsoft.com) & [Empyreal96/Appx_Re-Sign](https://github.com/Empyreal96/Appx_Re-Sign)

Provided the tools and reference materials needed to edit Appx.

#### [GitHub Copilot](https://github.com/features/copilot)

Translated the Chinese text into English.
