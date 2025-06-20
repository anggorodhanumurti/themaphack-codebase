<h1 align="center">
  <br>
  <a href="http://https://github.com/anggorodhanumurti/themaphack/"><img src="https://raw.githubusercontent.com/anggorodhanumurti/themaphack/refs/heads/main/images/tmh-logo.png" alt="tmh" width="200"></a>
  Themaphack.
</h1>
<h3 align="center"> Mod menu like no others</h3>
<p align="center">
  <a href="https://whatismyandroidversion.com/"><img src="https://img.shields.io/badge/Android-10--14+-brightgreen?logo=android" alt="Android - 10-14+">
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.mobile.legends"><img src="https://img.shields.io/badge/Game-Mobile_Legends-important?logo=youtubegaming" alt="Game - Mobile Legends">
  </a>
  <a href="https://t0pgamemurah.xyz/freeKey"><img src="https://img.shields.io/badge/generate-key-blue?logo=keeweb&logoColor=fff" alt="generate - key">
  </a>
  <a href="https://github.com/anggorodhanumurti/themaphack/releases/"><img src="https://img.shields.io/github/tag/anggorodhanumurti/themaphack?include_prereleases=&sort=semver&color=blue" alt="GitHub tag"></a>
  <a href="https://www.patreon.com/themaphack"><img src="https://img.shields.io/badge/Get-Latest_updates-ff69b4?logo=patreon" alt="Get - Latest updates"></a>
</p>

