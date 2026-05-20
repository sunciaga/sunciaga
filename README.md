# Brian | Backend & Systems Engineer

I build resilient, fault-tolerant backend architectures. I specialize in designing systems that gracefully degrade under extreme load rather than collapsing, eliminating single points of failure through core software patterns.

---

### Technical Obsession: Engineering for Failure

Most developers write code for the happy path. I design for the worst-case scenario. I focus on distributed systems resilience, traffic shaping, and high-concurrency survival strategies using TypeScript and low-level infrastructure orchestration.

---

### High-Impact Open Source Repositories

#### 🛡️ Advanced Fault-Tolerance Pipeline & Traffic Shaper
*A zero-dependency TypeScript implementation of architectural resilience patterns designed to mitigate the Thundering Herd effect under heavy load.*

* **The Core:** Engineered a custom resilience layer featuring **Exponential Backoff with Jitter** and an autonomous **Circuit Breaker** state machine (Closed, Open, Half-Open).
* **The Stress Test:** Containerized the infrastructure using **Docker** and simulated a catastrophic spike of 5,000 concurrent requests using **k6** while forcefully injecting server downtime.
* **The Resolution:** Prevented cascading failures by dispersing retry waves over a 5-attempt dynamic window, stabilizing the core service recovery rate by 100% without data drops.

---

### 🧰 The System Diagnostics Toolkit

* **Load & Stress Testing:** Writing complex user behavior simulations in **k6** to locate memory leaks and API breaking points.
* **Environment Isolation:** Multi-stage **Docker** configurations to ensure deterministic production behavior across distributed nodes.
* **Asynchronous Primitives:** Mastery of event-loops, race conditions, non-blocking I/O, and strict error-as-values handling in TypeScript.

---

📬 **System Architecture Queries:** [samebriann@gmail.com](mailto:samebriann@gmail.com)

---

> "Just because the code works doesn't mean the system is reliable. True engineering happens when you design for the moment everything breaks."
