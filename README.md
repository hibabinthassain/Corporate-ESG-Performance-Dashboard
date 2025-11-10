<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Power BI Dashboard Project — Corporate ESG Performance Analysis</title>
  <style>
    :root{
      --bg:#f6f8fb; --card:#ffffff; --muted:#657080; --accent:#0b5cff;
      --success:#0f9d58; --warning:#f4b400;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:var(--bg);color:#101828}
    .container{max-width:960px;margin:36px auto;padding:28px}
    .card{background:var(--card);border-radius:14px;box-shadow:0 6px 20px rgba(15,23,42,0.06);padding:28px}
    header{display:flex;gap:16px;align-items:center;justify-content:space-between}
    .title{display:flex;gap:14px;align-items:center}
    .title h1{margin:0;font-size:20px}
    .subtitle{color:var(--muted);font-size:13px;margin-top:6px}
    .meta{font-size:13px;color:var(--muted)}
    .section{margin-top:20px}
    .bullets{margin:14px 0;padding-left:18px}
    .bullets li{margin:8px 0}
    .insights{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin-top:12px}
    .insight{background:#fbfdff;border-radius:10px;padding:12px;border:1px solid rgba(11,92,255,0.04)}
    .insight b{display:block;font-size:14px}
    .footer{margin-top:22px;font-size:13px;color:var(--muted);display:flex;justify-content:space-between;align-items:center}
    .cta{display:flex;gap:8px}
    .btn{padding:10px 12px;border-radius:8px;border:0;cursor:pointer;font-weight:600}
    .btn--primary{background:var(--accent);color:#fff}
    .btn--ghost{background:transparent;border:1px solid rgba(3,102,214,0.08)}
    pre{background:#0b1220;color:#e6f0ff;padding:12px;border-radius:8px;overflow:auto}
    @media (max-width:600px){.container{margin:16px;padding:16px}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card" role="main" aria-labelledby="projectTitle">
      <header>
        <div class="title">
          <div style="font-size:30px">💼</div>
          <div>
            <h1 id="projectTitle">Power BI Dashboard Project: Corporate ESG Performance Analysis 🌍</h1>
            <div class="subtitle">Interactive Power BI dashboard for monitoring corporate Environmental, Social, and Governance (ESG) performance across global facilities.</div>
          </div>
        </div>

        <div class="meta" aria-hidden="true">Power BI • ESG • Data Visualization</div>
      </header>

      <section class="section" aria-labelledby="one-line">
        <h2 id="one-line" style="font-size:16px;margin:0 0 10px 0">Overview</h2>
        <p style="margin:0;color:var(--muted)">
          Designed and developed an interactive <strong>Power BI dashboard</strong> to monitor and evaluate corporate ESG performance metrics — including CO₂ emissions, renewable energy usage, water consumption, waste recycling, and consolidated ESG scores across countries and facilities.
        </p>
      </section>

      <section class="section" aria-labelledby="features">
        <h2 id="features" style="font-size:16px;margin:12px 0">What I built</h2>
        <ul class="bullets" aria-label="Key features">
          <li>🔹 <strong>Data Integration & Modeling</strong> – Consolidated multi-country sustainability datasets (CO₂, renewable energy, waste, water).</li>
          <li>🔹 <strong>Dynamic KPIs & Visuals</strong> – Real-time KPI cards and drill-down analytics for Total CO₂, Renewable Energy %, Emission Intensity, Waste Recycled %, and ESG Score.</li>
          <li>🔹 <strong>Geographical Insights</strong> – Geo-maps to visualize CO₂ emissions and ESG performance across regions (North America, Europe, Asia).</li>
          <li>🔹 <strong>Interactive Filtering</strong> – Filters by year, country, and waste recycling range for comparative analysis and trend exploration.</li>
          <li>🔹 <strong>Data Storytelling & Design</strong> – Executive-style layout optimized for clarity and actionable reporting.</li>
        </ul>
      </section>

      <section class="section" aria-labelledby="insights">
        <h2 id="insights" style="font-size:16px;margin:12px 0">🔑 Key Insights</h2>

        <div class="insights" role="list">
          <div class="insight" role="listitem">
            <b>🌱 Total CO₂ Emissions</b>
            <span>5M across all facilities</span>
          </div>
          <div class="insight" role="listitem">
            <b>⚡ Renewable Energy Contribution</b>
            <span>4,862% aggregate usage</span>
          </div>
          <div class="insight" role="listitem">
            <b>💧 Water Use</b>
            <span>Highest in Plant C (3M m³)</span>
          </div>
          <div class="insight" role="listitem">
            <b>🔄 Waste Recycled</b>
            <span>5,096% total recycled across regions</span>
          </div>
          <div class="insight" role="listitem">
            <b>🏆 Top ESG Performer</b>
            <span>Japan and Canada lead in sustainability metrics</span>
          </div>
        </div>
      </section>

      <section class="section" aria-labelledby="impact">
        <h2 id="impact" style="font-size:16px;margin:12px 0">Impact</h2>
        <p class="meta" style="margin:0">
          ✨ This project strengthened my expertise in <strong>Power BI, ESG analytics, and corporate sustainability reporting</strong>, enabling data-driven decisions for environmental impact reduction and responsible governance.
        </p>
      </section>

      <section class="section" aria-labelledby="usage">
        <h2 id="usage" style="font-size:16px;margin:12px 0">How to use</h2>
        <ol style="margin:0 0 12px 18px;color:var(--muted)">
          <li>Open the Power BI project file in Power BI Desktop (or Power BI Service if published).</li>
          <li>Use the filter panel to select Year, Country, and Water / Waste ranges to explore scenarios.</li>
          <li>Drill down on charts and map pins to inspect facility-level details and trends.</li>
        </ol>

        <div style="display:flex;gap:10px;align-items:center;margin-top:8px">
          <button class="btn btn--primary" onclick="copyReadme()">Copy README Text</button>
          <a class="btn btn--ghost" href="#" onclick="window.print();return false">Print</a>
        </div>

        <pre id="readmeText" hidden>
💼 Power BI Dashboard Project: Corporate ESG Performance Analysis 🌍
Designed and developed an interactive Power BI dashboard to monitor and evaluate corporate Environmental, Social, and Governance (ESG) performance metrics across global facilities.

Data Integration & Modeling – Consolidated multi-country sustainability datasets, including CO₂ emissions, renewable energy usage, waste recycling rates, and water consumption.
Dynamic KPIs & Visuals – Built real-time visual indicators and drill-down analytics to track Total CO₂, Renewable Energy %, Emission Intensity, Waste Recycled %, and ESG Scores.
Geographical Insights – Implemented geo-mapping to visualize CO₂ emissions and ESG performance across regions such as North America, Europe, and Asia.
Interactive Filtering – Enabled filters by year, country, and waste recycling range for comparative analysis and trend exploration.
Data Storytelling & Design – Designed a clean, executive-style layout for clear communication of sustainability performance and improvement opportunities.

Key Insights:
• Total CO₂ Emissions: 5M across all facilities
• Renewable Energy Contribution: 4,862% aggregate usage
• Water Use: Highest in Plant C (3M m³)
• Waste Recycled: 5,096% total recycled across regions
• Top ESG Performer: Japan and Canada lead in sustainability metrics

This project strengthened my expertise in Power BI, ESG analytics, and corporate sustainability reporting, enabling data-driven decisions for environmental impact reduction and responsible governance.
        </pre>
      </section>

      <div class="footer">
        <div class="meta">Author: <!-- add your name here --> • Updated: <!-- add date --> </div>
        <div style="font-size:13px;color:var(--muted)">License: MIT</div>
      </div>
    </div>
  </div>

  <script>
    function copyReadme(){
      const content = document.getElementById('readmeText').textContent.trim();
      if(!navigator.clipboard) {
        alert('Clipboard API not supported. Select and copy the text manually.');
        return;
      }
      navigator.clipboard.writeText(content).then(()=> {
        alert('README text copied to clipboard');
      }).catch(()=> alert('Unable to copy to clipboard'));
    }
  </script>
</body>
</html>
