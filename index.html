<!DOCTYPE html>
<html lang="pt-BR" data-theme="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Casa116-3D — Calculadora de Precificação de Impressão 3D</title>
  
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/basecoat-css@1.0.2/dist/basecoat.cdn.min.css">
  <style>
/* Skip artifact shell — fixed styles served beside every artifact.
   Complements basecoat; artifacts override --accent for their own identity. */
:root {
  color-scheme: light dark;
  --accent: #2563eb;
  --accent-contrast: #ffffff;
  --accent-text: color-mix(in srgb, var(--accent) 72%, #000);
  --bg: #f8f9fb;
  --surface: #ffffff;
  --text: #14171f;
  --text-muted: #5b6472;
  --border: rgba(20, 23, 31, 0.10);
  --radius: 10px;
  --shadow: 0 1px 3px rgba(20, 23, 31, 0.08);
  --space: 16px;
}
/* Theme resolution. Without data-theme the viewer's system preference decides,
   as it always did. With it, the artifact's own choice wins in BOTH directions:
   a page that hardcodes one palette must not be handed the opposite set of
   tokens by the machine it happens to be opened on. The dark values appear
   twice because a media query cannot be folded into a selector list.
   The attribute sits inside :where() so these blocks keep the specificity of a
   bare :root — the page's own <style> is linked after this file and must go on
   overriding any token it wants, exactly as it could before. */
@media (prefers-color-scheme: dark) {
  :root:where(:not([data-theme="light"])) {
    --accent-text: color-mix(in srgb, var(--accent) 78%, #fff);
    --bg: #101318;
    --surface: #181c23;
    --text: #eef1f6;
    --text-muted: #9aa4b2;
    --border: rgba(238, 241, 246, 0.12);
    --shadow: 0 1px 3px rgba(0, 0, 0, 0.4);
  }
}
:root:where([data-theme="dark"]) {
  color-scheme: dark;
  --accent-text: color-mix(in srgb, var(--accent) 78%, #fff);
  --bg: #101318;
  --surface: #181c23;
  --text: #eef1f6;
  --text-muted: #9aa4b2;
  --border: rgba(238, 241, 246, 0.12);
  --shadow: 0 1px 3px rgba(0, 0, 0, 0.4);
}
:root:where([data-theme="light"]) { color-scheme: light; }
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; }
body {
  background: var(--bg);
  color: var(--text);
  font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
  line-height: 1.55;
  -webkit-font-smoothing: antialiased;
}
img { max-width: 100%; display: block; }

.shell-container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
.shell-section { padding: calc(var(--space) * 2) 0; }
.shell-grid { display: grid; gap: var(--space); grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); }
.shell-toolbar { display: flex; flex-wrap: wrap; gap: 10px; align-items: center; margin-bottom: var(--space); }
.shell-footer { padding: 24px 0 40px; color: var(--text-muted); font-size: 13px; }

.shell-hero { padding: calc(var(--space) * 3) 0 calc(var(--space) * 2); }
.shell-hero h1 { font-size: clamp(26px, 4vw, 40px); line-height: 1.15; margin: 0 0 10px; text-wrap: balance; }
.shell-hero p { color: var(--text-muted); max-width: 60ch; margin: 0; }

.panel {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: var(--space);
}

.kpi { display: flex; flex-direction: column; gap: 4px; }
.kpi .kpi-value { font-size: 28px; font-weight: 650; line-height: 1.1; }
.kpi .kpi-label { font-size: 13px; color: var(--text-muted); }
.kpi .kpi-delta { font-size: 12.5px; font-weight: 600; }
.kpi .kpi-delta.up { color: #0a8f3c; }
.kpi .kpi-delta.down { color: #cf3131; }

table.shell-table { border-collapse: collapse; width: 100%; font-size: 14px; }
table.shell-table th {
  text-align: left; font-size: 11.5px; letter-spacing: 0.05em; text-transform: uppercase;
  color: var(--text-muted); font-weight: 600;
}
table.shell-table th, table.shell-table td { padding: 9px 12px 9px 0; border-bottom: 1px solid var(--border); }
table.shell-table td.num, table.shell-table th.num { text-align: right; font-variant-numeric: tabular-nums; }
table.shell-table tbody tr:hover { background: color-mix(in srgb, var(--accent) 6%, transparent); }

.chart-box { width: 100%; min-height: 220px; }
.chart-box svg { width: 100%; height: auto; display: block; }

.muted { color: var(--text-muted); }
.accent { color: var(--accent-text); }
.shell-badge {
  display: inline-flex; align-items: center; gap: 6px;
  font-size: 12px; font-weight: 600; padding: 3px 10px; border-radius: 999px;
  background: color-mix(in srgb, var(--accent) 12%, transparent); color: var(--accent-text);
}

@media (prefers-reduced-motion: no-preference) {
  .shell-fade { animation: shell-fade 400ms ease both; }
  @keyframes shell-fade { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: none; } }
}

</style>
  

  <style>
    :root {
      --accent: #00bcd4;
      --accent-text: #22d3ee;
      --accent-contrast: #090d16;
      --card-bg: rgba(22, 27, 34, 0.75);
      --card-border: rgba(255, 255, 255, 0.08);
      --highlight-badge: rgba(0, 188, 212, 0.12);
    }

    [data-theme="light"] {
      --card-bg: rgba(255, 255, 255, 0.85);
      --card-border: rgba(0, 0, 0, 0.08);
      --accent: #0284c7;
      --accent-text: #0369a1;
      --accent-contrast: #ffffff;
      --highlight-badge: rgba(2, 132, 199, 0.1);
    }

    body {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    /* Top Bar */
    .top-nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 0;
      border-bottom: 1px solid var(--border);
      margin-bottom: 2rem;
    }

    .brand-mark {
      display: flex;
      align-items: center;
      gap: 0.65rem;
      font-weight: 700;
      font-size: 1.2rem;
      letter-spacing: -0.02em;
    }

    .brand-logo-icon {
      width: 34px;
      height: 34px;
      background: linear-gradient(135deg, var(--accent), #6366f1);
      border-radius: 8px;
      display: grid;
      place-items: center;
      color: #fff;
      font-weight: 800;
      font-size: 1.1rem;
      box-shadow: 0 4px 12px rgba(0, 188, 212, 0.25);
    }

    .nav-actions {
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    /* Main Grid */
    .calc-layout {
      display: grid;
      grid-template-columns: 1fr;
      gap: 2rem;
      align-items: start;
    }

    @media (min-width: 1024px) {
      .calc-layout {
        grid-template-columns: 1.25fr 0.95fr;
      }
    }

    /* Section Cards */
    .calc-card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.4rem;
      margin-bottom: 1.25rem;
      transition: transform 0.15s ease, border-color 0.2s ease, box-shadow 0.2s ease;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
    }

    .calc-card:hover {
      border-color: rgba(0, 188, 212, 0.35);
    }

    .calc-card-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 1.15rem;
      padding-bottom: 0.65rem;
      border-bottom: 1px solid var(--border);
    }

    .calc-card-title {
      font-size: 1.05rem;
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 0.5rem;
      margin: 0;
    }

    .calc-card-icon {
      font-size: 1.15rem;
      line-height: 1;
    }

    /* Form Fields Grid */
    .form-row {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1rem;
      margin-bottom: 1rem;
    }

    @media (min-width: 640px) {
      .form-row-2 {
        grid-template-columns: 1fr 1fr;
      }
      .form-row-3 {
        grid-template-columns: 1fr 1fr 1fr;
      }
    }

    .field-group {
      display: flex;
      flex-direction: column;
      gap: 0.35rem;
    }

    .field-group label {
      font-size: 0.825rem;
      font-weight: 500;
      color: var(--text-muted);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .field-group label .hint {
      font-size: 0.75rem;
      opacity: 0.8;
      font-weight: normal;
    }

    .input-addon {
      display: flex;
      align-items: center;
      position: relative;
    }

    .input-addon input,
    .input-addon select {
      width: 100%;
      padding: 0.65rem 0.8rem;
      border-radius: var(--radius);
      border: 1px solid var(--border);
      background: var(--bg);
      color: var(--text);
      font-size: 0.95rem;
      outline: none;
      transition: border-color 0.2s, box-shadow 0.2s;
    }

    .input-addon input:focus,
    .input-addon select:focus {
      border-color: var(--accent);
      box-shadow: 0 0 0 2px rgba(0, 188, 212, 0.18);
    }

    .input-addon .suffix {
      position: absolute;
      right: 0.85rem;
      pointer-events: none;
      color: var(--text-muted);
      font-size: 0.85rem;
      font-weight: 500;
    }

    .input-addon input.has-suffix {
      padding-right: 2.8rem;
    }

    /* Quick Preset Buttons */
    .preset-pill-group {
      display: flex;
      flex-wrap: wrap;
      gap: 0.4rem;
      margin-top: 0.4rem;
    }

    .preset-pill {
      font-size: 0.75rem;
      padding: 0.25rem 0.6rem;
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: 999px;
      cursor: pointer;
      color: var(--text-muted);
      transition: all 0.15s ease;
    }

    .preset-pill:hover,
    .preset-pill.active {
      border-color: var(--accent);
      color: var(--accent-text);
      background: var(--highlight-badge);
    }

    /* Sticky Summary Column */
    .summary-pane {
      position: sticky;
      top: 1.5rem;
    }

    .price-hero-card {
      background: linear-gradient(145deg, var(--surface), rgba(0, 188, 212, 0.08));
      border: 2px solid var(--accent);
      border-radius: 14px;
      padding: 1.5rem;
      margin-bottom: 1.25rem;
      box-shadow: 0 8px 24px rgba(0, 188, 212, 0.12);
      position: relative;
      overflow: hidden;
    }

    .price-hero-card::after {
      content: '';
      position: absolute;
      top: -30px;
      right: -30px;
      width: 120px;
      height: 120px;
      background: radial-gradient(circle, rgba(0, 188, 212, 0.2) 0%, transparent 70%);
      pointer-events: none;
    }

    .price-title-tag {
      font-size: 0.78rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--accent-text);
      margin-bottom: 0.35rem;
      display: block;
    }

    .price-big-number {
      font-size: 2.75rem;
      font-weight: 800;
      line-height: 1.1;
      color: var(--text);
      letter-spacing: -0.03em;
    }

    .price-sub-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.75rem;
      margin-top: 1.2rem;
      padding-top: 1rem;
      border-top: 1px dashed var(--border);
    }

    .price-sub-item .sub-label {
      font-size: 0.78rem;
      color: var(--text-muted);
      display: block;
    }

    .price-sub-item .sub-val {
      font-size: 1.15rem;
      font-weight: 700;
      color: var(--text);
    }

    .sub-val.profit-val {
      color: #10b981;
    }

    /* Breakdown Visual */
    .chart-panel {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.25rem;
      margin-bottom: 1.25rem;
    }

    .breakdown-bars {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      margin-top: 1rem;
    }

    .bar-row {
      display: flex;
      flex-direction: column;
      gap: 0.25rem;
    }

    .bar-header {
      display: flex;
      justify-content: space-between;
      font-size: 0.8rem;
    }

    .bar-track {
      width: 100%;
      height: 8px;
      background: var(--bg);
      border-radius: 4px;
      overflow: hidden;
      display: flex;
    }

    .bar-fill {
      height: 100%;
      border-radius: 4px;
      transition: width 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }

    /* Batch production block */
    .batch-box {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.25rem;
      margin-bottom: 1.25rem;
    }

    .batch-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0.4rem 0;
      font-size: 0.875rem;
      border-bottom: 1px solid var(--border);
    }

    .batch-row:last-child {
      border-bottom: none;
      padding-bottom: 0;
      font-weight: 600;
    }

    /* Action buttons */
    .action-button-group {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.75rem;
    }

    .btn-action {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
      padding: 0.75rem 1rem;
      font-size: 0.875rem;
      font-weight: 600;
      border-radius: var(--radius);
      cursor: pointer;
      border: 1px solid var(--border);
      background: var(--surface);
      color: var(--text);
      transition: all 0.2s;
    }

    .btn-action:hover {
      background: var(--bg);
      border-color: var(--accent);
      color: var(--accent-text);
    }

    .btn-action.btn-accent {
      background: var(--accent);
      color: var(--accent-contrast);
      border-color: var(--accent);
    }

    .btn-action.btn-accent:hover {
      filter: brightness(1.1);
    }

    /* Print styles */
    @media print {
      body {
        background: #fff !important;
        color: #000 !important;
      }
      .top-nav, .action-button-group, .preset-pill-group, .nav-actions {
        display: none !important;
      }
      .calc-layout {
        display: block;
      }
      .calc-card, .chart-panel, .price-hero-card, .batch-box {
        break-inside: avoid;
        box-shadow: none !important;
        border: 1px solid #ddd !important;
        background: #fff !important;
        color: #000 !important;
        margin-bottom: 1rem;
      }
      .price-big-number, .sub-val {
        color: #000 !important;
      }
    }

    /* Notification toast */
    #toast {
      position: fixed;
      bottom: 1.5rem;
      right: 1.5rem;
      background: #10b981;
      color: #fff;
      padding: 0.75rem 1.25rem;
      border-radius: 8px;
      font-size: 0.875rem;
      font-weight: 600;
      box-shadow: 0 4px 16px rgba(0,0,0,0.3);
      opacity: 0;
      transform: translateY(12px);
      transition: opacity 0.2s, transform 0.2s;
      pointer-events: none;
      z-index: 9999;
    }
    #toast.show {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body>
  <div class="shell-container">
    
    <!-- Top Nav -->
    <header class="top-nav">
      <div class="brand-mark">
        <div class="brand-logo-icon">3D</div>
        <div>
          <span>Casa116-3D</span>
          <span class="shell-badge" style="margin-left: 0.5rem; font-size: 0.7rem; vertical-align: middle;">v2.5 Pro</span>
        </div>
      </div>
      <div class="nav-actions">
        <button id="themeToggleBtn" class="btn-action" style="padding: 0.45rem 0.8rem; font-size: 0.8rem;" title="Alternar Modo Claro/Escuro">
          <span id="themeIcon">☀️</span> <span id="themeText">Claro</span>
        </button>
      </div>
    </header>

    <!-- Hero Title -->
    <section class="shell-hero" style="margin-bottom: 2rem;">
      <h1 style="font-size: 1.9rem; font-weight: 800; letter-spacing: -0.02em; margin-bottom: 0.5rem;">
        Calculadora de Precificação de Impressão 3D
      </h1>
      <p class="muted" style="max-width: 680px; font-size: 0.95rem; margin: 0;">
        Calcule o custo fabril exato e o preço de venda justo considerando consumo elétrico, desgaste de equipamento, filamento, pós-processamento, perdas e margem de lucro.
      </p>
    </section>

    <!-- Identification input -->
    <div class="calc-card" style="padding: 1rem 1.4rem; margin-bottom: 1.5rem;">
      <div class="field-group">
        <label for="pieceName">Identificação da Peça ou Pedido <span class="hint">Opcional para orçamentos</span></label>
        <div class="input-addon">
          <input type="text" id="pieceName" placeholder="Ex: Suporte de Headphone Articulado - V1" value="Action Figure / Suporte Robótico">
        </div>
      </div>
    </div>

    <!-- Main Workspace -->
    <main class="calc-layout">
      
      <!-- Left Column: All Input Sections -->
      <div class="inputs-column">

        <!-- 1. MATERIAL -->
        <section class="calc-card">
          <div class="calc-card-header">
            <h2 class="calc-card-title">
              <span class="calc-card-icon">🧵</span> 1. Material (Filamento / Resina)
            </h2>
            <span id="badgeCostMaterial" class="shell-badge accent">R$ 0,00</span>
          </div>

          <div class="form-row form-row-3">
            <div class="field-group">
              <label for="materialPreset">Tipo de Material</label>
              <div class="input-addon">
                <select id="materialPreset">
                  <option value="100" selected>PLA (Padrão)</option>
                  <option value="115">PETG (Técnico)</option>
                  <option value="95">ABS (Resistente)</option>
                  <option value="160">TPU (Flexível)</option>
                  <option value="240">Nylon (Engenharia)</option>
                  <option value="180">Resina UV Standard</option>
                  <option value="custom">Outro (Personalizado)</option>
                </select>
              </div>
            </div>

            <div class="field-group">
              <label for="materialPrice">Preço do Rolo / Kg <span class="hint">R$/kg</span></label>
              <div class="input-addon">
                <input type="number" id="materialPrice" step="0.5" min="0" value="100.00" class="has-suffix">
                <span class="suffix">R$/kg</span>
              </div>
            </div>

            <div class="field-group">
              <label for="pieceWeight">Peso da Peça <span class="hint">do Fatiador</span></label>
              <div class="input-addon">
                <input type="number" id="pieceWeight" step="1" min="0" value="85" class="has-suffix">
                <span class="suffix">g</span>
              </div>
            </div>
          </div>
          <p class="muted" style="font-size: 0.78rem; margin: 0;">Fórmula: (Preço / 1000) × Peso da peça.</p>
        </section>

        <!-- 2. ENERGIA -->
        <section class="calc-card">
          <div class="calc-card-header">
            <h2 class="calc-card-title">
              <span class="calc-card-icon">⚡</span> 2. Consumo de Energia Elétrica
            </h2>
            <span id="badgeCostEnergy" class="shell-badge accent">R$ 0,00</span>
          </div>

          <div class="form-row form-row-2">
            <div class="field-group">
              <label for="printerPower">Potência Média da Máquina</label>
              <div class="input-addon">
                <input type="number" id="printerPower" step="5" min="0" value="120" class="has-suffix">
                <span class="suffix">W</span>
              </div>
              <div class="preset-pill-group">
                <button type="button" class="preset-pill" onclick="setPower(110)">Ender 3 (110W)</button>
                <button type="button" class="preset-pill" onclick="setPower(160)">Bambu P1/X1 (160W)</button>
                <button type="button" class="preset-pill" onclick="setPower(180)">Prusa MK3 (180W)</button>
                <button type="button" class="preset-pill" onclick="setPower(220)">Creality K1 (220W)</button>
              </div>
            </div>

            <div class="field-group">
              <label for="energyRate">Tarifa de Energia <span class="hint">Conta de luz</span></label>
              <div class="input-addon">
                <input type="number" id="energyRate" step="0.02" min="0" value="0.85" class="has-suffix">
                <span class="suffix">R$/kWh</span>
              </div>
              <p class="muted" style="font-size: 0.75rem; margin-top: 0.4rem;">Média nacional Brasil: R$ 0,75 a R$ 1,05/kWh</p>
            </div>
          </div>

          <div class="form-row form-row-2">
            <div class="field-group">
              <label for="printHours">Horas de Impressão</label>
              <div class="input-addon">
                <input type="number" id="printHours" min="0" step="1" value="5" class="has-suffix">
                <span class="suffix">h</span>
              </div>
            </div>
            <div class="field-group">
              <label for="printMinutes">Minutos Adicionais</label>
              <div class="input-addon">
                <input type="number" id="printMinutes" min="0" max="59" step="1" value="30" class="has-suffix">
                <span class="suffix">min</span>
              </div>
            </div>
          </div>
        </section>

        <!-- 3. MÃO DE OBRA -->
        <section class="calc-card">
          <div class="calc-card-header">
            <h2 class="calc-card-title">
              <span class="calc-card-icon">⏱️</span> 3. Mão de Obra & Operação
            </h2>
            <span id="badgeCostLabor" class="shell-badge accent">R$ 0,00</span>
          </div>

          <div class="form-row form-row-2">
            <div class="field-group">
              <label for="laborMinutes">Tempo de Preparo & Pós-processo <span class="hint">Fatiar, mesa, suportes</span></label>
              <div class="input-addon">
                <input type="number" id="laborMinutes" step="5" min="0" value="25" class="has-suffix">
                <span class="suffix">min</span>
              </div>
            </div>

            <div class="field-group">
              <label for="laborHourlyRate">Valor da sua Hora de Trabalho</label>
              <div class="input-addon">
                <input type="number" id="laborHourlyRate" step="5" min="0" value="30.00" class="has-suffix">
                <span class="suffix">R$/h</span>
              </div>
            </div>
          </div>
        </section>

        <!-- 4. DEPRECIAÇÃO & DESGASTE -->
        <section class="calc-card">
          <div class="calc-card-header">
            <h2 class="calc-card-title">
              <span class="calc-card-icon">🛠️</span> 4. Depreciação e Manutenção
            </h2>
            <span id="badgeCostDeprec" class="shell-badge accent">R$ 0,00</span>
          </div>

          <div class="form-row form-row-2">
            <div class="field-group">
              <label for="printerCost">Valor de Compra da Impressora</label>
              <div class="input-addon">
                <input type="number" id="printerCost" step="50" min="0" value="2200.00" class="has-suffix">
                <span class="suffix">R$</span>
              </div>
            </div>

            <div class="field-group">
              <label for="printerLifespanHours">Vida Útil Estimada <span class="hint">Tempo total produtivo</span></label>
              <div class="input-addon">
                <input type="number" id="printerLifespanHours" step="250" min="100" value="3500" class="has-suffix">
                <span class="suffix">horas</span>
              </div>
            </div>
          </div>
          <p class="muted" style="font-size: 0.78rem; margin: 0;">
            Custo hora de equipamento: <strong id="deprecRatePerHour">R$ 0,63/h</strong> (cobre bicos, correias, tubos e reinvestimento).
          </p>
        </section>

        <!-- 5. OUTROS CUSTOS & FALHAS -->
        <section class="calc-card">
          <div class="calc-card-header">
            <h2 class="calc-card-title">
              <span class="calc-card-icon">📦</span> 5. Insumos Fixos & Taxa de Falhas
            </h2>
            <span id="badgeCostExtras" class="shell-badge accent">R$ 0,00</span>
          </div>

          <div class="form-row form-row-3">
            <div class="field-group">
              <label for="packagingCost">Embalagem <span class="hint">Caixa/Plástico</span></label>
              <div class="input-addon">
                <input type="number" id="packagingCost" step="0.5" min="0" value="3.50" class="has-suffix">
                <span class="suffix">R$</span>
              </div>
            </div>

            <div class="field-group">
              <label for="otherCosts">Outros Insumos <span class="hint">Cola, Álcool, Lixa</span></label>
              <div class="input-addon">
                <input type="number" id="otherCosts" step="0.5" min="0" value="1.50" class="has-suffix">
                <span class="suffix">R$</span>
              </div>
            </div>

            <div class="field-group">
              <label for="failureRate">Taxa de Falha / Risco <span class="hint">Perdas médias</span></label>
              <div class="input-addon">
                <input type="number" id="failureRate" step="1" min="0" max="100" value="8" class="has-suffix">
                <span class="suffix">%</span>
              </div>
            </div>
          </div>
        </section>

        <!-- 6. MARGEM DE LUCRO & LOTE -->
        <section class="calc-card">
          <div class="calc-card-header">
            <h2 class="calc-card-title">
              <span class="calc-card-icon">🎯</span> 6. Margem de Lucro & Quantidade
            </h2>
          </div>

          <div class="form-row form-row-2">
            <div class="field-group">
              <label for="profitMargin">Margem de Lucro Desejada</label>
              <div class="input-addon">
                <input type="number" id="profitMargin" step="5" min="0" value="65" class="has-suffix">
                <span class="suffix">%</span>
              </div>
              <div class="preset-pill-group">
                <button type="button" class="preset-pill" onclick="setMargin(35)">35% (Volume)</button>
                <button type="button" class="preset-pill" onclick="setMargin(50)">50% (Padrão)</button>
                <button type="button" class="preset-pill" onclick="setMargin(80)">80% (Maker)</button>
                <button type="button" class="preset-pill" onclick="setMargin(120)">120% (Exclusivo)</button>
              </div>
            </div>

            <div class="field-group">
              <label for="batchQuantity">Quantidade no Lote <span class="hint">Multiplicador</span></label>
              <div class="input-addon">
                <input type="number" id="batchQuantity" step="1" min="1" value="1" class="has-suffix">
                <span class="suffix">un.</span>
              </div>
            </div>
          </div>
        </section>

      </div>

      <!-- Right Column: Results & Analytics Sticky Panel -->
      <aside class="summary-pane">
        
        <!-- Big Price Highlight -->
        <div class="price-hero-card">
          <span class="price-title-tag">Preço de Venda Sugerido</span>
          <div class="price-big-number" id="displaySellingPrice">R$ 0,00</div>

          <div class="price-sub-grid">
            <div class="price-sub-item">
              <span class="sub-label">Custo Unitário Total</span>
              <span class="sub-val" id="displayTotalCost">R$ 0,00</span>
            </div>
            <div class="price-sub-item">
              <span class="sub-label">Lucro Líquido Unitário</span>
              <span class="sub-val profit-val" id="displayNetProfit">+ R$ 0,00</span>
            </div>
          </div>
        </div>

        <!-- KPI Mini Grid -->
        <div class="shell-grid" style="grid-template-columns: repeat(2, 1fr); gap: 0.75rem; margin-bottom: 1.25rem;">
          <div class="kpi">
            <span class="kpi-label">Custo por Grama</span>
            <span class="kpi-value" id="kpiCostPerGram" style="font-size: 1.2rem;">R$ 0,00</span>
          </div>
          <div class="kpi">
            <span class="kpi-label">Custo por Hora</span>
            <span class="kpi-value" id="kpiCostPerHour" style="font-size: 1.2rem;">R$ 0,00</span>
          </div>
        </div>

        <!-- Visual Breakdown Bars -->
        <div class="chart-panel">
          <div style="display: flex; justify-content: space-between; align-items: center;">
            <h3 style="font-size: 0.95rem; font-weight: 600; margin: 0;">Composição do Custo Real</h3>
            <span class="muted" style="font-size: 0.75rem;" id="breakdownSubtotalLabel">100% da base</span>
          </div>

          <div class="breakdown-bars">
            <!-- Material -->
            <div class="bar-row">
              <div class="bar-header">
                <span>🧵 Filamento / Resina</span>
                <span id="barLabelMaterial">R$ 0,00 (0%)</span>
              </div>
              <div class="bar-track">
                <div id="barFillMaterial" class="bar-fill" style="background: #00bcd4; width: 0%;"></div>
              </div>
            </div>

            <!-- Labor -->
            <div class="bar-row">
              <div class="bar-header">
                <span>⏱️ Mão de Obra</span>
                <span id="barLabelLabor">R$ 0,00 (0%)</span>
              </div>
              <div class="bar-track">
                <div id="barFillLabor" class="bar-fill" style="background: #3b82f6; width: 0%;"></div>
              </div>
            </div>

            <!-- Depreciation -->
            <div class="bar-row">
              <div class="bar-header">
                <span>🛠️ Desgaste da Máquina</span>
                <span id="barLabelDeprec">R$ 0,00 (0%)</span>
              </div>
              <div class="bar-track">
                <div id="barFillDeprec" class="bar-fill" style="background: #8b5cf6; width: 0%;"></div>
              </div>
            </div>

            <!-- Energy -->
            <div class="bar-row">
              <div class="bar-header">
                <span>⚡ Energia Elétrica</span>
                <span id="barLabelEnergy">R$ 0,00 (0%)</span>
              </div>
              <div class="bar-track">
                <div id="barFillEnergy" class="bar-fill" style="background: #f59e0b; width: 0%;"></div>
              </div>
            </div>

            <!-- Extras & Failures -->
            <div class="bar-row">
              <div class="bar-header">
                <span>📦 Embalagem + Perdas</span>
                <span id="barLabelExtras">R$ 0,00 (0%)</span>
              </div>
              <div class="bar-track">
                <div id="barFillExtras" class="bar-fill" style="background: #ef4444; width: 0%;"></div>
              </div>
            </div>
          </div>
        </div>

        <!-- Batch Summary (Updates with quantity) -->
        <div class="batch-box" id="batchSection">
          <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.65rem;">
            <h3 style="font-size: 0.92rem; font-weight: 600; margin: 0;">Simulação de Produção (<span id="batchCountLabel">1 un.</span>)</h3>
          </div>
          <div class="batch-row">
            <span class="muted">Custo Total do Lote:</span>
            <span id="batchTotalCost">R$ 0,00</span>
          </div>
          <div class="batch-row">
            <span class="muted">Preço Total de Venda:</span>
            <span id="batchTotalSelling" style="color: var(--accent-text);">R$ 0,00</span>
          </div>
          <div class="batch-row">
            <span>Lucro Líquido Acumulado:</span>
            <span id="batchTotalProfit" style="color: #10b981;">+ R$ 0,00</span>
          </div>
        </div>

        <!-- Action Buttons -->
        <div class="action-button-group">
          <button type="button" class="btn-action btn-accent" id="btnCopyQuote">
            <span>📋</span> Copiar Orçamento
          </button>
          <button type="button" class="btn-action" onclick="window.print()">
            <span>🖨️</span> Imprimir / PDF
          </button>
        </div>

      </aside>

    </main>

    <!-- Footer with Maker Tip -->
    <footer class="shell-footer" style="margin-top: 3.5rem; padding: 2rem 0; border-top: 1px solid var(--border);">
      <div style="background: var(--surface); border: 1px solid var(--border); border-radius: 10px; padding: 1.25rem; display: flex; gap: 1rem; align-items: center;">
        <span style="font-size: 1.8rem; line-height: 1;">💡</span>
        <div style="font-size: 0.85rem; line-height: 1.45;">
          <strong>Dica Pro para Makers:</strong> Para maior precisão, retire o peso exato e o tempo de impressão diretamente no fatiador configurado para sua impressora (como <em>UltiMaker Cura</em>, <em>PrusaSlicer</em>, <em>OrcaSlicer</em> ou <em>Bambu Studio</em>). Não se esqueça de pesar a peça final com suportes e brim para aferir suas perdas reais.
        </div>
      </div>
      <p class="muted" style="text-align: center; font-size: 0.8rem; margin-top: 1.5rem;">
        Casa116-3D &bull; Ferramenta estática livre para impressões 3D FDM e SLA &bull; Desenvolvido para makers e pequenas oficinas
      </p>
    </footer>

  </div>

  <!-- Notification Toast -->
  <div id="toast">Orçamento copiado para a área de transferência!</div>

  <script>
    // --- Helper Formatters ---
    function formatBRL(val) {
      if (window.skipShell && window.skipShell.fmt && window.skipShell.fmt.brl) {
        return window.skipShell.fmt.brl(val);
      }
      return (Number(val) || 0).toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' });
    }

    function formatNumber(val, decimals = 2) {
      return (Number(val) || 0).toLocaleString('pt-BR', { minimumFractionDigits: decimals, maximumFractionDigits: decimals });
    }

    // --- State Elements ---
    const elPieceName = document.getElementById('pieceName');
    const elMaterialPreset = document.getElementById('materialPreset');
    const elMaterialPrice = document.getElementById('materialPrice');
    const elPieceWeight = document.getElementById('pieceWeight');

    const elPrinterPower = document.getElementById('printerPower');
    const elEnergyRate = document.getElementById('energyRate');
    const elPrintHours = document.getElementById('printHours');
    const elPrintMinutes = document.getElementById('printMinutes');

    const elLaborMinutes = document.getElementById('laborMinutes');
    const elLaborHourlyRate = document.getElementById('laborHourlyRate');

    const elPrinterCost = document.getElementById('printerCost');
    const elPrinterLifespanHours = document.getElementById('printerLifespanHours');

    const elPackagingCost = document.getElementById('packagingCost');
    const elOtherCosts = document.getElementById('otherCosts');
    const elFailureRate = document.getElementById('failureRate');

    const elProfitMargin = document.getElementById('profitMargin');
    const elBatchQuantity = document.getElementById('batchQuantity');

    // Outputs
    const badgeCostMaterial = document.getElementById('badgeCostMaterial');
    const badgeCostEnergy = document.getElementById('badgeCostEnergy');
    const badgeCostLabor = document.getElementById('badgeCostLabor');
    const badgeCostDeprec = document.getElementById('badgeCostDeprec');
    const badgeCostExtras = document.getElementById('badgeCostExtras');
    const deprecRatePerHour = document.getElementById('deprecRatePerHour');

    const displaySellingPrice = document.getElementById('displaySellingPrice');
    const displayTotalCost = document.getElementById('displayTotalCost');
    const displayNetProfit = document.getElementById('displayNetProfit');

    const kpiCostPerGram = document.getElementById('kpiCostPerGram');
    const kpiCostPerHour = document.getElementById('kpiCostPerHour');

    // Bars
    const barLabelMaterial = document.getElementById('barLabelMaterial');
    const barFillMaterial = document.getElementById('barFillMaterial');
    const barLabelLabor = document.getElementById('barLabelLabor');
    const barFillLabor = document.getElementById('barFillLabor');
    const barLabelDeprec = document.getElementById('barLabelDeprec');
    const barFillDeprec = document.getElementById('barFillDeprec');
    const barLabelEnergy = document.getElementById('barLabelEnergy');
    const barFillEnergy = document.getElementById('barFillEnergy');
    const barLabelExtras = document.getElementById('barLabelExtras');
    const barFillExtras = document.getElementById('barFillExtras');

    // Batch Outputs
    const batchCountLabel = document.getElementById('batchCountLabel');
    const batchTotalCost = document.getElementById('batchTotalCost');
    const batchTotalSelling = document.getElementById('batchTotalSelling');
    const batchTotalProfit = document.getElementById('batchTotalProfit');

    // Toast
    const toast = document.getElementById('toast');
    function showToast(msg) {
      toast.textContent = msg;
      toast.classList.add('show');
      setTimeout(() => toast.classList.remove('show'), 2600);
    }

    // Preset helper functions
    window.setPower = function(watts) {
      elPrinterPower.value = watts;
      calculateAll();
    };

    window.setMargin = function(pct) {
      elProfitMargin.value = pct;
      calculateAll();
    };

    // Material Preset handler
    elMaterialPreset.addEventListener('change', (e) => {
      const val = e.target.value;
      if (val !== 'custom') {
        elMaterialPrice.value = parseFloat(val).toFixed(2);
      }
      calculateAll();
    });

    // Theme toggling
    const themeToggleBtn = document.getElementById('themeToggleBtn');
    const themeIcon = document.getElementById('themeIcon');
    const themeText = document.getElementById('themeText');

    function syncThemeUI(theme) {
      if (theme === 'dark') {
        themeIcon.textContent = '☀️';
        themeText.textContent = 'Claro';
      } else {
        themeIcon.textContent = '🌙';
        themeText.textContent = 'Escuro';
      }
    }

    themeToggleBtn.addEventListener('click', () => {
      const current = document.documentElement.getAttribute('data-theme') || 'dark';
      const next = current === 'dark' ? 'light' : 'dark';
      document.documentElement.setAttribute('data-theme', next);
      syncThemeUI(next);
      try { localStorage.setItem('calc3d_theme', next); } catch(err){}
    });

    // Restore stored theme if available
    try {
      const savedTheme = localStorage.getItem('calc3d_theme');
      if (savedTheme) {
        document.documentElement.setAttribute('data-theme', savedTheme);
        syncThemeUI(savedTheme);
      }
    } catch(err){}

    // --- Calculation Engine ---
    let currentSummaryData = {};

    function calculateAll() {
      // 1. Material
      const matPriceKg = Math.max(0, parseFloat(elMaterialPrice.value) || 0);
      const weightG = Math.max(0, parseFloat(elPieceWeight.value) || 0);
      const costMaterial = (matPriceKg / 1000) * weightG;

      // 2. Energy
      const powerW = Math.max(0, parseFloat(elPrinterPower.value) || 0);
      const energyTariff = Math.max(0, parseFloat(elEnergyRate.value) || 0);
      const hours = Math.max(0, parseFloat(elPrintHours.value) || 0);
      const mins = Math.max(0, Math.min(59, parseFloat(elPrintMinutes.value) || 0));
      const totalPrintHours = hours + (mins / 60);
      const costEnergy = (powerW / 1000) * totalPrintHours * energyTariff;

      // 3. Labor
      const laborMins = Math.max(0, parseFloat(elLaborMinutes.value) || 0);
      const laborRateHour = Math.max(0, parseFloat(elLaborHourlyRate.value) || 0);
      const laborHours = laborMins / 60;
      const costLabor = laborHours * laborRateHour;

      // 4. Depreciation
      const machineCost = Math.max(0, parseFloat(elPrinterCost.value) || 0);
      const machineLife = Math.max(1, parseFloat(elPrinterLifespanHours.value) || 1);
      const deprecPerHourVal = machineCost / machineLife;
      const costDeprec = deprecPerHourVal * totalPrintHours;
      deprecRatePerHour.textContent = `${formatBRL(deprecPerHourVal)}/h`;

      // 5. Fixed & Extras
      const packCost = Math.max(0, parseFloat(elPackagingCost.value) || 0);
      const extraOther = Math.max(0, parseFloat(elOtherCosts.value) || 0);
      const failRatePct = Math.max(0, parseFloat(elFailureRate.value) || 0);

      const baseSubtotal = costMaterial + costEnergy + costLabor + costDeprec + packCost + extraOther;
      const failureAdjustment = baseSubtotal * (failRatePct / 100);
      const totalCostUnit = baseSubtotal + failureAdjustment;

      // 6. Profit & Selling
      const marginPct = Math.max(0, parseFloat(elProfitMargin.value) || 0);
      const sellingPriceUnit = totalCostUnit * (1 + (marginPct / 100));
      const profitUnit = sellingPriceUnit - totalCostUnit;

      // Batch
      const batchQty = Math.max(1, parseInt(elBatchQuantity.value) || 1);
      const batchTotalC = totalCostUnit * batchQty;
      const batchTotalS = sellingPriceUnit * batchQty;
      const batchTotalP = profitUnit * batchQty;

      // Unit Metrics
      const costPerG = weightG > 0 ? (totalCostUnit / weightG) : 0;
      const costPerH = totalPrintHours > 0 ? (totalCostUnit / totalPrintHours) : 0;

      // Render Badges
      badgeCostMaterial.textContent = formatBRL(costMaterial);
      badgeCostEnergy.textContent = formatBRL(costEnergy);
      badgeCostLabor.textContent = formatBRL(costLabor);
      badgeCostDeprec.textContent = formatBRL(costDeprec);
      badgeCostExtras.textContent = formatBRL(packCost + extraOther + failureAdjustment);

      // Render Hero Numbers
      displaySellingPrice.textContent = formatBRL(sellingPriceUnit);
      displayTotalCost.textContent = formatBRL(totalCostUnit);
      displayNetProfit.textContent = `+ ${formatBRL(profitUnit)}`;

      // Render KPIs
      kpiCostPerGram.textContent = `${formatBRL(costPerG)}/g`;
      kpiCostPerHour.textContent = `${formatBRL(costPerH)}/h`;

      // Render Breakdown Bars
      const costExtrasAndFailures = packCost + extraOther + failureAdjustment;
      const safeTotal = totalCostUnit > 0 ? totalCostUnit : 1;

      const pMat = ((costMaterial / safeTotal) * 100);
      const pLab = ((costLabor / safeTotal) * 100);
      const pDep = ((costDeprec / safeTotal) * 100);
      const pEne = ((costEnergy / safeTotal) * 100);
      const pExt = ((costExtrasAndFailures / safeTotal) * 100);

      barLabelMaterial.textContent = `${formatBRL(costMaterial)} (${formatNumber(pMat, 1)}%)`;
      barFillMaterial.style.width = `${Math.min(100, pMat)}%`;

      barLabelLabor.textContent = `${formatBRL(costLabor)} (${formatNumber(pLab, 1)}%)`;
      barFillLabor.style.width = `${Math.min(100, pLab)}%`;

      barLabelDeprec.textContent = `${formatBRL(costDeprec)} (${formatNumber(pDep, 1)}%)`;
      barFillDeprec.style.width = `${Math.min(100, pDep)}%`;

      barLabelEnergy.textContent = `${formatBRL(costEnergy)} (${formatNumber(pEne, 1)}%)`;
      barFillEnergy.style.width = `${Math.min(100, pEne)}%`;

      barLabelExtras.textContent = `${formatBRL(costExtrasAndFailures)} (${formatNumber(pExt, 1)}%)`;
      barFillExtras.style.width = `${Math.min(100, pExt)}%`;

      // Batch display
      batchCountLabel.textContent = `${batchQty} ${batchQty > 1 ? 'unidades' : 'unidade'}`;
      batchTotalCost.textContent = formatBRL(batchTotalC);
      batchTotalSelling.textContent = formatBRL(batchTotalS);
      batchTotalProfit.textContent = `+ ${formatBRL(batchTotalP)}`;

      // Save summary cache for copying
      currentSummaryData = {
        pieceName: elPieceName.value || 'Peça sem título',
        materialType: elMaterialPreset.options[elMaterialPreset.selectedIndex].text,
        weight: `${weightG}g`,
        printTime: `${hours}h ${mins}min`,
        costMaterial,
        costEnergy,
        costLabor,
        costDeprec,
        costExtrasAndFailures,
        totalCostUnit,
        marginPct,
        profitUnit,
        sellingPriceUnit,
        batchQty,
        batchTotalCost: batchTotalC,
        batchTotalSelling: batchTotalS,
        batchTotalProfit: batchTotalP
      };
    }

    // Attach listeners to all inputs
    const allInputs = document.querySelectorAll('input, select');
    allInputs.forEach(input => {
      input.addEventListener('input', calculateAll);
      input.addEventListener('change', calculateAll);
    });

    // Copy Quote Button
    document.getElementById('btnCopyQuote').addEventListener('click', () => {
      const d = currentSummaryData;
      const text = 
`📦 ORÇAMENTO DE IMPRESSÃO 3D — ${d.pieceName}
---------------------------------------------
⚙️ Material: ${d.materialType} (${d.weight})
⏱️ Tempo de Impressão: ${d.printTime}
---------------------------------------------
📊 COMPOSIÇÃO DE CUSTOS (por unidade):
• Material / Filamento: ${formatBRL(d.costMaterial)}
• Mão de Obra (Preparo/Pós): ${formatBRL(d.costLabor)}
• Desgaste da Máquina: ${formatBRL(d.costDeprec)}
• Energia Elétrica: ${formatBRL(d.costEnergy)}
• Embalagem, Insumos e Risco: ${formatBRL(d.costExtrasAndFailures)}
---------------------------------------------
💰 Custo Unitário: ${formatBRL(d.totalCostUnit)}
🎯 Margem Aplicada: ${d.marginPct}%
⭐ PREÇO UNITÁRIO SUGERIDO: ${formatBRL(d.sellingPriceUnit)}
${d.batchQty > 1 ? `
📦 LOTE (${d.batchQty} un.):
• Custo Total do Lote: ${formatBRL(d.batchTotalCost)}
• Preço Total de Venda: ${formatBRL(d.batchTotalSelling)}
• Lucro Líquido do Lote: ${formatBRL(d.batchTotalProfit)}` : ''}
---------------------------------------------
Orçamento gerado com Calc3D.`;

      if (navigator.clipboard && navigator.clipboard.writeText) {
        navigator.clipboard.writeText(text).then(() => {
          showToast('Orçamento copiado para a área de transferência!');
        }).catch(() => {
          fallbackCopyText(text);
        });
      } else {
        fallbackCopyText(text);
      }
    });

    function fallbackCopyText(text) {
      const textarea = document.createElement('textarea');
      textarea.value = text;
      textarea.style.position = 'fixed';
      textarea.style.opacity = '0';
      document.body.appendChild(textarea);
      textarea.select();
      try {
        document.execCommand('copy');
        showToast('Orçamento copiado com sucesso!');
      } catch (e) {
        alert('Não foi possível copiar automaticamente. Selecione e copie o resumo.');
      }
      document.body.removeChild(textarea);
    }

    // Initial calculation on load
    document.addEventListener('DOMContentLoaded', () => {
      calculateAll();
    });
  </script>
