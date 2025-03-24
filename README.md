# system-design-problem


## Problem Statement

You are tasked with designing the **frontend architecture and data layer** for an **admin dashboard** used by major media clients (e.g. Netflix, NBCUniversal). Our company provides an API that makes videos **shoppable** by linking real-life products to video content. We **don’t store the full videos** — only metadata and processed insights related to video segments, product tags, and performance. This dashboard will allow media clients to:
1. **View their catalog of processed videos** (title, episode, season, thumbnail, publish status, etc.).
2. **See business metrics** tied to those videos, including:
    - Best-selling product in a given video or show
    - Revenue generated per video, season, or product
    - Click-through rates and conversion metrics
3. **Search, filter, and sort** by product, video, or performance


### **Clarifications**
- ***You should define your own approach to data storage and querying.** (Relational? OLAP? Indexing strategy? etc.)*
- **You may assume authentication is handled**.
- You should focus on **frontend structure, UX considerations, and interaction with data** (how/when it’s queried, performance, visualizations, etc.)
