<a href="https://idraakk.github.io/Portfolio_Website/"><img align="right" width="148" src="https://idraakk.github.io/Portfolio_Website/portfolio-character.png" alt="Portrait from Idraak’s portfolio"></a>

# Idraak Mohd Khan

**Software Engineer · Backend, AWS & Agentic AI**

I build Java backend services on AWS and AI tools that retrieve information and take action.

**Based in India · Open to Software Engineer / SDE I opportunities**

[<kbd>Open portfolio ↗</kbd>](https://idraakk.github.io/Portfolio_Website/) &nbsp; [Résumé](https://idraakk.github.io/Portfolio_Website/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/idraak) · [Email](mailto:idraakmk@gmail.com)

[`products.md`](#products) · [`projects.tsx`](#projects) · [`experience.json`](#experience) · [`skills.ts`](#skills) · [`education.yml`](#education)

<br clear="right">

## Products

### MicroGram · Android

MicroGram turns YouTube videos and playlists into swipeable learning reels. Choose a reel length, save frames and notes, and pick up where you left off. The app also tracks your daily goal and progress by lecture.

<p>
  <a href="https://idraakk.github.io/Microgram_Preview_Web/">
    <img width="104" src="https://idraakk.github.io/Portfolio_Website/microgram-lecture-profile.webp" alt="Lecture overview with watch progress and reel tiles">
    <img width="104" src="https://idraakk.github.io/Portfolio_Website/microgram-library.webp" alt="MicroGram library showing imported videos and playlists">
    <img width="104" src="https://idraakk.github.io/Portfolio_Website/microgram-reel.webp" alt="Lecture playing in MicroGram’s full-screen reel player">
  </a>
</p>

**[Get the Android app](https://idraakk.github.io/Idraak-Collection/microgram/index.html)** · [Try the browser demo](https://idraakk.github.io/Microgram_Preview_Web/) · [Explore Idraak’s Collection](https://idraakk.github.io/Idraak-Collection/)

## Projects

### Agentic Browser

An AI-powered browser extension that turns natural-language requests into browser actions. It uses DOM snapshots and screenshots to plan and execute nine action types, with step limits and execution feedback.

[<img width="640" src="https://idraakk.github.io/Portfolio_Website/agentic-browser.webp" alt="Illustration of Agentic Browser reading a trail guide to find the shortest route">](https://github.com/idraakk/Agentic_Browser)

[Source code](https://github.com/idraakk/Agentic_Browser) · **Jul–Sep 2026**

<details>
<summary>Architecture</summary>

- **Browser extension** uses React and TypeScript to surface the plan, actions, and results.
- **Orchestration** uses LangGraph for ReAct and multi-agent workflows, with live server-sent events.
- **Backend** uses Python and FastAPI, supports six LLM providers, and stores vector-searchable memory in PostgreSQL. An MCP server exposes browser capabilities to external coding agents.

</details>

### RustNet

I built a small, fully connected neural network from scratch in Rust for binary classification, with Python bindings via PyO3 and maturin. The code includes forward and backward passes, training examples, and JSON model persistence. [Source code](https://github.com/idraakk/RustNet_library)

## Experience

### Amazon · Software Development Engineering Intern

**Jan–Jun 2026 · Bengaluru, India**

I modernized a production backend-for-frontend, rebuilt Java APIs for vendor marketplace expansion, and built configuration workflows with Amazon Bedrock.

<details>
<summary>Selected work at Amazon</summary>

**Selection & Growth Hub**

- Designed AWS AppSync GraphQL schemas, data sources, and resolvers to replace a Spring Boot backend-for-frontend.
- Moved configuration to offline artifacts for local browser reads, removing a three-hop runtime lookup. Rolled out the new gateway to 100% of production traffic and retired the legacy ECS-backed pipeline.

**Marketplace Expansion Service**

- Rebuilt marketplace status and vendor expansion APIs in Java. Used DynamoDB `BatchGetItem` with retries for unprocessed keys, replacing individual marketplace lookups.
- Added batched SQS FIFO publishing, conditional writes, and idempotent request handling to prevent duplicate submissions and support per-marketplace retries.
- Provisioned API Gateway, VPC Link, a Network Load Balancer, and ECS Fargate with AWS CDK. Moved from seven legacy hosts to a three-task baseline and added CloudWatch monitoring, integration tests, and automated rollback safeguards.

**Agentic Configuration Management Platform**

- Built a ticket-triggered Bedrock agent that uses tool calling and business rules to identify and validate configuration changes and open code reviews.
- Built onboarding that generates location-specific configurations and code reviews, with merge-conflict resolution for a system managing 3,000+ attributes across hundreds of locations.

</details>

### Code Gain Technologies Pvt. Ltd. · AI Engineering Intern

**Jul–Dec 2025 · Remote**

I built a study assistant for YouTube videos and uploaded lectures. It made lectures searchable and generated answers, summaries, and quizzes.

<details>
<summary>Lecture assistant architecture</summary>

- Built the product with FastAPI, React, TypeScript, and PostgreSQL.
- Combined lexical and embedding-based retrieval. Ranked results using Jaccard and cosine similarity.
- Integrated configurable LLM providers with server-sent event streaming, fallback models, and retries for rate limits and transient failures.

</details>

## Skills

| Area | Tools and concepts |
| --- | --- |
| Languages | Java, Python, JavaScript |
| Backend and data | Spring Boot, FastAPI, REST, GraphQL, microservices, PostgreSQL, DynamoDB, SQL |
| AI and retrieval | LLMs, RAG, LangChain, LangGraph, MCP, AI agents, tool calling, hybrid retrieval |
| AWS | AppSync, API Gateway, VPC, Network Load Balancer, ECS Fargate, SQS, IAM, CDK, CloudWatch, infrastructure as code |
| Frontend | React, TypeScript |
| Engineering fundamentals | Data structures and algorithms, OOP, SOLID, DBMS, distributed systems |
| Testing and delivery | JUnit, integration testing, end-to-end testing, Git, GitHub, CI/CD |

## Education

- **Jaypee Institute of Information Technology, Noida** · B.Tech. in Electronics and Communication Engineering · 2022–2026
- **Indian Institute of Technology Madras** · BS Foundation Program in Data Science and Programming · 2023–2024

**Competitive programming** · [Codeforces Expert (1716)](https://codeforces.com/profile/Zaxas) · [LeetCode](https://leetcode.com/u/aaron1april/)

[Open the full portfolio ↗](https://idraakk.github.io/Portfolio_Website/)
