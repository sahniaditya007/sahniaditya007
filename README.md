# Hi, I'm Aditya Sahni

**Software Engineer · Full-Stack (MERN/Next.js) · ML & Systems Enthusiast**

- **Location:** Noida / New Delhi, India  
- **Email:** [sahniaditya007@gmail.com](mailto:sahniaditya007@gmail.com)  
- **Phone:** +91-9971121047  
- **LinkedIn:** [linkedin.com/in/sahniaditya007](https://linkedin.com/in/sahniaditya007)  
- **GitHub:** [github.com/sahniaditya007](https://github.com/sahniaditya007)  
- **LeetCode:** [leetcode.com/sahniaditya007](https://leetcode.com/sahniaditya007)  
- **Codeforces:** [codeforces.com/adityasahni](https://codeforces.com/adityasahni)  

---

## About Me

I’m a Computer Science undergraduate at **Bennett University (2022–2026)** with hands-on experience building **production-grade MERN applications**, designing **real-time data pipelines**, and developing **end-to-end ML systems** (feature engineering → training → evaluation → deployment).

I enjoy working at the intersection of:

- **Backend engineering** (APIs, data models, systems design)  
- **AI/ML** (modeling, evaluation, deployment)  
- **Low-level systems** (OS internals, performance, tooling)

I care about **clear abstractions**, **reliable systems**, and **measurable impact**.

---

## Technical Skills

| **Category** | **Skills** |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=python" height="26" alt="Python" /> <img src="https://skillicons.dev/icons?i=c" height="26" alt="C" /> <img src="https://skillicons.dev/icons?i=cpp" height="26" alt="C++" /> <img src="https://skillicons.dev/icons?i=js" height="26" alt="JavaScript" /> <img src="https://skillicons.dev/icons?i=html" height="26" alt="HTML5" /> <img src="https://skillicons.dev/icons?i=css" height="26" alt="CSS3" /> <img src="https://skillicons.dev/icons?i=mysql" height="26" alt="SQL" /> <br/>Python · C · C++ · Assembly · JavaScript · SQL · HTML5 · CSS3 |
| **Frameworks & Runtimes** | <img src="https://skillicons.dev/icons?i=react" height="26" alt="React.js" /> <img src="https://skillicons.dev/icons?i=nextjs" height="26" alt="Next.js" /> <img src="https://skillicons.dev/icons?i=nodejs" height="26" alt="Node.js" /> <img src="https://skillicons.dev/icons?i=express" height="26" alt="Express.js" /> <img src="https://skillicons.dev/icons?i=fastapi" height="26" alt="FastAPI" /> <br/>React.js · Next.js · Remix · Node.js · Express.js · FastAPI |
| **AI/ML** | <img src="https://skillicons.dev/icons?i=pytorch" height="26" alt="PyTorch" /> <img src="https://skillicons.dev/icons?i=tensorflow" height="26" alt="TensorFlow" /> <br/>PyTorch · TensorFlow · scikit-learn · NumPy · Pandas · Hugging Face Transformers · LangChain |
| **Databases & Data Engineering** | <img src="https://skillicons.dev/icons?i=postgres" height="26" alt="PostgreSQL" /> <img src="https://skillicons.dev/icons?i=mysql" height="26" alt="MySQL" /> <img src="https://skillicons.dev/icons?i=mongodb" height="26" alt="MongoDB" /> <img src="https://skillicons.dev/icons?i=redis" height="26" alt="Redis" /> <img src="https://skillicons.dev/icons?i=kafka" height="26" alt="Apache Kafka" /> <br/>PostgreSQL · MySQL · MongoDB · Redis · Apache Kafka · Qdrant |
| **DevOps & Tooling** | <img src="https://skillicons.dev/icons?i=git" height="26" alt="Git" /> <img src="https://skillicons.dev/icons?i=github" height="26" alt="GitHub" /> <img src="https://skillicons.dev/icons?i=docker" height="26" alt="Docker" /> <img src="https://skillicons.dev/icons?i=linux" height="26" alt="Linux/Unix" /> <img src="https://skillicons.dev/icons?i=vscode" height="26" alt="VS Code" /> <br/>Git · GitHub · Docker · Linux/Unix · WSL · Zsh · VS Code · QEMU · SCons |
| **Cloud & APIs** | <img src="https://skillicons.dev/icons?i=gcp" height="26" alt="Google Cloud Platform" /> <img src="https://skillicons.dev/icons?i=aws" height="26" alt="AWS" /> <img src="https://skillicons.dev/icons?i=azure" height="26" alt="Microsoft Azure" /> <br/>GCP · AWS · Azure · OpenAI API · Gemini API |

---

## Experience

### IPOTHESIS RESEARCH PRIVATE LIMITED — Software Engineer Intern  
*Jan 2025 – Present · New Delhi, India*

- Built an end-to-end **ML trading signal pipeline** processing **50,000+ daily market data points**, computing **25+ technical indicators**, training ensemble models, and generating signals with **~65% directional accuracy**.  
- Developed **backtesting frameworks** to evaluate **15+ strategies** over **3 years** of historical data and automated A/B experiments across **8 model variants**, improving **Sharpe ratio by 0.4**.  
- Standardized dataset splits (**70/15/15** train/validation/test), **20+ feature configurations**, and versioned training artifacts, reducing experiment setup time by **60%** and improving reproducibility.  
- Shipped and maintained **3 production MERN applications** serving **500+ daily users**, exposing **12+ REST APIs** with Node.js/Express and achieving **sub-200ms** response times on **90%+ endpoints**.  
- Collaborated in a **4-person cross-functional team** to deliver **20+ production features** over **2 sprints**, achieving **99.5% uptime** and improving frontend load times by **35%**.

---

## Selected Projects

### Real-Time UPI Fraud Detection System  
**Tech:** Apache Kafka · Redis · Python · scikit-learn  
*Feb 2026*

- Designed a real-time fraud detection pipeline processing **10,000+ transactions/hour** with **~100ms end-to-end latency**, ingesting streaming events via Kafka across **3 consumer groups** with **99.9% uptime**.  
- Built a Redis-backed behavioral state engine tracking **6 fraud signals** using **1M+ TTL-based keys** over **5-minute sliding windows**, reducing false positives by **30%**.  
- Developed an explainable hybrid risk-scoring engine combining **8 heuristic rules** with **Logistic Regression (AUC 0.87)** trained via weak supervision on **100K+ synthetic transactions**.  
- Orchestrated offline training on **250K+ labeled transactions** and online inference with **15+ consistent features**, achieving **82% precision** and **78% recall** in production scoring.

---

### The Operating System Project  
**Tech:** C · x86 Assembly · SCons · QEMU/Bochs  
*Nov 2025*

- Implemented a **32-bit i686 operating system** (~8,000 LOC) with a **two-stage bootloader** (512B stage-1) using **E820 BIOS** memory detection and boot parameter passing to a **64KB kernel image**.  
- Built a **FAT12/16/32 filesystem reader** (4KB clusters) in stage-2 and an **ELF loader** parsing **10+ section headers** to locate and jump to `/boot/kernel.elf`.  
- Set up core CPU/interrupt infrastructure: **GDT (5 segments), IDT (256 vectors), 32 ISRs, 16 IRQs**, **8259 PIC driver**, and **x87 FPU initialization**, achieving **~2ms boot time**.  
- Developed a VGA GUI (320×200, 16-color), PS/2 keyboard/mouse drivers, and **3 desktop-style applications** (text editor, file browser, calculator).

---

### AI Technical Interviewer  
**Tech:** Next.js · FastAPI · LangChain · Google Gemini API  
*Sep 2025*

- Built a full-stack interview platform supporting **100+ sessions** with adaptive difficulty across **5 levels**, using **Next.js** (frontend) and **FastAPI** (backend, **8 REST endpoints**) with **99% uptime**.  
- Deployed a **4-stage LangChain pipeline** using Gemini for question generation (**3 questions/round**) and evaluation, processing **500+ responses** with **92% agreement** vs. human reviewers.  
- Designed a difficulty adaptation algorithm over **7 scoring dimensions** (normalized 0–100), increasing engagement by **45%** via personalized progression.

---

## Currently Exploring

- Real-time systems (Kafka/Redis), ML in production, and evaluation tooling  
- LLM applications with LangChain and modern inference stacks  
- Operating systems, developer tooling, and performance-focused engineering  

---

## Get In Touch

If you’d like to collaborate or discuss opportunities:

- **Email:** [sahniaditya007@gmail.com](mailto:sahniaditya007@gmail.com)  
- **LinkedIn:** [linkedin.com/in/sahniaditya007](https://linkedin.com/in/sahniaditya007)
