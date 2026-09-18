<div align="center">

# 🪷 S-004 · Starryear-Monet-Stamp 星年莫奈印章

**把一张真实照片转译为摄影证据、符号印记与莫奈记忆共存的旅行档案。**

![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=for-the-badge&logo=openai&logoColor=white)
[![Usage](https://img.shields.io/badge/Usage-Personal%20%26%20Non--commercial-lightgrey?style=for-the-badge)](./LICENSE.md)
![Language](https://img.shields.io/badge/Language-中文%20%7C%20English-blue?style=for-the-badge)

</div>

---

## ⚠️ 声明

> **仅限个人学习、非营利研究与非商业创作。**任何商业使用均须事先取得 Starryear年 的书面许可。分享作品时，欢迎标注来源并 **@Starryear年**。

## 📖 关于本项目

本 Skill 以照片为唯一视觉证据，将同一场景依次保存、压缩并重构为三层旅行档案；地点不确定时用真实可见的场景身份替代猜测，让作品完整而不虚构。

- ✅ 忠实保留摄影证据，并从当前照片生成独有符号、色彩与邮戳。
- ✅ 将下部重构为明亮、透气、源色可辨的印象派记忆，而非滤镜。
- ❌ 不猜测知名景点，不复制具体莫奈画作，不套用固定复古模板。

> Skill 内含语义对齐的中文与英文完整提示词。

## 🖼️ 示例作品

> 测试通过后补充。当前 `assets/examples/` 保持为空，不放置参考图、测试图或临时生成图。

## 📋 目录

- [使用方法](#-使用方法)
- [可自由调整的部分](#️-可自由调整的部分)
- [核心原则](#-核心原则)
- [内容结构](#-内容结构)
- [许可证](#-许可证)

## 🚀 使用方法

### 方式一：作为 Codex Skill 使用

1. 将 `starryear-monet-stamp` 文件夹复制到 `~/.codex/skills/`。
2. 开启新对话，上传一张自己的旅行、建筑、风景、街景或安静纪实照片。
3. 输入：`使用 $starryear-monet-stamp 制作这张照片；地点是杭州西湖。`

若地点不确定，可以不提供；Skill 会在无法可靠验证时使用可观察场景名。

### 方式二：直接使用完整提示词

| 语言 | 文件 |
| :---: | :--- |
| 中文 | [references/starryear-monet-stamp-prompt.zh-CN.md](references/starryear-monet-stamp-prompt.zh-CN.md) |
| English | [references/starryear-monet-stamp-prompt.en.md](references/starryear-monet-stamp-prompt.en.md) |

## 🎛️ 可自由调整的部分

| 参数 | 说明 |
| :--- | :--- |
| 地点信息 | 已知时直接提供到可靠层级；未知时保持为空。 |
| 场景标题 | 可提供用户偏好的英文场景名，但不得伪装成未经证实的地名。 |
| 纸张老化 | 可在“极轻”到“克制”之间调整，始终保持 80–90% 干净透气。 |
| 信息密度 | 可减少说明文字，但下部必须保持英文且保留档案层级。 |

## 💡 核心原则

1. **证据优先** — 用户地点与照片可见证据决定身份，设计需要不能替代事实。
2. **一图一印** — 符号、色彩、重构、场景名与邮戳都由当前照片重新生成。
3. **三态分明** — 上部是照片，中部是结构压印，下部是重新编排的绘画记忆。
4. **明亮克制** — 旧纸与印刷痕迹服务于档案感，不覆盖源色、光线和空气。

## 📁 内容结构

```text
starryear-monet-stamp/
├── README.md
├── LICENSE.md
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── starryear-monet-stamp-prompt.zh-CN.md
│   └── starryear-monet-stamp-prompt.en.md
└── assets/examples/
```

> 初版测试包中的 `assets/examples/` 必须为空。仅在 Starryear年 确认测试通过后，加入其提供或明确认可的最终成品图。

## 📄 许可证

本项目采用 [LICENSE.md](./LICENSE.md) 中规定的使用条款。

<div align="center">

**如果这个项目对你有帮助，欢迎 Star ⭐ 支持！**

</div>
