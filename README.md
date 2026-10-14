<div align="center">

# 🎬 suspense-title-sequence-generator

## 6 张关键帧先锁脸，再出 15 秒片头
## Six keyframes lock the look before a 15-second title sequence

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

只给你五个变量——电影类型、片名、一句话剧情、演员表和可选参考图——它就能产出一支 15 秒 16:9 横版悬疑电影片头。执行顺序是硬性的：先确认影片资料与参考图理解，再生成 6 个关键帧生图提示词，出完 6 张关键帧锚图并请你确认，最后才基于关键帧编译视频提示词。这样做是为了避免原始人物参考图直接进视频，导致构图和身份崩坏。视觉语言固定为复古日系动画片头：硬边剪影、漫画拼贴、非对称分屏、强烈几何色块、清晰英文署名、少量日文片假名装饰，气质是 60% 悬疑加 40% 爵士。一句话剧情只用于内部推断画面意象，绝不写进最终提示词或旁白。

### ✨ 能做什么

- 只收 5 个变量（类型 / 片名 / 一句话剧情 / 演员表 / 参考图），其余走默认模板
- 先出 6 张关键帧锚图并等你确认，确认后才进入视频生成
- 参考图自动分角色：主角 / 配角 / 道具 / 场景 / 风格 / 镜头构图
- 署名只出现你提供的职位与姓名，未提供就整段删除，不自动补虚构名字
- 固定复古拼贴视觉语言加 60% 悬疑 40% 爵士，六镜各带明确图形转场
- 默认 15 秒 16:9 横版、英文片名与署名，失败先报告不自动重跑

### 📦 包含的技能

- `suspense-title-sequence-generator` —— 见 [`suspense-title-sequence-generator/SKILL.md`](suspense-title-sequence-generator/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/suspense-title-sequence-generator.git
cp -r suspense-title-sequence-generator/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Give it five variables — film genre, title, one-line logline, cast list and optional reference images — and it produces a 15-second 16:9 suspense film title sequence. The order is rigid: confirm the film data and reference-image reading, generate six keyframe image prompts, produce the six keyframe anchors and get your confirmation, and only then compile the video prompt from those keyframes. That sequencing exists to stop raw character references from going straight into video and wrecking composition and identity. The visual language is fixed retro anime-style: hard-edged silhouettes, comic collage, asymmetric split screens, strong geometric color blocks, crisp English credits and sparse katakana accents, with a mood that is 60% suspense and 40% jazz. The logline is used only to infer imagery internally and never appears in the final prompt or as narration.

### ✨ What it does

- Takes only 5 variables (genre / title / logline / cast / references) and uses defaults for everything else
- Produces the 6 keyframe anchors first and waits for confirmation before any video generation
- Classifies reference images by role: protagonist, supporting, prop, scene, style or shot reference
- Credits show only the roles and names you supply; missing roles are deleted entirely rather than invented
- Fixed retro-collage visual language with a 60% suspense, 40% jazz mood and an explicit graphic transition per shot
- Defaults to 15 seconds, 16:9, English title and credits; on failure it reports the cause instead of auto-retrying

### 📦 Skills included

- `suspense-title-sequence-generator` — [`suspense-title-sequence-generator/SKILL.md`](suspense-title-sequence-generator/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/suspense-title-sequence-generator.git
cp -r suspense-title-sequence-generator/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
