<div align="center">

# Victor Monteiro

**Backend Software Engineer · Go · Distributed Systems**

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&random=false&width=700&lines=Backend+Engineering+%7C+Go+%7C+APIs;Distributed+Systems+%7C+Microservices;Network+Engineering+%7C+Event-Driven;Kafka+%7C+RabbitMQ+%7C+Messaging;Data+Pipelines+%7C+ETL+%7C+Performance;Always+learning%2C+always+building)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/-Victor_Monteiro-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-hugo-monteirocs/)
[![TryHackMe](https://img.shields.io/badge/-virtostrk-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/virtostrk)

</div>

---

## 🧑‍💻 About Me

```go
package main

type VictorMonteiro struct {
	Role      string
	Company   string
	Education string
	Location  string
	Focus     []string
}

func New() *VictorMonteiro {
	return &VictorMonteiro{
		Role:      "Backend Software Engineer",
		Company:   "Grupo FGF",
		Education: "Information Systems @ UFU",
		Location:  "Uberlândia, MG 🇧🇷",
		Focus:     []string{"Golang", "Distributed Systems", "Microservices", "Network Engineering", "Event-Driven Architecture", "Data Engineering"},
	}
}

func (v *VictorMonteiro) CurrentWork() []string {
	return []string{
		"Migrating a legacy Pentaho ETL & backend ecosystem to Go (up to 28x faster)",
		"Concurrency with goroutines and worker pools; messaging with Kafka and RabbitMQ (producer/consumer)",
		"REST API design, query optimization (MySQL, PostgreSQL) and safe reprocessing",
		"Hexagonal architecture, error monitoring, Docker and Linux deployments",
	}
}

func (v *VictorMonteiro) FunFact() string {
	return "I automate what can be automated and measure what can be improved ✨"
}
```

---

## 🚀 Projects

- **[wallet-go](https://github.com/VictorM0nteiro/wallet-go-)** — Digital wallet API in Go: append-only ledger, idempotent transfers between accounts, and a measured comparison of locking strategies. Transactional outbox with relay, balance projector and Redis projection.
- **payrouter** *(in progress)* — Payment instruction router in Go that treats the unknown state (timeouts with no response) as a first-class state. Event sourcing on PostgreSQL, Kafka, CQRS, MongoDB projections and Redis cache.

---

## 🛠️ Tech Stack

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=amazon-dynamodb&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 💼 Experience

**Backend Software Engineer — Grupo FGF** *(Mar 2026 – present)*
- Migrated critical Pentaho routines to Go: one went from 2h+ to under 5 minutes, another from a problematic ~1-week run to under 6 hours.
- Built a reusable routine-monitoring layer for error logging, plus a database housekeeping routine (backup validation, purge, `OPTIMIZE`/`ANALYZE`) that stopped a core system from locking up.
- Resolved data divergences between systems and took part in large routine and server migrations.

**Earlier:** Data & AI Analyst (ML models, n8n agents, ETL with Python, SQL, IBM Cognos and DataStage) and Backend & BI Developer (Flask, PostgreSQL, Power BI).

---

## 🔐 Security Background

Google Cybersecurity Certificate · Fortinet FCF · Cisco Cyberthreat Management · TryHackMe **Blue Team** and **DevSecOps** paths (completed). I bring a security mindset to backend design: least privilege, safe reprocessing, auditability.

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VictorM0nteiro&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&text_color=C9D1D9" alt="Top Languages" />
	<img src="https://streak-stats.demolab.com/?user=VictorM0nteiro&theme=tokyonight&hide_border=true&background=0D1117&ring=6C63FF&fire=6C63FF&currStreakLabel=6C63FF" alt="GitHub Streak" />
</div>

---

<div align="center">

*Building backends, one commit at a time* 🚀

</div>
