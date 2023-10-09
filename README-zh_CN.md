# NotoCJK (Modded by Bejukoro)
[![Download](https://img.shields.io/github/downloads/bejukoro/notocjk-with-inter/total.svg)](https://github.com/bejukoro/notocjk-with-inter/releases)

[English](./README.md) | 简体中文

适用于 Android 设备的 [NotoSansCJK 和 NotoSerifCJK](https://github.com/googlefonts/noto-cjk) 全字重补丁。同时，使用[煮豆黑体](https://github.com/Buernia/Zhudou-Sans)、[Inter](https://rsms.me/inter/) 和 [Hack](https://sourcefoundry.org/hack/) 替换了 CJK 标点、拉丁文和等宽字体。 

- NotoSansCJK 可变字体的全字重支持适用于 Android O+。
- NotoSerifCJK 可变字体的全字重支持适用于 Android P+。
- 本项目中的 Inter 字体固定启用了其 cv05（手写风格的小写 L）和 cv08（衬线风格的大写 i）两个 OpenType 特性。同时也去除了左右引号（“” & ‘’），以调用 CJK 字体的引号。
- 本项目中的煮豆黑体固定启用了其 ss02（蝌蚪形逗号）的 OpenType 特性。

字体由 Google、Buernia、rsms 和 Source Foundry 提供。

## 注意事项

您应使用最新版本的 [Magisk Manager](https://github.com/topjohnwu/Magisk/releases) 来安装此模块。如果您在通过 Magisk Manager 安装时遇到了任何问题，请尝试通过 Recovery 模式安装它。

### Known issues

The Zhudou Sans in this module currently only supports Simplified Chinese punctuation. This issue will be improved later.

HK fonts style is pending & waiting for Google solution in later android versions.

Font weight in Firefox is not current (all be thin) if force it to use Noto Sans CJK VF. ([Original repo #28](https://github.com/simonsmh/notocjk/issues/28))

Android 12 may crash in some app after installed version 10 and above with Magisk Hide enabled. See: (Chinese only, more details of logs in comments) https://t.me/magiskalpha/297

## Credit

- 本 Magisk 模块是在 simonsmh 制作的 [notocjk](https://github.com/simonsmh/notocjk) 模块基础上修改而来。非常感谢原版模块的开发者的工作。
  - 若您希望在不改变 Android 默认的拉丁字体的情况下为 NotoSansCJK & NotoSerifCJK 添加全字重支持，请移步上述原版模块。
- 在 [GitHub](https://github.com/bejukoro/notocjk-with-inter) 上标星此模块。