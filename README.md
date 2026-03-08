<div align="center">

# 🧠 System Design Lab

### The most comprehensive interactive System Design learning platform on the web

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org)
[![License](https://img.shields.io/badge/License-Copyright%20%C2%A9%202026-red?style=for-the-badge)](https://www.linkedin.com/in/thesumitsuman/)

<br/>

**Created by [Sumit Suman](https://www.linkedin.com/in/thesumitsuman/)**

*From OOP basics to distributed systems — all in one interactive file.*

---

![System Design Lab Preview](https://img.shields.io/badge/Status-Live%20%26%20Published-brightgreen?style=flat-square)
![Size](https://img.shields.io/badge/Single%20File-467KB-blue?style=flat-square)
![Sections](https://img.shields.io/badge/Sections-25-cyan?style=flat-square)
![No Framework](https://img.shields.io/badge/Framework-None%20(Vanilla%20JS)-orange?style=flat-square)

</div>

---

## 📋 Table of Contents

- [Overview](#overview)
- [Why This Exists](#why-this-exists)
- [Features at a Glance](#features-at-a-glance)
- [All 25 Sections](#all-25-sections)
- [Learning Paths](#learning-paths)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Architecture Decisions](#architecture-decisions)
- [Security & Copyright](#security--copyright)
- [Author](#author)

---

## Overview

**System Design Lab** is a single-file (`index.html`) interactive learning platform designed to take engineers from Object-Oriented Programming fundamentals all the way through distributed systems, FAANG interview preparation, and large-scale architecture design.

No frameworks. No backend. No build step. Just open the file and start learning.

It combines **25 interactive sections** — including live simulations, 3D visualizations, a chaos engineering lab, a mock interview coach, a drag-and-drop architecture builder, a real-time global traffic map, and a full learning path curriculum — into one cohesive, visually polished platform.

---

## Why This Exists

Every existing system design resource has a critical gap:

| Resource | Gap |
|---|---|
| YouTube videos | Passive watching, zero interactivity |
| Books (DDIA, etc.) | Great depth, no hands-on |
| Paid courses | Expensive, still mostly passive |
| GitHub repos | Text-heavy, no visualization |
| Interview prep sites | Shallow, question-driven not concept-driven |

**System Design Lab** fills all of these gaps simultaneously — deep theory, live simulations, visual learning, interview practice, and a structured curriculum — all in one place, completely free to use.

---

## Features at a Glance

| Category | What You Get |
|---|---|
| 🎓 **Learning** | Structured 4-track curriculum with 24 modules, quizzes, and outcomes |
| 💻 **LLD** | OOP deep-dives, all 23 GoF patterns with code, SOLID with diagrams |
| 🏗️ **HLD** | Architecture patterns, scalability, CAP theorem, NFRs |
| ⚡ **Simulations** | Real-time traffic simulator, chaos engineering lab, CAP playground |
| 🌍 **Global Map** | Canvas-based live world map with 14 AWS regions, CDN/failover modes |
| 🎮 **Gamification** | Distributed systems survival game with scoring |
| 🤖 **AI Architecture** | Template-based architecture generator for 8 major systems |
| 📊 **Analytics** | Latency heatmap, scalability analysis, capacity calculator |
| 💰 **Cost Estimator** | AWS cost estimation with 8 line items and doughnut chart |
| 🎯 **Interview Prep** | Mock interview coach with timer, checklists, and scoring |
| 🖊️ **Whiteboard** | Excalidraw-style canvas for free-form design |
| 🔷 **3D Viz** | Three.js 3D architecture visualization |
| 🔒 **Security** | Copyright-protected, obfuscated, watermarked source code |

---

## All 25 Sections

### 🏠 Home
Animated particle canvas with live request journey visualization and feature discovery cards.

---

### 📚 LLD Fundamentals
**`section-lld-basics`**

Deep-dive into Object-Oriented Programming with tabbed navigation:
- **Encapsulation** — private state, public interface, access modifiers
- **Abstraction** — hiding complexity, abstract classes, interfaces
- **Inheritance** — class hierarchies, method overriding, super calls
- **Polymorphism** — runtime dispatch, method overloading
- **UML Diagrams** — class relationships (inheritance, composition, aggregation, association, dependency), sequence diagrams, use case diagrams

Each concept includes animated SVG diagrams and production-quality code examples.

---

### 🧱 SOLID Principles
**`section-solid`**

All five SOLID principles with violation → correct code transformation:

| Principle | What It Means |
|---|---|
| **S** — Single Responsibility | One class, one reason to change |
| **O** — Open/Closed | Open for extension, closed for modification |
| **L** — Liskov Substitution | Subtypes must be substitutable for base types |
| **I** — Interface Segregation | Clients shouldn't depend on unused interfaces |
| **D** — Dependency Inversion | Depend on abstractions, not concretions |

Each principle includes a side-by-side "Bad Code → Good Code" comparison with animated diagrams.

---

### 🎨 Design Patterns (All 23 GoF)
**`section-patterns`**

Complete coverage of all 23 Gang of Four patterns, filterable by category:

**Creational (5)** — Singleton, Factory Method, Abstract Factory, Builder, Prototype  
**Structural (7)** — Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy  
**Behavioral (11)** — Chain of Responsibility, Command, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, Visitor, Interpreter

Each pattern includes: intent, when to use, UML diagram, and production code example.

---

### ⚙️ Advanced LLD
**`section-lld-adv`**

- **Concurrency** — Threads, race conditions, mutex, semaphores, deadlock prevention
- **Database Design** — Normalization, indexing strategies, schema design
- **API Design** — REST principles, versioning, error handling, rate limiting
- **Error Handling** — Exception hierarchies, retry logic, circuit breaker

---

### 🏛️ High-Level Design (HLD)
**`section-hld`**

- **Architecture Patterns** — Monolith vs Microservices, Layered, Event-Driven, CQRS, Hexagonal
- **Scalability & NFRs** — Latency, throughput, availability, partition tolerance, SLAs
- **CAP Theorem** — Interactive slider, real-world database classification
- **Architecture Examples** — Netflix, Amazon, Twitter, Uber reference architectures

---

### 🔧 Infrastructure Components
**`section-infra`**

- **Load Balancers** — L4 vs L7, Round Robin, Least Connections, IP Hash, sticky sessions
- **Caching** — Redis, Memcached, CDN, browser cache, cache invalidation strategies
- **CDN** — Edge nodes, cache-control, origin pull, push CDN
- **Message Queues** — Kafka, RabbitMQ, SQS comparison with use-case guide
- **Circuit Breaker** — State machine, Hystrix configuration, fallback patterns

---

### 🌐 Distributed Systems
**`section-distributed`**

- **Sharding** — Range, hash, directory-based; consistent hashing with virtual nodes
- **Replication** — Synchronous vs async, master-slave, multi-master
- **Consistency Models** — Strong, eventual, causal, read-your-writes, linearizability
- **Leader Election** — Raft algorithm, ZooKeeper ephemeral nodes
- **Observability** — Metrics, logs, traces; RED method; SLIs/SLOs/SLAs

---

### 🛝 System Playground
**`section-playground`**

Step-by-step architecture walkthroughs for 5 real systems:
- URL Shortener
- Twitter Feed
- Netflix Streaming
- Uber Ride-Sharing
- WhatsApp Messaging

Each system walks through 6–8 architectural steps with animated canvas diagrams.

---

### 🔷 3D Architecture Lab
**`section-lab3d`**

Three.js 3D visualizations of 4 pre-built architectures rendered in real-time:
- Microservices mesh
- CDN distribution network
- Database sharding cluster
- Event-driven pipeline

Interactive camera controls (orbit, zoom, pan).

---

### ⚡ Live Simulator
**`section-simulator`**

4 simulation modes on an animated canvas:
- **Normal Load** — baseline request flow
- **Traffic Spike** — sudden surge with autoscaling
- **Node Failure** — failover and recovery
- **Cache Miss Storm** — thundering herd scenario

---

### 🎯 Interview Wizard
**`section-interview`**

7-step structured interview framework:
1. Requirements gathering
2. Scale estimation
3. API design
4. Data model
5. Core architecture
6. Deep-dive
7. Evaluation

Guided prompts at each step with evaluation rubric.

---

### 🧰 Architecture Builder
**`section-builder`**

Drag-and-drop canvas builder with:
- 12+ component types (Client, CDN, Load Balancer, API Gateway, Service, Database, Cache, Queue, Storage, Worker, Monitoring)
- Connection drawing between components
- AI Advisor panel with architecture recommendations
- Export to PNG

---

### 📖 Question Bank
**`section-qbank`**

8 FAANG-style system design questions with animated solutions:
- Design Twitter (news feed, fanout)
- Design Netflix (streaming, CDN)
- Design Uber (geospatial, real-time)
- Design WhatsApp (messaging, presence)
- Design URL Shortener (base62, caching)
- Design Google Search (crawling, indexing)
- Design Dropbox (sync, conflict resolution)
- Design Distributed Rate Limiter

Each question includes: approach steps, component diagram, key decisions, tradeoffs.

---

### 🎮 Game Mode: Distributed Systems Survival
**`section-gamemode`**

An event-driven survival game where you respond to:
- Traffic spikes
- Node failures
- Database corruption
- Network partitions
- Cache evictions

Score points for correct architectural responses. Survival time determines your tier.

---

### 🖊️ Whiteboard
**`section-whiteboard`**

Excalidraw-inspired freeform canvas with:
- Pen, shape, text, connector tools
- Pre-built component stamps (servers, databases, clouds, users, load balancers)
- Undo/redo, color picker, stroke sizes
- Export to PNG

---

### 📊 Performance Analyzer
**`section-perf`**

- **Latency Heatmap** — Interactive cache/load parameter sliders with color-coded heat map
- **Scalability Analysis** — Animated bar chart comparing architectural approaches
- **Capacity Calculator** — Input DAU, request rate, data size → server/storage/bandwidth estimates

---

### 🤖 AI Architecture Generator
**`section-aiarch`**

Type any system description (or pick a quick-chip) and get:
- Component breakdown with type badges and descriptions
- Architecture diagram with connection flow
- Back-of-envelope numbers (QPS, storage, bandwidth)
- Key tradeoffs and scaling considerations

Pre-built templates for: YouTube, WhatsApp, URL Shortener, Twitter, Netflix, Uber, Redis Cluster, Google Search.

---

### 🚦 Real-Time Traffic Simulator
**`section-traffic`**

- Logarithmic RPS slider: 100 → 10,000,000 RPS
- 3 architecture modes: Basic, Full Stack, Microservices
- Live HUD: requests/sec, p99 latency, error rate, throughput
- Animated particle flow through nodes with load ring visualization
- Bottleneck detection alerts
- Rolling Chart.js line chart

---

### 💥 Chaos Engineering Lab
**`section-chaos`**

Inject real failure scenarios and observe system behavior:

**Failures:** Server Crash, DB Failure, Network Partition, High Latency, Cache Eviction, CPU Spike  
**Mitigations:** DB Replica, Redis Cache, Circuit Breaker, Message Queue, Multi-AZ Deploy

Live resilience score (0–100%) with timestamped event log.

---

### 🔺 CAP Theorem Playground
**`section-caplab`**

Interactive canvas triangle showing real database positions:
- **AP systems**: Cassandra, Redis, DynamoDB
- **CP systems**: MongoDB, ZooKeeper
- **CA systems**: PostgreSQL

Simulate network partition → see how each system responds. PACELC tradeoff visualization.

---

### 🌍 Global Traffic Map
**`section-worldmap`**

Canvas-based real-time world map with:
- **14 AWS region data centers** with accurate coordinates and latency data
- **16 major city clusters** with population-scaled markers
- **4 simulation modes**: CDN Routing, Region Failover, Latency Heatmap, Live Traffic
- Animated request packets along curved arc paths
- Color-coded latency heatmap (green <30ms, amber 30-70ms, red >70ms)
- Live request counter and metrics HUD

---

### 💰 Infrastructure Cost Estimator
**`section-costs`**

Input your scale parameters → get AWS cost breakdown:

**Inputs:** DAU, Requests/user/day, Response size (KB), Storage/user (MB), Cache hit ratio, Regions  
**Outputs:** EC2, RDS, ElastiCache, S3, Data Transfer, Load Balancer, CloudFront, Support

Doughnut chart visualization + optimization recommendations.

---

### 🎓 Mock Interview Coach
**`section-mockinterview`**

3 difficulty tiers with real interview questions:

| Tier | Time | Questions |
|---|---|---|
| Junior | 30 min | URL Shortener, Parking Lot |
| Senior | 45 min | Twitter, Kafka |
| Staff/Principal | 60 min | Google Drive, Spanner, Collaborative Editor |

Per-question checklists (7–9 FAANG criteria), countdown timer (amber <5min, red <2min), and final scoring: **Strong Hire / Hire / Borderline / No Hire**.

---

### 📍 Learning Path
**`section-learning`**

4 structured tracks from beginner to expert:

#### 🟢 Beginner Track (OOP + LLD Fundamentals)
1. Object-Oriented Programming
2. SOLID Principles
3. Design Patterns (GoF)
4. UML Diagrams
5. LLD Practice: Library System
6. LLD Practice: Parking Lot

#### 🔵 Intermediate Track (System Design Fundamentals)
1. HLD Fundamentals
2. Scalability Patterns
3. Infrastructure Components
4. Database Design at Scale
5. Back-of-Envelope Estimation
6. Design: URL Shortener

#### 🟠 Advanced Track (Distributed Systems)
1. Distributed Systems Fundamentals
2. Consensus & Leader Election
3. Sharding & Replication
4. Chaos Engineering
5. Design: WhatsApp / Chat System
6. Design: Twitter / Social Feed

#### 🟣 Expert Track (Large-Scale Architecture)
1. Global Scale Architecture
2. Database Internals
3. Stream Processing
4. Distributed Transactions
5. Staff-Level System Design
6. Capstone: Design a Payment System

Each module includes estimated time, 4 detailed subtopics, outcome statement, a quiz question, and a direct link to the relevant platform section.

---

## Tech Stack

| Technology | Version | Usage |
|---|---|---|
| HTML5 | — | Structure, semantic markup |
| CSS3 | — | Custom properties, glassmorphism, animations |
| Vanilla JavaScript | ES2020 | All interactivity, simulations, state management |
| Three.js | r128 | 3D architecture visualizations |
| Chart.js | 4.4.0 | Line charts, doughnut charts |
| D3.js | v7.9.0 | Data visualizations |
| Google Fonts | — | Poppins, Inter, JetBrains Mono |

**No React. No Vue. No Angular. No build tools. No Node.js. No backend.**

Everything runs client-side in a single HTML file.

---

## Getting Started

### Option 1: Open Locally
```bash
# Download index.html
# Double-click to open in any modern browser
# That's it.
```

### Option 2: Host on GitHub Pages
```bash
# 1. Create a GitHub repository
# 2. Upload index.html to the root
# 3. Go to Settings → Pages → Deploy from branch → main / (root)
# 4. Your site is live at https://yourusername.github.io/repo-name
```

### Option 3: Host on Netlify / Vercel
```bash
# Drag and drop index.html to netlify.com/drop
# Live URL in 30 seconds
```

### Option 4: CDN / Self-Host
```bash
# Deploy to any static hosting (S3, CloudFront, nginx, Apache)
# No server-side processing required
```

### Browser Requirements
- Chrome 90+ ✅
- Firefox 88+ ✅
- Safari 14+ ✅
- Edge 90+ ✅

WebGL required for 3D Lab section (Three.js). All other sections work without WebGL.

---

## Architecture Decisions

### Why a Single File?
The decision to build everything in one `index.html` was deliberate:

1. **Zero deployment friction** — anyone can open it locally or host it with a CDN URL
2. **No dependency hell** — no `npm install`, no build pipeline failures
3. **Offline capable** — works without internet (fonts/CDN degrade gracefully)
4. **Shareable** — email the file, host it, fork it — no setup required
5. **Inspectable** — while the JS is obfuscated, the HTML structure is learnable itself

### Why Vanilla JS?
- No framework overhead (~0KB of framework code)
- No version churn or breaking changes
- Forces clean imperative thinking — matching how system design itself works
- Faster initial load, no hydration delay

### Lazy Rendering
Each of the 25 sections is rendered on demand via `showSection(id)`. This means:
- Initial page load is fast (only home section rendered)
- Canvas simulations only start when you navigate to them
- Animation loops are paused when you leave a section
- Memory footprint stays low despite 25 interactive sections

### Canvas vs SVG for Simulations
All real-time simulations (Traffic, Chaos, World Map, Simulator) use `<canvas>` rather than SVG for:
- 60fps animation without DOM reflow
- Thousands of particles without performance degradation
- Complex gradient and path operations at scale
- Single draw call per frame

---
---

## Security & Copyright

This project is **copyright protected**.

```
Copyright © 2026 Sumit Suman. All Rights Reserved.

This project and its source code are protected by copyright law.
Unauthorized copying, redistribution, modification, or resale
of this software is strictly prohibited without written permission.
```

---


## 📄 License

Copyright © 2026 Sumit Suman. All Rights Reserved.

This project is **not open source** and is not distributed under any open-source license.

### What You Can Do ✅
- Use the live platform at [sumit6258.github.io/System-Design](https://sumit6258.github.io/System-Design/) freely for personal learning
- Share the link with others who want to learn system design
- Reference this project in your portfolio, resume, or blog posts (with attribution)
- Star and fork the repository for personal reference

### What You Cannot Do ❌
- Copy, reproduce, or redistribute the source code (in whole or in part)
- Modify the source code and publish it as your own work
- Use this project or its contents commercially without written permission
- Remove or alter copyright notices, watermarks, or authorship signatures
- Republish this project under a different name or on a different platform

### Attribution
If you reference this project in any public content (articles, videos, courses, talks),
you must clearly credit **Sumit Suman** and link to the original:
> [https://sumit6258.github.io/System-Design/](https://sumit6258.github.io/System-Design/)

### Contact
For licensing inquiries, collaborations, or permissions beyond the above:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sumit%20Suman-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thesumitsuman/)

---

> *The source code of this project is legally protected under copyright law.*
> *Authorship is cryptographically embedded in the code via SHA-256 signature.*

## Author

<div align="center">

**Sumit Suman**

Software Engineer | System Design Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thesumitsuman/)

*Built with ❤️ to make system design accessible to every engineer.*

---

> *"The best way to learn distributed systems is to build them — or at least simulate breaking them."*

</div>

---

<div align="center">

**System Design Lab** — © 2026 Sumit Suman

*Star ⭐ this project if it helped you land that offer.*

</div>