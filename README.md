<h1>🧊 Chill Guy Aura Calculator</h1>

<p>
    A fun, interactive, glass-morphism style webpage that determines if you're a 
    <strong>Chill Guy</strong>, <strong>Normal Guy</strong>, or <strong>Kid</strong>. 
    Although it looks like a meme personality quiz, 
    <strong>this project secretly contains multiple CTF-style challenges, hidden flags, and puzzles</strong>
    embedded inside the HTML, logic, and structure.  
    <br><br>
    Perfect for learning frontend basics, debugging, reverse engineering, and web exploitation techniques while having fun!
</p>

<hr>

<h2>🌐 Live Demo</h2>
<p>Simply open <code>index.html</code> in a browser — no setup needed.</p>

<hr>

<h2>✨ Features</h2>
<ul>
    <li>🎨 <strong>Dark & Light Mode Toggle</strong> with smooth animations</li>
    <li>🧊 <strong>Chill Aura Scoring System</strong> with 11 personality-on-lifestyle questions</li>
    <li>🔊 Plays custom chill background music on “Chill Guy” result</li>
    <li>🎉 Confetti celebration for achieving top tier</li>
    <li>📊 Animated Aura Meter (Progress Bar)</li>
    <li>💎 Glassmorphism UI design</li>
    <li>🧹 Reset system that clears audio + animations</li>
    <li>🕵️ <strong>Hidden CTF elements</strong>: flags, commented-out clues, and logic-based challenges</li>
</ul>

<hr>

<h2>🕵️ Not Just a Meme – Contains CTF Challenges</h2>
<p>
    This project includes several <strong>Capture The Flag</strong> style hidden elements:
</p>
<ul>
    <li>🔐 Hidden comments and Easter eggs (e.g., <code>flag{Y0r'er_C3rtifi3d_Chill_Guy}</code>)</li>
    <li>🕳 Clues embedded in HTML structure</li>
    <li>🧩 Logic-based puzzles inside the scoring script</li>
    <li>🎧 Audio-related trick objects</li>
    <li>🐟 Rickroll bait / misleading decoy comment blocks</li>
</ul>
<p>
    These can be used as:  
    <br>
    ✔️ Beginner-friendly web hacking practice  
    <br>
    ✔️ Teaching HTML inspection + debugging  
    <br>
    ✔️ Fun puzzles for CTF teams  
</p>

<hr>

<h2>📁 File Structure</h2>
<pre>
project/
│── index.html        # Main HTML with embedded CSS, JS, music triggers & hidden flags
</pre>

<hr>

<h2>🚀 How It Works</h2>

<h3>1. User Answers 11 Lifestyle Questions</h3>
<p>Each “chill” answer = 1 point.</p>

<h3>2. Age + Chill Score Determine Result</h3>
<table border="1" cellpadding="6">
    <tr>
        <th>Age</th>
        <th>Chill Score</th>
        <th>Result</th>
    </tr>
    <tr>
        <td>18+</td>
        <td>7–10</td>
        <td><strong>Chill Guy 😎</strong></td>
    </tr>
    <tr>
        <td>13–18</td>
        <td>Any</td>
        <td>Normal Guy 🙂</td>
    </tr>
    <tr>
        <td>12 or below</td>
        <td>Any</td>
        <td>Kid 👶</td>
    </tr>
</table>

<h3>3. Visual & Audio Effects</h3>
<ul>
    <li>Confetti animation (using <code>canvas-confetti</code>)</li>
    <li>Chill background track plays</li>
    <li>Aura meter animates smoothly</li>
</ul>

<hr>

<h2>🔧 Dependencies</h2>
<p>Only one external library:</p>

<pre><code>&lt;script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"&gt;&lt;/script&gt;</code></pre>

<p>Background music is loaded from GitHub-hosted audio.</p>

<hr>

<h2>🛠 Customization</h2>
<ul>
    <li>Modify theme colors in the CSS variables (<code>:root</code>)</li>
    <li>Replace music file with your own track</li>
    <li>Edit confetti effect parameters</li>
    <li>Add more questions + scoring rules easily</li>
    <li>Add more CTF flags for challenge sets</li>
</ul>

<hr>

<h2>🤝 Credits</h2>
<p>
    Designed by a Chill Guy.  
    <br>
    GitHub: <a href="https://github.com/div3107" target="_blank">https://github.com/div3107</a>
</p>

<hr>

<h2>📜 License</h2>
<p>Free to use, modify, remix, or include in your own challenge sets.</p>
