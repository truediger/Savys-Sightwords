# Sight Word Stars ⭐

A free, interactive sight words learning app for Kindergarten and 1st Grade students. Built as a single HTML file — no build tools, no frameworks, no backend required.

**Live URL:** [savys-sightwords-app.vercel.app](https://savys-sightwords-app.vercel.app)

---

## Overview

Sight Word Stars helps kids practice high-frequency sight words through 10 different game modes. It supports two grade levels (Kindergarten and 1st Grade) with words organized by quarter or week. The app uses the Web Speech API for text-to-speech so kids can hear every word spoken aloud.

Designed for mobile-first use on iPhones and iPads. Can be added to the home screen for an app-like experience.

---

## Tech Stack

- **Single HTML file** — no dependencies, no build step
- **Vanilla JavaScript** — no React, no frameworks
- **Google Fonts** — Fredoka (kid-friendly, bubbly)
- **Web Speech API** — text-to-speech with voice picker
- **Hosted on Vercel** — auto-deploys from GitHub
- **GitHub Repo:** [github.com/truediger/Savys-Sightwords](https://github.com/truediger/Savys-Sightwords)

---

## Word Lists

### Kindergarten (Quarters)
| Quarter | Word Count | Example Words |
|---------|-----------|---------------|
| Q1 | 13 | to, by, my, am, at, go, man, no, is, the, a, see, I |
| Q2 | 23 | can, and, you, an, it, has, ran, he, she, did, in, put... |
| Q3 | 36 | lot, not, are, was, had, be, do, ten, but, up, look... |
| Q4 | 36 | cut, must, said, when, off, will, down, so, back, let... |

**Total: 108 Kindergarten words**

### 1st Grade (Weeks 1–21)
| Weeks | Word Count | Example Words |
|-------|-----------|---------------|
| 1–5 | 40 | a, first, good, had, he, I, my, was, and, find... |
| 6–10 | 40 | by, call, could, know, be, here, jump, right... |
| 11–15 | 40 | again, away, because, cold, any, done, laugh... |
| 16–20 | 40 | animal, heads, keep, below, far, hear, air... |
| 21 | 8 | brown, few, funny, myself, new, once, thank, words |

**Total: 168 First Grade words (and growing)**

Source: Frazier Elementary High-Frequency Word List + Kindergarten Sight Words by Quarter

---

## Game Modes (10 Total)

### 🃏 Flashcards
- Tap card to reveal the word
- Mark as "I know it!" or "Practice more"
- Tap 🔊 to hear the word spoken

### ✏️ Spelling Bee
- Hear a word spoken aloud
- Type the word to spell it
- Hint button shows the first letter
- Can replay audio as many times as needed

### 🧩 Memory Match
- 6 words displayed as 12 face-down cards (4×3 grid)
- Flip two cards to find matching pairs
- Matched pairs show word + animal emoji

### 🔤 Word Builder
- Letters of a word are scrambled
- Tap letters in the correct order to spell the word
- Instruction screen explains how to play
- 🔊 button to hear the target word
- Only uses words 3–7 letters long

### 🎯 Word Bingo
- 4×4 grid of 16 sight words
- A word is spoken aloud
- Find and tap the matching word on the grid
- 🔊 "Hear Again" button available

### 🔍 Missing Letter
- A word is shown with one letter replaced by `_`
- Pick the correct letter from 4 choices
- Correct answer fills in the letter (highlighted green)
- Word is spoken aloud on correct answer

### ⚡ Speed Read
- Target word flashes on screen briefly and is spoken
- Switches to a grid of 8 words
- Find and tap the target word before the timer runs out
- Timer gets faster each round (5s → 2s)
- 🔊 "Hear Again" button available
- Instruction screen before starting

### 📖 Read to Me
- Displays simple sentences using sight words
- Tap 🔊 to hear the full sentence read aloud
- Tap individual words to hear them separately
- No scoring — just reading practice

### 📦 Word Sort
- Sort words into categories (Action Words, Describing Words, Question Words, People Words)
- Tap a word, then tap the correct category box
- Categories auto-populate based on selected words

### 🏁 Word Race
- Hear a word spoken aloud
- Two word choices appear side by side
- Tap the correct word as fast as possible
- Speed feedback: ⚡ Lightning (<1s), 🔥 Fast (<2s), 👍 Got it
- Instruction screen before starting

### 🫧 Pop the Word
- 5 word bubbles float up the screen
- Hear a target word spoken
- Find and tap the correct bubble before it floats away
- Wrong taps pop that bubble (shrink animation)
- Bubbles spread across horizontal lanes to avoid overlap
- Instruction screen before starting

---

## Features

- **Grade Toggle** — Switch between 🧒 Kindergarten and 📚 1st Grade
- **Week/Quarter Selector** — Pick specific time periods or Select All
- **Voice Picker** — Choose from available text-to-speech voices (auto-selects high-quality voices like Samantha/Karen)
- **Word Preview** — See all selected words on home screen, tap any to hear it
- **Progress Bar** — Visual star progress during each game
- **Celebration Animations** — Confetti on game completion
- **Mobile Optimized** — Full-screen PWA mode when added to home screen
- **No accounts, no tracking, no ads** — Just a learning tool

---

## Deployment

### GitHub → Vercel (Auto-Deploy)

1. Edit `index.html` in the GitHub repo
2. Commit changes to `main` branch
3. Vercel auto-deploys within ~30 seconds

### Add to Home Screen (iOS)

1. Open `savys-sightwords-app.vercel.app` in Safari
2. Tap the share button (square with arrow)
3. Tap "Add to Home Screen"
4. Name it "Sight Words" and tap Add

---

## Version History

### v1 — Initial Release
- 4 games: Flashcards, Spelling Bee, Memory Match, Word Builder
- 1st Grade words only (Weeks 1–20)
- Voice picker, week selector, progress tracking

### v2 — New Games & Improvements
- Added 6 new games: Word Bingo, Sentence Builder, Missing Letter, Speed Read, Read to Me, Word Sort
- Speed Read: word flashes then find it in a grid before timer runs out
- Missing Letter: shows completed word with filled-in letter highlighted
- Instruction screens for Speed Read and Word Builder
- Total: 10 game modes

### v3 — Sentence Rework
- Rewrote Sentence Builder with template-based real sentences
- Sentences dynamically match selected weeks

### v4 — Fluency Games & Bug Fixes
- Removed Sentences game
- Added Word Race (pick 1 of 2, speed feedback)
- Added Pop the Word (tap floating bubbles)
- Fixed Pop the Word bubbles not clickable on mobile
- Fixed audio still playing after hitting Home
- Spread out Pop the Word bubbles, increased speed
- Total: 10 game modes

### v5 — Kindergarten Support
- Added Kindergarten sight words (Q1–Q4, 108 words)
- Grade toggle: 🧒 Kindergarten / 📚 1st Grade
- Kindergarten shows quarters, 1st Grade shows weeks
- Added Week 21: brown, few, funny, myself, new, once, thank, words
- All 10 games work with both grade levels

---

## Future Ideas

- **Custom Word Lists** — Add words, name the list, share via URL code
- **Score Tracking** — Save results per game to localStorage
- **Word Mastery** — Track missed words, auto-build "Words to Practice" list
- **Streak Tracker** — Days played in a row

---

## File Structure

```
Savys-Sightwords/
└── index.html    ← entire app (single file, ~40KB)
```

That's it. One file. No build process. No node_modules. No package.json. Just HTML, CSS, and JavaScript.