<script>
/* Skip artifact shell — fixed helpers served beside every artifact. */
(function () {
  "use strict";

  var fmt = {
    num: function (v, opts) { return new Intl.NumberFormat("pt-BR", opts || {}).format(v); },
    brl: function (v) { return new Intl.NumberFormat("pt-BR", { style: "currency", currency: "BRL" }).format(v); },
    pct: function (v) { return new Intl.NumberFormat("pt-BR", { style: "percent", maximumFractionDigits: 1 }).format(v); }
  };

  // axisFmt keeps axis tick labels short (compact notation) so long values
  // (e.g. full BRL amounts) never clip against the plot edge.
  function axisFmt(v) {
    return fmt.num(v, { notation: "compact", maximumFractionDigits: 1 });
  }

  // format accepts a function OR one of the fmt names ("num" | "brl" | "pct").
  function coerceFormat(spec) {
    if (typeof spec === "function") return spec;
    if (typeof spec === "string" && fmt[spec]) return fmt[spec];
    return function (v) { return fmt.num(v); };
  }

  function accent() {
    return getComputedStyle(document.documentElement).getPropertyValue("--accent").trim() || "#2563eb";
  }
  function mutedColor() {
    return getComputedStyle(document.documentElement).getPropertyValue("--text-muted").trim() || "#5b6472";
  }
  function svgEl(tag, attrs) {
    var el = document.createElementNS("http://www.w3.org/2000/svg", tag);
    for (var k in attrs) el.setAttribute(k, attrs[k]);
    return el;
  }
  function frame(el, w, h) {
    var svg = svgEl("svg", { viewBox: "0 0 " + w + " " + h, role: "img" });
    el.innerHTML = "";
    el.appendChild(svg);
    return svg;
  }

  // maxOf guards the axis scale: empty values would give -Infinity (truthy,
  // so "|| 1" can't catch it) and a non-positive max would flip the chart.
  function maxOf(values) {
    var m = values.length ? Math.max.apply(null, values) : 0;
    return m > 0 ? m : 1;
  }

  // bar(el, {labels:[], values:[], color?, format?}) — vertical bar chart.
  function bar(el, cfg) {
    var W = 640, H = 280, padL = 46, padB = 30, padT = 12;
    var svg = frame(el, W, H);
    var max = maxOf(cfg.values);
    var n = cfg.values.length;
    var plotW = W - padL - 12, plotH = H - padT - padB;
    var step = plotW / n, bw = Math.min(step * 0.62, 64);
    var color = cfg.color || accent();
    var f = coerceFormat(cfg.format);
    for (var g = 0; g <= 4; g++) {
      var gy = padT + plotH - (plotH * g) / 4;
      svg.appendChild(svgEl("line", { x1: padL, y1: gy, x2: W - 12, y2: gy, stroke: "currentColor", "stroke-opacity": 0.08 }));
      var lbl = svgEl("text", { x: padL - 8, y: gy + 4, "text-anchor": "end", "font-size": 10, fill: mutedColor() });
      lbl.textContent = axisFmt((max * g) / 4);
      svg.appendChild(lbl);
    }
    cfg.values.forEach(function (v, i) {
      var bh = Math.max(0, (v / max) * plotH);
      var x = padL + i * step + (step - bw) / 2;
      var y = padT + plotH - bh;
      var r = svgEl("rect", { x: x, y: y, width: bw, height: bh, rx: 4, fill: color });
      var t = svgEl("title", {});
      t.textContent = cfg.labels[i] + ": " + f(v);
      r.appendChild(t);
      svg.appendChild(r);
      var tx = svgEl("text", { x: x + bw / 2, y: H - 10, "text-anchor": "middle", "font-size": 11, fill: mutedColor() });
      tx.textContent = cfg.labels[i];
      svg.appendChild(tx);
    });
  }

  // line(el, {labels:[], values:[], color?, format?}) — single-series line.
  function line(el, cfg) {
    var W = 640, H = 280, padL = 46, padB = 30, padT = 12;
    var svg = frame(el, W, H);
    var max = maxOf(cfg.values);
    var n = cfg.values.length;
    var plotW = W - padL - 16, plotH = H - padT - padB;
    var color = cfg.color || accent();
    var f = coerceFormat(cfg.format);
    for (var g = 0; g <= 4; g++) {
      var gy = padT + plotH - (plotH * g) / 4;
      svg.appendChild(svgEl("line", { x1: padL, y1: gy, x2: W - 16, y2: gy, stroke: "currentColor", "stroke-opacity": 0.08 }));
      var lbl = svgEl("text", { x: padL - 8, y: gy + 4, "text-anchor": "end", "font-size": 10, fill: mutedColor() });
      lbl.textContent = axisFmt((max * g) / 4);
      svg.appendChild(lbl);
    }
    var pts = cfg.values.map(function (v, i) {
      var x = padL + (n === 1 ? plotW / 2 : (plotW * i) / (n - 1));
      var y = padT + plotH - (v / max) * plotH;
      return [x, y];
    });
    var d = pts.map(function (p, i) { return (i ? "L" : "M") + p[0].toFixed(1) + " " + p[1].toFixed(1); }).join(" ");
    svg.appendChild(svgEl("path", { d: d, fill: "none", stroke: color, "stroke-width": 2, "stroke-linejoin": "round" }));
    pts.forEach(function (p, i) {
      var c = svgEl("circle", { cx: p[0], cy: p[1], r: 3.5, fill: color });
      var t = svgEl("title", {});
      t.textContent = cfg.labels[i] + ": " + f(cfg.values[i]);
      c.appendChild(t);
      svg.appendChild(c);
      var tx = svgEl("text", { x: p[0], y: H - 10, "text-anchor": "middle", "font-size": 11, fill: mutedColor() });
      tx.textContent = cfg.labels[i];
      svg.appendChild(tx);
    });
  }

  // donut(el, {labels:[], values:[], colors?}) — donut with center total.
  function donut(el, cfg) {
    var W = 320, H = 280, cx = W / 2, cy = H / 2, R = 92, r = 58;
    var svg = frame(el, W, H);
    var total = cfg.values.reduce(function (a, b) { return a + b; }, 0) || 1;
    var palette = cfg.colors || [accent(), "#1baf7a", "#eda100", "#e34948", "#4a3aa7", "#e87ba4"];
    var a0 = -Math.PI / 2;
    cfg.values.forEach(function (v, i) {
      var a1 = a0 + (v / total) * Math.PI * 2;
      var large = a1 - a0 > Math.PI ? 1 : 0;
      var p = ["M", cx + R * Math.cos(a0), cy + R * Math.sin(a0),
        "A", R, R, 0, large, 1, cx + R * Math.cos(a1), cy + R * Math.sin(a1),
        "L", cx + r * Math.cos(a1), cy + r * Math.sin(a1),
        "A", r, r, 0, large, 0, cx + r * Math.cos(a0), cy + r * Math.sin(a0), "Z"].join(" ");
      var path = svgEl("path", { d: p, fill: palette[i % palette.length] });
      var t = svgEl("title", {});
      t.textContent = cfg.labels[i] + ": " + fmt.num(v) + " (" + fmt.pct(v / total) + ")";
      path.appendChild(t);
      svg.appendChild(path);
      a0 = a1;
    });
    var center = svgEl("text", { x: cx, y: cy + 5, "text-anchor": "middle", "font-size": 20, "font-weight": 650, fill: "currentColor" });
    center.textContent = fmt.num(total);
    svg.appendChild(center);
  }

  window.skipShell = { fmt: fmt };
  window.skipChart = { bar: bar, line: line, donut: donut };
})();

</script>
</body>
</html>
