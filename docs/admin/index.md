---
layout: page
title: Admin
---

<style>
:root { --primary: #e94560; --dark: #1a1a2e; }
* { box-sizing: border-box; }
.admin-hero { background: linear-gradient(135deg, #1a1a2e, #16213e); color: white; padding: 2.5rem 2rem; border-radius: 12px; margin: 1.5rem 0; text-align: center; }
.admin-hero h2 { color: white; border: none; margin: 0; font-size: 1.8rem; }
.admin-hero p { opacity: 0.85; }
.admin-hero .lock { display: inline-block; background: rgba(233,69,96,0.2); border: 1px solid var(--primary); padding: 0.2rem 1rem; border-radius: 20px; font-size: 0.8rem; margin-top: 0.5rem; }
.grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 1.2rem; margin: 1.5rem 0; }
.card { border: 1px solid #e0e0e0; border-radius: 12px; overflow: hidden; transition: transform 0.15s, box-shadow 0.15s; background: white; }
.card:hover { transform: translateY(-3px); box-shadow: 0 6px 20px rgba(0,0,0,0.1); }
.card-b { padding: 1.5rem; }
.card h3 { margin: 0 0 0.5rem; font-size: 1.1rem; color: var(--dark); }
.card p { margin: 0 0 0.8rem; font-size: 0.85rem; color: #555; }
.card .links { display: flex; flex-direction: column; gap: 0.3rem; font-size: 0.85rem; }
.card .links a { color: var(--primary); text-decoration: none; }
.card .links a:hover { text-decoration: underline; }
.section-title { font-size: 1.3rem; font-weight: 700; color: var(--dark); margin: 2rem 0 0.5rem; border-bottom: 3px solid var(--primary); padding-bottom: 0.3rem; }
.warn { background: #fff3cd; border: 1px solid #ffc107; border-radius: 8px; padding: 1rem; margin: 1rem 0; font-size: 0.9rem; }
.warn strong { color: #856404; }
@media (max-width: 600px) { .grid { grid-template-columns: 1fr; } }
</style>

<div class="admin-hero">
  <h2>🛠️ Pannello Admin & Moderazione</h2>
  <p>Gestisci il repository, modera la community, configura il progetto</p>
  <div class="lock">🔒 Accesso richiede ruolo Admin/Mod su GitHub</div>
</div>

<div class="warn">
  <strong>⚠️ Importante:</strong> Questo pannello fornisce link diretti alle schermate di amministrazione su GitHub.com.
  Le azioni di moderazione e gestione si eseguono su GitHub. Assicurati di avere i permessi necessari.
</div>

## 📋 Gestione Repository

<div class="grid">

<div class="card">
  <div class="card-b">
    <h3>⚙️ Impostazioni Repository</h3>
    <p>Configurazione generale, collaboratori, branch, sicurezza</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings">🔧 Impostazioni generali</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/access">👥 Collaboratori e team</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/branches">🌿 Branch protection</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/secrets/actions">🔐 Secrets e variabili</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/hooks">🔗 Webhook</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/pages">📄 GitHub Pages</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>💬 Gestione Discussioni</h3>
    <p>Modera e configura il forum della community</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions">📢 Tutte le discussioni</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions?discussions_q=is%3Aunanswered">❓ Senza risposta</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/discussions">⚙️ Categorie discussione</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/discussions/categories/announcements">📢 Annunci</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>🐛 Issues</h3>
    <p>Gestisci bug report, richieste feature e task</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues">📋 Tutte le issues</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues?q=is%3Aopen+is%3Aissue">🟢 Aperte</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues?q=is%3Aissue+is%3Aclosed">🔴 Chiuse</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues/labels">🏷️ Label</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues/new/choose">✨ Nuova issue</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues/templates/edit">📝 Template issue</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>📥 Pull Requests</h3>
    <p>Revisiona e gestisci le modifiche al codice</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/pulls">📥 Tutte le PR</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/pulls?q=is%3Aopen+is%3Apr">🟢 PR aperte</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/pulls?q=is%3Apr+is%3Aclosed">🔴 PR chiuse</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/pulls?q=is%3Apr+is%3Aopen+review%3Arequired">👀 In attesa review</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>🔒 Security</h3>
    <p>Vulnerabilità, policy, audit</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/security">🛡️ Security overview</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/security/dependabot">🤖 Dependabot alerts</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/security/code-scanning">🔍 Code scanning</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/security/secret-scanning">🔐 Secret scanning</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>📊 Insights</h3>
    <p>Statistiche, traffico, community</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/graphs/contributors">👥 Contributors</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/graphs/traffic">📈 Traffico</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/graphs/code-frequency">📊 Code frequency</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/graphs/community">🏘️ Community profile</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/graphs/dependency-graph">🔗 Dependency graph</a>
    </div>
  </div>
</div>

</div>

## 👮 Moderazione Community

<div class="grid">

<div class="card">
  <div class="card-b">
    <h3>🚨 Moderazione</h3>
    <p>Gestisci segnalazioni e contenuti inappropriati</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/moderate">🛑 Moderazione discussioni</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/blocked-users">🚫 Utenti bloccati</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/interaction_limits">🔇 Limiti interazione</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/report-content">📩 Report contenuti</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>🏷️ Label</h3>
    <p>Gestisci le etichette per issues e discussioni</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/labels">📋 Tutte le label</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/issues/labels">🏷️ Gestione label</a>
      <a href="../forum/">🎯 Label forum (16 sezioni)</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>📜 Codice di Condotta</h3>
    <p>Applica e aggiorna le norme di comportamento</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/community/code-of-conduct">📜 Codice di condotta</a>
      <a href="../forum/regolamento">📋 Regolamento forum</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/blob/main/CONTRIBUTING.md">🤝 Guida contribuzione</a>
    </div>
  </div>
</div>

</div>

## ⚡ Azioni Rapide

<div class="grid">

<div class="card">
  <div class="card-b">
    <h3>⚙️ Actions & CI</h3>
    <p>Workflow e automazioni</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/actions">▶️ Esecuzioni workflow</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/actions/new">✨ Nuovo workflow</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/settings/actions">⚙️ Impostazioni Actions</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>📄 Wiki</h3>
    <p>Gestisci la documentazione</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/wiki">📖 Wiki</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/wiki/_new">➕ Nuova pagina wiki</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/wiki/_pages">📑 Pagine wiki</a>
    </div>
  </div>
</div>

<div class="card">
  <div class="card-b">
    <h3>📦 Releases</h3>
    <p>Gestisci versioni e rilasci</p>
    <div class="links">
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/releases">📦 Tutte le release</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/releases/new">✨ Nuova release</a>
      <a href="https://github.com/Shadowboundgdr/Shadowboundgdr/tags">🏷️ Tags</a>
    </div>
  </div>
</div>

</div>

<hr>
<p style="text-align:center;color:#666;font-size:0.85rem;">
  <a href="../">🏠 Dashboard</a> • <a href="../forum/">💬 Forum</a> • <a href="https://github.com/Shadowboundgdr/Shadowboundgdr">📦 Repository</a>
</p>
