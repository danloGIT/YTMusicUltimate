<p align="center">
<img src="https://user-images.githubusercontent.com/38832025/235781424-06d81647-b3db-4d9b-94dc-cd65cdf09145.png?raw=true" />
</p>    

<p align="center">
<img src="https://user-images.githubusercontent.com/38832025/235781207-6d1ad44e-0c32-4aec-9c75-cb928ca8a0d3.png?raw=true" />
</p>

<p align="center">
The best tweak for YouTube Music on iOS.
</p>

## Download Links

* **Jailbreak:**
  Add __[https://ginsu.dev/repo](https://ginsu.dev/repo)__ to your favorite installer and download the latest version from there, or from the __[Releases](https://github.com/ginsudev/YTMusicUltimate/releases)__ page.

  (arm.deb version for rootful and arm64.deb version for rootless devices)

* **Sideloading:**
  A compiled version is available on the unoffical website by me:  
  [YTMusicUltimateCompiled Release Website](https://danlogit.github.io/YTMusicUltimateCompiled/compiled/index.html).

  If you want to build the IPA yourself, follow these steps:

## How to build a YTMusicUltimate IPA by yourself using GitHub actions

If this is your first time here, start from step 1. If you built a YTMU IPA before, skip steps 1 and 2. Instead, click on the "Sync fork" button to get the latest version of the tweak and continue through step 3.

1. Fork this repository using the fork button on the top right.
2. On your forked repository, go to Repository Settings > Actions, enable Read and Write permissions.
3. Go to the Actions tab on your forked repo, click on "Build and Release YTMusicUltimate" located on the left side. Click the "Run workflow" button located on the right side.
4. Find a decrypted YTMusic .ipa file (we cannot provide you this due to legal reasons) and upload it to a file provider (filebin.net or Dropbox is recommended). Paste the URL into the necessary field and click "Run workflow."
5. Wait for the build to finish. You can download the tweaked IPA from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add `/releases` to the URL. For example: `github.com/user/YTMusicUltimate/releases`.)

## IPA building troubleshooting (I can't build the IPA/GitHub action fails/I can't find the releases section etc.)

99.9% of the time, the culprit is the IPA URL you provided. You HAVE TO provide a decrypted IPA. It cannot be any other extension; it has to be a **.ipa** file. Find a decrypted YTMusic IPA (we can't help you with that), upload it to filebin.net or Dropbox, and give the direct link to the GitHub action. If you find a working IPA and upload it properly, everything will start working perfectly, pinky promise.

If the GitHub action works and you cannot find where you can download the result, you need to add `/releases` to the URL of your forked repository. It'll probably look like this: `https://github.com/YOURUSERNAME/YTMusicUltimate/releases` (replace `YOURUSERNAME` with your GitHub username). It may seem invisible, but if the GitHub action is successful, the IPA will be there.

## How to build the package by yourself on your device
1. Install __[Theos](https://theos.dev/docs/installation)__
2. Clone this repo __[using git](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)__
3. CD into your YTMusicUltimate folder and run:

   • '**make clean package**' to build a `.deb` file for a rootful device  
   
   • '**make clean package ROOTLESS=1**' to build a `.deb` file for a rootless device  
   
   • '**make clean package SIDELOADING=1**' to build a `.deb` file for injecting into an IPA  

   • To learn how to inject tweaks into an IPA, visit __[here (Azule)](https://github.com/Al4ise/Azule)__

---

Made with ❤ by Ginsu and Dayanch96
Compiled with ❤ by Danlo Corporation
