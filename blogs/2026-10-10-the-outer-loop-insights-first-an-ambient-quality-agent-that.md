---
title: "The Outer Loop, Insights First: An Ambient Quality Agent That Diagnoses Your Production Agent"
url: "https://developers.googleblog.com/the-outer-loop-insights-first-an-ambient-quality-agent-that-diagnoses-your-production-agent/"
date: "2026-10-10"
feed_url: "https://developers.googleblog.com/feeds/posts/default"
---
How do you keep improving an AI agent after the first 80%, once it serves real production traffic and silent quality regressions return HTTP 200 OK? We are open-sourcing AQuA (Ambient Quality Agent), a reference implementation that runs beside your production agent in Google Cloud, sweeps and verifies failure clusters against conversation transcripts, and diagnoses root causes anchored to the exact deployed source snapshot.
