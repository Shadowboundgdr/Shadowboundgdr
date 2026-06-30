---
layout: page
title: Home
---

<style>
.hero { background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%); color: white; padding: 3rem 2rem; border-radius: 12px; margin: 1.5rem 0; text-align: center; }
.hero h1 { color: white; border: none; font-size: 2.2rem; margin: 0; }
.hero p { opacity: 0.9; font-size: 1.1rem; margin-top: 0.5rem; }
.hero .badge { display: inline-block; padding: 0.3rem 0.8rem; border-radius: 20px; font-size: 0.8rem; font-weight: 600; margin: 0.5rem 0.2rem; }
.hero .badge-cc { background: #e94560; color: white; }
.hero .badge-gdr { background: rgba(255,255,255,0.2); color: white; }
.section-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
.section-card { border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.2rem; transition: transform 0.15s, box-shadow 0.15s; }
.section-card:hover { transform: translateY(-2px); box-shadow: 0 4px 12px rgba(0,0,0,0.1); }
.section-card h3 { margin: 0 0 0.5rem; color: #e94560; font-size: 1.1rem; }
.section-card ul { list-style: none; padding: 0; margin: 0; }
.section-card li { margin: 0.3rem 0; }
.section-card a { color: #0366d6; text-decoration: none; font-size: 0.9rem; }
.section-card a:hover { text-decoration: underline; }
.forum-cta { background: linear-gradient(135deg, #e94560, #d6384d); color: white; border-radius: 10px; padding: 1.5rem 2rem; margin: 1.5rem 0; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 1rem; }
.forum-cta h3 { color: white; border: none; margin: 0; }
.forum-cta .btn { background: white; color: #e94560; padding: 0.6rem 1.5rem; border-radius: 6px; text-decoration: none; font-weight: 600; }
.forum-cta .btn:hover { background: #f8f8f8; }
@media (max-width: 600px) { .section-grid { grid-template-columns: 1fr; } }
</style>

<div class="hero">
  <span class="badge badge-gdr">GDR da Tavolo</span>
  <span class="badge badge-cc">CC-BY-4.0</span>
  <h1>🎲 Shadowbound GDR</h1>
  <p>Regolamento Dark Fantasy Open Source basato su D&D 5.2.1 SRD</p>
</div>

<div class="forum-cta">
  <div>
    <h3>💬 Unisciti alla community!</h3>
    <p style="opacity:0.9;margin:0;">Forum, discussioni e collaborazione su GitHub Discussions</p>
  </div>
  <a href="forum/" class="btn">Vai al Forum →</a>
</div>

## Manuali

<div class="section-grid">
  <div class="section-card">
    <h3>📖 Giocatore</h3>
    <ul>
      <li><a href="manuale-giocatore.md">Manuale del Giocatore</a></li>
      <li><a href="guida-rapida.md">Guida Rapida</a></li>
      <li><a href="guida-avanzati.md">Guida per Avanzati</a></li>
      <li><a href="guida-playtest.md">Guida al Playtest</a></li>
    </ul>
  </div>
  <div class="section-card">
    <h3>🎲 Dungeon Master</h3>
    <ul>
      <li><a href="manuale-dm.md">Manuale del DM</a></li>
      <li><a href="sistema-gioco.md">Sistema di Gioco</a></li>
    </ul>
  </div>
  <div class="section-card">
    <h3>🌍 Ambientazione</h3>
    <ul>
      <li><a href="ambientazione.md">Il mondo di Umbra</a></li>
      <li><a href="bestiario.md">Bestiario</a></li>
      <li><a href="razze.md">Razze</a></li>
      <li><a href="deita.md">Divinità</a></li>
    </ul>
  </div>
  <div class="section-card">
    <h3>⚔️ Regole</h3>
    <ul>
      <li><a href="crafting.md">Crafting</a></li>
      <li><a href="economia.md">Economia</a></li>
      <li><a href="fazioni.md">Fazioni</a></li>
      <li><a href="malattie.md">Malattie</a></li>
      <li><a href="artefatti.md">Artefatti</a></li>
    </ul>
  </div>
  <div class="section-card">
    <h3>🏷️ Brand</h3>
    <ul>
      <li><a href="brand/brand-identity.md">Brand Identity</a></li>
      <li><a href="brand/logo-specifications.md">Specifiche Logo</a></li>
      <li><a href="brand/color-palette.md">Palette Colori</a></li>
      <li><a href="brand/typography.md">Tipografia</a></li>
    </ul>
  </div>
  <div class="section-card">
    <h3>👥 Community</h3>
    <ul>
      <li><a href="community/guida-condivisione-avventure.md">Condividere Avventure</a></li>
      <li><a href="community/guida-dm-community.md">Programma DM</a></li>
      <li><a href="community/sistema-badge.md">Sistema Badge</a></li>
      <li><a href="community/guida-eventi.md">Eventi</a></li>
    </ul>
  </div>
</div>
