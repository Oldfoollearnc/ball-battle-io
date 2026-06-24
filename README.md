# 🏀 Ball Battle IO · 球球大作战

> **金铲铲模式 Agar.io 网页游戏** · A single-file HTML5 Agar.io-style battle game with a unique card-buff system.  
> 打开即玩，无需下载，无需服务器。 / Open and play — zero setup, zero dependencies.

[![Play Now](https://img.shields.io/badge/▶_在线游玩_Play_Now-4ecca3?style=for-the-badge)](https://oldfoollearnc.github.io/ball-battle-io/)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-important)
![Size](https://img.shields.io/badge/single_HTML-~150KB-blue)

---

## 🎮 在线游玩 / Play Online

**English**: [https://oldfoollearnc.github.io/ball-battle-io/](https://oldfoollearnc.github.io/ball-battle-io/)  
**中文**: [https://oldfoollearnc.github.io/ball-battle-io/](https://oldfoollearnc.github.io/ball-battle-io/)

Just open the link in your browser. No download, no registration, no server required.

---

## ⌨ 操作 / Controls

| 中文 | English | Key |
|------|---------|-----|
| 移动 | Move | 🖱 Mouse |
| 分裂 | Split | ␣ Space (hold for chain split) |
| 吐球 | Eject | <kbd>W</kbd> |
| 加速 | Sprint | <kbd>Shift</kbd> / Right-click |
| 聊天 | Chat | <kbd>Enter</kbd> (1-7 send, Esc close) |
| 暂停 | Pause | <kbd>Esc</kbd> |

---

## ✨ 核心特性 / Features

### 🃏 金铲铲模式 / Buff System
- **每 15 秒** 三选一强化符文 / Pick 1 of 3 buffs every **15 seconds**
- 16 种 Buff（8 普通 + 8 稀有），**可无限叠加** / 16 buffs (8 common + 8 rare), **infinitely stackable**
- AI 对手也随机获得 Buff / AI opponents also get random buffs

### 🎨 皮肤系统 / Skins
9 种皮肤 / 9 skins — 纯色/Solid / 🔥凤凰/Phoenix / ⚡雷电/Thunder / 👼天使/Angel / 👿恶魔/Demon / 🤖机甲/Mech / 🌀极光/Aurora / ✨星辰/Stellar / 👻幽靈/Ghost

- **独特的主场粒子特效** / Unique animated particle effects per skin (flame wings, lightning bolts, halos, demon eyes, thruster glow, aurora ribbons, orbital stars, ghost wisps)
- **Lv1-5 等级**，随玩家等级解锁更强特效 / Level up your skin for stronger effects
- 内置 **120×120 动画预览** / Built-in animated preview

### 🗺 地图要素 / Map Features

| 要素 / Feature | 说明 / Description |
|------|------|
| 🟢 **刺猬 Spike** | 吃后 +30 质量 + 分裂爆发 / Gain 30 mass + cascade split |
| ⭐ **超级食物 Super Food** | 每 12 秒刷新，大量质量 / Spawns every 12s, high mass reward |
| 🌌 **秘境 Secret Realm** | 金色传送门 → 副地图寻宝（💪质量/💨速度/👁️范围） / Golden portal → mini-map with treasures (mass/speed/range) |
| 🌀 **虫洞 Wormhole** | 两端传送，快速穿梭 / Teleport between paired portals |

### 🤖 AI
- **三个性格 / 3 Personalities**：莽夫/Berserker · 憨憨/Silly · 愣头/Rusher
- AI 成长快（吃范围 1.4×，食物增益 1.3×） / AI grows fast (1.4× eat range, 1.3× food gain)
- 但**战斗 AI 很蠢**（随机分裂、乱吐球），让玩家有爽感 / But **combat AI is dumb** (random splits, random eject) — you have the advantage

### ⏱ 随时间翻倍 / Time Multiplier
- 每过 1 分钟食物增益 **翻倍**，无上限 / Food value **doubles every minute**, no cap (2× → 4× → 8× → 16× …)
- 系统通知每次翻倍 / System notification on each level-up

### 🏆 排行榜 / Leaderboard
- 实时 Top 10 / Live top-10 ranking
  - 🥇 #1：皇冠 + 金色光环 / Crown + gold aura
  - 🥈🥉 #2-3：银色/铜色光圈 / Silver/bronze ring
  - 前十：名字金色发光 + 闪烁粒子 / Golden glowing name + sparkle particles

### 🎯 爽感反馈 / Satisfying Feedback
- **震屏 Screen Shake**：击杀 / 超级食物触发 / On kill or super food eat
- **连杀播报 Kill Streaks**：5 秒内连续击杀 / 5s window → Double/Triple/Quadra/Penta/Godlike
- **爆炸粒子 Explosion FX**：AI 死亡时细胞爆裂飞散 / Cells burst on AI death

### 🔊 音效 / Audio
- 8 种合成音效 / 8 synthesized SFX (eat, split, eject, sprint, death, achievement…)
- BGM：和弦铺底 + 贝斯脉冲 + 五声音阶 / Chord pads + bass pulse + pentatonic melody

### 🛠 其他 / Extras
- 📺 **回放 Replay**：记录最近 5 分钟 / Records last 5 minutes
- 👁 **观战 Spectate**：死后观看第一名 / Watch the leader after death
- 🗺 **增强小地图 Enhanced Minimap**：玩家名、虫洞连接、图例 / Player names, wormhole lines, legend
- 📱 **触屏支持 Touch Support**
- 🏆 **成就系统 Achievements**：10 项成就 / 10 achievements

---

## 🚀 本地运行 / Run Locally

直接双击 `index.html`，**零依赖，零构建**。  
Just double-click `index.html` — **no build tools, no dependencies**.

```bash
git clone https://github.com/Oldfoollearnc/ball-battle-io.git
cd ball-battle-io
# open index.html in your browser
```

---

## 📄 许可 / License

MIT
