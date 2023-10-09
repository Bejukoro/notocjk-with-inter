# NotoCJK (Modded by Bejukoro)
[![Download](https://img.shields.io/github/downloads/bejukoro/notocjk-with-inter/total.svg)](https://github.com/bejukoro/notocjk-with-inter/releases)

English | [简体中文](./README-zh_CN.md)

[NotoSansCJK & NotoSerifCJK](https://github.com/googlefonts/noto-cjk) full weight patch for Android devices. And replaced the CJK punctuation, default Latin and monospace font with [Zhudou Sans](https://github.com/Buernia/Zhudou-Sans), [Inter](https://rsms.me/inter/) and [Hack](https://sourcefoundry.org/hack/).

* NotoSansCJK VF support as full weight patch applies to Android O+. 
* NotoSerifCJK full weight patch applies to Android P+.
* In this repo, the Inter font has permanently enabled its cv05 (lowercase L with tail) and cv08 (uppercase i with serif) two OpenType features. It also removed the left and right quotation marks (“” & ‘’) to invoke the left and right quotation marks of the CJK font.
* In this repo, the Zhudou Sans font has permanently enabled its ss02 (Tadpole-shaped comma) OpenType features.

<!--
## Maintenance
Currently, this module is still maintained. You can download it directly in this repo's [release tabs](https://github.com/bejukoro/notocjk-with-inter/releases).
-->

## NOTICE

You should use the latest [Magisk](https://github.com/topjohnwu/Magisk/) Manager or [KernelSU](https://kernelsu.org/) Manager to install this module.

If you install this module through Magisk Manager, when updating the module, you only need to overwrite the new version of the module; however, if you install it through KernelSU Manager, please uninstall the old version of this module first and restart your device, then reinstall the new version of this module.

If you meet any problem under installation from Magisk Manager, please try to install it from recovery.

### Known issues

- HK fonts style is pending & waiting for Google solution in later android versions.
- Font weight in Firefox is not current (all be thin) if force it to use Noto Sans CJK VF. ([Original repo #28](https://github.com/simonsmh/notocjk/issues/28))
- Android 12 may crash in some app after installed version 10 and above with Magisk Hide enabled. See: (Chinese only, more details of logs in comments) https://t.me/magiskalpha/297

## Credit

* This Magisk module is modified based on [notocjk](https://github.com/simonsmh/notocjk) by simonsmh. Very grateful for the work of the original module developer. 
  * If you wish to add full weight support for NotoSansCJK & NotoSerifCJK without changing the default Latin font of Android, please go to the the original repo.
* Star this module at [GitHub](https://github.com/bejukoro/notocjk-with-inter).