# 🎵 Magic Song Machine | מכונת השירים הקסומה

A fun, colorful web app that helps kids create AI-generated songs using [Suno AI](https://suno.com). Built for classroom activities with 2nd graders — but anyone can use it!

![Hebrew](https://img.shields.io/badge/Language-Hebrew-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![No Install](https://img.shields.io/badge/Install-None!-orange)

## ✨ What Is This?

A single-page app (one HTML file!) that guides you through 6 fun steps to build a song concept. At the end, it generates a ready-to-use **Suno AI prompt** in English that you copy-paste into Suno to create your song.

The UI is in **Hebrew (RTL)** with big buttons, emojis, and animations — designed for kids but enjoyed by everyone.

## 🎮 How It Works

### Step 1–5: Make Choices
Click through 6 fun categories. Each click auto-advances to the next step:

| Step | Category | Example Options |
|------|----------|----------------|
| 🥁 | **הקצב** (Rhythm) | Pop, Rock, Hip-Hop, Disco, Jazz... |
| 💡 | **הנושא** (Topic) | Lost socks, Recess in space, Pizza party... |
| 📍 | **המקום** (Location) | Chocolate volcano, Underwater disco... |
| 🤪 | **מה מצחיק?** (Twist) | Chicken sounds, Opera section, Hiccups... |
| ✨ | **האווירה** (Mood) | Silly, Spooky-funny, Energetic... |

### Step 6: Magic Word
Type any word the kids choose — it gets featured in the song!

### 🎉 Result Screen
- **Summary** of all choices (Hebrew)
- **Silly rhyming poem** in Hebrew (for lyrics)
- **Suno prompt** in English (ready to copy!)

> Options are **randomized** each round from a pool of 8–10 choices per category, so every session feels fresh.

## 🤖 Using the Prompt in Suno

### Quick Start
1. Open the app and make your choices
2. Click **📋 העתק פרומפט** (Copy Prompt) on the result screen
3. Go to [suno.com](https://suno.com) and sign in (free tier gives ~10 songs/day)
4. Click **Create**
5. Paste the prompt into the **Song Description** field
6. *(Optional)* Paste the Hebrew poem into the **Lyrics** field
7. Click **Create** and wait ~30 seconds for your song!

### Example Prompt Output
```
A fun, silly and goofy children's song in hip-hop style about lost socks. 
Set at an underwater disco. Include chicken clucking sounds as a funny element. 
The magic word "banana" should be featured prominently. 
Catchy, kid-friendly, singalong chorus, playful and energetic vocals, silly sound effects.
```

### Tips for Best Results on Suno
- **Free tier** gives you enough credits for a classroom session
- The app generates the prompt in **English** because Suno works best with English descriptions
- You can paste the **Hebrew poem** as lyrics — Suno handles Hebrew reasonably well
- Try generating 2–3 versions and let the kids vote on their favorite!
- Use **"Custom Mode"** in Suno if you want to paste lyrics separately from the style description

## 🚀 Running the App

No install, no build, no dependencies. Just open the file:

```bash
# Option 1: Open directly
open index.html

# Option 2: Simple HTTP server (if needed)
python3 -m http.server 8080
# Then visit http://localhost:8080
```

Or visit the live version: **[nakashon.github.io/magic-song-machine](https://nakashon.github.io/magic-song-machine/)**

## 🏗️ Tech Stack

- **Single HTML file** — no build step, no framework
- **Tailwind CSS** (via CDN) — styling
- **Vanilla JavaScript** — all logic
- **Google Fonts (Rubik)** — Hebrew-friendly typography

## 📸 Classroom Use

This app was originally built for a 2nd grade classroom AI lesson. Here's how to run it:

1. **Open the app** on a projected screen
2. **Let the kids vote** on each category (raise hands or shout!)
3. **You click** the winning option — it auto-advances
4. **Type the magic word** they choose together
5. **Copy the prompt** and paste it into Suno live
6. **Play the generated song** — watch them go wild! 🎉
7. Click **🔄 שיר חדש** to make another round with fresh options

## 📄 License

MIT — use it, remix it, share it. Have fun! 🎵

---

*Built with ❤️ and AI by [Neon Ash](https://github.com/nakashon)*
