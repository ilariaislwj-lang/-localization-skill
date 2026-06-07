[README.md](https://github.com/user-attachments/files/28676948/README.md)
# 🌐 Localization Skill for Claude

> Transcreation for marketing and advertising copy — not just translation, but cultural adaptation that makes your content feel native.

---

## What It Does

Most translation tools convert words. This skill converts **feeling**.

It's built for marketing teams, copywriters, and brand managers who need their campaigns to resonate authentically in new markets — not just be understood.

**Key capabilities:**
- Produces both a literal translation and a culturally adapted version, side by side, so you can see exactly what was changed and why
- Adapts idioms, humor, wordplay, and cultural references instead of translating them literally
- Matches platform norms (e.g. Xiaohongshu vs. LinkedIn vs. TikTok tone)
- Flags cultural sensitivities and taboos before they become expensive mistakes
- Maintains brand voice consistency across languages

---

## Supported Languages

| Language | Region Notes |
|---|---|
| 🇨🇳 Chinese (Simplified) | Mainland China, platform-specific norms (WeChat, Douyin, Xiaohongshu) |
| 🇹🇼 Chinese (Traditional) | Taiwan & Hong Kong variants, Cantonese considerations |
| 🇯🇵 Japanese | Keigo levels, katakana branding, seasonal references |
| 🇰🇷 Korean | Generational tone, MZ slang, Konglish |
| 🇪🇸 Spanish | LATAM vs. Spain variants, regional vocabulary |
| 🇫🇷 French | France vs. Québec variants, register norms |
| 🇩🇪 German | *(coming soon)* |
| 🌍 Others | General transcreation principles applied |

---

## Example Output

**Input:** *"Taste the feeling."* (Coca-Cola) → Chinese (Simplified)

```
直译 / Literal:
品尝这种感觉。

本地化版 / Localized:
畅爽这一刻。

📝 Localization Notes:
- "Taste" as 品尝 is too literal and loses sensory impact.
  "畅爽" blends 畅快 (free-flowing) + 爽 (refreshing) — the term
  Coca-Cola actually uses in China.
- "感觉" → "这一刻" adds a time dimension and visual storytelling
  quality more natural to Chinese ad copy.
```

---

## Installation

### Claude Code
```bash
claude skill install localization
```

### Claude.ai (manual)
1. Download `localization.skill` from the [Releases](../../releases) page
2. Go to **Settings → Skills → Upload Skill**
3. Done — trigger by saying "localize this" or "adapt this for [market]"

---

## Trigger Phrases

The skill activates automatically when you use phrases like:

- *"Localize this for the Chinese market"*
- *"Transcreate this campaign into Japanese"*
- *"Make this feel native in French"*
- *"Adapt this slogan for Korea"*
- *"Translate this ad copy into Spanish"*

---

## When NOT to Use This Skill

This skill is optimized for **marketing and creative content**. For the following, it will default to accurate translation instead:

- Legal or compliance documents
- Technical documentation
- Medical instructions
- Financial disclosures

---

## Contributing

Contributions welcome! Areas where help is especially appreciated:

- 🇩🇪 German reference file (`references/de.md`)
- 🇧🇷 Brazilian Portuguese reference file
- 🇦🇪 Arabic reference file (RTL considerations)
- Additional platform-specific guides (TikTok, LinkedIn, etc.)

Please follow the existing reference file format and submit a PR.

---

## License

MIT — free to use, modify, and distribute.

---

*Built with the [Skill Creator](https://github.com/anthropics/skills/tree/main/skill-creator) · Compatible with Claude Code, Claude.ai, Codex CLI, and other SKILL.md-compatible platforms*
