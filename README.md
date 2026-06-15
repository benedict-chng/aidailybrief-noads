# AI Daily Brief — Ad-Free (TTS)

Auto-generated ad-free version of [The AI Daily Brief](https://aidailybrief.ai) podcast.

## How It Works

1. **Fetch** the daily episode transcript from aidailybrief.ai
2. **Strip** all sponsor reads, promos, and ad segments using AI
3. **Regenerate** audio with Microsoft Edge TTS (`en-US-AriaNeural` voice)
4. **Publish** the MP3 + RSS feed to GitHub Pages

## Why?

The original podcast is great but packed with sponsor reads (Robots and Pencils, Scrunch, Blitzy, OutSystems, etc.). This repo produces clean, ad-free episodes automatically.

## Subscribe

Copy this URL into your podcast player's "Add by URL":

```
https://benedict-chng.github.io/aidailybrief-noads/feed.xml
```

## Structure

```
├── index.html          # Landing page
├── feed.xml            # RSS podcast feed
└── episodes/
    └── *.mp3           # Generated audio files
```

## Details

- **Voice:** `en-US-AriaNeural` (Female, News/Narration style)
- **TTS Engine:** [edge-tts](https://github.com/rany2/edge-tts) (free, no API key)
- **Automation:** Daily at 5pm AEST via OpenClaw cron
- **Source:** [aidailybrief.ai](https://aidailybrief.ai)

---

_This is a personal project for private use. Original content © The AI Daily Brief._
