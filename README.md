## Auto-Language 版本说明（2026-02-28）

本仓库是基于原项目的定制 Fork，重点是实现 **中英文自动切换**（含简体/繁体中文）。

### 本版本特点
- 根据系统语言自动切换界面文案：中文系统显示中文（简体/繁体按地区），非中文系统默认英文。
- 将注入式对话框和 Toast 文案统一接入 i18n，减少硬编码英文文本。
- 补充了配置导入/导出、状态提示等场景的中英文资源。
- 已在 Android Studio 打包 debug APK 并验证可正常使用。

### 改动者与当前版本
- 改动者：**Codex（GPT-5）**
- 当前版本标识：**auto-language**
- README 说明更新日期：**2026-02-28**

### 改动文件（自动语言切换相关）
- `app/src/main/java/ps/reso/instaeclipse/utils/i18n/I18n.java` (new)
- `app/src/main/java/ps/reso/instaeclipse/utils/dialog/DialogUtils.java`
- `app/src/main/java/ps/reso/instaeclipse/mods/ui/UIHookManager.java`
- `app/src/main/java/ps/reso/instaeclipse/utils/ghost/GhostModeUtils.java`
- `app/src/main/java/ps/reso/instaeclipse/mods/devops/config/ConfigManager.java`
- `app/src/main/java/ps/reso/instaeclipse/mods/devops/config/JsonExportActivity.java`
- `app/src/main/java/ps/reso/instaeclipse/mods/devops/config/JsonImportActivity.java`
- `app/src/main/java/ps/reso/instaeclipse/utils/version/VersionCheckUtility.java`
- `app/src/main/res/values/strings.xml`
- `app/src/main/res/values-zh-rCN/strings.xml`
- `app/src/main/res/values-zh-rTW/strings.xml`

---

<p align="center">
  <img src="https://github.com/ReSo7200/InstaEclipse/blob/main/assets/logo.png" alt="InstaEclipse Logo" width="200"/>
</p>

# InstaEclipse ⚡ Enhance Your Instagram Experience!

InstaEclipse is an **LSPosed module** designed to enhance your Instagram experience with advanced features like developer options, ghost mode, distraction-free mode, and more! 🚀

This module is built to stay compatible with **new Instagram releases** by leveraging dynamic analysis to locate targeted classes and methods automatically. 🧠✨

