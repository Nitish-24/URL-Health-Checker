# 🔍 URL Health Checker (Microservice Monitor) [![Status](https://img.shields.io/badge/Status-In_Progress-yellow)](https://github.com/yourusername/url-health-checker)

A lightweight Spring Boot microservice to monitor website availability with scheduled health checks and reporting.

![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2+-6DB33F?logo=spring)
![H2](https://img.shields.io/badge/Database-H2/PostgreSQL-4479A1?logo=postgresql)
![Java](https://img.shields.io/badge/Java-17-007396?logo=java)

## ✨ Why This Project?
- **Beyond Basic CRUD**: Solves real-world infrastructure monitoring needs
- **Extensible Design**: Foundation for alerts (Slack/Email), dashboards, etc.
- **Learning Focus**: Covers Spring Scheduling, REST APIs, and database ops

## 🛠️ Tech Stack
| Component       | Technology                          |
|-----------------|------------------------------------|
| Backend         | Spring Boot 3.x                    |
| Database        | H2 (Dev) / PostgreSQL (Prod-ready) |
| HTTP Client     | Java 11+ HttpClient                |
| Scheduling      | Spring Scheduler                   |
| API Docs        | Swagger UI (Optional)              |

## 🚀 Getting Started
```bash
git clone https://github.com/yourusername/url-health-checker.git
cd url-health-checker
mvn spring-boot:run
