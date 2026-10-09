# 🇮🇷 Welcome to FarsiForge!

<p align="center">
  <b>Empowering Persian Gamers | Open-Source Localization & Reverse Engineering Tools</b>
</p>

FarsiForge is an open-source, community-driven initiative dedicated to bringing video games to Persian-speaking audiences. We build high-quality, robust tools that handle the heavy lifting of game localization—from text extraction and injection to RTL (Right-to-Left) rendering and installer generation.

## 🚀 Core Projects

### [🔨 FarsiForge](https://github.com/FarsiForge-dev/FarsiForge)
The ultimate professional toolkit for video game localization. It automatically detects game engines, extracts translatable text, applies RTL processing and Arabic shaping for Persian fonts, and builds ready-to-use patch installers.

### [🛠️ FarsiForgeTools](https://github.com/FarsiForge-dev/FarsiForgeTools)
Engine-specific utilities and generic CLI tools for advanced text manipulation and archiving. Features support for Unreal Engine (`.locres`), Godot (`.pck`), Unity, and various other custom engine formats.

---

## 🧰 FarsiForge Toolchain & Forked Tools
We maintain forks of essential reverse engineering and localization tools to ensure they stay available, stable, and can be extended with RTL/Persian-specific features. Here is a map of the tools available in our organization:

