---
title: "E-Commerce Delivery Analysis (Excel → SQL → Python → Power BI)"
collection: portfolio
permalink: /portfolio/ecommerce-analysis/
date: 2026-03-02
excerpt: "End-to-end delivery performance analysis: Excel checks, SQL analytics layer, Python EDA/modeling, Power BI dashboard."
thumbnail: /images/projects/ecommerce-analysis.jpg
github_url: https://github.com/pratishthaa/ECommerce_Analysis
readme_raw_url: https://raw.githubusercontent.com/pratishthaa/ECommerce_Analysis/main/README.md
tech_stack:
  - Excel
  - SQL Server
  - Python
  - Power BI
---

This project is an end-to-end analytics case study on e-commerce order delivery performance. :contentReference[oaicite:1]{index=1}

**Tech stack:** Excel, SQL Server, Python, Power BI. :contentReference[oaicite:2]{index=2}

**GitHub:** <a href="{{ page.github_url }}" target="_blank" rel="noopener">View repository</a>

## README (auto-loaded)
<div id="readme" style="margin-top: 1rem;">Loading README…</div>

<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
<script>
(async function () {
  try {
    const url = "{{ page.readme_raw_url }}";
    const res = await fetch(url);
    if (!res.ok) throw new Error("Failed to load README");
    const md = await res.text();
    document.getElementById("readme").innerHTML = marked.parse(md);
  } catch (e) {
    document.getElementById("readme").innerHTML =
      "Could not load README right now. Please use the GitHub link above.";
  }
})();
</script>
