<div align="center">

# 🧠 System Design Lab

### The most comprehensive interactive System Design learning platform on the web

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org)
[![Version](https://img.shields.io/badge/Version-v5.1.0-brightgreen?style=for-the-badge)](https://github.com/sumit6258/System-Design/releases)
[![License](https://img.shields.io/badge/License-Copyright%20%C2%A9%202026-red?style=for-the-badge)](https://www.linkedin.com/in/thesumitsuman/)

<br/>

**Created by [Sumit Suman](https://www.linkedin.com/in/thesumitsuman/)**

*From OOP basics to distributed systems - all in one interactive file.*

---

![System Design Lab Preview](https://img.shields.io/badge/Status-Live%20%26%20Published-brightgreen?style=flat-square)
![Size](https://img.shields.io/badge/Single%20File-503KB-blue?style=flat-square)
![Sections](https://img.shields.io/badge/Sections-25-cyan?style=flat-square)
![No Framework](https://img.shields.io/badge/Framework-None%20(Vanilla%20JS)-orange?style=flat-square)
![Game Levels](https://img.shields.io/badge/Game%20Levels-10-purple?style=flat-square)

</div>

---

## 📋 Table of Contents

- [What's New in v5.1.0](#whats-new-in-v510)
- [Overview](#overview)
- [Why This Exists](#why-this-exists)
- [Features at a Glance](#features-at-a-glance)
- [All 25 Sections](#all-25-sections)
- [🎮 System Architect Survival - Deep Dive](#-system-architect-survival--deep-dive)
- [Learning Paths](#learning-paths)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Architecture Decisions](#architecture-decisions)
- [Security & Copyright](#security--copyright)
- [Author](#author)

---

## 🆕 What's New in v5.1.0

> **Released: April 2026**

### 🎮 Game Mode: Complete Rebuild → *System Architect Survival*

The old game mode has been fully replaced with **System Architect Survival** - a 10-level progressive incident management game that teaches distributed systems through real production failure scenarios.

| | v5.0.0 (Old) | v5.1.0 (New) |
|---|---|---|
| Levels | 1 (endless) | 10 progressive levels |
| Failure types | 4 generic events | 10 named, realistic failures |
| Components | 5 actions | 7 deployable components |
| Difficulty modes | None | Easy / Normal / Hard / Chaos |
| HUD | 4 stats | 6 stats + level timer |
| Canvas | Basic nodes | Full layer architecture with HP rings, load rings, glow effects, particles |
| Concepts taught | Vague | Named real patterns (Cache-Aside, Circuit Breaker, Consistent Hashing, etc.) |
| Real-world context | None | Each level cites a real production incident (GitHub, Twitter, AWS, Slack…) |
| Panels | None | Node Inspector + Level Challenge + Active Incidents + Achievements |
| Achievements | None | 5 unlockable achievements |

**Everything else in the platform is untouched.** All 24 other sections, all JS functions, all CSS, and the learning content are byte-for-byte identical to v5.0.0.

---

## Overview

**System Design Lab** is a single-file (`index.html`) interactive learning platform designed to take engineers from Object-Oriented Programming fundamentals all the way through distributed systems, FAANG interview preparation, and large-scale architecture design.

No frameworks. No backend. No build step. Just open the file and start learning.

It combines **25 interactive sections** - including live simulations, 3D visualizations, a chaos engineering lab, a mock interview coach, a drag-and-drop architecture builder, a real-time global traffic map, a full learning path curriculum, and now a 10-level distributed systems survival game - into one cohesive, visually polished platform.

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

**System Design Lab** fills all of these gaps simultaneously - deep theory, live simulations, visual learning, interview practice, and a structured curriculum - all in one place, completely free to use.

---

## Features at a Glance

| Category | What You Get |
|---|---|
| 🎓 **Learning** | Structured 4-track curriculum with 24 modules, quizzes, and outcomes |
| 💻 **LLD** | OOP deep-dives, all 23 GoF patterns with code, SOLID with diagrams |
| 🏗️ **HLD** | Architecture patterns, scalability, CAP theorem, NFRs |
| ⚡ **Simulations** | Real-time traffic simulator, chaos engineering lab, CAP playground |
| 🌍 **Global Map** | Canvas-based live world map with 14 AWS regions, CDN/failover modes |
| 🎮 **Game** | **[NEW v5.1.0]** 10-level distributed systems survival game with 4 difficulty modes |
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
- **Encapsulation** - private state, public interface, access modifiers
- **Abstraction** - hiding complexity, abstract classes, interfaces
- **Inheritance** - class hierarchies, method overriding, super calls
- **Polymorphism** - runtime dispatch, method overloading
- **UML Diagrams** - class relationships (inheritance, composition, aggregation, association, dependency)

Each concept includes animated SVG diagrams and production-quality code examples.

---

### 🧱 SOLID Principles
**`section-solid`**

All five SOLID principles with violation → correct code transformation, side-by-side comparison, and animated diagrams.

---

### 🎨 Design Patterns (All 23 GoF)
**`section-patterns`**

Complete coverage of all 23 Gang of Four patterns, filterable by category:

**Creational (5)** - Singleton, Factory Method, Abstract Factory, Builder, Prototype  
**Structural (7)** - Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy  
**Behavioral (11)** - Chain of Responsibility, Command, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, Visitor, Interpreter

---

### 🏛️ High-Level Design (HLD)
**`section-hld`**

- Architecture Patterns - Monolith vs Microservices, Layered, Event-Driven, CQRS
- Scalability & NFRs - Latency, throughput, availability, partition tolerance, SLAs
- CAP Theorem - Interactive slider, real-world database classification
- Architecture Examples - Netflix, Amazon, Twitter, Uber reference architectures

---

### 🔧 Infrastructure Components
**`section-infra`**

Load Balancers, Caching layers, CDN, Message Queues (Kafka/RabbitMQ/SQS), Circuit Breaker pattern.

---

### 🌐 Distributed Systems
**`section-distributed`**

Sharding, Replication, Consistency Models, Leader Election (Raft), Observability (metrics/logs/traces).

---

### 🛝 System Playground
**`section-playground`**

Step-by-step architecture walkthroughs for URL Shortener, Twitter, Netflix, Uber, WhatsApp.

---

### 🔷 3D Architecture Lab
**`section-lab3d`**

Three.js 3D visualizations of 4 pre-built architectures with interactive camera controls.

---

### ⚡ Live Simulator
**`section-simulator`**

4 simulation modes: Normal Load, Traffic Spike, Node Failure, Cache Miss Storm.

---

### 🎯 Interview Wizard
**`section-interview`**

7-step structured interview framework with guided prompts and evaluation rubric.

---

### 🧰 Architecture Builder
**`section-builder`**

Drag-and-drop canvas builder with 12+ component types, AI Advisor panel, export to PNG.

---

### 📖 Question Bank
**`section-qbank`**

8 FAANG-style questions: Twitter, Netflix, Uber, WhatsApp, URL Shortener, Google Search, Dropbox, Rate Limiter. Each includes animated component diagrams and step-by-step solutions.

---

### 🎮 Game Mode: System Architect Survival ⭐ NEW in v5.1.0
**`section-gamemode`**

See the [full section below](#-system-architect-survival--deep-dive) for complete documentation.

---

### 🖊️ Whiteboard
**`section-whiteboard`**

Excalidraw-inspired freeform canvas with pen, shape, text, connector tools, pre-built stamps, and PNG export.

---

### 📊 Performance Analyzer
**`section-perf`**

Latency Heatmap, Scalability Analysis, Capacity Calculator.

---

### 🤖 AI Architecture Generator
**`section-aiarch`**

Type any system → get component breakdown, architecture diagram, back-of-envelope numbers, and key tradeoffs. Pre-built for 8 major systems.

---

### 🚦 Real-Time Traffic Simulator
**`section-traffic`**

Logarithmic RPS slider (100 → 10M), 3 architecture modes, live HUD, animated particle flow, bottleneck detection.

---

### 💥 Chaos Engineering Lab
**`section-chaos`**

Inject Server Crash, DB Failure, Network Partition, High Latency, Cache Eviction, CPU Spike. Apply mitigations. Live resilience score.

---

### 🔺 CAP Theorem Playground
**`section-caplab`**

Interactive triangle. Simulate partitions. See Cassandra vs MongoDB vs ZooKeeper behavior in real time.

---

### 🌍 Global Traffic Map
**`section-worldmap`**

Canvas world map with 14 AWS regions, 16 city clusters, 4 simulation modes, animated arc packets, latency heatmap.

---

### 💰 Infrastructure Cost Estimator
**`section-costs`**

DAU + scale inputs → EC2, RDS, ElastiCache, S3, CDN cost breakdown with chart + recommendations.

---

### 🎓 Mock Interview Coach
**`section-mockinterview`**

Junior / Senior / Staff tiers, countdown timer, per-question checklists, Strong Hire / Hire / Borderline / No Hire scoring.

---

### 📍 Learning Path
**`section-learning`**

4 tracks (Beginner → Expert), 24 modules, quizzes, outcome statements, direct section links.

---

---

## 🎮 System Architect Survival - Deep Dive

> *"The only way to learn distributed systems is to watch them break - and fix them under pressure."*

### Concept

System Architect Survival is a 10-level progressive incident management game. You play as the on-call engineer for a distributed system. Traffic increases, failures cascade, and your budget is finite. Build the right architecture before time runs out.

Every level is modeled on a **real production incident** from a company you recognize.

---

### The 10 Levels

| # | Level Name | Challenge | Real-World Context |
|---|---|---|---|
| 1 | Boot Sequence | Learn the basics, watch packets flow | Every production system started here |
| 2 | First Blood | DB queries slowing, deploy Redis | Twitter 2008: DB overload forced emergency caching |
| 3 | Traffic Spike | 3× load incoming, scale your API fleet | Product Hunt launches: instant 3× spikes |
| 4 | Server Down | API server crashes, traffic must reroute | AWS EC2 hardware failures monthly per large fleet |
| 5 | Cache Storm | Cache eviction + DB pressure simultaneously | Reddit 2014: memcached failure → total DB storm |
| 6 | Split Brain | Network partition, CAP theorem in action | MongoDB 2019: partition caused split-brain + data loss |
| 7 | Under Siege | DDoS overwhelms CDN and LB | GitHub 2018: 1.35 Tbps DDoS, largest recorded |
| 8 | DB Roulette | Primary DB failure, failover in <30s | Slack 2019: MySQL failure → 3-hour outage |
| 9 | Cascade | 3 sequential failures, circuit breakers critical | AWS us-east-1 2021: cascading across 24 services |
| 10 | Black Friday | ALL failure types simultaneously | Amazon Black Friday: 4M req/sec, zero tolerance |

---

### Failure Events

| Event | Difficulty | Affected Nodes | What Happens | Concept Taught |
|---|---|---|---|---|
| 💥 Server Crash | ★★ | API Servers | OOM or hardware fault, traffic drops | Circuit Breaker stops cascades |
| 🗄 DB Primary Failure | ★★★ | Database | All writes fail, system degrades | Replication + automatic failover |
| ⏱ High Latency Spike | ★ | API, LB | Network congestion, queuing | Cache-Aside reduces latency 80%+ |
| 💸 Cache Eviction Storm | ★★ | Redis Cache | LRU eviction, DB load spikes | TTL tuning + memory headroom |
| 🔥 CPU Spike | ★★ | API Servers | 100% CPU, hot loop or bad query | Horizontal scaling distributes load |
| ⚡ DDoS Attack | ★★★★ | CDN, LB | Malicious flood at entry points | Rate limiting blocks at the edge |
| 🔀 Network Partition | ★★★ | Database | Nodes can't communicate | CAP: choose CP or AP |
| 🔬 Memory Leak | ★★ | API Servers | Slow accumulation, OOM incoming | Canary deploys catch leaks early |
| 🦬 Thundering Herd | ★★★ | Database | Cache expired, all servers hit DB cold | Jitter + mutex lock on cache refill |
| 💾 Disk Full | ★★ | Database | Writes returning errors | Data archival + tiered storage |

---

### Deployable Components

| Component | Cost | What It Does | Real-World Pattern |
|---|---|---|---|
| + API Server | $50 | Adds stateless compute capacity | Horizontal Scaling |
| + Redis Cache | $40 | ~90% read hit rate, protects DB | Cache-Aside Pattern |
| + Kafka Queue | $45 | Decouples write pressure, buffers spikes | Event-Driven Architecture |
| + DB Replica | $60 | Async copy, <30s failover | Leader-Follower Replication |
| + CDN Node | $30 | 200ms → 5ms globally, absorbs DDoS | Content Delivery Network |
| Circuit Breaker | $20 | Fails fast, stops cascade | Hystrix / Resilience4j |
| Rate Limiter | $25 | Throttles per IP, blocks floods | Token Bucket / Leaky Bucket |

---

### Difficulty Modes

| Mode | Starting Budget | Who It's For |
|---|---|---|
| ☕ Easy | $2,000 | First time? Learn the mechanics |
| ⚡ Normal | $1,000 | Default. Balanced challenge |
| 💀 Hard | $500 | You've done Normal twice |
| 🔥 Chaos | $200 | You've read DDIA twice and want pain |

---

### Scoring

```
+5 pts / second survived
+50 pts per 1,000 requests served
+200 pts per level cleared
+100 pts bonus for 99.9%+ availability on that level
+75 pts bonus if no node died
−100 pts per node that goes offline
Budget efficiency bonus at end = budget_remaining / 8
```

**Final Rating:**  
★★★ - Availability > 99.5%  
★★☆ - Availability > 95%  
★☆☆ - Survived but barely  

---

### Achievements

| Achievement | How to Unlock |
|---|---|
| ⚡ Scale Master | Run 5+ API servers simultaneously |
| 🔮 Cache Whisperer | Deploy Redis under active DB pressure |
| 🔄 Failover Hero | Execute a DB failover under live traffic |
| ⚡ Circuit Opener | Deploy a circuit breaker to stop a cascade |
| 🛡 Rate Master | Rate limiter neutralizes a live DDoS |
| 🏆 Five Nines | Maintain 99.9%+ availability for 60+ seconds |
| 🔀 Partition Tolerant | Survive a network partition with >80% availability |
| 💰 Budget Architect | Complete level 5 with budget remaining |
| 🔬 Chaos Engineer | Encounter 4+ different failure types |

---

### What You Learn

Playing through all 10 levels, you naturally internalize:

- **Horizontal Scaling** - stateless servers behind a load balancer
- **Leader-Follower Replication** - async copy, election, failover
- **Cache-Aside Pattern** - read-through, TTL, eviction policies
- **Circuit Breaker Pattern** - closed → open → half-open state machine
- **Rate Limiting** - token bucket, leaky bucket, per-IP throttling
- **Event-Driven Architecture** - producer/consumer, decoupling
- **CAP Theorem** - what actually happens to CP vs AP systems during partition
- **Thundering Herd Prevention** - jitter, mutex locking, staggered TTLs
- **Database Failover** - replica promotion, consistency window during switchover
- **DDoS Mitigation** - CDN absorption, edge rate limiting, anycast routing

These are the same topics that appear on FAANG system design interviews. The game makes them muscle memory.

---

## Learning Paths

### 🟢 Beginner Track
OOP → SOLID → GoF Patterns → UML → LLD Practice (Library System, Parking Lot)

### 🔵 Intermediate Track
HLD → Scalability → Infrastructure → DB Design → Estimation → URL Shortener

### 🟠 Advanced Track
Distributed Systems → Consensus → Sharding → Chaos Engineering → WhatsApp → Twitter

### 🟣 Expert Track
Global Scale → DB Internals → Stream Processing → Distributed Transactions → Staff Design → Payment System

Each module: estimated time, 4 subtopics, outcome statement, quiz, and a direct section link.

---

## Tech Stack

| Technology | Version | Usage |
|---|---|---|
| HTML5 | - | Structure, semantic markup |
| CSS3 | - | Custom properties, glassmorphism, animations |
| Vanilla JavaScript | ES2020 | All interactivity, simulations, state management |
| Three.js | r128 | 3D architecture visualizations |
| Chart.js | 4.4.0 | Line charts, doughnut charts |
| D3.js | v7.9.0 | Data visualizations |
| Google Fonts | - | Poppins, Inter, JetBrains Mono |

**No React. No Vue. No Angular. No build tools. No Node.js. No backend.**

---

## Getting Started

**https://sumit6258.github.io/System-Design/**

No install. No account. Works in any modern browser.

### Browser Requirements
- Chrome 90+ ✅
- Firefox 88+ ✅
- Safari 14+ ✅
- Edge 90+ ✅

WebGL required for 3D Lab section. All other sections work without it.

---

## Architecture Decisions

### Why a Single File?
1. **Zero deployment friction** - open locally or host via CDN URL
2. **No dependency hell** - no `npm install`, no build pipeline
3. **Offline capable** - works without internet
4. **Shareable** - email the file, host it, fork it
5. **Inspectable** - the HTML structure is itself a learning resource

### Why Vanilla JS?
- No framework overhead
- No version churn or breaking changes
- Faster initial load, no hydration delay
- Matches how system design thinking works - imperative, clear, explicit

### Lazy Rendering
Each of the 25 sections renders on demand via `showSection(id)`. Canvas simulations only start when you navigate to them and are paused when you leave.

### Canvas for Simulations
All real-time simulations use `<canvas>` over SVG: 60fps without DOM reflow, thousands of particles without degradation, single draw call per frame.

---

## Security & Copyright

```
Copyright © 2026 Sumit Suman. All Rights Reserved.

This project and its source code are protected by copyright law.
Unauthorized copying, redistribution, modification, or resale
of this software is strictly prohibited.
```

The source code is partially obfuscated. Authorship is cryptographically embedded via SHA-256 signature visible in the source. A styled console watermark is displayed in DevTools as an additional attribution layer.

---

## 📄 License

Copyright © 2026 Sumit Suman. All Rights Reserved.

### What You Can Do ✅
- Use the live platform freely for personal learning
- Share the link with others
- Reference this project in your portfolio or blog (with attribution)

### What You Cannot Do ❌
- Copy, reproduce, or redistribute the source code
- Modify and publish as your own work
- Use commercially without written permission
- Remove copyright notices, watermarks, or authorship signatures

### Attribution
> [https://sumit6258.github.io/System-Design/](https://sumit6258.github.io/System-Design/)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sumit%20Suman-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thesumitsuman/)

---

## Author

<div align="center">

**Sumit Suman**

Software Engineer | System Design Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thesumitsuman/)

*Built with ❤️ to make system design accessible to every engineer.*

---

> *"The best way to learn distributed systems is to build them - or at least simulate breaking them."*

</div>

---

<div align="center">

**System Design Lab v5.1.0** - © 2026 Sumit Suman

*Star ⭐ this project if it helped you land that offer.*

</div>