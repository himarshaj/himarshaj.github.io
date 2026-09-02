---
title: "Analyzing Unnecessary Traffic In Web Archives"
collection: projects
permalink: /projects/unnecessary-traffic-web-archives
years: "2022"
date: 2022-12-01
---

Archived web pages can generate repeated, invisible HTTP requests, creating unnecessary traffic and potentially overwhelming web archive servers. Pages requiring frequent updates, such as sports scores or playlists, were especially likely to cause this problem, particularly when missing resources produce repeated 404 errors. We proposed to use Cache-Control headers to cache 404 responses, preventing unnecessary requests from reaching the archive server. Our results showed that this approach can reduce wasted network and computational resources during archival replay.
