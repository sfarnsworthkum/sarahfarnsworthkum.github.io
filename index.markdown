---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: STRENGTH • DISCIPLINE • POWER
---

<div class="hero-section">
    <div class="glitch-container">
        <h1 class="glitch" data-text="EMBRACE THE VOID">EMBRACE THE VOID</h1>
    </div>
    <p class="tagline">WHERE FITNESS MEETS DARKNESS</p>
</div>

<div class="image-section">
    <div class="image-container">
        <img src="{{ '/assets/images/sarah-action.png' | relative_url }}" alt="Sarah in action" class="feature-image">
        <div class="image-overlay"></div>
    </div>
    <div class="image-text">UNLEASH YOUR POWER</div>
</div>

<div class="grid-container">
    <div class="grid-item">
        <div class="number">01</div>
        <h2>DISCIPLINE</h2>
        <p>Break limits. Transcend pain. Find power.</p>
    </div>
    
    <div class="grid-item">
        <div class="number">02</div>
        <h2>STRENGTH</h2>
        <p>Dark aesthetics. Raw power. Pure focus.</p>
    </div>
    
    <div class="grid-item">
        <div class="number">03</div>
        <h2>ASCEND</h2>
        <p>Mind over matter. Beyond human limits.</p>
    </div>
</div>

<div class="manifesto">
    <p class="quote">"IN THE DARKNESS WE FIND OUR STRENGTH"</p>
</div>

<div class="cta-section">
    <h2>JOIN THE DARK SIDE OF FITNESS</h2>
    <div class="cta-buttons">
        <a href="/contact" class="cta-button">INITIATE</a>
        <a href="/blog" class="cta-button secondary">EXPLORE</a>
    </div>
</div>

<div class="button-grid">
    <div class="image-button fun">
        <img src="{{ '/assets/images/sweaty-fun.png' | relative_url }}" alt="Sweaty Fun Time Fitness" class="button-image">
        <div class="button-overlay fun-overlay"></div>
    </div>
</div>

<style>
body {
    background-color: #000000;
    color: #ffffff;
    font-family: 'Helvetica Neue', sans-serif;
}

.hero-section {
    background: #000;
    padding: 6em 1em;
    text-align: center;
    position: relative;
    overflow: hidden;
}

.image-section {
    position: relative;
    width: 100%;
    margin: 4em 0;
    overflow: hidden;
}

.image-container {
    position: relative;
    width: 100%;
    height: 60vh;
    overflow: hidden;
}

.feature-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter: contrast(120%) brightness(80%);
    transform: scale(1.02);
    transition: all 0.5s ease;
}

.image-overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(45deg, rgba(0,0,0,0.7) 0%, rgba(0,0,0,0.3) 100%);
    mix-blend-mode: multiply;
}

.image-text {
    position: absolute;
    bottom: 2em;
    left: 2em;
    font-size: 3em;
    font-weight: 900;
    letter-spacing: 0.2em;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    opacity: 0.9;
    transform: skew(-5deg);
}

.image-container:hover .feature-image {
    transform: scale(1.05);
    filter: contrast(130%) brightness(70%);
}

.glitch-container {
    position: relative;
    z-index: 2;
}

.glitch {
    font-size: 4em;
    font-weight: 900;
    text-transform: uppercase;
    position: relative;
    text-shadow: 0.05em 0 0 rgba(255,0,0,0.75),
                -0.025em -0.05em 0 rgba(0,255,0,0.75),
                0.025em 0.05em 0 rgba(0,0,255,0.75);
    animation: glitch 500ms infinite;
}

.glitch span {
    position: absolute;
    top: 0;
    left: 0;
}

