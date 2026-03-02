---
title: "Banking Customer Analytics (SQL Server + Python + Power BI)"
collection: portfolio
permalink: /portfolio/banking-case-study/
date: 2026-03-02
excerpt: "End-to-end mini project: SQL Server → Power BI dashboard + Python EDA (segmentation, correlations, plots)."
thumbnail: /images/projects/banking-case-study.jpg
github_url: https://github.com/pratishthaa/Banking-Case-Study
readme_raw_url: https://raw.githubusercontent.com/pratishthaa/Banking-Case-Study/main/README.md
tech_stack:
  - SQL Server
  - Python
  - Power BI
---

End-to-end project connecting SQL Server to Power BI and running Python EDA on the same dataset. :contentReference[oaicite:3]{index=3}

**Tech stack:** SQL Server, Python (Jupyter), Power BI. :contentReference[oaicite:4]{index=4}

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
