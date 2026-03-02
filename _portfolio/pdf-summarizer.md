---
title: "PDF Summarizer (RAG-based Document Q&A)"
collection: portfolio
permalink: /portfolio/pdf-summarizer/
date: 2026-03-02
excerpt: "PDF summarization + Q&A app using retrieval (RAG). Streamlit UI, FastAPI backend, Qdrant vector store."
thumbnail: /images/projects/pdf-summarizer.jpg
github_url: https://github.com/pratishthaa/PDF-Summarizer
readme_raw_url: https://raw.githubusercontent.com/pratishthaa/PDF-Summarizer/main/README.md
tech_stack:
  - Streamlit
  - FastAPI
  - Qdrant
  - OpenAI API
  - LlamaIndex
---

**Tech stack:** Streamlit, FastAPI, Qdrant, OpenAI API, LlamaIndex. :contentReference[oaicite:0]{index=0}

**GitHub:** <a href="{{ page.github_url }}" target="_blank" rel="noopener">View repository</a>

## README (auto-loaded)
<div id="readme" style="margin-top: 1rem;">Loading README…</div>

<!-- Markdown renderer -->
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
