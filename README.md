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

<div style="height: 1px; background-color: #e1e4e8;"></div>

### **Continuum (https://github.com/ruveendra/Continuum) :** An AI-assisted collaborative editor

Designed and built an AI-assisted rich text editor with Next.js, exploring inline AI editing on a real-time collaborative document layer.

Implemented:

* Multi-Session AI Editing: Concurrent AI suggestion system (capped session pool), each request tracked through its own loading/result/accept-reject lifecycle
* Position-Aware Highlighting: Custom ProseMirror decorations that keep AI-suggestion highlights anchored to their source text through live document edits
* Selection-Aware Tooltip UI: Floating UI tooltips positioned via ProseMirror coordinate data, supporting both live-selection and persistent per-session tooltips
* AI Integration: Next.js Route Handler calling Gemini for instruction-driven rewrites, with formatting-aware replacement logic
* Collaborative Sync Foundation: Y.js with WebSocket + IndexedDB providers for real-time, offline-first editing
* State Architecture: Domain-separated Zustand stores bridging React state into ProseMirror's plugin system

---

## 📫 Contact

* LinkedIn: [www.linkedin.com/in/ruveendra-dewshan](http://www.linkedin.com/in/ruveendra-dewshan)
* Email: [ruveendradeewshan@gmail.com](mailto:ruveendradeewshan@gmail.com)

