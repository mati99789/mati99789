<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=600&lines=Software+Engineer;Fullstack+Developer;System+Designer)](https://git.io/typing-svg)

**10+ Years Engineering Experience** | **Mechanical → Software** | 🇵🇱 🇬🇧 🇸🇪

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mateusz-urbaniak-133001117/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mateusz.urbaniak@example.com)

</div>

---

## 🚀 About Me

```yaml
experience:
  total: "10+ years"
  mechanical_engineer: "6 years"
  software_engineer: "4.5 years @ Accenture Poland"
  
current_role: "Frontend Engineer expanding to Fullstack"
location: "Poland"

languages:
  polish: "Native"
  english: "Fluent"
  swedish: "Conversational"

background: |
  Built a foundation in Mechanical Engineering through formal studies, then transitioned into Software Engineering,
  applying 6 years of systems thinking to 4.5 years of professional software development at Accenture.


mentoring: |
  Former mentor at devmentor.pl (Frontend), helping junior developers 
  level up their skills through code reviews and pair programming.

code_review: "Daily practice with team members - strict standards, constructive feedback"
```

---

## 🔥 Featured Project

### [GoTicket](https://github.com/mati99789/go-ticket) - Event Ticketing System

> High-performance, scalable ticketing system built in Go. From Modular Monolith to Microservices.

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

## 🏆 Achievements

- 95% test coverage in GoTicket  
- 200 concurrent booking tests passed without race conditions  
- Mentored junior developers at devmentor.pl  

**Architecture:** Clean Architecture (DDD) | **Concurrency:** 200 goroutines tested | **Coverage:** 95%

```mermaid
graph TD
    User((User))
    subgraph "GoTicket"
        HTTP[API Layer]
        subgraph "Domain Modules"
            Mod_Event[Event Module]
            Mod_Booking[Booking Module]
        end
        DB[(PostgreSQL)]
    end
    User --> HTTP
    HTTP --> Mod_Event
    HTTP --> Mod_Booking
    Mod_Event --> DB
    Mod_Booking --> DB
```

**Key Highlights:**
- ✅ **Zero Race Conditions** - Verified with 200 concurrent booking attempts
- ✅ **Atomic Reservations** - PostgreSQL row-level locking prevents double-booking
- ✅ **Type-Safe SQL** - `sqlc` generates compile-time verified queries
- ✅ **Real Integration Tests** - Testcontainers with actual Postgres, not mocks
- ✅ **Production-Ready** - Graceful shutdown, structured logging, strict linting
- ✅ **Clean Architecture** - Domain logic completely isolated from infrastructure

**What I Learned:**
- Domain-Driven Design in practice
- Go concurrency patterns (`sync/atomic`, `WaitGroups`)
- Database transaction isolation
- Race condition detection & prevention
- Repository pattern with testable abstractions

---

## 📚 What I'm Reading

> *"The reading of all good books is like conversation with the finest minds of past centuries."* — René Descartes

| Book | Author | Why It Matters |
|------|--------|----------------|
| **Designing Data-Intensive Applications** | Martin Kleppmann | The bible for backend engineers - understanding trade-offs in distributed systems |
| **Clean Architecture** | Robert C. Martin | Applying SOLID principles in GoTicket's layered architecture |
| **The Go Programming Language** | Donovan & Kernighan | Deep dive into Go's runtime, memory model, and idioms |
| **System Design Interview** | Alex Xu | Preparing for large-scale system challenges |

---

## 🧠 How I Work

### Not Vibe Coding: AI as Learning Accelerator

I use AI tools to **accelerate understanding**, not to skip it:

```
❌ "Generate me a booking system in Go"
✅ "Explain the trade-offs between optimistic and pessimistic locking 
    in PostgreSQL for high-concurrency ticket reservations"
```

**My AI Workflow:**
1. **Architecture Research** - "What are the patterns for handling concurrent reservations?"
2. **Deep Dives** - "Explain Go's memory model and happens-before relationships"
3. **Documentation** - "How does pgxpool implement connection pooling under the hood?"
4. **Code Review** - "What are potential race conditions in this code?"

**The Rule:** Every line of code must be justified. I don't copy-paste; I understand, adapt, and own the solution.

### Engineering Principles

- **"Why?" over "How?"** - Every technical decision must have a reason (why `pgx` over `database/sql`?)
- **No Framework Magic** - Using `net/http` instead of Gin/Fiber to understand HTTP under the hood
- **Production-First Mindset** - Graceful shutdown, observability, and error handling from day one
- **Test-Driven Confidence** - Real integration tests with containers, not mocks

---

## 💻 Tech Stack

### Frontend (4.5 Years Production Experience)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend (Growing Portfolio)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---
## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=mati99789&theme=cobalt&hide_border=true" width="48%" />
</div>



## 🚀 Other Projects

<div align="center">

### Comming soon


</div>

---

## 🎯 6-Month Learning Roadmap

```
Q1 2026:
├── AWS Solutions Architect certification
├── Kubernetes fundamentals
└── Terraform/OpenTofu for IaC

Q2 2026:
├── Advanced System Design
├── Kafka/RabbitMQ (event-driven architecture)
└── Production deployment of GoTicket to AWS
```


## 🤝 Let's Connect

<div align="center">

I'm always open to discussions about:

- System design & architecture  
- Go best practices  
- Frontend performance  
- AI-assisted engineering  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mateusz-urbaniak-133001117/)  
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matteus.urbaniak@hotmail.com)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mati99789)

<br/>

**Built with ❤️ and strict engineering principles**

> *"From mechanical systems to software systems — the principles of good engineering remain the same."*

</div>

