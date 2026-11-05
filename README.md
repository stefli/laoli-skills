# laoli-skills

老李 / Justin 自用技能系列索引。每个技能单独一个仓库（`laoli-xxx`），方便不同 agent / 机器拉同一份版本，也方便单独升级。

## Repos

| Repo | Name | What | Local id |
|---|---|---|---|
| [`laoli-wechat-copy`](https://github.com/stefli/laoli-wechat-copy) | 科技热点图文 | 公众号等多平台成稿：事实核、标题口味、配置接线骨架、Pages 交付 | `skill-1791963133511` |
| [`laoli-remotion-shorts`](https://github.com/stefli/laoli-remotion-shorts) | 科技短视频节奏与特效 | Remotion 竖屏科技快播 15s、特效与旁白 | `skill-1792119748981` |
| [`laoli-topic-pool`](https://github.com/stefli/laoli-topic-pool) | 公众号选题池 | 老李的AI江湖选题任务池与日更节奏 | `skill-1792165037013` |
| [`laoli-local-git`](https://github.com/stefli/laoli-local-git) | 优先本地推仓 | 小改动/文档默认本地 git，勿滥开云端 agent | `skill-1792292123460` |
| [`laoli-review`](https://github.com/stefli/laoli-review) | 成片与图文评审 | 竖屏短片与公众号图文独立打分，不代改不代发 | `skill-1792648294348` |
| [`laoli-tvp-cover`](https://github.com/stefli/laoli-tvp-cover) | 科技快播封面 | TVP/科技快播 3:4 封面与抖音 JPG 导出 | `skill-1793030834146` |
| [`laoli-tvp`](https://github.com/stefli/laoli-tvp) | tvp | HyperFrames/OpenDesign 科技竖屏成片（默认真 2K）一次性交付 | `tvp` |
| [`laoli-tvp-dh`](https://github.com/stefli/laoli-tvp-dh) | tvp-dh | 科技竖屏叠本人脸数字人圆窗口播 | `tvp-dh` |
| [`laoli-opendesign-codex`](https://github.com/stefli/laoli-opendesign-codex) | OpenDesign Codex免费动效 | Open Design 动效走本机 Codex→Magpie→WorkBuddy | `opendesign-codex` |
| [`laoli-she`](https://github.com/stefli/laoli-she) | she | 写实东亚女性半身短视频生成与迭代 | `she` |

## Sync recipe

```bash
# example: refresh wechat copy skill
git clone https://github.com/stefli/laoli-wechat-copy.git
# then copy or symlink SKILL.md (+ helpers) into the agent workflows folder
```

## Versioning

- One skill = one repo = independent semver/tags when you need them.
- Prefer small, focused commits per skill when upgrading.
- Index repo (`laoli-skills`) only holds this README; it does not vendor skill bodies.

## Privacy

Exported copies scrub Windows username `jl7134` → `<YOU>`. Do not commit real API keys or hostnames.