[Telegram Channel](https://t.me/InstaEclipse)

<details>
<summary><h2>✨ Features </h2></summary>

### 🎛️ Developer Options
- Access hidden developer tools within Instagram for advanced functionality.
- Import/Export config.
- **Note:** These options are intended for use with **Alpha** or **Beta** versions of Instagram. (Beta is better) 

### 👻 Ghost Mode
- Stay incognito while browsing stories, lives, or DMs.
- Mark messages as read (Hold on the Gallery icon inside the DM)
- No screenshot notifications sent.
- View "view once" media more than once.
- Hide your typing status in DMs.

### 🧘 Distraction-Free Mode
- Enjoy Instagram without stories, reels, or explore feed distractions.  
- **Important:** After enabling Distraction-Free Mode:  
  1. **Force stop Instagram**.  
  2. **Clear Instagram's cache**.  
  3. Launch Instagram for a clean experience.

### 🚫 Remove Ads
- Get rid of all Instagram ads.

### 📉 Remove Analytics
- Block Instagram's tracking and analytics to protect your privacy.  
- Prevent unnecessary data sharing and usage metrics.

### 🔧 Misc Options
- Disable Auto Story Flipping.  
- Disable Auto Play Videos.
- Follower indicator
</details>


<details>
<summary><h2>🛠️ Installation Instructions</h2></summary>

⚠️ Install Instagram from [APKMirror](https://www.apkmirror.com/apk/instagram/instagram-instagram/), as the module may not fully support Google Play Store versions.

---

 **Install the Module**  
- Download and install the **InstaEclipse APK**. You can find the latest release [here](https://github.com/ReSo7200/InstaEclipse/releases).

### ✅ Root Users (LSPosed)


1️⃣ **Enable the Module in LSPosed**  
- Make sure you're using the latest **LSPosed fork by [JingMatrix](https://github.com/JingMatrix/LSPosed)**.  
- Open **LSPosed Manager** and enable **InstaEclipse** for the **Instagram app**.

2️⃣ **Access the Features**  
- Open **Instagram**, then **long-press the search icon** to access InstaEclipse settings.

---

### 🟡 Non-Root Users (LSPatch)

1️⃣ **Install LSPatch (JingMatrix Fork)**  
- Download and install the **LSPatch fork by [JingMatrix](https://github.com/JingMatrix/LSPatch)**.

2️⃣ **Patch Instagram**  
- Patch the **installed Instagram** or an **APK**.
- Use **Local Patch Mode**.
- Enable **"Inject loader dex"** in patch settings.
- Install the patched APK and log in to Instagram.

3️⃣ **Enable the Module in LSPatch**  
- Reopen **LSPatch**, go to the module list, and enable **InstaEclipse** for **Instagram**.

4️⃣ **Access the Features**  
- Open **Instagram**, then **long-press the search icon** to access InstaEclipse settings.

</details>


<details>

<summary><h2> 📖 FAQ </h2></summary>

### ❓ Module not enabled/Features not working?
Disable and re-enable the module in LSPosed/LSPatch.
Force stop and restart Instagram.

### ❓ Why are some labels obfuscated or numbered?
This is due to obfuscation in **Stable** versions of Instagram. Use **Beta** or **Alpha** versions to avoid this.

### ❓ Distraction-Free Mode enabled, but content still appears?
Force stop Instagram and **clear its cache** to apply the changes properly.

</details>

<details>
<summary><h2>📂 Resources </h2></summary>

- 🐙 **GitHub Repository:** [Explore InstaEclipse](https://github.com/ReSo7200/InstaEclipse)  
- 💬 **Support & Updates:** [Telegram Channel](https://t.me/InstaEclipse)  
- ⚙️ **LSPosed - Fork By [JingMatrix](https://github.com/JingMatrix/)** [LSPosed](https://github.com/JingMatrix/LSPosed)


</details>

## 🎉 Contributors

### 👑 Project Owner
- [ReSo7200](https://github.com/ReSo7200/)

### 💡 Contributors
- [frknkrc44](https://github.com/frknkrc44)
- [BrianML](https://github.com/brianml31)
- [silvzr](https://github.com/silvzr)
- [oct888](https://github.com/oct888)
- [HalfManBear](https://github.com/halfmanbear)
- [ar5to](https://github.com/ar5to)

## 🙌 Special Thanks
- [xHookman](https://github.com/xHookman)  
- **Amàzing World**  
- **Bluepapilte (MyInsta Mod Owner)** [Telegram](https://t.me/instasmashrepo)  
- **BdrcnAYYDIN** [Telegram](https://t.me/BdrcnAYYDIN)  


### 🌍 Translation Contributors  
A heartfelt thank you to everyone who contributed to translating InstaEclipse into multiple languages. Your efforts help make the module accessible to users worldwide! 🌟


## 🛠️ Powered By

- [JingMatrix/LSPosed](https://github.com/JingMatrix/LSPosed), the foundation for module functionality.
- [LuckyPray/DexKit](https://github.com/LuckyPray/DexKit), enabling dynamic analysis for compatibility with new Instagram updates.  


### 💡 Contributions
We welcome contributions from everyone!  
- **Have an idea?** Open an issue or submit a feature request.  
- **Found a bug?** Report it through our [GitHub Issues](https://github.com/ReSo7200/InstaEclipse/issues).  
- **Want to help?** Submit a pull request to improve InstaEclipse.

> Every contribution, big or small, is highly valued. Thank you for helping us grow!
