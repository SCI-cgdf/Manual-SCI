<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SCI — Cartilha Interativa · JAD + PIP</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=IBM+Plex+Sans:wght@400;500;600&family=IBM+Plex+Mono:wght@500&display=swap" rel="stylesheet">
<style>
  :root {
    --navy:        #0d2240;
    --navy-mid:    #153460;
    --accent:      #1e5fa8;
    --accent-light:#c8dbf0;
    --accent-pale: #edf3fa;
    --warn-bg:     #fff8e1;
    --warn-border: #f0a000;
    --warn-text:   #7a5000;
    --green-bg:    #e8f5e9;
    --green-border:#388e3c;
    --text:        #1a1a2e;
    --muted:       #5a6070;
    --white:       #ffffff;
    --border:      #d0dce8;
    --bg:          #f4f7fb;
    --sidebar-w:   228px;
    --pip-color:   #0f3060;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: 'IBM Plex Sans', sans-serif;
    background: var(--bg);
    color: var(--text);
    display: flex;
    min-height: 100vh;
    font-size: 20px;
  }

  /* ── SIDEBAR ── */
  .sidebar {
    width: var(--sidebar-w);
    background: var(--navy);
    min-height: 100vh;
    position: fixed;
    top: 0; left: 0;
    display: flex;
    flex-direction: column;
    z-index: 100;
    overflow-y: auto;
  }
  .sidebar-logo {
    padding: 20px 18px 16px;
    border-bottom: 1px solid rgba(255,255,255,.1);
  }
  .sci-mark {
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 30px; font-weight: 800;
    color: white; letter-spacing: -1.5px; line-height: 1;
  }
  .sci-sub {
    font-size: 9px; font-weight: 600;
    color: #7aa8cc; letter-spacing: 1.4px;
    text-transform: uppercase; margin-top: 4px;
  }
  .sidebar-label {
    font-size: 9px; font-weight: 700;
    color: rgba(255,255,255,.3);
    letter-spacing: 1.5px; text-transform: uppercase;
    padding: 14px 18px 5px;
  }
  .nav-btn {
    display: flex; align-items: center; gap: 10px;
    padding: 9px 18px;
    cursor: pointer; border: none; background: none;
    color: #8ab4d8;
    font-family: 'IBM Plex Sans', sans-serif;
    font-size: 12.5px; font-weight: 500;
    text-align: left; width: 100%;
    border-left: 3px solid transparent;
    transition: background .12s, color .12s;
  }
  .nav-btn:hover { background: rgba(255,255,255,.06); color: white; }
  .nav-btn.active { background: rgba(30,95,168,.28); color: white; border-left-color: #5b9fd6; }
  .nav-icon { font-size: 13px; flex-shrink: 0; }
  .sidebar-footer {
    margin-top: auto;
    padding: 14px 18px;
    border-top: 1px solid rgba(255,255,255,.1);
    font-size: 9.5px; color: rgba(255,255,255,.28);
    line-height: 1.7;
  }

  /* ── MAIN ── */
  .main { margin-left: var(--sidebar-w); flex: 1; }
  .topbar {
    background: white;
    border-bottom: 2px solid var(--border);
    padding: 13px 28px;
    display: flex; align-items: center; gap: 8px;
    position: sticky; top: 0; z-index: 50;
  }
  .topbar-persona {
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 18px; font-weight: 800; color: var(--navy);
  }
  .topbar-desc { font-size: 13px; color: var(--muted); }
  .content { padding: 22px 28px; max-width: none; width: 95%; margin: 0 auto; }

  /* ── MODULE TABS ── */
  .mod-tabs {
    display: flex; border-bottom: 2px solid var(--border);
    margin-bottom: 20px;
  }
  .mod-tab {
    padding: 8px 22px;
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 11.5px; font-weight: 700;
    letter-spacing: .5px; text-transform: uppercase;
    cursor: pointer; border: none; background: none;
    color: var(--muted);
    border-bottom: 3px solid transparent;
    margin-bottom: -2px;
    transition: color .12s;
  }
  .mod-tab:hover { color: var(--navy); }
  .mod-tab.active-jad { color: var(--accent); border-bottom-color: var(--accent); }
  .mod-tab.active-pip { color: var(--pip-color); border-bottom-color: var(--pip-color); }

  /* ── SECTION TITLE ── */
  .sec-title {
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 14px; font-weight: 700;
    letter-spacing: 1.5px; text-transform: uppercase;
    color: var(--muted);
    margin: 20px 0 10px;
    padding-bottom: 6px;
    border-bottom: 1px solid var(--border);
  }
  .sec-title:first-of-type { margin-top: 0; }

  /* ── PERSONA INTRO ── */
  .persona-tag {
    display: inline-block;
    background: var(--accent);
    color: white;
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 14px; font-weight: 700;
    letter-spacing: 1px; text-transform: uppercase;
    padding: 3px 10px; border-radius: 2px;
    margin-bottom: 8px;
  }
  .persona-tag.pip-tag { background: var(--pip-color); }
  .persona-intro-box {
    background: var(--accent-pale);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 12px 15px;
    margin-bottom: 16px;
    font-size: 12px; line-height: 1.58;
  }

  /* ── ACCESS BOX ── */
  .access-box {
    background: var(--navy);
    color: #a8c4e0;
    padding: 7px 14px;
    border-radius: 4px;
    font-family: 'IBM Plex Mono', monospace;
    font-size: 14px;
    display: inline-block;
    margin-bottom: 14px;
  }

  /* ── STEP CARDS ── */
  .steps { display: flex; flex-direction: column; gap: 9px; margin-bottom: 14px; }
  .step-card {
    display: flex; gap: 13px;
    background: white;
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 11px 13px;
  }
  .step-num {
    width: 32px; height: 32px; flex-shrink: 0;
    background: var(--accent);
    border-radius: 50%;
    color: white;
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 14px; font-weight: 800;
    display: flex; align-items: center; justify-content: center;
  }
  .step-card.pip .step-num { background: var(--pip-color); }
  .step-title {
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 16px; font-weight: 700;
    color: var(--navy); margin-bottom: 5px;
  }
  .step-body ul { list-style: none; padding: 0; }
  .step-body li {
    padding: 2px 0 2px 14px;
    position: relative;
    font-size: 15px; line-height: 1.5;
  }
  .step-body li::before {
    content: '›'; position: absolute; left: 2px;
    color: var(--accent); font-weight: 700; font-size: 14px; line-height: 1.2;
  }
  .step-card.pip .step-body li::before { color: var(--pip-color); }
  .step-body li strong { color: var(--navy); }

  /* ── CALLOUTS ── */
  .callout {
    border-radius: 4px; padding: 9px 13px;
    font-size: 15px; margin: 8px 0; line-height: 1.55;
  }
  .callout-warn  { background: var(--warn-bg); border-left: 4px solid var(--warn-border); color: var(--warn-text); }
  .callout-info  { background: var(--accent-pale); border-left: 4px solid var(--accent); color: var(--navy-mid); }
  .callout-green { background: var(--green-bg); border-left: 4px solid var(--green-border); color: #1b4d1e; }
  .callout strong { font-weight: 700; }

  /* ── TABLES ── */
  .flow-table, .decision-table {
    width: 100%; border-collapse: collapse;
    font-size: 14px; margin: 6px 0;
  }
  .flow-table th, .decision-table th {
    background: var(--navy); color: white;
    padding: 6px 10px; text-align: left;
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 13px; font-weight: 700; letter-spacing: .5px;
  }
  .flow-table td, .decision-table td {
    padding: 6px 10px;
    border-bottom: 1px solid var(--border);
    vertical-align: top;
  }
  .flow-table tr:last-child td, .decision-table tr:last-child td { border-bottom: none; }
  .flow-table tr:nth-child(even) td,
  .decision-table tr:nth-child(even) td { background: var(--accent-pale); }
  .flow-table td:first-child { font-weight: 700; color: var(--navy); width: 24px; text-align: center; }
  .flow-table td:nth-child(2) { font-weight: 600; font-size: 11px; width: 28%; }
  .decision-table td:first-child { font-weight: 600; color: var(--navy); width: 32%; }

  /* ── SIGN SEQUENCE ── */
  .sign-seq {
    display: flex; align-items: center; gap: 6px; flex-wrap: wrap;
    background: var(--accent-pale);
    border: 1px solid var(--accent-light);
    border-radius: 5px; padding: 10px 14px;
    font-size: 11px; margin: 6px 0;
  }
  .sign-step {
    background: var(--accent); color: white;
    padding: 4px 11px; border-radius: 3px;
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 10px; font-weight: 700;
  }
  .sign-step.pip-step { background: var(--pip-color); }
  .sign-step.last     { background: var(--navy); }
  .sign-arrow { color: var(--muted); font-weight: 700; }

  /* ── GLOSSARY ── */
  .gloss-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; }
  .gloss-item {
    background: white; border: 1px solid var(--border);
    border-radius: 5px; padding: 10px 12px;
  }
  .gloss-term {
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-size: 15px; font-weight: 700;
    color: var(--accent); margin-bottom: 3px;
  }
  .gloss-def { font-size: 11px; color: var(--text); line-height: 1.45; }

  /* ── BADGES ── */
  .badge { display: inline-block; padding: 2px 8px; border-radius: 12px; font-size: 10px; font-weight: 600; }
  .badge-blue { background: var(--accent-light); color: var(--navy); }
  .badge-wait { background: #fff3e0; color: #7a4000; }
  .badge-done { background: #e8f5e9; color: #1b5e20; }

  /* ── CHECKLIST ── */
  .checklist { list-style: none; padding: 0; margin: 4px 0 12px; }
  .checklist li {
    padding: 3px 0 3px 20px; position: relative;
    font-size: 14px; line-height: 1.45;
  }
  .checklist li::before { content: '☐'; position: absolute; left: 0; color: var(--accent); }

  /* ── OVERVIEW CARD ── */
  .overview-card {
    background: white; border: 1px solid var(--border);
    border-radius: 6px; padding: 13px 15px; margin-bottom: 10px;
  }
  .overview-card p { font-size: 12px; line-height: 1.58; }
  .overview-card p + p { margin-top: 6px; }

  /* ── VISIBILITY ── */
  .tab-panel    { display: none; }
  .tab-panel.active  { display: block; }
  .section-page { display: none; }
  .section-page.active { display: block; }
</style>
</head>
<body>

<!-- ══════════════════════════════════════════
     SIDEBAR
══════════════════════════════════════════ -->
<nav class="sidebar">
  <div class="sidebar-logo">
    <div class="sci-mark">SCI</div>
    <div class="sci-sub">Sistema Correcional Integrado</div>
  </div>

  <div class="sidebar-label">Geral</div>
  <button class="nav-btn active" onclick="showSection('geral')" id="nav-geral">
    <span class="nav-icon">🏠</span> Visão Geral
  </button>

  <div class="sidebar-label" style="margin-top:6px">Por Perfil</div>
  <button class="nav-btn" onclick="showSection('apoio')" id="nav-apoio">
    <span class="nav-icon">📋</span> Apoio à Autoridade
  </button>
  <button class="nav-btn" onclick="showSection('autoridade')" id="nav-autoridade">
    <span class="nav-icon">⚖️</span> Autoridade Correcional
  </button>
  <button class="nav-btn" onclick="showSection('gestor')" id="nav-gestor">
    <span class="nav-icon">📊</span> Gestor Correcional
  </button>
  <button class="nav-btn" onclick="showSection('analista')" id="nav-analista">
    <span class="nav-icon">🔍</span> Analista / Investigador
  </button>
  <button class="nav-btn" onclick="showSection('revisor')" id="nav-revisor">
    <span class="nav-icon">🔎</span> Revisor
  </button>
   <div class="sidebar-label" style="margin-top:6px">Documentos</div>
  <button class="nav-btn" onclick="showSection('regras')" id="nav-regras">
    <span class="nav-icon">👑</span> Regras de Ouro
  </button>
  <button class="nav-btn" onclick="showSection('fluxogramas')" id="nav-fluxogramas">
    <span class="nav-icon">📊</span> Fluxogramas
  </button>
  <div class="sidebar-footer">
    SCI · Cartilha de Uso · JAD + PIP<br>
    Março de 2026<br><br>
    <strong style="color:white;font-size:11px;display:block;margin-bottom:2px">Erika Oliveira</strong><span style="color:#93b3df;font-size:9px;display:block;margin-bottom:4px">Product Owner · Responsável Técnica SCI</span>erika.oliveira@cg.df.gov.br<br>☎ 61-2108-3294 · (61) 98334-1110
  </div>
</nav>

<!-- ══════════════════════════════════════════
     MAIN
══════════════════════════════════════════ -->
<div class="main">
  <div class="topbar">
    <span class="topbar-persona" id="topbar-title">Visão Geral</span>
    <span class="topbar-desc" id="topbar-desc">· Fluxos, glossário e perfis</span>
  </div>

  <div class="content">

    <!-- ══════════════════════════════
         VISÃO GERAL
    ══════════════════════════════ -->
    <div class="section-page active" id="page-geral">

      <div class="sec-title">O que é o SCI</div>
      <div class="overview-card">
        <p>O Sistema Correcional Integrado (SCI) é a plataforma corporativa do Governo do Distrito Federal, sob a governança da Controladoria-Geral do Distrito Federal (CGDF), desenvolvida para gerenciar de forma integrada toda a atividade correcional — desde o recebimento de uma notícia de irregularidade até o encerramento do procedimento.</p>
        <p>Por meio do SCI, os órgãos e entidades do GDF passam a registrar, instruir, tramitar e acompanhar suas demandas correcionais em um ambiente digital único, com fluxos padronizados, controle de prazos, rastreabilidade dos atos praticados e informações gerenciais consolidadas. A solução fortalece a integração entre as unidades correcionais e a CGDF, promovendo maior eficiência, transparência, segurança jurídica e conformidade na condução dos procedimentos.</p>
      </div>
      <div class="callout callout-info">
        <strong>Base legal:</strong> Lei nº 4.938/2012 (SICOR/DF) · Lei Complementar nº 840/2011 · Decreto nº 42.830/2021 · IN nº 02/2021-CGDF
      </div>
      <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

      <div class="sec-title">Perfis de Usuário</div>
      <div class="gloss-grid">
        <div class="gloss-item"><div class="gloss-term">📋 Apoio à Autoridade</div><div class="gloss-def">Registra demandas no sistema e realiza encaminhamentos formais por meio do SEI</div></div>
        <div class="gloss-item"><div class="gloss-term">⚖️ Autoridade Correcional</div><div class="gloss-def">Instância decisória responsável pelo juízo final de admissibilidade e pela deliberação quanto à instauração, condução e encerramento dos procedimentos correcionais no sistema.</div></div>
        <div class="gloss-item"><div class="gloss-term">📊 Gestor Correcional</div><div class="gloss-def">Coordena a tramitação das demandas correcionais, realiza a distribuição de processos, designa analistas/investigadores e promove a revisão técnica das análises e manifestações produzidas, antes da aprovação pela autoridade competente.</div></div>
        <div class="gloss-item"><div class="gloss-term">🔍 Analista / Investigador</div><div class="gloss-def">Responsável pela instrução técnica dos autos, mediante a realização de análises, diligências e coleta de elementos informativos, com vistas a subsidiar a tomada de decisão da autoridade competente.</div></div>
        <div class="gloss-item"><div class="gloss-term">🔎 Revisor</div><div class="gloss-def">Revisa as análises técnicas correcionais, realizando o controle de qualidade e a validação prévia das manifestações antes do encaminhamento para deliberação do Gestor Correcional.</div></div>
      </div>

      <div class="sec-title" style="margin-top:22px">Glossário Essencial</div>
      <div class="gloss-grid">
        <div class="gloss-item"><div class="gloss-term">Demanda</div><div class="gloss-def">Notícia de possível irregularidade relacionada à atuação de agentes públicos ou privados no âmbito da Administração Pública do Distrito Federal.</div></div>
        <div class="gloss-item"><div class="gloss-term">JAD</div><div class="gloss-def">Juízo de Admissibilidade: Análise preliminar destinada a verificar a existência de elementos mínimos que justifiquem a instauração de procedimento correcional.</div></div>
        <div class="gloss-item"><div class="gloss-term">PIP</div><div class="gloss-def">Procedimento destinado à apuração inicial de possível irregularidade, instaurado quando o Juízo de Admissibilidade (JAD) identifica indícios mínimos de materialidade e autoria.</div></div>
        <div class="gloss-item"><div class="gloss-term">Fato</div><div class="gloss-def">Ocorrência registrada para fins de análise correcional, descrita com base nas informações constantes do relato, podendo conter ou não elementos como data, local e demais circunstâncias.</div></div>
        <div class="gloss-item"><div class="gloss-term">Envolvido</div><div class="gloss-def">Agente público ou ente privado indicado como possível responsável pela irregularidade sob apuração no Sistema Correcional Integrado.</div></div>
        <div class="gloss-item"><div class="gloss-term">Conduta</div><div class="gloss-def">Ação ou omissão irregular atribuída ao envolvido</div></div>
        <div class="gloss-item"><div class="gloss-term">Evidência</div><div class="gloss-def">Documento, registro, arquivo ou informação que fundamenta ou corrobora a análise.</div></div>
        <div class="gloss-item"><div class="gloss-term">Diligência (PIP)</div><div class="gloss-def">Ação investigativa destinada à coleta e verificação de informações, com vistas a avaliar a veracidade de possível irregularidade em apuração.</div></div>
        <div class="gloss-item"><div class="gloss-term">Fundamentação</div><div class="gloss-def">Exposição técnico-jurídica que apresenta os elementos normativos, fáticos e analíticos que sustentam e justificam a recomendação formulada.</div></div>
        <div class="gloss-item"><div class="gloss-term">Matriz de Responsabilização</div><div class="gloss-def">Instrumento de sistematização que relaciona fatos, envolvidos, condutas, enquadramentos e recomendações, com vistas a subsidiar a análise e a tomada de decisão.</div></div>
        <div class="gloss-item"><div class="gloss-term">JAD Origem (PIP)</div><div class="gloss-def">Trata-se do JAD que originou a instauração do Procedimento de Investigação Preliminar (PIP). As informações cadastradas nesse JAD são automaticamente vinculadas e herdadas pelo sistema no registro do PIP, garantindo a continuidade e a rastreabilidade dos dados desde a origem da demanda.</div></div>
      </div>

      <div class="sec-title" style="margin-top:22px">Fluxo Geral — JAD</div>
      <table class="flow-table">
        <thead><tr><th>#</th><th>Persona</th><th>O que faz</th><th>Resultado</th></tr></thead>
        <tbody>
          <tr><td>1</td><td>Apoio à Autoridade</td><td>Registra a demanda no SCI</td><td><em>Demanda criada</em></td></tr>
          <tr><td>2</td><td>Autoridade Correcional</td><td>Analisa e encaminha a demanda</td><td><em>JAD criado (Aguardando distribuição)</em></td></tr>
          <tr><td>3</td><td>Gestor Correcional</td><td>Distribui o JAD para um analista</td><td><em>JAD atribuído</em></td></tr>
          <tr><td>4</td><td>Analista</td><td>Cadastra fatos, envolvidos, evidências; elabora análise e fundamentação</td><td><em>JAD enviado ao Revisor</em></td></tr>
          <tr><td>5</td><td>Revisor JAD</td><td>Revisa a análise. Aprova ou devolve</td><td><em>JAD enviado ao Gestor ou devolvido ao analista</em></td></tr>
          <tr><td>6</td><td>Gestor Correcional</td><td>Revisa o parecer. Aprova ou devolve</td><td><em>JAD enviado à Autoridade ou devolvido ao analista</em></td></tr>
          <tr><td>7</td><td>Autoridade Correcional</td><td>Aprova ou devolve. Inicia ciclo de assinaturas (Analista → Revisor → Gestor → Autoridade)</td><td><em>Assinaturas em curso</em></td></tr>
          <tr><td>8</td><td>Autoridade Correcional</td><td>Assinatura final</td><td><em>Processo retorna ao Analista para finalização</em></td></tr>
          <tr><td>9</td><td>Analista</td><td>Finaliza o JAD no sistema</td><td><em>Processo encerrado → cai na caixa do Apoio</em></td></tr>
          <tr><td>10</td><td>Apoio à Autoridade</td><td>Faz o download da nota técnica assinada e inclui o processo no SEI para seguir com a recomendação proposta</td><td><em>JAD encerrado</em></td></tr>
        </tbody>
      </table>

      <div class="sec-title" style="margin-top:18px">Status do JAD</div>
      <table class="flow-table">
        <thead><tr><th colspan="2">Status</th><th>Significa</th></tr></thead>
        <tbody>
<tr><td colspan="2"><span class="badge badge-wait">Aguardando distribuição</span></td><td>JAD criado pela Autoridade. Gestor ainda não distribuiu para nenhum analista</td></tr>
<tr><td colspan="2"><span class="badge badge-wait">Aguardando cadastro</span></td><td>JAD distribuído pelo Gestor. Analista ainda não iniciou</td></tr>
<tr><td colspan="2"><span class="badge badge-blue">Em cadastro</span></td><td>Analista iniciou o registro de fatos, envolvidos e evidências</td></tr>
<tr><td colspan="2"><span class="badge badge-wait">Aguardando análise</span></td><td>Cadastro concluído. Processo está com o Analista, mas ele ainda não iniciou a fase de análise técnica</td></tr>
<tr><td colspan="2"><span class="badge badge-blue">Em análise</span></td><td>Cadastro concluído. Analista na fase de análise técnica</td></tr>
<tr><td colspan="2"><span class="badge badge-blue">Em revisão — Revisor</span></td><td>Análise concluída e enviada ao Revisor</td></tr>
<tr><td colspan="2"><span class="badge badge-blue">Em revisão — Gestor</span></td><td>Aprovado pelo Revisor, agora com o Gestor</td></tr>
<tr><td colspan="2"><span class="badge badge-blue">Em revisão — Autoridade</span></td><td>Aprovado pelo Gestor, agora com a Autoridade</td></tr>
<tr><td colspan="2"><span class="badge badge-wait">Aguardando assinaturas</span></td><td>Aprovado pela Autoridade. Aguardando ciclo de assinaturas</td></tr>
<tr><td colspan="2"><span class="badge badge-wait">Aguardando Finalização</span></td><td>Nota técnica assinada por todos. Processo retornou ao Analista, que precisa realizar a ação final (Finalizar, Invalidar ou Encaminhar). Atenção: o Apoio não deve agir neste status.</td></tr>
<tr><td colspan="2"><span class="badge badge-done">Concluído</span></td><td>Nota técnica assinada por todos e Analista finalizou. Processo pronto para o Apoio registrar o número do processo SEI.</td></tr>
<tr><td colspan="2"><span class="badge badge-done">Finalizado - Encaminhado via SEI</span></td><td>Apoio registrou o número do processo SEI. Ciclo totalmente encerrado.</td></tr>
<!-- NOVOS STATUS - ENCAMINHAMENTO A ÓRGÃO EXTERNO -->
<tr><td colspan="2"><span class="badge badge-wait">Aguardando Encaminhamento</span></td><td>Analista preparou o processo para encaminhamento a órgão externo. Apoio à Autoridade (CGDF) revisa os documentos antes do envio.</td></tr>
<tr><td colspan="2"><span class="badge badge-blue">Processo Encaminhado</span></td><td>Apoio confirmou. Processo recebido na caixa de Processos Recebidos da Autoridade do órgão de destino</td></tr>
<tr><td colspan="2"><span class="badge badge-wait">Aguardando Decisão da Devolução</span></td><td>Órgão de destino devolveu o processo. Autoridade da CGDF decide entre aceitar a avocação ou rejeitar a devolução</td></tr>

          <table class="flow-table">
        <thead><tr><th>#</th><th>Persona</th><th>O que faz</th><th>Resultado</th></tr></thead>
        <tbody>
          <tr><td>1</td><td>Gestor Correcional</td><td>Sugere os Servidores Designados (Investigadores) para o PIP</td><td><em>Investigadores indicados</em></td></tr>
          <tr><td>2</td><td>Autoridade Correcional</td><td>Valida investigadores e assina a instauração</td><td><em>PIP formalmente instaurado</em></td></tr>
          <tr><td>3</td><td>Apoio à Autoridade</td><td>Elabora despacho, registra no SEI e encaminha ao Investigador</td><td><em>Processo autuado; Investigador habilitado</em></td></tr>
          <tr><td>4</td><td>Servidor Designado</td><td>Edita fato herdado do JAD, registra diligências, preenche análise e fundamentação</td><td><em>Relatório concluído → Revisor</em></td></tr>
          <tr><td>5</td><td>Revisor Correcional</td><td>Revisa a análise técnica. Aprova ou devolve</td><td><em>PIP enviado ao Gestor</em></td></tr>
          <tr><td>6</td><td>Gestor Correcional</td><td>Valida institucionalmente. Aprova ou devolve</td><td><em>PIP enviado à Autoridade</em></td></tr>
          <tr><td>7</td><td>Autoridade Correcional</td><td>Aprova ou devolve. Inicia ciclo de assinaturas</td><td><em>Assinaturas em curso</em></td></tr>
          <tr><td>8</td><td>Autoridade Correcional</td><td>Assinatura final</td><td><em>PIP concluído → Apoio</em></td></tr>
          <tr><td>9</td><td>Apoio à Autoridade</td><td>Download do relatório e encaminhamento via SEI</td><td><em>Processo encerrado</em></td></tr>
        </tbody>
      </table>

      <div class="sec-title" style="margin-top:18px">Status do PIP</div>
      <table class="flow-table">
        <thead><tr><th colspan="2">Status</th><th>Significa</th></tr></thead>
        <tbody>
          <tr><td colspan="2"><span class="badge badge-wait">Aguardando Despacho</span></td><td>Autoridade determinou a instauração do PIP. Apoio precisa elaborar o despacho de instauração</td></tr>
          <tr><td colspan="2"><span class="badge badge-blue">Em cadastro</span></td><td>Investigador iniciou o registro de fatos e diligências</td></tr>
          <tr><td colspan="2"><span class="badge badge-blue">Em análise</span></td><td>Cadastro concluído. Investigador na fase de análise técnica</td></tr>
          <tr><td colspan="2"><span class="badge badge-blue">Em revisão — Revisor</span></td><td>Análise concluída e enviada ao Revisor</td></tr>
          <tr><td colspan="2"><span class="badge badge-blue">Em revisão — Gestor</span></td><td>Aprovado pelo Revisor, agora com o Gestor</td></tr>
          <tr><td colspan="2"><span class="badge badge-blue">Em revisão — Autoridade</span></td><td>Aprovado pelo Gestor, agora com a Autoridade</td></tr>
          <tr><td colspan="2"><span class="badge badge-wait">Aguardando assinaturas</span></td><td>Aprovado pela Autoridade. Aguardando ciclo de assinaturas</td></tr>
          <tr><td colspan="2"><span class="badge badge-wait">Aguardando registro no SEI</span></td><td>Despacho assinado pela Autoridade. Apoio deve autuar o processo no SEI e registrar o número</td></tr>
          <tr><td colspan="2"><span class="badge badge-done">Concluído</span></td><td>Relatório assinado por todos. PIP encerrado</td></tr>
        </tbody>
      </table>
    </div><!-- /geral -->
    
    <!-- REGRAS DE OURO -->
    <div class="section-page" id="page-regras">
      <div class="sec-title">👑 Regras de Ouro do SCI</div>
      <div class="callout callout-info" style="background: #0d2240; color: white; border-left-color: #f0a000;">
        <strong style="font-size: 18px;">Princípio Fundamental do SCI</strong><br>
        O sistema pode simplificar, automatizar e acelerar atividades, mas nunca pode contrariar a legislação, os normativos aplicáveis ou as garantias do processo correcional.
      </div>
      <div class="gloss-grid" style="grid-template-columns: 1fr;">
        <div class="gloss-item"><div class="gloss-term">1. A legislação prevalece sobre o sistema</div><div class="gloss-def">O SCI é uma ferramenta de apoio à atividade correcional. Suas funcionalidades refletem os procedimentos previstos na legislação, que permanece como referência principal para a atuação dos usuários.</div></div>
        <div class="gloss-item"><div class="gloss-term">2. O sistema organiza, mas não realiza a análise</div><div class="gloss-def">A responsabilidade pela análise técnica permanece com os agentes públicos.</div></div>
        <div class="gloss-item"><div class="gloss-term">3. Toda conclusão deve possuir fundamentação</div><div class="gloss-def">Toda conclusão deve estar devidamente fundamentada, com indicação dos elementos que a sustentam. Não devem ser emitidas recomendações sem motivação adequada e registro correspondente.</div></div>
        <div class="gloss-item"><div class="gloss-term">4. Fato com elementos mínimos</div><div class="gloss-def">A descrição do fato deve permitir compreensão clara por terceiros.</div></div>
        <div class="gloss-item"><div class="gloss-term">5. Evidências não substituem análise</div><div class="gloss-def">Documentos anexados precisam de análise técnica correspondente.</div></div>
        <div class="gloss-item"><div class="gloss-term">6. Rastreabilidade obrigatória</div><div class="gloss-def">O sistema registra automaticamente todas as ações realizadas (logs de acesso, edições, envios e assinaturas), garantindo a rastreabilidade. O usuário deve evitar práticas que comprometam esse registro, como edições indevidas ou exclusão de informações sem justificativa.</div></div>
        <div class="gloss-item"><div class="gloss-term">7. Histórico deve refletir a realidade</div><div class="gloss-def">O sistema registra as informações inseridas pelos usuários. Cabe a cada usuário garantir que os registros reflitam fielmente os atos praticados, inserindo dados corretos e completos, e utilizando os campos de justificativa quando houver necessidade de correção ou retificação.</div></div>
        <div class="gloss-item"><div class="gloss-term">8. Perfis definem responsabilidades</div><div class="gloss-def">Cada perfil possui atribuições específicas.</div></div>
        <div class="gloss-item"><div class="gloss-term">9. Assinar significa concordar</div><div class="gloss-def">Assinatura eletrônica = responsabilidade pelo conteúdo.</div></div>
      </div>
    </div>
    
    <!-- ==================== FLUXOGRAMAS ==================== -->
    <div class="section-page" id="page-fluxogramas">
      <div class="sec-title">📊 Fluxogramas do SCI</div>

    <!-- BOTÃO JAD -->
      <div style="text-align: center; margin-bottom: 20px;">
        <button id="btn-jad-fluxo" style="background: var(--accent); color: white; border: none; padding: 12px 30px; border-radius: 40px; font-size: 16px; font-weight: bold; cursor: pointer; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">
          ⚖️ Ver Fluxo do JAD
        </button>
      </div>

      <!-- CONTEÚDO JAD (oculto inicialmente) -->
      <div id="conteudo-jad" style="display: none;">
        <div class="sec-title" style="margin-top: 10px;">Fluxo do JAD (Juízo de Admissibilidade)</div>
        <div style="background: white; border-radius: 16px; padding: 24px;">
          <div style="display: flex; flex-direction: column; align-items: center; gap: 8px;">
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📋 DENÚNCIA</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📝 DEMANDA — Registrada pelo <span style="color: #ffd966;">APOIO</span></div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--accent); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">⚖️ AUTORIDADE — Analisa e encaminha para o JAD</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📊 GESTOR — Distribui o JAD para um ANALISTA</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">🔍 ANALISTA — Cadastra fatos, envolvidos e evidências</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">🔎 REVISOR — Revisa a análise técnica </div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: #fff3e0; color: #7a5000; padding: 8px 20px; border-radius: 30px; text-align: center; font-weight: bold;">🔄 A qualquer momento, os perfis podem DEVOLVER o processo para a etapa anterior com justificativa</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📊 GESTOR — Revisa a Nota Técnica</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">⚖️ AUTORIDADE — Faz a revisão final</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--accent); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">✍️ CICLO DE ASSINATURAS — Analista → Revisor → Gestor → Autoridade</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">🔍 ANALISTA — Finaliza o JAD</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--accent); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">✅ CONCLUÍDO — Nota técnica assinada</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📋 APOIO — Registra no SEI e encaminha</div>
            
          </div>
        </div>
      </div>

      <!-- BOTÃO PIP -->
      <div style="text-align: center; margin: 30px 0 20px;">
        <button id="btn-pip-fluxo" style="background: var(--pip-color); color: white; border: none; padding: 12px 30px; border-radius: 40px; font-size: 16px; font-weight: bold; cursor: pointer; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">
          🔍 Ver Fluxo do PIP
        </button>
      </div>

      <!-- CONTEÚDO PIP (oculto inicialmente) -->
      <div id="conteudo-pip" style="display: none;">
        <div class="sec-title" style="margin-top: 10px;">Fluxo do PIP (Procedimento de Investigação Preliminar)</div>
        <div style="background: white; border-radius: 16px; padding: 24px;">
          <div style="display: flex; flex-direction: column; align-items: center; gap: 8px;">
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📊 GESTOR — Sugere os investigadores</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📋 APOIO — Elabora despacho e registra no SEI</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--accent); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">⚖️ AUTORIDADE — Valida os investigadores e assina a instauração</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">🔍 INVESTIGADOR — Conduz a investigação (diligências, análise)</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">🔎 REVISOR — Revisão técnica do relatório</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">📊 GESTOR — Valida o relatório</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--navy); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">⚖️ AUTORIDADE — Decisão final</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--accent); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">✍️ CICLO DE ASSINATURAS — Investigador → Revisor → Gestor → Autoridade</div>
            <div style="font-size: 20px;">↓</div>
            
            <div style="background: var(--accent); color: white; padding: 10px 20px; border-radius: 40px; font-weight: bold; text-align: center;">✅ PIP CONCLUÍDO — Apoio encaminha via SEI</div>
            
          </div>
        </div>
        <div style="display: flex; justify-content: center; margin-top: 15px;">
          <div style="background: #fff3e0; border-radius: 30px; padding: 8px 20px; text-align: center;">
            <span style="font-size: 13px;">🔄 Todos os perfis podem <strong>DEVOLVER</strong> o processo para a etapa anterior</span>
          </div>
        </div>
      </div>

      <!-- Legenda -->
      <div class="callout callout-info" style="margin-top: 20px; font-size: 12px;">
        <strong>📌 Significados:</strong> JAD = Juízo de Admissibilidade · PIP = Procedimento de Investigação Preliminar
      </div>
    </div>
    
    <!-- ══════════════════════════════
         APOIO À AUTORIDADE
    ══════════════════════════════ -->
    <div class="section-page" id="page-apoio">
      <div class="mod-tabs">
        <button class="mod-tab active-jad" onclick="showTab('apoio','jad')" id="tab-apoio-jad">Módulo JAD</button>
        <button class="mod-tab" onclick="showTab('apoio','pip')" id="tab-apoio-pip">Módulo PIP</button>
      </div>

      <div class="tab-panel active" id="panel-apoio-jad">
        <div class="persona-intro-box">
          <span class="persona-tag">Apoio à Autoridade · JAD</span>
          <p>Responsável por registrar no SCI toda denúncia, ofício ou comunicação que chegue ao órgão imputando irregularidade a agente público ou ente privado. Sem esse registro, a denúncia não existe para o sistema. Ao final do ciclo, realiza o download da nota técnica assinada e autua o processo no SEI.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Registrar Nova Demanda</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Acessar o Painel de Demandas</div>
              <ul>
                <li>Menu lateral → <strong>Demandas</strong></li>
                <li>Clique em <strong>+ Nova Demanda</strong> (canto superior esquerdo)</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Preencher os Dados da Demanda</div>
              <ul>
                <li><strong>Documento/Processo vinculado</strong> (opcional): número do processo SEI já existente que deu origem à demanda (ex.: processo de uma denúncia que já tramita no SEI). Caso a demanda ainda não tenha processo SEI, deixe em branco.</li>
                <li><strong>Tipo de documento</strong> (obrigatório): Denúncia, Ofício, Carta, Circular etc.</li>
                <li><strong>Origem da Demanda</strong> (obrigatório): ex. Ouvidoria Geral do DF, MPDFT</li>
                <li><strong>Documento Origem</strong> (obrigatório): número do documento (ex.: OUV-070846/2026)</li>
                <li><strong>Assunto</strong> (obrigatório): selecione da lista predefinida</li>
                <li><strong>Âmbito funcional</strong> (obrigatório): órgão ou setor onde a irregularidade teria ocorrido</li>
                <li><strong>Descrição</strong> (obrigatório — até 1.000 caracteres)</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="callout callout-info">
          <strong>Padrão recomendado para Descrição:</strong> [Doc. origem] – [Anônimo/Identificado] – [Nome, se houver] – [Órgão/setor] – [Resumo da conduta]
        </div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Informar Demandante e Agente Envolvido</div>
              <ul>
                <li><strong>Demandante:</strong> Anônimo ou Identificado</li>
                <li><strong>Agente Envolvido:</strong> Agente Público, Privado, Ambos ou Nenhum</li>
                <li><strong>Data/período da ocorrência:</strong> preencha se souber (não bloqueante)</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">4</div>
            <div class="step-body">
              <div class="step-title">Adicionar Anexos (Opcional)</div>
              <ul>
                <li>Formatos: txt, pdf, png, jpg, mp3, mp4 · Limite: 10 MB por arquivo</li>
                <li>Sempre anexe o documento original que gerou a demanda</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">5</div>
            <div class="step-body">
              <div class="step-title">Cadastrar e Confirmar</div>
              <ul>
                <li>Revise todos os campos e clique em <strong>"Cadastrar Demanda"</strong></li>
                <li>Status resultante: <span class="badge badge-wait">Aguardando análise</span></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="callout callout-warn">⚠ A demanda só pode ser editada enquanto a Autoridade ainda não encaminhou. Após o encaminhamento, os dados ficam bloqueados. Corrija erros o quanto antes.</div>

        <div class="sec-title">Ações no Painel</div>
        <table class="decision-table">
          <thead><tr><th>Ação</th><th>Significado</th></tr></thead>
          <tbody>
            <tr><td>Ícone de olho</td><td>Visualiza todos os dados da demanda sem editar</td></tr>
            <tr><td>Ícone de lápis</td><td>Edição disponível apenas enquanto status = Aguardando análise</td></tr>
            <tr><td>Filtros</td><td>Localiza demandas por identificador, assunto, documento de origem ou status</td></tr>
          </tbody>
        </table>

        <div class="sec-title">Autuação Final no JAD</div>
        <div class="overview-card">
          <p>Após o ciclo completo de assinaturas, localize os JADs com status <span class="badge badge-done">Concluído</span>, faça o download da nota técnica assinada e autue o processo no SEI conforme a recomendação da Autoridade.</p>
        </div>
            <!-- ══════════════════════════════════════════════════════════
         BLOCO NOVO — REGISTRO DO PROCESSO NO SEI (APOIO)
         Inserir entre "Autuação Final no JAD" e "Duplo Check"
         ══════════════════════════════════════════════════════════ -->

    <div class="sec-title" style="margin-top:20px">Registro do Processo no SEI</div>

    <div class="callout callout-info">
      <strong>📌 Novo fluxo a partir do JAD concluído</strong><br>
      Quando o Analista finaliza o JAD, o processo aparece na lista do Apoio com um <strong>terceiro ícone</strong> (após visualizar a demanda e a nota técnica). Esse ícone permite registrar o número do processo SEI, encerrando definitivamente o ciclo no sistema.
    </div>

    <div class="steps">
      <div class="step-card">
        <div class="step-num">1</div>
        <div class="step-body">
          <div class="step-title">Localizar o JAD Concluído</div>
          <ul>
            <li>No módulo <strong>Admissibilidade</strong>, filtre os processos com status <strong>"Processo Concluído"</strong></li>
            <li>Identifique o ícone de <strong>registro SEI</strong> (terceiro ícone, ao lado do botão "Visualizar Nota Técnica")</li>
          </ul>
        </div>
      </div>

      <div class="step-card">
        <div class="step-num">2</div>
        <div class="step-body">
          <div class="step-title">Registrar o Número SEI</div>
          <ul>
            <li>Clique no ícone de registro</li>
            <li>Uma tela será aberta com o campo <strong>"Número do Processo SEI"</strong></li>
            <li>Preencha com o número do processo autuado no SEI (ex.: 00000-00000000/0000-00)</li>
            <li>Clique em <strong>"Registrar"</strong></li>
          </ul>
        </div>
      </div>

      <div class="step-card">
        <div class="step-num">3</div>
        <div class="step-body">
          <div class="step-title">Status Atualizado</div>
          <ul>
            <li>Após o registro, o status do JAD muda automaticamente para <strong>"Finalizado - Encaminhado via SEI"</strong></li>
            <li>O sistema registra a data e hora do encaminhamento</li>
            <li>O processo sai da lista de pendências do Apoio</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="callout callout-green">
      <strong>✅ Fim do ciclo — sem planilhas!</strong><br>
      Com esse registro, o Apoio não precisa mais manter controles paralelos. O SCI já indica que o processo foi encaminhado ao SEI, garantindo rastreabilidade e transparência para toda a equipe.
    </div>

         <!-- ══════════════════════════════════════════════════════════
         BLOCO 2 — APOIO À AUTORIDADE · JAD (ENCAMINHAMENTO)
         ══════════════════════════════════════════════════════════ -->

    <div class="sec-title" style="margin-top:20px">Duplo Check — Encaminhamento a Órgão Externo</div>

    <!-- NOVO CALLOUT VERMELHO - REGRA FUNDAMENTAL -->
    <div class="callout callout-warn" style="background: #ffebee; border-left-color: #d32f2f; padding: 12px 16px; border-radius: 6px; margin-bottom: 12px;">
      <strong style="font-size: 1.05rem;">🚨 REGRA FUNDAMENTAL — ENCAMINHAMENTO DE PROCESSOS</strong><br>
      Apenas a <strong>CGDF</strong> pode encaminhar processos a outros órgãos pelo SCI.<br>
      Órgãos de destino <strong>recebem</strong> os processos, mas <strong>NÃO os reencaminham</strong> para terceiros.<br>
      Se um órgão entender que o processo não é de sua competência, a via correta é <strong>devolver à CGDF</strong>.
    </div>

    <!-- CALLOUT AZUL EXISTENTE - DUPLO CHECK -->
    <div class="callout callout-info" style="margin-top: 10px;">
      Antes de o processo sair oficialmente da CGDF, o Apoio confere se os documentos
      estão corretos e sem conteúdo sensível exposto. É a última verificação interna.
    </div>

    <div class="steps">
      <div class="step-card">
        <div class="step-num">1</div>
        <div class="step-body">
          <div class="step-title">Localizar o Processo</div>
          <ul>
            <li>No módulo <strong>Admissibilidade</strong>, localize JADs com status <strong>"Aguardando Encaminhamento"</strong></li>
            <li>Clique no ícone de encaminhamento para abrir a tela de revisão</li>
          </ul>
        </div>
      </div>

      <div class="step-card">
        <div class="step-num">2</div>
        <div class="step-body">
          <div class="step-title">Conferir o Conteúdo</div>
          <ul>
            <li>Verifique o <strong>órgão de destino</strong> selecionado pelo Analista</li>
            <li>Faça o download da Nota Técnica e dos anexos para inspeção</li>
            <li>Confirme que nenhum dado sensível está exposto</li>
          </ul>
        </div>
      </div>

      <div class="step-card">
        <div class="step-num">3</div>
        <div class="step-body">
          <div class="step-title">Tomar a Decisão</div>
          <table class="decision-table">
            <thead><tr><th>Botão</th><th>Quando usar</th><th>O que acontece</th></tr></thead>
            <tbody>
              <tr>
                <td><strong>Encaminhar</strong> <span style="color:var(--text-muted,#888);font-size:.85em;">(antes: Aprovar)</span></td>
                <td>Documentos corretos, sem conteúdo sensível exposto</td>
                <td>Processo enviado diretamente à caixa de <strong>Processos Recebidos</strong> da Autoridade Correcional do órgão de destino</td>
              </tr>
              <tr>
                <td><strong>Devolver</strong> <span style="color:var(--text-muted,#888);font-size:.85em;">(antes: Reprovar)</span></td>
                <td>Conteúdo sensível sem tarja, órgão errado ou qualquer inconsistência</td>
                <td>Retorna ao Analista com o motivo registrado para correção</td>
              </tr>
            </tbody>
          </table>
          <div class="callout callout-warn" style="margin-top:.75rem;">
            <strong>⚠</strong> Se identificar conteúdo sensível sem tarja, use <strong>Devolver</strong>. Não encaminhe com dados expostos.
          </div>
        </div>
      </div>
    </div>

      </div><!-- /panel-apoio-jad -->

      <div class="tab-panel" id="panel-apoio-pip">
        <div class="persona-intro-box">
          <span class="persona-tag pip-tag">Apoio à Autoridade · PIP</span>
          <p>O Apoio elabora a minuta do despacho de instauração, registra o processo no SEI e, ao final do ciclo, realiza o download do relatório e executa o encaminhamento determinado pela Autoridade. É o elo entre o sistema e os registros formais do SEI.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Passo a passo</div>
        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Acessar e Localizar o Processo</div>
              <ul>
                <li>Menu lateral → <strong>PIP</strong></li>
                <li>Localize o processo com status <span class="badge badge-wait">Aguardando Despacho</span></li>
                <li>Clique em <strong>"Iniciar Despacho"</strong></li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Preencher o Despacho de Instauração</div>
              <ul>
                <li>Preencha o campo <strong>Atos de competência da autoridade</strong> (obrigatório)</li>
                <li>Clique em <strong>"Verificar e Salvar"</strong></li>
                <li>O processo é encaminhado automaticamente à Autoridade para assinatura</li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Após Assinatura da Autoridade</div>
              <ul>
                <li>Status muda para <span class="badge badge-wait">Aguardando registro no SEI</span></li>
                <li>Clique em <strong>Download Despacho</strong> e autue no SEI</li>
                <li>Informe no SCI: <strong>Número SEI</strong> e <strong>Data de registro</strong></li>
                <li>Clique em <strong>"Salvar e registrar"</strong> — o processo segue automaticamente ao Investigador</li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">4</div>
            <div class="step-body">
              <div class="step-title">Encaminhamento Final</div>
              <ul>
                <li>Após o ciclo de assinaturas, o processo retorna como <span class="badge badge-done">Concluído</span></li>
                <li>Realize o download do relatório e execute o encaminhamento via SEI</li>
              </ul>
            </div>
          </div>
        </div>
      </div><!-- /panel-apoio-pip -->
    </div><!-- /page-apoio -->


    <!-- ══════════════════════════════
         AUTORIDADE CORRECIONAL
    ══════════════════════════════ -->
    <div class="section-page" id="page-autoridade">
      <div class="mod-tabs">
        <button class="mod-tab active-jad" onclick="showTab('autoridade','jad')" id="tab-autoridade-jad">Módulo JAD</button>
        <button class="mod-tab" onclick="showTab('autoridade','pip')" id="tab-autoridade-pip">Módulo PIP</button>
      </div>

      <div class="tab-panel active" id="panel-autoridade-jad">
        <div class="persona-intro-box">
          <span class="persona-tag">Autoridade Correcional · JAD</span>
          <p>A Autoridade recebe a demanda registrada pelo Apoio, analisa e decide para onde encaminhar: JAD, Triagem TCE ou ambos. No módulo JAD, atua na validação final da nota técnica e realiza a assinatura que formaliza o documento.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Módulo Demanda — Tratar Demanda</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Acessar o Painel de Demandas</div>
              <ul><li>O sistema abre na lista de demandas com status <span class="badge badge-wait">Aguardando análise</span></li></ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisar a Demanda</div>
              <ul>
                <li>Clique no ícone de olho para visualizar os detalhes</li>
                <li>Leia descrição, origem, assunto e documentos anexados</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Encaminhar a Demanda</div>
              <ul><li>Clique no ícone de encaminhamento (seta) ao lado da demanda</li></ul>
              <table class="decision-table" style="margin-top:8px">
                <thead><tr><th>Opção</th><th>Quando usar</th></tr></thead>
                <tbody>
                  <tr><td>→ Juízo de Admissibilidade</td><td>Conduta de agente público e/ou ente privado</td></tr>
                  <tr><td>→ Triagem TCE</td><td>Indícios de dano ao erário</td></tr>
                  <tr><td>→ Ambos</td><td>Conduta funcional + recursos públicos</td></tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>

        <div class="sec-title">Revisão Final e Assinatura</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar JADs para Revisão Final</div>
              <ul><li>No módulo Admissibilidade, localize JADs com status <span class="badge badge-blue">Em revisão — Autoridade</span></li></ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisar a Nota Técnica</div>
              <ul>
                <li>Clique em <strong>"Visualizar análise"</strong> para acessar a prévia completa</li>
                <li>Avalie fatos, envolvidos, enquadramentos, recomendações e fundamentação</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Decisão</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr><td>Devolver</td><td>Retorna ao Analista com orientações. Status: <span class="badge badge-blue">Em análise</span></td></tr>
                  <tr><td>Aprovar</td><td>Inicia ciclo de assinaturas: Analista → Revisor → Gestor → Autoridade</td></tr>
                </tbody>
              </table>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">4</div>
            <div class="step-body">
              <div class="step-title">Assinatura Final</div>
              <ul>
                <li>Após Analista → Revisor → Gestor assinarem, o processo retorna à Autoridade</li>
                <li>Com a assinatura final, o JAD é formalizado</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="sign-seq">
          <span class="sign-step">1º Analista</span><span class="sign-arrow">→</span>
          <span class="sign-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>

        <!-- ══════════════════════════════════════════════════════════
             BLOCO 3 — AUTORIDADE CORRECIONAL · ÓRGÃO DE DESTINO
        ═══════════════════════════════════════════════════════════════ -->
        <div class="sec-title" style="margin-top:20px">Processos Recebidos — Encaminhamento da CGDF</div>
        <div class="callout callout-info">
          O órgão de destino <strong>não encaminha</strong> processos por esta via — apenas os recebe.
          A notificação chega diretamente na aba <strong>Processos Recebidos</strong> do menu lateral.
        </div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Acessar "Processos Recebidos"</div>
              <ul>
                <li>Menu lateral → <strong>Processos Recebidos</strong></li>
                <li>Aba <strong>"Recebidos"</strong>: processos aguardando decisão, status <strong>"Enviado"</strong></li>
                <li>Aba <strong>"Devolvidos"</strong>: histórico de processos já devolvidos à CGDF</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Visualizar o Processo e os Documentos</div>
              <ul>
                <li>Clique no ícone de visualização (olho) para acessar a Nota Técnica e os anexos encaminhados</li>
                <li>Os documentos ficam disponíveis para download nesta tela</li>
                <li>Leia integralmente antes de decidir</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar a Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Ação</th><th>Quando usar</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr>
                    <td><strong>Aceitar</strong></td>
                    <td>Processo é de competência do órgão e documentos estão adequados</td>
                    <td>Processo entra no fluxo JAD do órgão normalmente</td>
                  </tr>
                  <tr>
                    <td><strong>Devolver</strong></td>
                    <td>Processo não é de competência do órgão ou há impedimento</td>
                    <td>Obrigatório preencher a <strong>Justificativa</strong>. Processo retorna à CGDF com status <strong>"Aguardando Decisão da Devolução"</strong></td>
                  </tr>
                </tbody>
              </table>
              <div class="callout callout-warn" style="margin-top:.75rem;">
                <strong>⚠ Justificativa obrigatória na devolução</strong><br>
                Preencha com clareza — esse texto orienta a decisão da Autoridade da CGDF sobre avocação ou rejeição da devolução.
              </div>
            </div>
          </div>
        </div>

        <!-- ══════════════════════════════════════════════════════════
             BLOCO 4 — AUTORIDADE CORRECIONAL · CGDF
        ═══════════════════════════════════════════════════════════════ -->
        <div class="sec-title" style="margin-top:20px">Decisão sobre Devolução pelo Órgão de Destino</div>
        <div class="callout callout-info">
          Quando o órgão devolve o processo, a Autoridade da CGDF recebe a notificação
          na aba <strong>"Devolvidos"</strong> em <em>Processos Encaminhados</em>
          e decide entre aceitar a avocação ou rejeitar a devolução.
        </div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar o Processo Devolvido</div>
              <ul>
                <li>Menu lateral → <strong>Processos Encaminhados</strong> → aba <strong>"Devolvidos"</strong></li>
                <li>Status: <strong>"Aguardando Decisão da Devolução"</strong></li>
                <li>Clique no ícone de ação para abrir a tela de decisão</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Ler a Justificativa do Órgão</div>
              <p>A justificativa preenchida pelo órgão de destino fica visível na tela — campo <strong>"Justificativa do Encaminhamento"</strong>. Leia antes de decidir.</p>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar a Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Ação</th><th>Quando usar</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr>
                    <td><strong>Aceitar a Avocação</strong></td>
                    <td>A devolução é procedente — CGDF assume a condução do processo</div></td>
                    <td>Avocação registrada. A continuidade ocorre <strong>via SEI</strong> (fora do SCI, por ora)</td>
                  </tr>
                  <tr>
                    <td><strong>Rejeitar a Devolução</strong></td>
                    <td>A devolução não tem fundamento — o órgão de destino deve receber o processo</div></td>
                    <td>Obrigatório preencher <strong>Justificativa</strong> e confirmar a rejeição</div></td>
                  </tr>
                </tbody>
              </table>
              <div class="callout callout-info" style="margin-top:1rem;">
                <strong>📌 Momento atual do sistema</strong><br>
                O acompanhamento pós-avocação dentro do SCI ainda está em desenvolvimento.
                Processos avocados prosseguem pela tramitação convencional no SEI.
              </div>
            </div>
          </div>
        </div>

      </div><!-- /panel-autoridade-jad -->

      <div class="tab-panel" id="panel-autoridade-pip">
        <div class="persona-intro-box">
          <span class="persona-tag pip-tag">Autoridade Correcional · PIP</span>
          <p>A Autoridade atua em <strong>três momentos</strong>: (1) valida os investigadores indicados pelo Gestor e assina a instauração; (2) analisa e aprova ou devolve a nota técnica; (3) realiza a assinatura final encerrando o procedimento. É a única que pode reabrir o processo após o início das assinaturas.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Validação e Assinatura da Instauração</div>
              <ul>
                <li>Visualize o JAD de origem, os investigadores indicados pelo Gestor e os documentos vinculados</li>
                <li>Confirme e realize a <strong>Assinatura da Instauração</strong></li>
                <li>O PIP é formalmente instaurado e encaminhado ao Apoio para autuação no SEI</li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisão e Decisão sobre a Nota Técnica</div>
              <ul><li>Clique em <strong>"Prévia da Nota"</strong> para visualizar o relatório</li><li>Avalie enquadramentos, fundamentação, providências e recomendações</li></ul>
              <table class="decision-table" style="margin-top:8px">
                <thead><tr><th>Decisão</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr><td>Devolver</div></td><td>Retorna ao Investigador com observações detalhadas</div></td></tr>
                  <tr><td>Aprovar</div></td><td>Inicia automaticamente o ciclo de assinaturas</div></td></tr>
                </tbody>
              </table>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Assinatura Final</div>
              <ul>
                <li>Após Investigador → Revisor → Gestor assinarem, o processo retorna à Autoridade</li>
                <li>Durante o ciclo, o relatório está <strong>bloqueado para edição</strong></li>
                <li>Após a assinatura final, o processo retorna ao Apoio para encaminhamento</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="callout callout-warn">
          ⚠ <strong>Reabertura de Mérito (uso excepcional):</strong> apenas a Autoridade pode cancelar o fluxo, derrubar assinaturas e reabrir o processo. Exige motivação obrigatória, gera histórico e invalida assinaturas anteriores. Nenhum outro perfil tem essa capacidade.
        </div>
        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="sign-seq">
          <span class="sign-step pip-step">1º Investigador</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>
      </div><!-- /panel-autoridade-pip -->
    </div><!-- /page-autoridade -->


    <!-- ══════════════════════════════
         GESTOR CORRECIONAL
    ══════════════════════════════ -->
    <div class="section-page" id="page-gestor">
      <div class="mod-tabs">
        <button class="mod-tab active-jad" onclick="showTab('gestor','jad')" id="tab-gestor-jad">Módulo JAD</button>
        <button class="mod-tab" onclick="showTab('gestor','pip')" id="tab-gestor-pip">Módulo PIP</button>
      </div>

      <div class="tab-panel active" id="panel-gestor-jad">
        <div class="persona-intro-box">
          <span class="persona-tag">Gestor Correcional · JAD</span>
          <p>O Gestor JAD atua em dois momentos distintos: distribui o JAD a um analista e, depois, revisa a análise técnica antes de encaminhar à Autoridade. Também participa do ciclo de assinaturas.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Momento 1 — Distribuir o JAD</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar JADs Aguardando Distribuição</div>
              <ul><li>No módulo Admissibilidade, localize JADs com status <span class="badge badge-wait">Aguardando distribuição</span></li></ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Distribuir para um Analista</div>
              <ul>
                <li>Clique no ícone de distribuição ao lado do JAD</li>
                <li>O sistema exibe a lista de analistas com o número de processos de cada um</li>
                <li>Selecione considerando a carga de trabalho e confirme</li>
                <li>Status resultante: <span class="badge badge-wait">Aguardando cadastro</span> na lista do analista</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="sec-title">Momento 2 — Revisar a Análise</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar JADs para Revisão</div>
              <ul><li>Localize JADs com status <span class="badge badge-blue">Em análise</span> prontos para revisão do Gestor</li></ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisar o Conteúdo</div>
              <ul>
                <li>Acesse <strong>"Visualizar análise"</strong> para ver a prévia da nota técnica</li>
                <li>Verifique fatos, envolvidos, evidências, enquadramentos e fundamentação</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Decisão</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr><td>Devolver</div></td><td>Retorna ao Analista com observações. Status: <span class="badge badge-blue">Em análise</span></div></td></tr>
                  <tr><td>Enviar à Autoridade</div></td><td>Pode indicar acordo/desacordo e adicionar considerações</div></td></tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="sign-seq">
          <span class="sign-step">1º Analista</span><span class="sign-arrow">→</span>
          <span class="sign-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>
      </div><!-- /panel-gestor-jad -->

      <div class="tab-panel" id="panel-gestor-pip">
        <div class="persona-intro-box">
          <span class="persona-tag pip-tag">Gestor Correcional · PIP</span>
          <p>O Gestor PIP atua em dois momentos: (1) sugere os Servidores Designados no momento da instauração; (2) recebe os processos para avaliação gerencial após revisão do Revisor, antes de encaminhar à Autoridade. Também participa do ciclo de assinaturas.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Momento 1 — Indicar Investigadores</div>
        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Selecionar os Servidores Designados</div>
              <ul>
                <li>No módulo PIP, localize o processo a ser instaurado</li>
                <li>Indique o(s) <strong>Servidor(es) Designado(s)</strong> (Investigadores) para condução do procedimento</li>
                <li>Após a indicação, o processo segue à Autoridade para validação e assinatura da instauração</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="sec-title">Momento 2 — Revisão Gerencial</div>
        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar PIPs para Revisão</div>
              <ul><li>Localize os processos com status <span class="badge badge-blue">Em revisão — Gestor</span></li></ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisar o Conteúdo</div>
              <ul>
                <li>Acesse <strong>"Prévia da Nota"</strong></li>
                <li>Verifique coerência técnica, consistência jurídica e adequação das providências recomendadas</li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Decisão</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr><td>Devolver</div></td><td>Retorna ao Investigador com observações detalhadas</div></td></tr>
                  <tr><td>Enviar à Autoridade</div></td><td>Pode indicar acordo/desacordo e adicionar considerações finais</div></td></tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="sign-seq">
          <span class="sign-step pip-step">1º Investigador</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>
      </div><!-- /panel-gestor-pip -->
    </div><!-- /page-gestor -->


    <!-- ══════════════════════════════
         ANALISTA / INVESTIGADOR
    ══════════════════════════════ -->
    <div class="section-page" id="page-analista">
      <div class="mod-tabs">
        <button class="mod-tab active-jad" onclick="showTab('analista','jad')" id="tab-analista-jad">Módulo JAD</button>
        <button class="mod-tab" onclick="showTab('analista','pip')" id="tab-analista-pip">Módulo PIP</button>
      </div>

      <div class="tab-panel active" id="panel-analista-jad">
        <div class="persona-intro-box">
          <span class="persona-tag">Analista de Admissibilidade · JAD</span>
          <p>O Analista é o responsável pela construção técnica do JAD: cadastrar os dados do caso, identificar envolvidos e condutas, registrar evidências, elaborar a análise de responsabilização e redigir a fundamentação técnico-jurídica.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Fase 1 — Cadastro</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Abrir o JAD e Visualizar a Demanda Originária</div>
              <ul>
                <li>Clique no ícone de cadastro ao lado do JAD com status <span class="badge badge-wait">Aguardando cadastro</span></li>
                <li>Clique em <strong>"Visualizar Demanda Originária"</strong> — leia antes de começar o cadastro</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Cadastrar Fatos</div>
              <ul>
                <li>Clique em <strong>+ Fato</strong></li>
                <li><strong>Assunto</strong> (obrigatório): selecione da lista predefinida</li>
                <li><strong>Descrição</strong> (obrigatório — até 1.000 caracteres)</li>
                <li><strong>Data inicial/final</strong> e <strong>Local da ocorrência</strong></li>
                <li>Clique em <strong>Salvar</strong>. Pode cadastrar múltiplos fatos</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Cadastrar Envolvidos</div>
              <ul>
                <li>Clique no ícone de pessoas no card do fato</li>
                <li>Tipos: <strong>Servidor público, Pessoa física, Pessoa jurídica</strong> ou <strong>Não identificado</strong></li>
                <li>Para Servidor: pesquise por Nome ou CPF — o sistema busca na base do GDF (nome, CPF, matrícula, órgão, lotação)</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">4</div>
            <div class="step-body">
              <div class="step-title">Cadastrar Evidências</div>
              <ul>
                <li>Clique em <strong>+ Evidência</strong> e vincule ao(s) envolvido(s)</li>
                <li><strong>Título</strong> (obrigatório) e <strong>Descrição</strong> (até 500 caracteres)</li>
                <li>Anexo opcional: txt, pdf, png, jpg, mp3, mp4 — até 10 MB</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">5</div>
            <div class="step-body">
              <div class="step-title">Concluir Cadastro</div>
              <ul>
                <li>Clique em <strong>"Concluir cadastro"</strong></li>
                <li>Status muda para <span class="badge badge-blue">Em análise</span></li>
              </ul>
            </div>
          </div>
        </div>

        <div class="sec-title">Fase 2 — Análise Técnica</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">6</div>
            <div class="step-body">
              <div class="step-title">Preencher a Matriz de Responsabilização</div>
              <ul>
                <li>Clique em <strong>"Análise de admissibilidade"</strong> no topo da tela</li>
                <li>Para cada envolvido: <strong>Enquadramento legal</strong> (múltiplos permitidos), <strong>Recomendação</strong> e <strong>Elementos faltantes</strong></li>
                <li>Clique em <strong>Salvar</strong> para cada envolvido</li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">7</div>
            <div class="step-body">
              <div class="step-title">Elaborar a Fundamentação</div>
              <ul>
                <li>Clique em <strong>"Fundamentação"</strong> no topo da tela</li>
                <li>Redija a análise técnica e jurídica (até 8.000 caracteres)</li>
                <li>Clique em <strong>Salvar</strong></li>
              </ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">8</div>
            <div class="step-body">
              <div class="step-title">Concluir e Enviar para Revisão</div>
              <ul>
                <li>Clique em <strong>"Concluir e enviar para revisão"</strong></li>
                <li>O processo segue automaticamente ao Revisor JAD</li>
                <li>Possível <strong>"Reabrir cadastro"</strong> a qualquer momento antes de enviar</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="callout callout-green">✅ O preenchimento detalhado e correto é essencial. Fatos, envolvidos, condutas e evidências formarão a nota técnica final assinada por todos.</div>

        <div class="sec-title">Ciclo de Assinaturas</div>
        <p style="font-size:12px; margin-bottom:8px">Após aprovação da Autoridade, o processo retorna ao Analista para iniciar o ciclo de assinaturas. O Analista é o <strong>primeiro a assinar</strong>.</p>
        <div class="sign-seq">
          <span class="sign-step">1º Analista</span><span class="sign-arrow">→</span>
          <span class="sign-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>

        <div class="sec-title" style="margin-top:20px">Encerramento — Após Todas as Assinaturas</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">9</div>
            <div class="step-body">
              <div class="step-title">Finalizar ou Invalidar a Nota Técnica</div>
              <ul>
                <li>Após a assinatura final da Autoridade, o processo retorna ao Analista para encerramento</li>
                <li>Revise a nota técnica antes de tomar a decisão final</li>
              </ul>
              <table class="decision-table" style="margin-top:8px">
                <thead><tr><th>Ação</th><th>Quando usar</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr>
                    <td><strong>Finalizar</strong></td>
                    <td>Nota correta e sem pendências</div></td>
                    <td>JAD encerrado. Processo cai na caixa do Apoio para autuação no SEI</div></td>
                  </tr>
                  <tr>
                    <td><strong>Invalidar</strong></div></td>
                    <td>Constatado erro material na nota após as assinaturas</div></td>
                    <td>Nota invalidada com registro do motivo. Gera histórico e invalida as assinaturas</div></td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
        <div class="callout callout-warn">⚠ A invalidação deve ser usada apenas em casos de <strong>erro material comprovado</strong>. O uso indevido compromete a integridade do processo e invalida todas as assinaturas já realizadas.</div>

        <!-- ══════════════════════════════════════════════════════════
             BLOCO 1 — ANALISTA DE ADMISSIBILIDADE · JAD (ENCAMINHAMENTO)
        ═══════════════════════════════════════════════════════════════ -->
        <div class="callout callout-warn" style="margin-top:16px">
          <strong>⚠ Prerrogativa exclusiva da CGDF</strong><br>
          Apenas a <strong>CGDF</strong> pode encaminhar processos a outros órgãos pelo SCI.
          Os órgãos de destino recebem os processos, mas não os originam por essa via.
        </div>

        <div class="sec-title" style="margin-top:20px">Encaminhamento a Órgão Externo</div>

        <p>
          Quando a recomendação do JAD for <em>"Remeter ao órgão/entidade de origem para conhecimento e providências"</em>,
          após o ciclo completo de assinaturas o Analista terá, na etapa de encerramento,
          uma <strong>terceira opção</strong> disponível além de <strong>Finalizar</strong> e <strong>Invalidar</strong>.
        </p>

        <table class="decision-table">
          <thead><tr><th>Ação</th><th>Quando usar</th><th>O que acontece</th></tr></thead>
          <tbody>
            <tr>
              <td><strong>Finalizar</strong></div></td>
              <td>Nota correta, processo encerrado na CGDF</div></td>
              <td>JAD encerrado. Cai na caixa do Apoio para autuação no SEI</div></td>
            </tr>
            <tr>
              <td><strong>Invalidar</strong></div></td>
              <td>Erro material na nota após as assinaturas</div></td>
              <td>Nota invalidada com registro do motivo</div></td>
            </tr>
            <tr>
              <td><strong>Encaminhar a Órgão Externo</strong></div></td>
              <td>Recomendação é de remessa ao órgão de origem — processo não é de competência da CGDF</div></td>
              <td>Abre a tela de encaminhamento descrita abaixo</div></td>
            </tr>
          </tbody>
        </table>

        <div class="sec-subtitle" style="margin-top:16px">Passo a passo — Encaminhar a Órgão Externo</div>
        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Selecionar o Órgão de Destino</div>
              <ul>
                <li>Campo <strong>"Órgão de Destino"</strong> (obrigatório): selecione ou busque o órgão que receberá o processo</li>
                <li>Apenas órgãos cadastrados no SCI aparecem na lista</li>
              </ul>
            </div>
          </div>

          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Definir o que será enviado</div>
              <table class="decision-table" style="margin-top:8px">
                <thead><tr><th>Documento</th><th>Quando enviar</th><th>Como proceder</th></tr></thead>
                <tbody>
                  <tr>
                    <td><strong>Nota Técnica</strong></div></td>
                    <td>Não houver dados sensíveis a tarjar</div></td>
                    <td>Marque <strong>"Anexar Nota Técnica"</strong> — o sistema inclui o PDF gerado automaticamente</div></td>
                  </tr>
                  <tr>
                    <td><strong>Nota Técnica tarjada</strong></div></td>
                    <td>Houver conteúdo sensível (dados de terceiros, informações protegidas)</div></td>
                    <td>Faça o download da nota, tarje manualmente os trechos, salve e anexe via <strong>"Adicionar novo anexo"</strong></div></td>
                  </tr>
                  <tr>
                    <td><strong>Anexos da demanda</strong></div></td>
                    <td>Os documentos originais puderem ser vistos pelo órgão de destino</div></td>
                    <td>Selecione na lista <strong>"Anexos da demanda"</strong>. Se algum for sensível, não o selecione — baixe, tarje e reenvie manualmente</div></td>
                  </tr>
                </tbody>
              </table>
              <div class="callout callout-warn" style="margin-top:12px">
                <strong>⚠ Conteúdo sensível</strong><br>
                Antes de encaminhar, verifique se a Nota Técnica ou os anexos contêm dados pessoais
                ou informações protegidas. Se sim: baixe, tarje e reenvie o documento modificado.
                Nunca encaminhe dados sensíveis sem tarja ao órgão externo.
              </div>
            </div>
          </div>

          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Clicar em "Encaminhar"</div>
              <ul>
                <li>O sistema pergunta: <em>"O conteúdo sensível da Nota Técnica está tarjado?"</em></li>
                <li>Responda <strong>Sim</strong> se já tarjou (ou se não há conteúdo sensível) → confirmação final: <em>"Tem certeza que deseja encaminhar o processo?"</em> → clique em <strong>Sim</strong></li>
                <li>Responda <strong>Não</strong> para cancelar e corrigir antes de prosseguir</li>
              </ul>
              <p>O processo sai da caixa do Analista e segue para o <strong>Apoio à Autoridade (CGDF)</strong> para duplo check. Status: <strong>"Aguardando Encaminhamento"</strong> <span style="color:var(--muted); font-size:.9em;">(anteriormente "Aguardando Aprovação do Apoio")</span>.</p>
            </div>
          </div>
        </div>

      </div><!-- /panel-analista-jad -->

      <div class="tab-panel" id="panel-analista-pip">
        <div class="persona-intro-box">
          <span class="persona-tag pip-tag">Servidor Designado · PIP</span>
          <p>O Servidor Designado é o responsável pela construção técnica do PIP: editar o fato herdado do JAD, registrar diligências, vincular evidências, analisar cada envolvido individualmente, redigir a fundamentação conclusiva e enviar para o ciclo de revisão.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="sec-title">Fase 1 — Cadastro</div>
        <div class="callout callout-warn">
          ⚠ <strong>Ordem obrigatória:</strong> não clique em "Concluir Cadastro" antes de registrar as diligências. A sequência correta é: Salvar cadastro → Registrar diligências → Concluir cadastro. Inverter essa ordem causa perda de acesso à tela de diligências.
        </div>
        <div class="steps" style="margin-top:10px">
          <div class="step-card pip">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Acessar o PIP</div>
              <ul>
                <li>Menu lateral → <strong>PIP</strong></li>
                <li>Localize o processo com status <span class="badge badge-blue">Em Cadastro</span></li>
                <li>Coluna AÇÕES: <strong>Editar PIP</strong> e <strong>Visualizar Diligências</strong></li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Editar Fato</div>
              <ul>
                <li>O sistema abre com informações herdadas do JAD (matriz de fatos, nota técnica, despacho)</li>
                <li>Confira os dados importados e complemente o necessário</li>
                <li>Mantenha, exclua ou inclua envolvidos e evidências</li>
                <li>Clique em <strong>Salvar</strong></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="callout callout-info">As alterações realizadas no PIP <strong>não alteram o JAD de origem</strong>. Os dados importados são cópia.</div>
        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Registrar Diligências</div>
              <ul>
                <li>Clique em <strong>Visualizar Diligências</strong> → <strong>Nova Diligência</strong></li>
                <li>Preencha: <strong>Tipo, Data, Descrição, Participantes, Envolvido relacionado, Resultado</strong></li>
                <li>Clique em <strong>Salvar</strong> — repita para todas as diligências</li>
                <li>Clique em <strong>Vincular</strong> se quiser que a diligência componha formalmente o conjunto probatório</li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">4</div>
            <div class="step-body">
              <div class="step-title">Concluir Cadastro</div>
              <ul>
                <li>Após finalizar todas as diligências, retorne ao cadastro</li>
                <li>Clique em <strong>Concluir Cadastro</strong></li>
                <li>O sistema libera a prévia do relatório e habilita as opções de análise</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="sec-title">Fase 2 — Análise Técnica</div>
        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">5</div>
            <div class="step-body">
              <div class="step-title">Análise por Envolvido</div>
              <ul>
                <li>Selecione cada envolvido individualmente</li>
                <li>Preencha: <strong>Enquadramentos legais, Tipificações, Recomendações</strong> e Elementos faltantes</li>
                <li>Clique em <strong>Salvar</strong> para cada envolvido</li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">6</div>
            <div class="step-body">
              <div class="step-title">Fundamentação e Providências</div>
              <ul>
                <li>Campo <strong>Fundamentação</strong>: redija a análise conclusiva consolidando o entendimento técnico</li>
                <li>Campo <strong>Providências Adicionais</strong>: ex. envio ao MP, remessa ao órgão de origem</li>
                <li>Clique em <strong>Salvar</strong></li>
              </ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">7</div>
            <div class="step-body">
              <div class="step-title">Concluir e Enviar para Revisão</div>
              <ul>
                <li>Clique em <strong>"Concluir e Enviar para Revisão"</strong></li>
                <li>O processo segue automaticamente: <strong>Revisor → Gestor → Autoridade</strong></li>
              </ul>
            </div>
          </div>
        </div>

        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="callout callout-info">
          Com status <span class="badge badge-wait">Aguardando assinaturas</span>, verifique antes de assinar: diligências registradas, análise por envolvido coerente com a fundamentação, providências justificadas. A assinatura representa responsabilidade técnica pelo conteúdo.
        </div>
        <div class="sign-seq">
          <span class="sign-step pip-step">1º Investigador</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>
        <div class="callout callout-warn" style="margin-top:8px">⚠ Durante o ciclo de assinaturas, o relatório está bloqueado para edição. Não é possível incluir diligências, alterar enquadramentos nem devolver o processo.</div>
      </div><!-- /panel-analista-pip -->
    </div><!-- /page-analista -->


    <!-- ══════════════════════════════
         REVISOR
    ══════════════════════════════ -->
    <div class="section-page" id="page-revisor">
      <div class="mod-tabs">
        <button class="mod-tab active-jad" onclick="showTab('revisor','jad')" id="tab-revisor-jad">Módulo JAD</button>
        <button class="mod-tab" onclick="showTab('revisor','pip')" id="tab-revisor-pip">Módulo PIP</button>
      </div>

      <div class="tab-panel active" id="panel-revisor-jad">
        <div class="persona-intro-box">
          <span class="persona-tag">Revisor JAD</span>
          <p>O Revisor atua após o Analista concluir a análise. Verifica coerência da fundamentação, adequação dos enquadramentos e completude das informações antes de enviar ao Gestor. Também participa do ciclo de assinaturas.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="steps">
          <div class="step-card">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar JADs para Revisão</div>
              <ul><li>No módulo Admissibilidade, localize JADs com status <span class="badge badge-blue">Em revisão — Revisor</span></li></ul>
            </div>
          </div>
          <div class="step-card">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisar a Análise Técnica</div>
              <ul>
                <li>Clique no ícone de revisar e acesse <strong>"Visualizar análise"</strong></li>
                <li>Leia a Matriz de Responsabilização e a Fundamentação do Analista</li>
              </ul>
            </div>
          </div>
        </div>

        <p style="font-size:12px; font-weight:700; color:var(--navy); margin:10px 0 5px">Checklist de Revisão</p>
        <ul class="checklist">
          <li>Os fatos estão descritos com clareza e precisão?</li>
          <li>Os enquadramentos legais são pertinentes?</li>
          <li>A recomendação é adequada ao caso?</li>
          <li>A fundamentação está coerente e juridicamente sustentada?</li>
          <li>Há elementos faltantes que comprometam a análise?</li>
        </ul>

        <div class="steps">
          <div class="step-card">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Decisão</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr>
                    <td>Retornar para ajustes</div></td>
                    <td>Devolve ao Analista com observações. Status: <span class="badge badge-blue">Em análise</span></div></td>
                  </tr>
                  <tr>
                    <td>Enviar ao Gestor</div></td>
                    <td>Pode indicar acordo/desacordo e adicionar considerações</div></td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="sign-seq">
          <span class="sign-step">1º Analista</span><span class="sign-arrow">→</span>
          <span class="sign-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>
      </div><!-- /panel-revisor-jad -->

      <div class="tab-panel" id="panel-revisor-pip">
        <div class="persona-intro-box">
          <span class="persona-tag pip-tag">Revisor Correcional · PIP</span>
          <p>O Revisor atua após o Investigador concluir a análise. Verifica coerência da fundamentação, adequação dos enquadramentos, completude das evidências e diligências antes de enviar ao Gestor. Também participa do ciclo de assinaturas.</p>
        </div>
        <div class="access-box">🔗 sci.cg.df.gov.br &nbsp;·&nbsp; Login e Senha PARTICIPA</div>

        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">1</div>
            <div class="step-body">
              <div class="step-title">Localizar PIPs para Revisão</div>
              <ul><li>No módulo PIP, localize os processos com status <span class="badge badge-blue">Em revisão — Revisor</span></li></ul>
            </div>
          </div>
          <div class="step-card pip">
            <div class="step-num">2</div>
            <div class="step-body">
              <div class="step-title">Revisar a Análise Técnica</div>
              <ul>
                <li>Clique em <strong>"Prévia da Nota"</strong></li>
                <li>Verifique: fatos, diligências, evidências, análise por envolvido, enquadramentos e fundamentação</li>
              </ul>
            </div>
          </div>
        </div>

        <p style="font-size:12px; font-weight:700; color:var(--navy); margin:10px 0 5px">Checklist de Revisão</p>
        <ul class="checklist">
          <li>Os fatos estão descritos com clareza e precisão?</li>
          <li>As diligências são suficientes e corretamente registradas?</li>
          <li>Os enquadramentos legais são pertinentes ao caso?</li>
          <li>A fundamentação está coerente e juridicamente sustentada?</li>
          <li>As recomendações são adequadas? Há elementos faltantes?</li>
        </ul>

        <div class="steps">
          <div class="step-card pip">
            <div class="step-num">3</div>
            <div class="step-body">
              <div class="step-title">Tomar Decisão</div>
              <table class="decision-table">
                <thead><tr><th>Decisão</th><th>O que acontece</th></tr></thead>
                <tbody>
                  <tr>
                    <td>Devolver</div></td>
                    <td>Retorna ao Investigador com observações. Status: <span class="badge badge-blue">Em análise</span></div></td>
                  </tr>
                  <tr>
                    <td>Enviar ao Gestor</div></td>
                    <td>Pode indicar acordo/desacordo e adicionar considerações</div></td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
        <div class="sec-title">Ciclo de Assinaturas</div>
        <div class="sign-seq">
          <span class="sign-step pip-step">1º Investigador</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">2º Revisor</span><span class="sign-arrow">→</span>
          <span class="sign-step pip-step">3º Gestor</span><span class="sign-arrow">→</span>
          <span class="sign-step last">4º Autoridade</span>
        </div>
      </div><!-- /panel-revisor-pip -->
    </div><!-- /page-revisor -->

  </div><!-- /content -->