### 🟩 Unity Engine
* **[AssetRipper](https://github.com/FarsiForge-dev/AssetRipper):** Comprehensive asset extraction (models, textures, text).
* **[UABEA](https://github.com/FarsiForge-dev/UABEA) / [AssetsTools.NET](https://github.com/FarsiForge-dev/AssetsTools.NET):** Reading, extracting, and modifying Unity asset bundles.
* **[Il2CppDumper](https://github.com/FarsiForge-dev/Il2CppDumper) / [Cpp2IL](https://github.com/FarsiForge-dev/Cpp2IL):** Decompiling and analyzing Unity IL2CPP games.
* **[BepInEx](https://github.com/FarsiForge-dev/BepInEx) / [HarmonyX](https://github.com/FarsiForge-dev/HarmonyX) / [Il2CppInterop](https://github.com/FarsiForge-dev/Il2CppInterop):** The standard modding frameworks and hooks for injecting custom DLLs into Unity games.
* **[XUnity.AutoTranslator](https://github.com/FarsiForge-dev/XUnity.AutoTranslator):** On-the-fly text translation plugin.
* **[UnityPy](https://github.com/FarsiForge-dev/UnityPy):** Python library for scripting Unity asset modifications.

### 🟦 Unreal Engine
* **[FModel](https://github.com/FarsiForge-dev/FModel):** Exploring and extracting Unreal Engine `.pak`, `.utoc`, and `.ucas` archives.
* **[UnrealLocres](https://github.com/FarsiForge-dev/UnrealLocres):** Extracting and packing Unreal Engine localization (`.locres`) files.
* **[repak](https://github.com/FarsiForge-dev/repak) / [retoc](https://github.com/FarsiForge-dev/retoc):** CLI utilities for packing and unpacking Unreal Engine archives.
* **[UAssetGUI](https://github.com/FarsiForge-dev/UAssetGUI):** Low-level editor for Unreal Engine `.uasset` and `.uexp` files.

### 🟦 Godot & 🟨 GameMaker
* **[Godot RE Tools (gdsdecomp)](https://github.com/FarsiForge-dev/gdsdecomp):** Full decompilation and asset extraction for Godot `.pck` files.
* **[UndertaleModTool](https://github.com/FarsiForge-dev/UndertaleModTool):** The ultimate tool for reverse engineering and localizing GameMaker Studio games.

### 🔬 General Reverse Engineering & Debugging
* **[Ghidra](https://github.com/FarsiForge-dev/ghidra):** NSA's powerful reverse engineering framework.
* **[x64dbg](https://github.com/FarsiForge-dev/x64dbg):** The standard open-source x64/x32 debugger for Windows.
* **[dnSpy](https://github.com/FarsiForge-dev/dnSpy) / [ILSpy](https://github.com/FarsiForge-dev/ILSpy):** .NET decompilers and assembly editors.
* **[ImHex](https://github.com/FarsiForge-dev/ImHex):** Advanced hex editor for data analysis.
* **[QuickBMS](https://github.com/FarsiForge-dev/QuickBMS):** Universal script-based archive extractor and reimporter.
* **[Steamless](https://github.com/FarsiForge-dev/Steamless):** DRM remover for Steam stub executables.
* **[Detect-It-Easy](https://github.com/FarsiForge-dev/Detect-It-Easy):** Identifying engine, compiler, and packer signatures.

### 🎨 Fonts, Text, and Automation (Python & CLI)
* **[fonttools](https://github.com/FarsiForge-dev/fonttools) / [fontforge](https://github.com/FarsiForge-dev/fontforge):** Creating, editing, and patching fonts to support Persian glyphs.
* **[python-arabic-reshaper](https://github.com/FarsiForge-dev/python-arabic-reshaper) & [python-bidi](https://github.com/FarsiForge-dev/python-bidi):** Essential Python libraries for correcting RTL (Right-to-Left) and isolated Arabic/Persian letters in games without native support.
* **[vazirmatn](https://github.com/FarsiForge-dev/vazirmatn):** The standard open-source Persian font.
* **[ImageMagick](https://github.com/FarsiForge-dev/ImageMagick):** CLI tool for texture/image manipulation.
* **[jq](https://github.com/FarsiForge-dev/jq):** Swiss-army knife for parsing JSON localization data.

---

## 🌍 Our Mission
We believe language shouldn't be a barrier to enjoying great stories. By providing automated, scriptable, and easy-to-use tools, we help translators and modders focus on what they do best: *translating*. 

* **Automated Workflows:** Say goodbye to hex-editing strings manually. 
* **Seamless RTL Support:** Overcoming the hardest challenge in Persian localization with built-in text reshaping and font fixes.
* **Open & Collaborative:** Built transparently on GitHub, for the community.

## 🤝 Get Involved!
Whether you're a translator, reverse engineer, or developer (C#, Python, C++), we welcome your contributions!
- Check out our [Repositories](https://github.com/orgs/FarsiForge-dev/repositories) and start contributing.
- Found a bug or have a feature request? Feel free to open an issue in the respective repository.

<br>
<p align="center">
  <i>Made with ❤️ for the Persian gaming community.</i>
</p>

<br>
<hr>
<br>

<div dir="rtl">

# 🇮🇷 به FarsiForge خوش آمدید!

<p align="center">
  <b>توانمندسازی گیمرهای ایرانی | ابزارهای متن‌باز برای بومی‌سازی و مهندسی معکوس</b>
</p>

پروژه FarsiForge یک ابتکار متن‌باز و جامعه‌محور است که با هدف فارسی‌سازی بازی‌های ویدیویی فعالیت می‌کند. ما ابزارهای حرفه‌ای و قدرتمندی می‌سازیم که بخش‌های سخت و پیچیده‌ی بومی‌سازی بازی‌ها—از استخراج و تزریق متن گرفته تا رندر راست‌چین (RTL) و ساخت نصب‌کننده‌ها—را بر عهده می‌گیرند.

## 🚀 پروژه‌های اصلی

### [🔨 FarsiForge](https://github.com/FarsiForge-dev/FarsiForge)
کامل‌ترین ابزار حرفه‌ای برای بومی‌سازی بازی‌های ویدیویی. این برنامه به‌طور خودکار موتور بازی را تشخیص می‌دهد، متن‌های قابل ترجمه را استخراج می‌کند، پردازش‌های مربوط به راست‌چین‌سازی (RTL) و چسباندن حروف فارسی را اعمال کرده، و در نهایت نصب‌کننده‌ی پچ (پچ‌ساز) را تولید می‌کند.

### [🛠️ FarsiForgeTools](https://github.com/FarsiForge-dev/FarsiForgeTools)
مجموعه‌ای از ابزارهای خط‌فرمان (CLI) و پردازشگرهای تخصصی برای دستکاری متن‌ها در موتورهای مختلف. پشتیبانی از آنریل انجین (`.locres`)، گودو (`.pck`)، یونیتی و فرمت‌های اختصاصی دیگر.

---

## 🧰 زنجیره ابزار و برنامه‌های فورک‌شده
ما نسخه‌های فورک‌شده‌ی ابزارهای ضروری مهندسی معکوس و بومی‌سازی را نگهداری می‌کنیم تا همواره در دسترس و پایدار باشند و بتوانیم ویژگی‌های مخصوص زبان فارسی/راست‌چین را به آن‌ها اضافه کنیم. در اینجا نقشه‌ی ابزارهای موجود در سازمان ما را می‌بینید:

### 🟩 یونیتی (Unity Engine)
* **[AssetRipper](https://github.com/FarsiForge-dev/AssetRipper):** استخراج جامع فایل‌ها (مدل‌ها، تکسچرها، متون).
* **[UABEA](https://github.com/FarsiForge-dev/UABEA) / [AssetsTools.NET](https://github.com/FarsiForge-dev/AssetsTools.NET):** خواندن، استخراج و ویرایش فایل‌های Asset Bundle در یونیتی.
* **[Il2CppDumper](https://github.com/FarsiForge-dev/Il2CppDumper) / [Cpp2IL](https://github.com/FarsiForge-dev/Cpp2IL):** دی‌کامپایل و تحلیل بازی‌های IL2CPP.
* **[BepInEx](https://github.com/FarsiForge-dev/BepInEx) / [HarmonyX](https://github.com/FarsiForge-dev/HarmonyX) / [Il2CppInterop](https://github.com/FarsiForge-dev/Il2CppInterop):** فریم‌ورک‌های استاندارد مادسازی و هوک برای تزریق فایل‌های DLL کاستوم به بازی‌های یونیتی.
* **[XUnity.AutoTranslator](https://github.com/FarsiForge-dev/XUnity.AutoTranslator):** پلاگین ترجمه لحظه‌ای (On-the-fly) متن بازی.
* **[UnityPy](https://github.com/FarsiForge-dev/UnityPy):** کتابخانه پایتون برای اسکریپت‌نویسی و دستکاری اسِت‌های یونیتی.

### 🟦 آنریل انجین (Unreal Engine)
* **[FModel](https://github.com/FarsiForge-dev/FModel):** بررسی و استخراج فایل‌های `.pak`، `.utoc` و `.ucas` در آنریل انجین.
* **[UnrealLocres](https://github.com/FarsiForge-dev/UnrealLocres):** استخراج و بسته‌بندی فایل‌های متنی (`.locres`) آنریل.
* **[repak](https://github.com/FarsiForge-dev/repak) / [retoc](https://github.com/FarsiForge-dev/retoc):** ابزارهای خط‌فرمان برای پکینگ و آنپکینگ فایل‌های بازی.
* **[UAssetGUI](https://github.com/FarsiForge-dev/UAssetGUI):** ویرایشگر سطح پایین برای فایل‌های `.uasset` و `.uexp`.

### 🟦 گودو و 🟨 گیم‌میکر (Godot & GameMaker)
* **[Godot RE Tools (gdsdecomp)](https://github.com/FarsiForge-dev/gdsdecomp):** دی‌کامپایل کامل و استخراج فایل‌های `.pck` بازی‌های گودو.
* **[UndertaleModTool](https://github.com/FarsiForge-dev/UndertaleModTool):** ابزار نهایی برای مهندسی معکوس و بومی‌سازی بازی‌های ساخته شده با GameMaker Studio.

### 🔬 مهندسی معکوس و دیباگ (General RE)
* **[Ghidra](https://github.com/FarsiForge-dev/ghidra):** فریم‌ورک قدرتمند مهندسی معکوس متعلق به NSA.
* **[x64dbg](https://github.com/FarsiForge-dev/x64dbg):** دیباگر استاندارد و متن‌باز x64/x32 برای ویندوز.
* **[dnSpy](https://github.com/FarsiForge-dev/dnSpy) / [ILSpy](https://github.com/FarsiForge-dev/ILSpy):** دی‌کامپایلر و ویرایشگر اسمبلی برای برنامه‌های دات‌نت (.NET).
* **[ImHex](https://github.com/FarsiForge-dev/ImHex):** ویرایشگر Hex پیشرفته برای تحلیل داده‌ها.
* **[QuickBMS](https://github.com/FarsiForge-dev/QuickBMS):** ابزار همه‌کاره مبتنی بر اسکریپت برای استخراج و بازگردانی فایل‌های فشرده‌ی بازی‌ها.
* **[Steamless](https://github.com/FarsiForge-dev/Steamless):** ابزاری برای حذف DRM استیم از فایل‌های اجرایی (exe).
* **[Detect-It-Easy](https://github.com/FarsiForge-dev/Detect-It-Easy):** تشخیص انجین، کامپایلر و پروتکتور (پکر) بازی.

### 🎨 فونت، متن و اتوماسیون (Python & CLI)
* **[fonttools](https://github.com/FarsiForge-dev/fonttools) / [fontforge](https://github.com/FarsiForge-dev/fontforge):** ساخت، ویرایش و پچ کردن فونت‌ها جهت اضافه کردن کاراکترهای فارسی.
* **[python-arabic-reshaper](https://github.com/FarsiForge-dev/python-arabic-reshaper) و [python-bidi](https://github.com/FarsiForge-dev/python-bidi):** کتابخانه‌های ضروری پایتون برای اصلاح متون راست‌چین (RTL) و رفع مشکل جداجدا نوشته شدن حروف فارسی در بازی‌هایی که پشتیبانی بومی ندارند.
* **[vazirmatn](https://github.com/FarsiForge-dev/vazirmatn):** فونت استاندارد و متن‌باز فارسی (وزیرمتن).
* **[ImageMagick](https://github.com/FarsiForge-dev/ImageMagick):** ابزار خط‌فرمان برای دستکاری و تغییر فرمت تکسچرها و عکس‌ها.
* **[jq](https://github.com/FarsiForge-dev/jq):** ابزاری همه‌کاره برای پردازش داده‌های متنی با فرمت JSON.

---

## 🌍 ماموریت ما
ما معتقدیم زبان نباید مانعی برای لذت بردن از داستان‌های فوق‌العاده باشد. با فراهم کردن ابزارهای خودکار، قابل اسکریپت‌نویسی و کاربرپسند، به مترجم‌ها و مادسازها کمک می‌کنیم روی کاری تمرکز کنند که در آن بهترین هستند: *ترجمه*.

* **روندهای کاری خودکار:** با ویرایش هگز (Hex-editing) دستی رشته‌ها خداحافظی کنید.
* **پشتیبانی بی‌نقص از RTL:** غلبه بر سخت‌ترین چالش در فارسی‌سازی با راهکارهای داخلی برای اصلاح فونت و فرم حروف.
* **باز و مشارکتی:** ساخته شده به صورت شفاف در گیت‌هاب، توسط کاربران و برای کاربران.

## 🤝 به ما بپیوندید!
چه مترجم باشید، چه مهندس معکوس و چه برنامه‌نویس (C#، Python، C++)، ما از مشارکت شما استقبال می‌کنیم!
- [ریپازیتوری‌های ما](https://github.com/orgs/FarsiForge-dev/repositories) را ببینید و شروع به مشارکت کنید.
- باگی پیدا کردید یا ایده‌ای دارید؟ کافیست در ریپازیتوری مربوطه یک Issue ثبت کنید.

</div>
