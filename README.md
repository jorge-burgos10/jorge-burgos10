# Hi, I'm Jorge Burgos

**Computer Engineering Student @ UPRM · Backend · Data · Automation · Cloud Security**

I'm a Computer Engineering student at the University of Puerto Rico at Mayagüez. I build backend and data systems and automate the work around them, from ETL pipelines and REST APIs to event-driven cloud functions and CI workflows, and I work on a production serverless AWS backend as an undergraduate researcher.

- B.S. in Computer Engineering, expected **December 2027**
- Undergraduate Research Assistant, **SCOPE Project** (Software Team), IoT Lab, UPRM
- Currently learning: Flask, React, Azure data services
- Mayagüez, Puerto Rico
- Spanish (native) · English (proficient) · French (basic)
- Looking for **Summer 2027 internships** in backend, data engineering, automation, or cloud

---

## Research: SCOPE Project, UPRM

Working on a production serverless AWS application inherited from a previous capstone team (~40 Lambda functions, API Gateway, S3, SQS, RDS PostgreSQL).

- **Security:** Audited the architecture and secured unauthenticated API routes with IAM authorization and rate limiting, verified in production.
- **Privacy:** Designed S3 lifecycle rules and an event-driven Lambda that deletes processed images within seconds, removing ~12 GB of stored photos.
- **Performance:** Measured and analyzed API latency to separate cold-start from warm response times.
- **Engineering practice:** Set up GitHub Actions CI with automated tests; ship changes through pull requests and code reviews.

---

## Featured Projects

### [Car Tracking System: REST API & ETL Pipeline](https://github.com/DBSpring26)
Team project (3 members) for Database Systems (CIIC 4060 / ICOM 5016), Spring 2026.
- Built the **ETL orchestration and data-validation step** that loads 9 Parquet datasets into **PostgreSQL 17 / PostGIS**, fixing data-quality bugs before load (dtype corruption, EWKB vs. WKB geometry, ID sequences).
- Created the initial **FastAPI** backend and Docker setup for a **28-endpoint REST API** (handler/DAO architecture, geospatial queries).
- Built a **Streamlit** dashboard (Plotly, Folium) and an **AI assistant with a custom MCP server** for natural-language data queries.

`Python` `FastAPI` `PostgreSQL` `PostGIS` `pandas` `Docker` `Streamlit` `MCP`

### [PA-RISC Pipelined Processor](https://github.com/jorge-burgos10/pa-risc-ppu)
A 5-stage pipelined PA-RISC processor with hazard detection, a 32-bit ALU, and a test bench.

`Verilog`

### [EV Charging Station Reservation System](https://github.com/jorge-burgos10/EV-Charging-Station-Reservation-System)
Console-based reservation platform for 5 UPRM campus charging stations, with conflict detection, an automated wait queue, and stack-based undo.

`Java` `Data Structures`

---

## Tech Stack

**Languages:** Python · Java · C · C++ · SQL · JavaScript · Verilog · PowerShell
**Backend & Data:** FastAPI · REST APIs · PostgreSQL · PostGIS · pandas · ETL pipelines · Streamlit
**Cloud:** AWS (Lambda, API Gateway, S3, IAM, CloudFormation, CloudWatch, RDS, SQS) · AWS CLI
**Automation:** GitHub Actions CI · event-driven AWS Lambda · S3 lifecycle rules · ETL orchestration · Excel macros
**DevOps & Tools:** Git/GitHub · Docker · Linux · POSIX
**AI:** MCP servers · LLM tool calling · Claude Code · Cursor

---

## Contact

[![Email](https://img.shields.io/badge/Email-jorgeburgos859%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:jorgeburgos859@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jorge%20Burgos-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorge-burgos-b5a8748a)
[![Portfolio](https://img.shields.io/badge/Portfolio-jorgeburgos.me-000000?logo=googlechrome&logoColor=white)](https://jorgeburgos.me)
