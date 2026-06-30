---
layout: page
title: Forum
---

<style>
.forum-hero { background: linear-gradient(135deg, #1a1a2e, #16213e); color: white; padding: 2.5rem 2rem; border-radius: 12px; margin: 1.5rem 0; text-align: center; }
.forum-hero h2 { color: white; border: none; margin: 0; font-size: 1.8rem; }
.forum-hero p { opacity: 0.9; margin-top: 0.5rem; }
.forum-hero .stats { display: flex; gap: 2rem; justify-content: center; margin-top: 1.5rem; flex-wrap: wrap; }
.forum-hero .stat { text-align: center; }
.forum-hero .stat-num { font-size: 1.4rem; font-weight: 700; }
.forum-hero .stat-label { font-size: 0.8rem; opacity: 0.7; }
.forum-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
.forum-card { border: 1px solid #e0e0e0; border-radius: 10px; padding: 0; overflow: hidden; transition: transform 0.15s, box-shadow 0.15s; }
.forum-card:hover { transform: translateY(-2px); box-shadow: 0 4px 12px rgba(0,0,0,0.1); }
.forum-card-header { padding: 1.2rem 1.2rem 0.5rem; }
.forum-card h3 { margin: 0; font-size: 1.1rem; color: #1a1a2e; }
.forum-card p { margin: 0.3rem 0 0; font-size: 0.85rem; color: #555; }
.forum-card-footer { padding: 0.5rem 1.2rem 1rem; display: flex; gap: 0.5rem; flex-wrap: wrap; }
.forum-card-footer .btn { display: inline-block; padding: 0.3rem 0.8rem; border-radius: 5px; text-decoration: none; font-size: 0.8rem; font-weight: 500; }
.btn-discuss { background: #e94560; color: white; }
.btn-discuss:hover { background: #d6384d; }
.btn-label { background: #f0f0f0; color: #333; border: 1px solid #ddd; }
.btn-label:hover { background: #e0e0e0; }
.forum-actions { display: flex; gap: 1rem; margin: 1.5rem 0; flex-wrap: wrap; }
.forum-actions .btn { flex: 1; text-align: center; padding: 0.8rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: 600; font-size: 0.9rem; min-width: 180px; }
.btn-primary { background: #e94560; color: white; }
.btn-primary:hover { background: #d6384d; }
.btn-secondary { background: #1a1a2e; color: white; }
.btn-secondary:hover { background: #2a2a4e; }
.btn-outline { border: 2px solid #e94560; color: #e94560; background: transparent; }
.btn-outline:hover { background: #e94560; color: white; }
.quick-links { background: #f8f9fa; border-radius: 10px; padding: 1.2rem; margin: 1.5rem 0; }
.quick-links h3 { margin: 0 0 0.8rem; font-size: 1rem; color: #1a1a2e; }
.quick-links a { display: inline-block; margin: 0.3rem; padding: 0.3rem 0.8rem; background: white; border: 1px solid #ddd; border-radius: 5px; text-decoration: none; font-size: 0.85rem; color: #0366d6; }
.quick-links a:hover { background: #f0f0f0; }
@media (max-width: 600px) { .forum-grid { grid-template-columns: 1fr; } }
</style>

<div class="forum-hero">
  <h2>💬 Forum di Shadowbound</h2>
  <p>Benvenuto nella community! Partecipa alle discussioni su GitHub.</p>
  <div class="stats">
    <div class="stat"><div class="stat-num">6</div><div class="stat-label">Sezioni</div></div>
    <div class="stat"><div class="stat-num">Label</div><div class="stat-label">Organizzazione</div></div>
    <div class="stat"><div class="stat-num">GitHub</div><div class="stat-label">Piattaforma</div></div>
  </div>
</div>

<div class="forum-actions">
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new/choose" class="btn btn-primary">✨ Nuova Discussione</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions" class="btn btn-secondary">📢 Sfoglia il Forum</a>
  <a href="regolamento" class="btn btn-outline">📜 Regolamento</a>
</div>

## Sezioni

<div class="forum-grid">

<div class="forum-card">
  <div class="forum-card-header">
    <h3>🎮 Sessioni di Gioco</h3>
    <p>Condividi e discuti le tue sessioni, racconta storie epiche</p>
  </div>
  <div class="forum-card-footer">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%8E%AE+Sessioni+di+Gioco" class="btn btn-discuss">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8E%AE+Sessioni+di+Gioco%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="forum-card">
  <div class="forum-card-header">
    <h3>📝 Proposte e Suggerimenti</h3>
    <p>Proponi nuove regole, classi, mostri o miglioramenti</p>
  </div>
  <div class="forum-card-footer">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%9D+Proposte" class="btn btn-discuss">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9D+Proposte%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="forum-card">
  <div class="forum-card-header">
    <h3>🤔 Domande e Aiuto</h3>
    <p>Chiedi chiarimenti sul regolamento o aiuto per problemi di gioco</p>
  </div>
  <div class="forum-card-footer">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%A4%94+Domande" class="btn btn-discuss">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%A4%94+Domande%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="forum-card">
  <div class="forum-card-header">
    <h3>🎨 Creazioni della Community</h3>
    <p>Mostra personaggi, avventure, mappe e altre creazioni originali</p>
  </div>
  <div class="forum-card-footer">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%8E%A8+Creazioni" class="btn btn-discuss">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8E%A8+Creazioni%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="forum-card">
  <div class="forum-card-header">
    <h3>📚 Strategie e Tattiche</h3>
    <p>Discuti build, equipaggiamento, tattiche di combattimento</p>
  </div>
  <div class="forum-card-footer">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%9A+Strategie" class="btn btn-discuss">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9A+Strategie%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="forum-card">
  <div class="forum-card-header">
    <h3>📖 Storytelling e Narrazione</h3>
    <p>Scambia idee su trame, personaggi e tecniche narrative</p>
  </div>
  <div class="forum-card-footer">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%96+Storytelling" class="btn btn-discuss">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%96+Storytelling%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

</div>

<div class="quick-links">
  <h3>🔗 Link Rapidi</h3>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8E%AE+Sessioni+di+Gioco%22">🎮 Sessioni di Gioco</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9D+Proposte%22">📝 Proposte</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%A4%94+Domande%22">🤔 Domande</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8E%A8+Creazioni%22">🎨 Creazioni</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9A+Strategie%22">📚 Strategie</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%96+Storytelling%22">📖 Storytelling</a>
  <a href="regolamento">📜 Regolamento</a>
  <a href="guida">🎯 Guida</a>
</div>
