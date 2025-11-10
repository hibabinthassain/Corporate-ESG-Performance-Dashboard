<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Corporate ESG Performance Dashboard — README</title>
  <style>
    :root{
      --bg:#f6f8fb; --card:#ffffff; --muted:#5b6b76; --accent:#0b5cff;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }
    html,body{height:100%;margin:0;background:var(--bg);color:#0b1320}
    .wrap{max-width:900px;margin:36px auto;padding:28px}
    .card{background:var(--card);border-radius:12px;box-shadow:0 8px 30px rgba(2,6,23,0.06);padding:28px}
    header{display:flex;align-items:flex-start;gap:14px;flex-wrap:wrap}
    .emoji{font-size:36px;line-height:1}
    h1{margin:0;font-size:20px}
    p.lead{color:var(--muted);margin-top:8px}
    .features{margin-top:18px}
    .features ul{padding-left:20px;color:var(--muted)}
    .features li{margin:10px 0}
    .insights{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin-top:18px}
    .insight{background:#fbfdff;border-radius:10px;padding:12px;border:1px solid rgba(11,92,255,0.04)}
    .insight b{display:block;margin-bottom:6px}
    .impact{margin-top:18px;color:var(--muted)}
    .controls{display:flex;gap:10px;align-items:center;margin-top:18px}
    .btn{padding:9px 12px;border-radius:8px;border:0;cursor:pointer;font-weight:600}
    .btn--primary{background:var(--accent);color:#fff}
    .btn--ghost{background:transparent;border:1px solid rgba(3,102,214,0.08)}
    footer{margin-top:22px;font-size:13px;color:var(--muted);display:flex;justify-content:space-between;align-items:center}
    pre{display:none}
    @media (max-width:640px){.wrap{margin:14px;padding:16px}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="main" aria-labelledby="title">
      <header>
        <div class="emoji" aria-hidden="true">💼🌍</div>
        <div>
          <h1 id="title">Corporate ESG Performance Dashboard — Power BI Dashboard Project</h1>
          <p class="lead">
            Designed and developed an interactive <strong>Power BI dashboard</strong> to monitor and evaluate corporate Environmental, Social, and Governance (ESG) performance metrics across global facilities.
          </p>
        </div>
      </header>

      <section class="features" aria-labelledby="featuresTitle">
        <h2 id="featuresTitle" style="font-size:16px;margin:12px 0 8px 0">What I built</h2>
        <ul>
          <li>🔹 <strong>Data Integration & Modeling</strong> – Consolidated multi-country sustainability datasets, including CO₂ emissions, renewable energy usage, waste recycling rates, and water consumption.</li>
          <li>🔹 <strong>Dynamic KPIs & Visuals</strong> – Built real-time visual indicators and drill-down analytics to track Total CO₂, Renewable Energy %, Emission Intensity, Waste Recycled %, and ESG Scores.</li>
          <li>🔹 <strong>Geographical Insights</strong> – Implemented geo-mapping to visualize CO₂ emissions and ESG performance across regions such as North America, Europe, and Asia.</li>
          <li>🔹 <strong>Interactive Filtering</strong> – Enabled filters by year, country, and waste recycling range for comparative analysis and trend exploration.</li>
          <li>🔹 <strong>Data Storytelling & Design</strong> – Designed a clean, executive-style layout for clear communication of sustainability performance and improvement opportunities.</li>
        </ul>
      </section>

      <section class="insights" aria-labelledby="insightsTitle">
        <h2 id="insightsTitle" style="width:100%;font-size:16px;margin:12px 0 6px 0">🔑 Key Insights</h2>

        <div class="insight" role="article">
          <b>🌱 Total CO₂ Emissions</b>
          <div>5M across all facilities</div>
        </div>

        <div class="insight" role="article">
          <b>⚡ Renewable Energy Contribution</b>
          <div>4,862% aggregate usage</div>
        </div>

        <div class="insight" role="article">
          <b>💧 Water Use</b>
          <div>Highest in Plant C (3M m³)</div>
        </div>

        <div class="insight" role="article">
          <b>🔄 Waste Recycled</b>
          <div>5,096% total recycled across regions</div>
        </div>

        <div class="insight" role="article">
          <b>🏆 Top ESG Performer</b>
          <div>Japan and Canada lead in sustainability metrics</div>
        </div>
      </section>

      <section class="impact" aria-labelledby="impactTitle">
        <h2 id="impactTitle" style="font-size:16px;margin:14px 0 8px 0">Impact</h2>
        <p>
          ✨ This project strengthened my expertise in <strong>Power BI, ESG analytics, and corporate sustainability reporting</strong>, enabling data-driven decisions for environmental impact reduction and responsible governance.
        </p>
      </section>

      <div class="controls" aria-hidden="true">
        <button class="btn btn--primary" onclick="copyReadme()">Copy README text</button>
        <button class="btn btn--ghost" onclick="window.print();">Print</button>
      </div>

      <pre id="readmeText">