</div><!-- /main -->

<script>
  const titles = {
    geral:      ['Visão Geral',            '· Fluxos, glossário e perfis'],
    apoio:      ['Apoio à Autoridade',     '· JAD + PIP'],
    autoridade: ['Autoridade Correcional', '· JAD + PIP'],
    gestor:     ['Gestor Correcional',     '· JAD + PIP'],
    analista:   ['Analista / Investigador','· JAD + PIP'],
    revisor:    ['Revisor',                '· JAD + PIP'],
    regras:     ['Regras de Ouro',         '· Princípios fundamentais'],
    fluxogramas: ['Fluxogramas',           '· JAD e PIP'],
  };

  function showSection(id) {
    document.querySelectorAll('.section-page').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
    document.getElementById('page-' + id).classList.add('active');
    document.getElementById('nav-' + id).classList.add('active');
    document.getElementById('topbar-title').textContent = titles[id][0];
    document.getElementById('topbar-desc').textContent  = titles[id][1];
    window.scrollTo(0, 0);
  }

  function showTab(persona, mod) {
    ['jad','pip'].forEach(m => {
      document.getElementById('tab-' + persona + '-' + m).className = 'mod-tab';
      document.getElementById('panel-' + persona + '-' + m).classList.remove('active');
    });
    document.getElementById('tab-' + persona + '-' + mod).className = 'mod-tab active-' + mod;
    document.getElementById('panel-' + persona + '-' + mod).classList.add('active');
  }
   // ==================== CÓDIGO DOS FLUXOGRAMAS ====================
  document.getElementById('btn-jad-fluxo')?.addEventListener('click', function() {
    var conteudo = document.getElementById('conteudo-jad');
    if (conteudo.style.display === 'none') {
      conteudo.style.display = 'block';
    } else {
      conteudo.style.display = 'none';
    }
  });

  document.getElementById('btn-pip-fluxo')?.addEventListener('click', function() {
    var conteudo = document.getElementById('conteudo-pip');
    if (conteudo.style.display === 'none') {
      conteudo.style.display = 'block';
    } else {
      conteudo.style.display = 'none';
    }
  });

</script>
</body>
</html>
