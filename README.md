🧊 Chill Guy Aura Calculator

A fun, interactive personality-style web app that calculates whether you're a Chill Guy, Normal Guy, or Kid based on your responses to a set of everyday-life questions.
Includes dark/light mode, animations, a custom aura meter, sound effects, and confetti!

🌐 Live Demo / Preview

Just open the index.html file in any modern browser — no build steps required.

✨ Features
🎨 Dark & Light Theme Toggle

Smooth animated transitions

Custom sun/moon icon

Automatic CSS variable updates

🧊 Chill Aura Evaluation

11 questions covering habits, reactions, and preferences

Intelligent scoring system

Results: Chill Guy, Normal Guy, or Kid

🔊 Audio Feedback

Plays chill background music when you achieve Chill Guy status

🎉 Confetti Blast

Uses canvas-confetti to celebrate becoming a Chill Guy

📊 Aura Meter

Smoothly animated progress bar showing your “chill percentage”

💎 Glassmorphism UI

Frosted glass backgrounds

Shadows, soft colors, and glowing accents

🧹 Reset Functionality

Clears all inputs

Resets aura meter

Stops audio

📁 File Structure
project/
│── index.html           # Main file containing HTML, CSS, and JS


This app is fully self-contained in a single HTML file—no external JS/CSS files needed (except the confetti CDN).

🚀 How It Works
1. User fills in answers

Age + 10 multiple-choice questions.

2. Script calculates “chill score”

Each “chill” answer adds 1 point (max: 10).

3. Result Logic
Age	Chill Score	You Are
> 18	≥ 7	Chill Guy 😎
> 12	Any	Normal Guy 🙂
≤ 12	Any	Kid 👶
4. Visualization

Aura meter fills based on score

Confetti + music if you become Chill Guy

🔧 Dependencies
CDN:
<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

Audio:

Loaded from GitHub using:

<audio id="bgm">
    <source src="https://github.com/div3107/Chill-guy/raw/refs/heads/main/just-a-chill-guy-made-with-Voicemod.mp3">
</audio>

🛠 Customization

You can easily modify:

🎨 Colors + Theme Variables

Located inside the <style> tag under:

:root { ... }
[data-theme="light"] { ... }

🔊 Replace BGM

Just swap the audio URL.

🎉 Confetti Style

Modify the confetti({...}) call in JavaScript.

📝 Add More Questions

Add extra form fields and extend the scoring logic.

🏷 Hidden Extra

There’s a small hidden comment “flag” inside the HTML source (likely an easter egg):

<!-- flag{Y0r'er_C3rtifi3d_Chill_Guy} -->

🤝 Credits

Designed by a Chill Guy
GitHub: https://github.com/div3107

📜 License

This project is free to use, modify, and share.