![screenshot](https://raw.githubusercontent.com/anggorodhanumurti/themaphack/refs/heads/main/images/themaphack-demo.gif)

<p align="center">
  <a href="#key-advantage">Key Advantage</a> •
  <a href="#main-features">Main Features</a> •
  <a href="#build">Build</a> •
  <a href="#download">Download</a> •
  <a href="#usage">Usage</a> •
  <a href="#faq">FAQ</a>
</p>

## Key Advantage

The fact that there is no 100% cheats that safe from being banned.

Remember when you paid for premium mod just for 30 days they claim it safe but end up getting banned for 30 years (even when the usage duration not yet over).

You lost your acount without refund that suck! we dont want to overclaim but here the best thing we can give:

* Free forever
  - You can generate free key (unlimited) in our [website](https://t0pgamemurah.xyz/freeKey).
  
* Open source, Transparency & Modular
  - Feel free to use this source code as a template for your mod menu project
  - Transparency is guaranteed, allowing users to inspect the source code, ensuring there are no malicious components.
  - The modular design lets users extend the features of this mod to suit their specific needs.

* **Account Safety**
  -  To mitigate the risk of bans, a [special guide](https://www.patreon.com/posts/guide-how-to-not-130259867?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link) is available to VIP users aimed at avoiding detection.

## Main Features

![screenshot](https://raw.githubusercontent.com/anggorodhanumurti/themaphack/refs/heads/main/images/complete-esp.gif)

* Responsive maphack
  - Automatically adjusts to the phone's screen resolution when activated, providing a seamless user experience.
  
* Complete ESP
  - Tracks enemy health, outlines, monster hero icons, and more, enhancing situational awareness in gameplay.

## Build

_An extensive tutorial is available for building Themaphack using ndk-build within the Termux terminal emulator. Detailed steps are provided:_

### Prepare
We have set up custom [ndk-build](https://github.com/anggorodhanumurti/themaphack/releases/tag/ndk_aide_latest) to work on this project or you can download Android ndk at its [official website](https://developer.android.com/ndk/downloads)
- Download our custom [ndk-build](https://github.com/anggorodhanumurti/themaphack/releases/tag/ndk_aide_latest) tools
- Install [Termux](https://termux.dev/en/) on your Android devices or just use your `terminal/cmd` if you build on PC

```Termux
# Update repository Termux
$ pkg update && pkg upgrade -y

# Install required tools
$ pkg install git openssh wget

# Change to Termux $HOME directory
$ cd ~/

# Download ndk-build system
$ wget https://github.com/anggorodhanumurti/themaphack/releases/download/ndk_aide_latest/ndk-build.tar.gz

# Extract ndk-build
$ tar -xvzf ndk-build.tar.gz

# Clone themaphack repository
$ git clone https://github.com/anggorodhanumurti/themaphack.git && cd themaphack

# Run compile script
$ ./compile.sh
```
> [!NOTE]
> Ensure you select the appropriate library based on your device's architecture. If you're not sure you can check your device architecture using [64bit checker](https://play.google.com/store/apps/details?id=com.danielpolish.a64bitchecker)
- libs/arm64-v8a for 64bit
- libs/armeabi-v7a for 32bit

_I assume you're using 64bit Android_

After `compile.sh` script runs succesfully, lib file will generated on your working directory `libs/arm64-v8a` the filename is `libAkSoundEngine2.so`

Open [Zarchiver](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver) Copy that `libAkSoundEngine2.so` to mlbb folder: `Android/data/com.mobile.legends/files/dragon2017/assets/comlibs/arm64-v8a` then rename original **```libAkSoundEngine.bytes```** to **```libTMH.bytes```** also rename mod lib **`libAkSoundEngine2.so`** to **`libAkSoundEngine.bytes`** done TMH is installed succesfully!


## Download

There are 2 version of `Themaphack` is a Virtual and External

* **Virtual** version using apk virtualization methode and obfuscated code to ensure full control between modmenu and game client make it **`more secure and stable (no lag/crash)`** as a result we dont open source the code at this version
  - Download Virtual version **[tmh_virtual_apk.nova.zip](https://github.com/anggorodhanumurti/themaphack/releases/download/v1.2.2-virtual(64bit)/tmh_virtual_apk.nova.zip)**

* **External** version is the outcome of compiling source code from this project in a form of `.so files` which is injected into mlbb folder. No obfuscated code so you can customize its feature and function to suit your needs easily
  - Download External Version **[stable-v1.1.2-64bit](https://github.com/anggorodhanumurti/themaphack/releases/tag/v1.1.2-64bit)**

## Usage
### Installation & how to get key

1. We recommend you to use [`TMH virtual`](https://github.com/anggorodhanumurti/themaphack/releases/tag/v1.2.2-virtual(64bit)) because it is safer and more stable than the external version. Here a [direct download](https://github.com/anggorodhanumurti/themaphack/releases/download/v1.2.2-virtual(64bit)/tmh_virtual_apk.nova.zip) link

2. Extract **`tmh_virtual_apk.nova.zip`** and install **`NovaLauncher.apk`**

3. Open `Nova Launcher` click `Start` allow permission for `Nova Launcher` to manage all files

4. Add `mlbb` to `Nova Launcher` by Selecting `Mobile Legends` then click **`Clone`**. At this stage you've successfully installed modmenu but **dont open mlbb** before finishing the step bellow or your account will be banned for sure!

5. You must have a key to acces modmenu within `Nova Launcher`. Get a key [here](https://vimeo.com/1095182829/b14412f5f5) after you got a key, just Copy the key! and save that key in your android note app you will need that for login to modmenu.

6. TMH Virtual version is installed succesfully! but **your account is still not safe from banned**. So before you open mlbb game from `Nova Launcher` make sure you follow this [guide](https://www.patreon.com/posts/guide-how-to-not-130259867?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link)

7. After you complete step 6, now you're safe to play MLBB, open `Nova Launcher` start Mobile Legends, then when modmenu appear paste your `Key`, and click `Login` 

> enjoy and outplay your enemy ;)

## FAQ

> <details><summary> Click this text to get Answered?</summary>
> Answered
</details>

**<details><summary>1. is it safe?</summary>**
<p>
I can not guarantee you that this mod is 100% safe from being banned, but i can minimize the banned risk up to 98% as long as you follow my guidance

Why 98% its because the rest 2 % is depend on your playstyle and report from other player

Playstyle means your behavior when using mod "dont make it too obvious" it will lead you to report by others player.

As long as you follow [this guide](https://www.patreon.com/posts/guide-how-to-not-130259867?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link) consistently your account will be safe.
</p>
</details>

**<details><summary>2. Why not share bypass guide in public?</summary>**
<p>
Offcourse due to avoid m00nt0n detection.
The less people knows is better, so keep this <a href="https://www.patreon.com/checkout/themaphack?rid=26019842">valuable </a> info just for yourself
</p>
</details>

**<details><summary>3. Why key duration is only for 24h ?</summary>**
<p>
Our keygen server has limited resources so by limit duration it will minimize server load
</p>
</details>

**<details><summary>4. Why only maphack and ESP, Where the other features (room info, auto retri, enemy cooldown, auto combo heroes, etc) ?</summary>**
<p>
I made it like that on purpose because features you mentioned above had high banned rate.

Considering that TMH source code is not obfuscated, it will be so easy for antich**t system to detect.
</p>
</details>

**<details><summary>5. Can i have web panel source code that you used in your keygen web?</summary>**
<p>
Absolutely yes, <a href="https://www.patreon.com/c/themaphack/membership?">Download here</a>
</p>
</details>

## Support

<a href="https://www.patreon.com/themaphack">
	<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## License

> Released under <a href="/LICENSE">GNU GPL V3</a> by <a href="https://github.com/anggorodhanumurti">@anggorodhanumurti</a>.

> Twitter [@casperspy](https://twitter.com/casperspy)