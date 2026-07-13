<img width="1586" height="396" alt="mountain-range-forest-daytime-scenery" src="https://github.com/user-attachments/assets/dcce9397-6e06-493d-b467-90b75f19a29b" />

## Hey, I'm Ruveendra

I love a good problem that sits in a grey area, working through it until it's properly articulated and structuring a solution around it. Software engineering is a space where you get to do exactly that: learn, understand, build, bring value, and live long enough to tell the tale!

My academic background is in software engineering, business analytics, and communication. My work background is in building web-based collaboration engines, distributed systems, and full-stack applications, with a strong background in cloud engineering working as a senior engineer. 

My current interests are integrating LLMs and AI agents into platforms to build better workflows. I'm currently exploring how AI can build on top of different domains, especially in collaborative systems.

Outside of programming, you'll usually find me outdoors or playing my beautiful British Racing Green Fender Telecaster. 🎸

📍 Athens, GA, USA

---

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

## 🚀 Featured Project

### **Atticus (https://www.atticus.io/) :** A book-writing and formatting platform with 100K+ active authors

Core senior engineer leading the collaboration engine for Atticus, built on top of its rich-text editor, allowing authors to co-author books in real-time

Implemented:

* CRDT-Based Sync Engine: Integrated Yjs to handle concurrent, offline-first document synchronization and automatic conflict resolution
* Social Collaboration Features: live presence tracking, commenting systems, and a suggestions (track changes) engine
* Custom Rich-Text Extensions: Slate custom serializers, normalizers, and plugins to support formatting
* Asynchronous Document Processing: Designed off-thread compilation pipelines to handle PDF and ePub rendering without blocking the main editor thread


### **Continuum (https://github.com/ruveendra/Continuum) :** An AI-assisted editor built with Next.js, exploring inline AI-powered editing on top of a real-time collaborative document layer

Independently designed and built the full editing and AI-suggestion engine as a self-directed learning project, architecting the system before writing implementation code.

Implemented:

* Multi-Session AI Editing System: Designed a concurrent AI suggestion architecture (capped session pool) allowing multiple in-flight AI edit requests to coexist independently, each tracked through its own loading/result/accept-reject lifecycle
* Position-Aware Highlight Tracking: Built a custom ProseMirror decoration system that keeps AI-suggestion highlights correctly anchored to their source text as the document is edited elsewhere, using transaction-mapping to reconcile state living outside ProseMirror's own model
* Selection-Aware Tooltip UI: Implemented Floating UI tooltips anchored to virtual reference elements derived from ProseMirror's coordinate system, supporting both a live selection-following tooltip and persistent per-session tooltips that track document changes in real time
* AI Integration Layer: Connected a Next.js Route Handler to Google's Gemini API for instruction-driven text rewriting, with formatting-aware replacement logic that distinguishes whole-block versus partial-selection edits to avoid corrupting document structure
* Document Sync Foundation: Set up Y.js with WebSocket and IndexedDB providers for offline-first, real-time editor state, as the base the AI-editing layer is built on top of
* State Architecture: Structured editor and AI-session state with a domain-separated Zustand store design, bridging React state into ProseMirror's plugin system via transaction metadata

---

## 📫 Contact

* LinkedIn: [www.linkedin.com/in/ruveendra-dewshan](http://www.linkedin.com/in/ruveendra-dewshan)
* Email: [ruveendradeewshan@gmail.com](mailto:ruveendradeewshan@gmail.com)

