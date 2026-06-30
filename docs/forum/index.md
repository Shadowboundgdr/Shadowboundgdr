---
layout: page
title: Forum
---

<style>
.hero { background: linear-gradient(135deg, #1a1a2e, #16213e); color: white; padding: 2.5rem 2rem; border-radius: 12px; margin: 1.5rem 0; text-align: center; }
.hero h2 { color: white; border: none; margin: 0; font-size: 1.8rem; }
.hero .badge { display: inline-block; background: rgba(233,69,96,0.2); border: 1px solid #e94560; padding: 0.2rem 1rem; border-radius: 20px; font-size: 0.8rem; margin-top: 0.5rem; }
.hero .stats { display: flex; gap: 2rem; justify-content: center; margin-top: 1.5rem; flex-wrap: wrap; }
.hero .stat { text-align: center; }
.hero .stat-num { font-size: 1.4rem; font-weight: 700; }
.hero .stat-label { font-size: 0.8rem; opacity: 0.7; }
.forum-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
.card { border: 1px solid #e0e0e0; border-radius: 10px; overflow: hidden; transition: transform 0.15s, box-shadow 0.15s; background: white; }
.card:hover { transform: translateY(-2px); box-shadow: 0 4px 14px rgba(0,0,0,0.1); }
.card-h { padding: 1.2rem 1.2rem 0.5rem; }
.card-h h3 { margin: 0; font-size: 1.1rem; color: #1a1a2e; }
.card-h p { margin: 0.3rem 0 0; font-size: 0.85rem; color: #555; }
.card-f { padding: 0.5rem 1.2rem 1rem; display: flex; gap: 0.5rem; flex-wrap: wrap; }
.btn { display: inline-block; padding: 0.3rem 0.8rem; border-radius: 5px; text-decoration: none; font-size: 0.8rem; font-weight: 500; transition: opacity 0.15s; }
.btn:hover { opacity: 0.85; }
.btn-primary { background: #e94560; color: white; }
.btn-label { background: #f0f0f0; color: #333; border: 1px solid #ddd; }
.btn-label:hover { background: #e0e0e0; }
.actions { display: flex; gap: 1rem; margin: 1.5rem 0; flex-wrap: wrap; }
.actions .act { flex: 1; text-align: center; padding: 0.8rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: 600; font-size: 0.9rem; min-width: 160px; transition: opacity 0.15s; }
.act:hover { opacity: 0.9; }
.act-primary { background: #e94560; color: white; }
.act-dark { background: #1a1a2e; color: white; }
.act-outline { border: 2px solid #e94560; color: #e94560; background: transparent; }
.act-outline:hover { background: #e94560; color: white; }
@media (max-width: 600px) { .forum-grid { grid-template-columns: 1fr; } }
</style>

<div class="hero">
  <h2>💬 Forum di Shadowbound</h2>
  <p>Benvenuto nella community! Partecipa alle discussioni su GitHub.</p>
  <div class="badge">16 sezioni • Label italiane</div>
  <div class="stats">
    <div class="stat"><div class="stat-num">16</div><div class="stat-label">Sezioni</div></div>
    <div class="stat"><div class="stat-num">Label</div><div class="stat-label">Organizzazione</div></div>
    <div class="stat"><div class="stat-num">GitHub</div><div class="stat-label">Piattaforma</div></div>
  </div>
</div>

<div class="actions">
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new/choose" class="act act-primary">✨ Nuova Discussione</a>
  <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions" class="act act-dark">📢 Sfoglia il Forum</a>
  <a href="regolamento" class="act act-outline">📜 Regolamento</a>
  <a href="guida" class="act act-outline">🎯 Guida</a>
</div>

## 🎮 Gioco e Sessioni

<div class="forum-grid">

<div class="card">
  <div class="card-h">
    <h3>🎮 Sessioni di Gioco</h3>
    <p>Racconta le tue sessioni, condividi storie epiche e consigli</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%8E%AE+Sessioni+di+Gioco" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8E%AE+Sessioni+di+Gioco%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>⚔️ Classi e Abilità</h3>
    <p>Discuti classi, talenti, build dei personaggi</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%E2%9A%94%EF%B8%8F+Classi+e+Abilit%C3%A0" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%E2%9A%94%EF%B8%8F+Classi+e+Abilit%C3%A0%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🧙 Magia e Incantesimi</h3>
    <p>Parla del sistema magico, incantesimi, poteri arcani</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%A7%99+Magia+e+Incantesimi" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%A7%99+Magia+e+Incantesimi%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>📚 Strategie e Tattiche</h3>
    <p>Build, equipaggiamento, tattiche di combattimento</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%9A+Strategie" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9A+Strategie%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🐉 Mostri e Nemici</h3>
    <p>Bestiario, creazione nemici, bilanciamento incontri</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%90%89+Mostri+e+Nemici" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%90%89+Mostri+e+Nemici%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

</div>

## 🏗️ Community e Contributi

<div class="forum-grid">

<div class="card">
  <div class="card-h">
    <h3>📝 Proposte e Suggerimenti</h3>
    <p>Proponi nuove regole, meccaniche o miglioramenti</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%9D+Proposte" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9D+Proposte%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🤔 Domande e Aiuto</h3>
    <p>Chiedi chiarimenti sul regolamento o meccaniche di gioco</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%A4%94+Domande" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%A4%94+Domande%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🎨 Creazioni della Community</h3>
    <p>Mostra personaggi, avventure, mappe, artefatti originali</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%8E%A8+Creazioni" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8E%A8+Creazioni%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🤝 Collaborazioni</h3>
    <p>Cerca o offri aiuto su progetti, traduzioni, grafica</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%A4%9D+Collaborazioni" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%A4%9D+Collaborazioni%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>❌ Segnalazioni</h3>
    <p>Segnala bug, problemi tecnici o violazioni delle regole</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%E2%9D%8C+Segnalazioni" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%E2%9D%8C+Segnalazioni%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🏠 Nuovo Giocatore</h3>
    <p>Presentati, chiedi informazioni per iniziare a giocare</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%8F%A0+Nuovo+Giocatore" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8F%A0+Nuovo+Giocatore%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

</div>

## 🌍 Mondo e Narrazione

<div class="forum-grid">

<div class="card">
  <div class="card-h">
    <h3>📖 Storytelling e Narrazione</h3>
    <p>Scambia idee su trame, personaggi, tecniche narrative</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%96+Storytelling" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%96+Storytelling%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>🗺️ Lore e Ambientazione</h3>
    <p>Approfondisci il mondo, la storia, le fazioni e i luoghi</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%97%BA%EF%B8%8F+Lore+e+Ambientazione" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%97%BA%EF%B8%8F+Lore+e+Ambientazione%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>📜 Regolamento</h3>
    <p>Discussioni sulle regole, chiarimenti e proposte di modifica</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%93%9C+Regolamento" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%93%9C+Regolamento%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

</div>

## 📢 Annunci e Varie

<div class="forum-grid">

<div class="card">
  <div class="card-h">
    <h3>🏆 Eventi e Annunci</h3>
    <p>Eventi organizzati, tornei, sessioni speciali e annunci ufficiali</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%8F%86+Eventi+e+Annunci" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%8F%86+Eventi+e+Annunci%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

<div class="card">
  <div class="card-h">
    <h3>💬 Off-Topic</h3>
    <p>Chiacchiere libere, giochi, sondaggi e tutto ciò che non rientra altrove</p>
  </div>
  <div class="card-f">
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/new?category=general&labels=%F0%9F%92%AC+Off-Topic" class="btn btn-primary">Nuova →</a>
    <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=label%3A%22%F0%9F%92%AC+Off-Topic%22" class="btn btn-label">Sfoglia</a>
  </div>
</div>

</div>

<hr>
<p style="text-align:center;color:#666;font-size:0.85rem;">
  💡 Usa le label per filtrare le discussioni • <a href="regolamento">Regolamento</a> • <a href="guida">Guida</a> • <a href="../admin">Admin Panel</a>
</p>
