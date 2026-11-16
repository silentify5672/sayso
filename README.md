# Sayso

**Learn a language by actually talking.** Sayso is a language-learning web app you can also install like a phone app. Every lesson ends in a real conversation, every mistake gets explained, and you never run out of hearts.

<p align="center"><img src="icons/icon-512.png" width="120" alt="Sayso mascot: a smiling speech bubble"></p>

## Languages

Each language has the full Unit 1, *Survive your first trip*: 4 lessons and 28 exercises.

| Group | Languages |
|---|---|
| European | 🇪🇸 Spanish · 🇫🇷 French · 🇩🇪 German |
| Indian | 🇮🇳 Hindi · 🇮🇳 Tamil |
| East Asian | 🇯🇵 Japanese · 🇰🇷 Korean · 🇨🇳 Mandarin |

Hindi, Tamil, Japanese, Korean and Mandarin show pronunciation under every word (romaji, pinyin and so on). Learners can hide it with the **Aa** toggle once they can read the script.

## What makes it different

- **Real conversations:** each lesson ends with a branching chat set in a real place, like a chai stall in Delhi, a café in Seoul or asking for directions in Osaka.
- **Every mistake explained:** a short "Why?" grammar note written for that specific language.
- **No hearts, no lockouts:** mistakes become Smart Review cards (spaced repetition) instead of punishments.
- **Combo XP:** three right answers in a row doubles your XP.
- **Native audio with slow mode:** one tap to hear any phrase, another to hear it slowly.
- **Flexible daily goal** of 10–50 XP, with streaks that don't guilt-trip you.
- **Installable and offline:** add it to your home screen, and it works without a connection.

## Exercise types

Picture choice · meaning choice · listening · sentence builder · match pairs · branching conversation

## Run it locally

No build step and no dependencies: it's a single page.

```bash
# from the project folder
python3 -m http.server 8000
# then open http://localhost:8000
```

In VS Code, the **Live Server** extension works too: right-click `index.html` and choose **Open with Live Server**.

## Put it online (free)

**GitHub Pages:** go to the repo's **Settings → Pages → Build and deployment**, set **Source: Deploy from a branch**, choose **Branch: `main` / root**, and save. The site goes live at `https://silentify5672.github.io/sayso/`.

On a phone, open that link and choose **Add to Home Screen** to install it like an app.

## Project structure

```
index.html            the whole app: content, styles and logic
manifest.webmanifest  app name, icons and colours for installing
sw.js                 service worker: offline support and caching
icons/                app icons (SVG source and PNG sizes)
```

## Roadmap

- ✍️ **Script lessons:** learn Hiragana, Hangul and Devanagari letter by letter, with tracing, Hangul block building and pronunciation hints that fade as you learn
- 🤖 **AI conversation partner:** free chat with gentle corrections and voice input
- 📸 **Learn from the world:** photograph a menu or sign and get an instant lesson
- 🎙️ **Speaking coach:** pronunciation feedback, including a Mandarin tone graph
- 🌐 **Learn in your own language:** app instructions in Hindi, Tamil, Mandarin and more
- ♿ **Accessibility:** dyslexia-friendly font, text size, high contrast, reduced motion

## License

MIT, see [LICENSE](LICENSE).
