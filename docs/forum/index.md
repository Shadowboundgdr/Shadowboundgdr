---
layout: page
title: Forum
---

<style>
.forum-hero { background: linear-gradient(135deg, #1a1a2e, #16213e); color: white; padding: 2rem; border-radius: 12px; margin: 1.5rem 0; text-align: center; }
.forum-hero h2 { color: white; border: none; margin: 0; font-size: 1.8rem; }
.forum-hero p { opacity: 0.9; margin-top: 0.5rem; }
.forum-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
.forum-card { border: 1px solid #e0e0e0; border-radius: 10px; padding: 1.2rem; transition: transform 0.15s, box-shadow 0.15s; }
.forum-card:hover { transform: translateY(-2px); box-shadow: 0 4px 12px rgba(0,0,0,0.1); }
.forum-card h3 { margin: 0 0 0.3rem; font-size: 1.1rem; color: #e94560; }
.forum-card p { margin: 0; font-size: 0.9rem; color: #555; }
.forum-card .btn { display: inline-block; margin-top: 0.7rem; padding: 0.3rem 1rem; background: #e94560; color: white; border-radius: 5px; text-decoration: none; font-size: 0.85rem; }
.forum-card .btn:hover { background: #d6384d; }
.forum-actions { display: flex; gap: 1rem; margin: 1.5rem 0; flex-wrap: wrap; }
.forum-actions .btn { flex: 1; text-align: center; padding: 0.8rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: 600; font-size: 0.95rem; min-width: 200px; }
.btn-primary { background: #e94560; color: white; }
.btn-primary:hover { background: #d6384d; }
.btn-secondary { background: #1a1a2e; color: white; }
.btn-secondary:hover { background: #2a2a4e; }
.btn-outline { border: 2px solid #e94560; color: #e94560; background: transparent; }
.btn-outline:hover { background: #e94560; color: white; }
.forum-stats { display: flex; gap: 2rem; justify-content: center; margin: 1.5rem 0; flex-wrap: wrap; }
.stat-box { text-align: center; padding: 1rem 1.5rem; background: #f8f9fa; border-radius: 8px; }
.stat-box .num { font-size: 1.5rem; font-weight: 700; color: #1a1a2e; }
.stat-box .label { font-size: 0.8rem; color: #666; }
@media (max-width: 600px) { .forum-grid { grid-template-columns: 1fr; } }
</style>

<div class="forum-hero">
  <h2>💬 Forum di Shadowbound</h2>
  <p>Benvenuto nella community! Il forum è basato su GitHub Discussions.<br>Ti serve un account GitHub gratuito per partecipare.</p>
</div>

<div class="forum-actions">
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new/choose" class="btn btn-primary">✨ Nuova Discussione</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions" class="btn btn-secondary">📢 Sfoglia il Forum</a>
  <a href="regolamento" class="btn btn-outline">📜 Regolamento</a>
</div>

## Categorie

<div class="forum-grid">

<div class="forum-card">
  <h3>📢 Annunci</h3>
  <p>Novità, aggiornamenti e comunicazioni ufficiali dal team</p>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/categories/announcements" class="btn">Apri →</a>
</div>

<div class="forum-card">
  <h3>🎮 Generale</h3>
  <p>Sessioni di gioco, strategie, storytelling e discussioni generali</p>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/categories/general" class="btn">Apri →</a>
</div>

<div class="forum-card">
  <h3>📝 Idee</h3>
  <p>Proponi nuove regole, classi, mostri o miglioramenti per Shadowbound</p>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/categories/ideas" class="btn">Apri →</a>
</div>

<div class="forum-card">
  <h3>🤔 Q&A</h3>
  <p>Fai domande sul regolamento o chiedi chiarimenti di gioco</p>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/categories/q-a" class="btn">Apri →</a>
</div>

<div class="forum-card">
  <h3>🎨 Show and Tell</h3>
  <p>Mostra personaggi, avventure, mappe e creazioni originali</p>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/categories/show-and-tell" class="btn">Apri →</a>
</div>

</div>

<div class="forum-stats">
  <div class="stat-box">
    <div class="num">5</div>
    <div class="label">Categorie</div>
  </div>
  <div class="stat-box">
    <div class="num">GitHub</div>
    <div class="label">Piattaforma</div>
  </div>
  <div class="stat-box">
    <div class="num">CC-BY-4.0</div>
    <div class="label">Licenza</div>
  </div>
</div>

## Guide

- [Regolamento del Forum](regolamento) — Leggi le regole prima di partecipare
- [Guida alla Partecipazione](guida) — Come usare il forum e GitHub Discussions
