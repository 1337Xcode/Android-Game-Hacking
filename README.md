<h1 align="center">Android Game Hacking</h1>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![GitHub Issues](https://img.shields.io/github/issues/1337Xcode/Android-Game-Hacking.svg)](https://github.com/1337Xcode/Android-Game-Hacking/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/1337Xcode/Android-Game-Hacking.svg)](https://github.com/1337Xcode/Android-Game-Hacking/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

## About

This repository is a compilation of tools, utilities, and mod menu source codes designed for hacking and modding Android games.

## Disclaimer
> ### Legal Disclaimer
> For any inquiries or concerns regarding the content of this repository or If you believe any content should be removed for legal or ethical reasons, please reach out to discuss further on Telegram [@XCode](https://t.me/XCode).

The content provided in this repository is for educational and research purposes only. Use of the information and tools for any unauthorized or illegal activities is strictly prohibited. The authors and contributors of this repository are not liable for any misuse or consequences resulting from the use of this content.

## To-Do

- [ ] Add more mod menu templates.
- [ ] Include additional hooking libraries and templates.
- [ ] Add list of dumping tools for UE4 and Unity engines to [Categories](#Categories).
- [ ] Include repositories with specific game hacking sources.
- [ ] Add detailed guides to game modding.

## Categories
> Organized for easy browsing—pick your poison!

<details>
<summary><b>1. Mod Menu Templates</b></summary>

<br>

<details style="margin-left: 20px;">
<summary><i>1.1 Internal Mod Menu Templates</i></summary>

| Link | Description |
| --- | --- |
| [Android-Mod-Menu](https://github.com/LGLTeam/Android-Mod-Menu) | A Java based mod menu template for Unity (portable to any) |
| [Android-Login-Form-Java](https://github.com/LGLTeam/Android-Login-Form-Java) | A Java based menu template with simple login form. |
| [Android-Hooking-Patching-Template](https://github.com/LGLTeam/Android-Hooking-Patching-Template) | A Hooking and Patching menu template for Android. |
| [Mod-Menu-Without-Overlay-Permission-Demo](https://github.com/LGLTeam/Mod-Menu-Without-Overlay-Permission-Demo) | A mod menu template without overlay permission requirement. |
| [Android-Mod-Menu-Animation](https://github.com/LGLTeam/Android-Mod-Menu-Animation) | A mod menu template with animation. |
| [VipMod-Mod-Menu-With-Canvas](https://github.com/LGLTeam/VipMod-Mod-Menu-With-Canvas) | A Canvas based mod menu template. |
| [Android-Mod-Menu-Kotlin](https://github.com/LGLTeam/Android-Mod-Menu-Kotlin) | A Kotlin based mod menu template. |
| [UnityModMenuAndroid](https://github.com/AndnixSH/UnityModMenuAndroid) | A Unity DLL mod menu template. |
| [ImGui-Android-Mod-Menu](https://github.com/FrenchModding/ImGui-Android-Mod-Menu) | An ImGui based mod menu source for Unity. |
| [Android-Mod-Menu-ImGui](https://github.com/gameSecMaterials/Android-Mod-Menu-ImGui) | An ImGui based mod menu template for Unity3D (ex. Granny 3). |
| [Android-Mod-Menu-ImGui](https://github.com/c4-off/Android-Mod-Menu-ImGui) | An Advanced ImGui based mod menu template for Unity. |
| [Android_ImGui_Surface_Mod_Menu_Template](https://github.com/LaughingMuffin/android_imgui_surface_mod_menu_template) | An ImGUI GLSurfaceView based mod menu template. |
| [Android-ImGui-Mod-Menu](https://github.com/reveny/Android-ImGui-Mod-Menu) | An ImGui menu template with remap hide for Unity (portable to UE4) |

</details>

<details style="margin-left: 20px;">
<summary><i>1.2 External Mod Menu Templates</i></summary>

:warning: **Warning:** Intermediate knowledge of C++ required for module based templates to avoid bootloops.

| Link | Description |
| --- | --- |
| [Zygisk-ImGui-Mod-Menu](https://github.com/reveny/Zygisk-ImGui-Mod-Menu) | A Zygisk module based ImGui menu template. |
| [Zygisk-ImGui-Menu](https://github.com/fedes1to/Zygisk-ImGui-Menu) | A Zygisk module based ImGui menu template for Unity (portable) |
| :x: | Application-based sources will be added soon.
</details>

</details>

<details>
<summary><b>2. Modding And Reversing Tools</b></summary>

<br>

<details>
  <summary><i>2.1 Disassemblers</i></summary>

| Tool Link                                                      | Description                                         |
| --- | --- |
| [IDA Pro](https://www.hex-rays.com/products/ida/)              | Interactive Disassembler.                           |
| [Ghidra](https://ghidra-sre.org/)                              | Software reverse engineering suite.                 |
| [radare2](https://github.com/radareorg/radare2)                | UNIX-like reverse engineering framework and command-line toolset. |
</details>

<details>
<summary><i>2.2 Decompilers</i></summary>

| Tool | Description |
|------|-------------|
| [Apktool](https://github.com/iBotPeaches/Apktool) | A tool for reverse engineering Android apk files. |
| [jadx](https://github.com/skylot/jadx) | Dex to Java decompiler. |
| [fernflower](https://github.com/fesh0r/fernflower) | Unofficial mirror of FernFlower Java decompiler. |
| [Krakatau](https://github.com/Storyyeller/Krakatau) | Java decompiler, assembler, and disassembler. |
| [Bytecode-Viewer](https://github.com/Konloch/bytecode-viewer) | Powerfull GUI for multiple decompilers like JADX, Fernflower, Krakatau, smali and co. |
| [dex2jar](https://github.com/pxb1988/dex2jar) | Tools to work with android .dex and java .class files. |

</details>

</details>

<details>
  <summary><b>3. Hooking Libraries and Templates</b></summary>

<br>

<details>
  <summary><i>3.0 General Hook Frameworks</i></summary>

| Link | Description |
| ---- | ---- |
| [Dobby](https://github.com/jmpews/Dobby) | A lightweight, multi-platform, multi-architecture hook framework.. |
| [subhook](https://github.com/zeex/subhook) | A simple hooking library for C/C++ (x86 only, 32/64-bit, no dependencies) |
| [whale](https://github.com/aslody/whale) | A hook framework for Android/IOS/Linux/MacOS. |
| [TLSHook](https://github.com/keith2018/TLSHook) | An opengl es function call hook for Android. |
</details>

<details>
  <summary><i>3.1 inline Hooks</i></summary>

| Link | Description |
| ---- | ---- |
| [And64InlineHook](https://github.com/Rprop/And64InlineHook) | Lightweight ARMv8-A(ARM64, AArch64, Little-Endian) Inline Hook Library for Android C/C++. |
| [SubstrateHook](https://github.com/Octowolve/Substrate-Hooking-Example) | A simple template for the usage example of Cydia Substrate. |
| [ShadowHook](https://github.com/bytedance/android-inline-hook) | An inline hook library for Android apps. |
| [SandHook](https://github.com/ganyao114/SandHook) | An Android Native Inline Hook. |
| [Android-Inline-Hook](https://github.com/ele7enxxh/Android-Inline-Hook) | thumb16 thumb32 arm32 inlineHook in Android. |
</details>

<details>
  <summary><i>3.2 PLT Hooks</i></summary>

| Link | Description |
| ---- | ---- |
| [xHook](https://github.com/iqiyi/xHook) | A PLT hook library for Android native ELF. |
| [bhook](https://github.com/bytedance/bhook) | A PLT hook framework for Android apps. |
| [LSPlt](https://github.com/LSPosed/LSPlt) | A Simple PLT hook for Android. |
| [plthook](https://github.com/kubo/plthook) | A Multiplatform PLT(Procedure Linkage Table) Hook. |
</details>

</details>

<details>
<summary><b>4. Memory Patching Utilities</b></summary>

<br>

<details style="margin-left: 20px;">
<summary><i>4.1 Internal Memory Patching</i></summary>

| Link | Description |
| --- | --- |
| [KittyMemory](https://github.com/MJx0/KittyMemory) | A library for runtime code patching on both Android and iOS. |
| [ByNameModding](https://github.com/ByNameModding/BNM-Android) | A library for modding il2cpp games by classes, methods, field names on Android. |
</details>

<details style="margin-left: 20px;">
<summary><i>4.2 External Memory Patching</i></summary>
  
| Link | Description |
| --- | --- |
| [KittyMemoryEx](https://github.com/MJx0/KittyMemoryEx) | A library for runtime code patching on both Android and Linux. |
| [Android-Memory-Tools](https://github.com/Anonym0usWork1221/C-Android-Memory-Tool) | A C++ tool that provides functionality for reading and writing memory of a target process. |
</details>

</details>

## Contributing

We welcome contributions from the community to enhance and expand this repository. If you have any suggestions, tools, utilities, or mod menu templates to add, please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file to submit them for consideration by creating an issue or pull request for this repository.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<p align="left"><a href="https://github.com/1337Xcode/Android-Game-Hacking#"><img src="http://randojs.com/images/backToTopButton.png" alt="Back to top" height="29"/></a></p>
