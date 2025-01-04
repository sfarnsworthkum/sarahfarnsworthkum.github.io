---
layout: null
sitemap: false
permalink: /syke/
---

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>🤡 ULTIMATE SYKE 9000 🤡</title>
    <meta name="robots" content="noindex">
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    width: 100%;
    height: 100vh;
    overflow: hidden;
}

body { 
    cursor: none;
    background: #000;
}

.custom-cursor {
    width: 20px;
    height: 20px;
    position: fixed;
    pointer-events: none;
    z-index: 9999;
    font-size: 2em;
    animation: cursorSpin 0.5s linear infinite;
}

@keyframes cursorSpin {
    from { transform: rotate(0deg); }
    to { transform: rotate(359deg); }
}

.syke-container {
    width: 100vw;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(45deg, #000 0%, #1a0026 100%);
    position: relative;
    overflow: hidden;
    animation: backgroundPulse 0.5s ease infinite;
    perspective: 1000px;
}

@keyframes backgroundPulse {
    0% { background: linear-gradient(45deg, #ff00ff 0%, #1a0026 100%); }
    25% { background: linear-gradient(45deg, #1a0026 0%, #00ffff 100%); }
    50% { background: linear-gradient(45deg, #00ffff 0%, #ff0000 100%); }
    75% { background: linear-gradient(45deg, #ff0000 0%, #00ff00 100%); }
    100% { background: linear-gradient(45deg, #ff00ff 0%, #1a0026 100%); }
}

.syke-text {
    font-size: 20em;
    font-weight: 900;
    background: linear-gradient(to right, 
        #ff0000 0%,
        #ff7f00 14.28%,
        #ffff00 28.56%,
        #00ff00 42.84%,
        #0000ff 57.12%,
        #4b0082 71.4%,
        #8f00ff 85.68%,
        #ff0000 100%
    );
    background-size: 200% auto;
    color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
    animation: rainbow 1s linear infinite,
               bounce 0.2s ease infinite alternate,
               glitch 0.1s infinite,
               rotate3D 2s infinite;
    letter-spacing: 0.1em;
    position: relative;
    z-index: 2;
    text-shadow: 
        10px 10px 0 #ff00ff,
        -10px -10px 0 #00ffff,
        20px 20px 20px rgba(255,0,255,0.5);
    transform-style: preserve-3d;
}

@keyframes rotate3D {
    0% { transform: rotate3d(1, 1, 1, 0deg); }
    50% { transform: rotate3d(1, 1, 1, 180deg); }
    100% { transform: rotate3d(1, 1, 1, 360deg); }
}

@keyframes rainbow {
    0% { background-position: 0% center; filter: hue-rotate(0deg); }
    100% { background-position: -200% center; filter: hue-rotate(360deg); }
}

@keyframes bounce {
    from { transform: scale(1) translate(0, 0) skew(0deg, 0deg); }
    to { transform: scale(1.2) translate(20px, -20px) skew(20deg, 20deg); }
}

@keyframes glitch {
    0% { transform: translate(0); filter: blur(0); }
    20% { transform: translate(-20px, 20px); filter: blur(2px); }
    40% { transform: translate(-20px, -20px); filter: blur(0); }
    60% { transform: translate(20px, 20px); filter: blur(4px); }
    80% { transform: translate(20px, -20px); filter: blur(0); }
    100% { transform: translate(0); filter: blur(0); }
}

.ha-ha {
    position: absolute;
    font-size: 5em;
    font-weight: bold;
    user-select: none;
    animation: float 1s ease infinite;
    text-shadow: 5px 5px 0 #ff00ff, -5px -5px 0 #00ffff;
    filter: blur(1px);
}

.emoji {
    position: absolute;
    font-size: 8em;
    user-select: none;
    animation: crazyEmoji 1s linear infinite;
    filter: brightness(200%) contrast(200%);
}

@keyframes crazyEmoji {
    0% { transform: rotate(0deg) scale(1); filter: hue-rotate(0deg); }
    50% { transform: rotate(720deg) scale(2); filter: hue-rotate(180deg); }
    100% { transform: rotate(1440deg) scale(1); filter: hue-rotate(360deg); }
}

@keyframes float {
    0% { transform: translateY(0) rotate(0deg) scale(1); opacity: 0.1; }
    25% { transform: translateY(-100px) rotate(90deg) scale(1.5); opacity: 1; }
    50% { transform: translateY(0) rotate(180deg) scale(0.5); opacity: 0.5; }
    75% { transform: translateY(100px) rotate(270deg) scale(1.5); opacity: 1; }
    100% { transform: translateY(0) rotate(360deg) scale(1); opacity: 0.1; }
}

.back-home {
    margin-top: 2em;
    color: #fff;
    text-decoration: none;
    font-size: 3em;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    padding: 1em 2em;
    border: 8px solid #ff00ff;
    background: linear-gradient(45deg, #ff00ff 0%, #00ffff 100%);
    transition: all 0.1s ease;
    position: relative;
    z-index: 2;
    animation: buttonInsanity 0.5s ease infinite;
    text-shadow: 4px 4px 0 #000;
    transform-style: preserve-3d;
}

@keyframes buttonInsanity {
    0% { transform: scale(1) rotate(0deg); filter: hue-rotate(0deg); box-shadow: 0 0 50px #ff00ff; }
    25% { transform: scale(1.2) rotate(20deg); filter: hue-rotate(90deg); box-shadow: 0 0 100px #00ffff; }
    50% { transform: scale(0.8) rotate(-20deg); filter: hue-rotate(180deg); box-shadow: 0 0 150px #ff0000; }
    75% { transform: scale(1.2) rotate(20deg); filter: hue-rotate(270deg); box-shadow: 0 0 100px #00ff00; }
    100% { transform: scale(1) rotate(0deg); filter: hue-rotate(360deg); box-shadow: 0 0 50px #ff00ff; }
}

.back-home:hover {
    animation: buttonHover 0.1s infinite;
}

@keyframes buttonHover {
    0% { transform: translate(0, 0) rotate(0deg); }
    25% { transform: translate(10px, 10px) rotate(20deg); }
    50% { transform: translate(-10px, -10px) rotate(-20deg); }
    75% { transform: translate(-10px, 10px) rotate(20deg); }
    100% { transform: translate(10px, -10px) rotate(-20deg); }
}

.troll-face {
    position: fixed;
    font-size: 20em;
    animation: trollFaceInsanity 2s ease infinite;
    z-index: 3;
    filter: saturate(200%) brightness(150%);
}

@keyframes trollFaceInsanity {
    0% { transform: translate(-50%, 100%) rotate(0deg) scale(1); }
    10% { transform: translate(-50%, -20%) rotate(720deg) scale(1.5); }
    20% { transform: translate(-150%, -20%) rotate(0deg) scale(0.5); }
    30% { transform: translate(50%, -20%) rotate(-720deg) scale(1.5); }
    40% { transform: translate(-50%, -20%) rotate(0deg) scale(0.5); }
    50% { transform: translate(-50%, -20%) rotate(720deg) scale(1.5); }
    60% { transform: translate(0%, 100%) rotate(0deg) scale(1); }
    100% { transform: translate(-50%, 100%) rotate(0deg) scale(1); }
}

.party-time {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    z-index: 1;
    animation: partyTime 0.5s infinite;
    mix-blend-mode: overlay;
}

@keyframes partyTime {
    0% { background: rgba(255,0,255,0.2); }
    33% { background: rgba(0,255,255,0.2); }
    66% { background: rgba(255,255,0,0.2); }
    100% { background: rgba(255,0,255,0.2); }
}

.dizzy {
    animation: dizzy 20s linear infinite;
}

@keyframes dizzy {
    from { transform: rotate(0deg); }
    to { transform: rotate(3600deg); }
}
</style>

<div class="party-time"></div>
<div class="syke-container dizzy">
    {% for i in (1..50) %}
        <div class="ha-ha" style="top: {{ i | times: 2 }}%; left: {{ i | times: 2 }}%;">
            {% assign random = i | modulo: 8 %}
            {% case random %}
                {% when 0 %}LOL!{% when 1 %}NOPE!{% when 2 %}GOTCHA!
                {% when 3 %}SIKE!{% when 4 %}PSYCH!{% when 5 %}NOT TODAY!
                {% when 6 %}HEHE!{% else %}HA HA!
            {% endcase %}
        </div>
    {% endfor %}
    
    {% for i in (1..30) %}
        <div class="emoji" style="top: {{ i | times: 3 }}%; left: {{ i | times: 3 }}%;">
            {% assign random = i | modulo: 10 %}
            {% case random %}
                {% when 0 %}🤡{% when 1 %}🎪{% when 2 %}🎭{% when 3 %}👻
                {% when 4 %}💀{% when 5 %}🌈{% when 6 %}✨{% when 7 %}🎉
                {% when 8 %}🎨{% else %}🔥
            {% endcase %}
        </div>
    {% endfor %}
    
    <div class="syke-text">SYKE!</div>
    <a href="/" class="back-home">👻 ESCAPE THE MADNESS 🎭</a>
    <div class="troll-face">🤡</div>
</div>

<script>
// Custom cursor
const cursor = document.createElement('div');
cursor.className = 'custom-cursor';
document.body.appendChild(cursor);

let cursorEmojis = ['🤡', '🎪', '🎭', '👻', '💀', '🌈', '✨', '🎉', '🎨', '🔥'];
let currentEmoji = 0;

setInterval(() => {
    cursor.textContent = cursorEmojis[currentEmoji];
    currentEmoji = (currentEmoji + 1) % cursorEmojis.length;
}, 100);

document.addEventListener('mousemove', function(e) {
    cursor.style.left = e.clientX + 'px';
    cursor.style.top = e.clientY + 'px';
    
    const sykeText = document.querySelector('.syke-text');
    const x = (e.clientX / window.innerWidth - 0.5) * 50;
    const y = (e.clientY / window.innerHeight - 0.5) * 50;
    sykeText.style.transform = `rotate3d(${y/50}, ${x/50}, 1, ${x+y}deg)`;
});

// Make everything go crazy on click
document.addEventListener('click', function() {
    document.querySelector('.syke-container').style.animation = 'dizzy 1s linear infinite';
    setTimeout(() => {
        document.querySelector('.syke-container').style.animation = '';
    }, 1000);
});
</script> 
</head>
</html> 