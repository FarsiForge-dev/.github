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
