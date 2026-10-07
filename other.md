---
layout: default
title: Others
photo: images/the-fool.jpg
photo_alt: The Fool
photo_caption: The Fool (Klein) from LOTM
---

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 400" width="100%" height="auto" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.5); margin-bottom: 2.5rem;">
  <defs>
    <!-- Gray Fog Gradient -->
    <radialGradient id="fog" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="#5a5a5a" stop-opacity="0.4"/>
      <stop offset="60%" stop-color="#1a1a1a" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#050505" stop-opacity="1"/>
    </radialGradient>
    
    <!-- Golden Glow Filter -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>

    <!-- Arcane Fonts Import -->
    <style>
      @import url('https://fonts.googleapis.com/css2?family=UnifrakturMaguntia&family=Metamorphous&display=swap');
      
      .hermes-text {
        font-family: 'UnifrakturMaguntia', serif;
        fill: #f5cc47;
        font-size: 28px;
        text-anchor: middle;
        filter: url(#glow);
        letter-spacing: 2px;
      }
      
      .sub-text {
        font-family: 'Metamorphous', serif;
        fill: #948c7c;
        font-size: 13px;
        text-anchor: middle;
        letter-spacing: 4px;
        text-transform: uppercase;
        opacity: 0.6;
      }
    </style>
  </defs>

  <!-- Background Base -->
  <rect width="100%" height="100%" fill="#050505"/>
  
  <!-- The Gray Fog -->
  <rect width="100%" height="100%" fill="url(#fog)"/>

  <!-- Mystical Swirls / Fog Paths -->
  <path d="M-100,150 Q200,300 400,150 T900,250" fill="none" stroke="#6b6b6b" stroke-width="4" opacity="0.15" filter="blur(4px)"/>
  <path d="M-100,250 Q250,50 500,250 T900,100" fill="none" stroke="#8f8b86" stroke-width="8" opacity="0.1" filter="blur(8px)"/>
  <path d="M0,200 C 200,100 600,300 800,200" fill="none" stroke="#4a4a4a" stroke-width="2" opacity="0.2" filter="blur(2px)"/>
  
  <!-- Ritual Embellishments -->
  <circle cx="400" cy="200" r="160" fill="none" stroke="#b38b22" stroke-width="1.5" opacity="0.2" stroke-dasharray="12 6" />
  <circle cx="400" cy="200" r="150" fill="none" stroke="#f5cc47" stroke-width="0.5" opacity="0.1" />

  <!-- The Incantation -->
  <text x="400" y="160" class="hermes-text">The Fool that doesn't belong to this era,</text>
  <text x="400" y="215" class="hermes-text">The mysterious ruler above the gray fog,</text>
  <text x="400" y="270" class="hermes-text">The King of Yellow and Black who wields good luck.</text>
  
  <!-- Aesthetic Subtitle -->
  <text x="400" y="340" class="sub-text">~ Hermes Incantation ~</text>
</svg>

## Things I like

Reading novels and manga, watching films and anime, folding origami.