@keyframes glitch {
    0% {
        text-shadow: 0.05em 0 0 rgba(255,0,0,0.75),
                    -0.025em -0.05em 0 rgba(0,255,0,0.75),
                    0.025em 0.05em 0 rgba(0,0,255,0.75);
    }
    14% {
        text-shadow: 0.05em 0 0 rgba(255,0,0,0.75),
                    -0.025em -0.05em 0 rgba(0,255,0,0.75),
                    0.025em 0.05em 0 rgba(0,0,255,0.75);
    }
    15% {
        text-shadow: -0.05em -0.025em 0 rgba(255,0,0,0.75),
                    0.025em 0.025em 0 rgba(0,255,0,0.75),
                    -0.05em -0.05em 0 rgba(0,0,255,0.75);
    }
    49% {
        text-shadow: -0.05em -0.025em 0 rgba(255,0,0,0.75),
                    0.025em 0.025em 0 rgba(0,255,0,0.75),
                    -0.05em -0.05em 0 rgba(0,0,255,0.75);
    }
    50% {
        text-shadow: 0.025em 0.05em 0 rgba(255,0,0,0.75),
                    0.05em 0 0 rgba(0,255,0,0.75),
                    0 -0.05em 0 rgba(0,0,255,0.75);
    }
    99% {
        text-shadow: 0.025em 0.05em 0 rgba(255,0,0,0.75),
                    0.05em 0 0 rgba(0,255,0,0.75),
                    0 -0.05em 0 rgba(0,0,255,0.75);
    }
    100% {
        text-shadow: -0.025em 0 0 rgba(255,0,0,0.75),
                    -0.025em -0.025em 0 rgba(0,255,0,0.75),
                    -0.025em -0.05em 0 rgba(0,0,255,0.75);
    }
}

.tagline {
    font-size: 1.2em;
    font-weight: 300;
    letter-spacing: 0.5em;
    margin-top: 2em;
    color: #ffffff;
    position: relative;
    z-index: 2;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2em;
    margin: 4em 0;
    padding: 0 2em;
}

.grid-item {
    background: #111;
    padding: 2em;
    position: relative;
    overflow: hidden;
    border: 1px solid #333;
    transition: all 0.3s ease;
}

.grid-item:hover {
    transform: translateY(-5px);
    border-color: #fff;
}

.number {
    position: absolute;
    top: 1em;
    right: 1em;
    font-size: 0.9em;
    color: #333;
    font-weight: 700;
}

.grid-item h2 {
    color: #fff;
    font-size: 1.8em;
    margin: 1em 0;
    font-weight: 700;
}

.grid-item p {
    color: #999;
    font-size: 1em;
    line-height: 1.6;
}

.manifesto {
    text-align: center;
    margin: 6em 0;
    padding: 0 2em;
}

.quote {
    font-size: 2em;
    font-weight: 300;
    letter-spacing: 0.2em;
    line-height: 1.4;
    color: #fff;
}

.cta-section {
    text-align: center;
    margin: 4em 0;
    padding: 4em 2em;
    background: #111;
    border-top: 1px solid #333;
    border-bottom: 1px solid #333;
}

.cta-section h2 {
    font-size: 2em;
    margin-bottom: 2em;
    font-weight: 700;
}

.cta-buttons {
    display: flex;
    gap: 2em;
    justify-content: center;
    flex-wrap: wrap;
}

.cta-button {
    display: inline-block;
    padding: 1em 3em;
    font-size: 1em;
    font-weight: 400;
    text-transform: uppercase;
    letter-spacing: 0.2em;
    text-decoration: none;
    color: #fff;
    background: transparent;
    border: 1px solid #fff;
    transition: all 0.3s ease;
}

.cta-button:hover {
    background: #fff;
    color: #000;
}

.cta-button.secondary {
    border-color: #333;
    color: #666;
}

.cta-button.secondary:hover {
    border-color: #fff;
    color: #fff;
    background: transparent;
}

@media (max-width: 768px) {
    .glitch {
        font-size: 2.5em;
    }
    
    .tagline {
        font-size: 1em;
        letter-spacing: 0.3em;
    }
    
    .quote {
        font-size: 1.5em;
    }
    
    .cta-buttons {
        flex-direction: column;
        gap: 1em;
    }
}

.button-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2em;
    margin: 4em auto;
    padding: 0 2em;
    max-width: 1000px;
}

.image-button {
    position: relative;
    height: auto;
    aspect-ratio: 16/9;
    overflow: hidden;
    cursor: pointer;
    transition: all 0.3s ease;
    border-radius: 10px;
}

.image-button.fun {
    border: 3px solid #FFD700;
    background: linear-gradient(135deg, #FF69B4, #FFD700);
    transform: rotate(0deg);
}

.button-image {
    width: 100%;
    height: 100%;
    object-fit: contain;
    filter: none;
    transition: all 0.5s ease;
    padding: 20px;
}

.fun-overlay {
    background: none !important;
    mix-blend-mode: normal !important;
}

.image-button.fun:hover {
    transform: scale(1.02);
    box-shadow: 0 0 30px rgba(255, 105, 180, 0.5);
}

@media (max-width: 768px) {
    .button-grid {
        padding: 0 1em;
    }
    
    .image-button {
        aspect-ratio: 4/3;
    }
}
</style>
