---

---



[◄◄ **Back to Guides**](https://www.reddit.com/r/piracy/wiki/guides)

[◄◄ **Back to FAQ**](https://www.reddit.com/r/piracy/wiki/guides)

---

---

# WINDOWS 10/LTSB/LTSC INSTALLATION AND ACTIVATION

&nbsp;

**Note:** Some people may recommend buying cheap keys elsewhere. This is not recommended, as these are grey-market keys, gathered from MSDN channels, each key sold multiple times ([extra reading](https://www.reddit.com/r/windows/comments/b7jolc/is_cheap_windows_10_licenses_lifetime_or_one_time/ejshgai/)). You're not buying directly from MS so you're not buying a license, you're just buying a key and living on the promise that MS won't discover and deactivate it.

It's essentially piracy with a middleman.

**Note 2**: We only recommend downloading and installing official/untouched Windows ISOs. Pre-cracked/altered windows ISOs are not recommended at all.

&nbsp;

---

## ► Downloading Windows 10

If you're on Windows, download and run the [**media creation tool**](https://www.microsoft.com/en-us/software-download/windows10) from microsoft. It will download Windows 10 and automatically create a bootable installation media for it on your USB drive.

If you're on a different platform, you can use [**tb.rg-adguard.net**](https://tb.rg-adguard.net/public.php), which is just a web interface for MSFT's techbench site - any downloads will be done through MSFT's CDN.

&nbsp;

**Windows LTSB / LTSC**

Note: The eval ISOs of LTSB/LTSC cannot be extended past their typical 3 month expiry window. You need to grab the full ISOs.

> LTSB isos hosted by the-eye: <https://the-eye.eu/public/MSDN/Windows%2010/>

> LTSC x86_64 (64-bit) iso: <https://mega.nz/folder/ChNTDaiL#nNqH2PTfIzTLAEs8nc-U0w>

More resources for Original Windows Installation Media in the [Megathread > Tools section](https://old.reddit.com/r/Piracy/wiki/megathread/tools)

Further reading: [**What is Windows LTSC?**](https://old.reddit.com/r/Windows10LTSC/wiki/index)

Note that LTSC will stay frozen on the feature set of Windows 10 build 1809 (until the next long term channel, to be released in 2021), if you have an Xbox Game Pass, you'll need build 1903, which is only attainable with the consumer edition of Windows 10. Be careful if you have newer hardware (2019 or later), research to see if your hardware will perform optimally on LTSC.

&nbsp;

## ► Creating a bootable USB drive and Installing Windows

This part is not strictly related to Piracy - you can find guides on how to install Windows anywhere on the internet. Example video here: [time stamp 3:15](https://youtu.be/MfwjISmkEJM?t=195).

Requirements:

* A USB drive of at least 4GB. The Windows 10 ISO installation media is approximately 3.5 GiB in size.

* Another working PC (If you are building a new PC).

If you're on Windows, this part is already covered by the previous step, and was achieved by running MSFT's Media Creation Tool - You may skip to the next step.

Alternatively if you want to create a bootable USB drive from the LTSB/LTSC ISOs, you'll need [**Rufus**](https://rufus.ie/), since the Microsoft's creation tool does not support LTSB/LTSC.

If you're on Linux, you'll need [**WoeUSB**](https://github.com/slacka/WoeUSB) or [**UNetbootin**](http://unetbootin.github.io/).

If you're on Mac, you'll need [**UNetbootin**](http://unetbootin.github.io/).

&nbsp;

## ► Activating Windows 10

Just download and run [MAS (Microsoft-Activation-Scripts)](http://www.reddit.com/r/piracy/wiki/megathread/tools) to activate. Download from the Releases page at the github repo. Extract the contents from the zip, then run the `cmd` file located in the `All-In-One-Version` directory. To activate Win10, run the `HWID` option and you're done.

This activation mode is permanent and will not install a background service, which would be liable to be removed by an antivirus, causing your windows to become de-activated, which was historically the case with previous KMS activation tools. It grants, by all intents and purposes, a genuine license, because it takes advantage of the fact that Microsoft still offers a free win7/8 -> win10 upgrade, spoofs that upgrade ticket, thus granting you a digital license to Windows 10.

&nbsp;

## ► Upgrading from Win10 Home to Pro

If you wish to upgrade from the Home edition to the Pro edition, you just need to run option `6: Extras` in MAS, then run option `3: Change Windows 10 Edition`

Alternatively, you may also use [hwidgen](https://reddit.com/r/piracy/wiki/megathread/tools) for this and choose the `license switch` function: <https://i.imgur.com/lmjLOtq.jpg>

&nbsp;

## ► Upgrading to Windows 10 (from a previous version of Windows)

Alternatively, if you're currently on a previous version of Windows, you'll be pleased to learn that Microsoft still offers a free upgrade to Windows 10 from a prior Windows version (7 and 8). The upgrade tool is still available through Microsoft's accessibility portal (for people who use assistive technologies) which can be found here:

> <https://go.microsoft.com/fwlink/?linkid=822784> (starts a 6 MiB download).

If your Windows 7 OS was activated with a SLIC loader (i.e. Daz's Windows loader), or your Windows 8.1 OS was activated with a KMS activator, then you will be able to upgrade to Windows 10 and your OS wil be genuine thanks to digital entitlement. Digital entitlement provides your Windows 10 copy a genuine digital license since "you upgraded to Windows 10 for free from an eligible device running a 'genuine' copy of Windows 7 or Windows 8.1."

This digital license is tied to your hardware. Therefore if you would prefer to "clean install" Windows 10 after the upgrade, you can reset Windows 10 and it will activate automatically after the clean installation. You may also sign in with your Microsoft account to have the key tied to your account.

Listed below are some relevant links to the upgrade process and digital entitlement:

><https://support.microsoft.com/en-us/help/12440/windows-10-activation>

><https://support.microsoft.com/en-us/help/20530/windows-10-reactivating-after-hardware-change>

><https://www.tenforums.com/tutorials/55398-link-microsoft-account-windows-10-digital-license.html>

&nbsp;
