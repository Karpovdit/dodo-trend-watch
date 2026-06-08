---
publish: true
title: "Building a Hyperlocal Dispatch Optimization Engine using Real Google Maps & Folium Data  🛵💨"
date: 2026-05-27
source_url: "https://www.linkedin.com/posts/gayathri-g-murali_predictive-hyperlocal-delivery-optimization-activity-7465368681716461568-JnAH?utm_source=combined_share_message&utm_medium=member_desktop&rcm=ACoAADyumqYBYLVH1eeuJYpnkGPGTON3r1TERRQ"
source_type: linkedin
author: "Gayathri G Murali"
author_url: "https://www.linkedin.com/in/gayathri-g-murali?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAAGRYBfIBC65zD6JmGKI_9_ciil_TlXyPnYQ"
author_headline: "​AI & ML Engineer | GenAI & NLP | Geospatial AI | Agentic Workflows | Designing Intelligent & Scalable Pipelines"
likes: 8
comments: 2
shares: 0
tags: [author-person, delivery, forecasting, int, linkedin, supply-chain]
---
> 🔗 [LinkedIn пост](https://www.linkedin.com/posts/gayathri-g-murali_predictive-hyperlocal-delivery-optimization-activity-7465368681716461568-JnAH?utm_source=combined_share_message&utm_medium=member_desktop&rcm=ACoAADyumqYBYLVH1eeuJYpnkGPGTON3r1TERRQ) · **Gayathri G Murali** · ​AI & ML Engineer | GenAI & NLP | Geospatial AI | Agentic Workflows | Designing Intelligent & Scalable Pipelines · 2026-05-27 · 👍 8 · 💬 2 · 🔁 0

🚀 Building a Hyperlocal Dispatch Optimization Engine using Real Google Maps & Folium Data  🛵💨

Hyperlocal delivery logistics are all about fighting against time and spatial constraints. To closely understand how quick-commerce giants manage multi-drop dispatches efficiently, I built an algorithmic Order Batching Optimization Engine mapped specifically for the Oachira grid in Kollam, Kerala — a region I know inside out.

Instead of relying on synthetic coordinates, I extracted real-world location data directly from Google Maps to make this simulation as close to reality as possible.

📌 The Real-World Bottleneck:

The standard "one-rider-per-order" dispatch model creates a massive operational overhead. When multiple riders traverse overlapping paths from the same restaurant hubs to nearby drop locations, it leads to sub-optimal fleet utilization, increased driver fatigue, and unnecessary fuel burn.

🛠️ Architecture & Engineering:

Geospatial Hotspot Mapping: Ingested real-world coordinate data for 10 accurate food hotspots inside Oachira (extracted via Google Maps) and simulated concurrent, real-time demand loops for 5 active customer delivery slots.

Spatial Routing Engine: Implemented the Haversine Formula to compute precise geodesic point-to-point distances over the dynamic grid to forecast realistic ETAs based on local speed constraints.

Dynamic Batching Heuristic: Built a greedy clustering mechanism with a 1.5 km proximity constraint to dynamically pool concurrent orders…

