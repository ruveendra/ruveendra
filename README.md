<img width="1586" height="396" alt="mountain-range-forest-daytime-scenery" src="https://github.com/user-attachments/assets/dcce9397-6e06-493d-b467-90b75f19a29b" />

## Hey, I'm Ruveendra

I love a good problem that sits in a grey area, working through it until it's properly articulated and structuring a solution around it. Software engineering is a space where you get to do exactly that: learn, understand, build, bring value, and live long enough to tell the tale!

My academic background is in software engineering, business analytics, and communication. My work background is in building web-based collaboration engines, distributed systems, and full-stack applications, with a strong background in cloud engineering working as a senior engineer. 

My current interests are integrating LLMs and AI agents into platforms to build better workflows. I'm currently exploring how AI can build on top of different domains, especially in collaborative systems.

Outside of programming, you'll usually find me outdoors or playing my beautiful British Racing Green Fender Telecaster. 🎸

📍 Athens, GA, USA

---

## 🚀 Featured Project

### **Continuum ([live demo](https://continuum-indol.vercel.app/) · [frontend](https://github.com/ruveendra/Continuum) · [sync server](https://github.com/ruveendra/continuum-sync-server)):** An AI-native collaborative writing platform, built to explore how AI-assisted editing can sit natively inside a real-time collaborative document — not bolted on as a separate tool

Designed and built the full editing, collaboration, and AI-suggestion engine end to end, from architecture through implementation.

**AI-Powered Editing**
* Context-Aware Rewriting: Select any text and instruct the AI to rewrite it in place — the AI receives the surrounding document as context, not just the selection in isolation
* Intent Classification: A dedicated AI call determines whether a chat instruction is actually targeting the user's current text selection before deciding how to act, rather than assuming any active selection is the intended edit target
* Persistent AI Chat with Memory: A docked chat panel reads the live document and conversation history on every message, letting users iteratively refine AI output turn by turn ("make it shorter" → "now more formal") without restarting context
* Customizable AI Personas: A "Personalize" system lets users define, edit, and switch between reusable AI writing-style profiles (tone, structure, constraints) that shape every generation and rewrite

**Review-First AI Workflow**
* Multi-Session AI Editing: A capped, concurrent AI suggestion pool — each request tracked independently through its own loading/result/accept-reject lifecycle, so multiple AI edits can be in flight across the document at once
* Position-Aware Highlighting: Custom ProseMirror decorations keep AI-suggestion highlights (and a strikethrough preview of replaced original text) correctly anchored to their source as the document is edited live around them
* Non-Destructive by Design: AI edits are reviewable and reversible — accept commits the change, reject restores the original content exactly, with dedicated UI both inline in the editor and in the chat itself

**Real-Time Collaboration**
* CRDT-Based Sync Engine: Y.js with WebSocket and IndexedDB providers for real-time, offline-first, multi-client document synchronization
* Standalone Sync Server: Self-hosted y-websocket server, deployed independently from the Next.js frontend

**Architecture**
* AI Integration Layer: Next.js Route Handlers calling Google Gemini, with prompt construction and rewrite/generation logic isolated from request handling
* State Architecture: Domain-separated Zustand stores bridging React state into ProseMirror's plugin system via transaction metadata
* Selection-Aware Tooltip UI: Floating UI tooltips positioned from ProseMirror coordinate data — both live-selection tooltips and persistent per-session tooltips that track document changes in real time


### **Atticus (https://www.atticus.io/):** A book-writing and formatting platform with 100K+ active authors

Core senior engineer leading the collaboration engine built on top of Atticus's rich-text editor — the system that lets authors co-write, comment, and revise books together in real time, at production scale.

**Real-Time Collaboration**
* CRDT-Based Sync Engine: Integrated Y.js to handle concurrent, offline-first document synchronization with automatic conflict resolution across simultaneous editors
* Live Presence & Commenting: Built presence tracking and a commenting system so co-authors can see who's editing what, in real time, across long-form documents
* Suggestions Engine: Designed a track-changes-style suggestion system, letting collaborators propose edits that the document owner can review and accept independently of the live sync layer

**Editor Internals**
* Custom Rich-Text Extensions: Wrote Slate serializers, normalizers, and plugins to support Atticus's book-specific formatting needs (chapters, scene breaks, front/back matter) beyond generic rich text

**Performance & Scale**
* Off-Thread Document Processing: Designed asynchronous compilation pipelines for PDF and ePub rendering, keeping the editor responsive for authors while long documents compile in the background
* Production Ownership: Maintained and evolved the collaboration engine as a system serving 100K+ active authors, balancing new feature work against the reliability demands of a live, heavily-used product

## 💻 Engineering Focus

* Real-Time Collaborative Systems using CRDTs, and offline-first architectures
* AI-Powered Workflows with LLMs and autonomous AI agents
* Distributed Systems, Cloud-Native Architecture, and Scalable Backend Infrastructure
* Full-Stack Product Engineering across frontend, backend, and system design

---

## 🛠️ Tech Stack

**Languages**
JavaScript • TypeScript • Python • Java • SQL

**Frontend**
React • Next.js

**Backend**
Node.js • Express • REST APIs • WebSockets • WebRTC

**Cloud**
AWS (EC2, ECS, Fargate, ElastiCache, Elastic Beanstalk, API Gateway, CloudFront, S3, VPC, Load Balancing)

**Databases**
PostgreSQL • MongoDB •  Redis

**Other**
Docker • Kafka • Git • CI/CD

---

## 📫 Contact

* LinkedIn: [www.linkedin.com/in/ruveendra-dewshan](http://www.linkedin.com/in/ruveendra-dewshan)
* Email: [ruveendradeewshan@gmail.com](mailto:ruveendradeewshan@gmail.com)

