<div align="center">

<img src="./assets/header.svg" width="100%" alt="Maxim Borisov — Go, PostgreSQL and systems programming. Novosibirsk, Russia. NSU student." />

<p>
  <a href="https://t.me/good_borus"><img src="https://img.shields.io/badge/Telegram-0D141F?style=for-the-badge&amp;logo=telegram&amp;logoColor=5EEAD4" alt="Telegram" /></a>
  <a href="mailto:mborisovwork@gmail.com"><img src="https://img.shields.io/badge/Email-0D141F?style=for-the-badge&amp;logo=gmail&amp;logoColor=7CBAFF" alt="Email" /></a>
  <a href="https://github.com/Borus25"><img src="https://img.shields.io/badge/GitHub-0D141F?style=for-the-badge&amp;logo=github&amp;logoColor=C5D2E2" alt="GitHub" /></a>
</p>

<a href="#-about-me">About</a> ·
<a href="#-tech-stack">Stack</a> ·
<a href="#-experience">Experience</a> ·
<a href="#-selected-work">Projects</a> ·
<a href="#-achievements">Achievements</a>

</div>

<br />

## 👨‍💻 About me

<img src="./assets/about.svg" width="100%" alt="Backend and systems programming enthusiast. Third-year NSU student. Developer internship at Postgres Professional. Learning Go at T-Bank T-Academy." />

I like looking beneath the abstractions: how processes communicate, how databases replicate data, and what determines latency under load.
My focus is **Go backend development**, **PostgreSQL internals**, and understanding systems through measurements and experiments.

## 🛠️ Tech stack

<div align="center">

<p><strong>Languages</strong></p>
<p>
  <img src="https://img.shields.io/badge/Go-0D141F?style=for-the-badge&amp;logo=go&amp;logoColor=5EEAD4" alt="Go" />
  <img src="https://img.shields.io/badge/C-0D141F?style=for-the-badge&amp;logo=c&amp;logoColor=7CBAFF" alt="C" />
  <img src="https://img.shields.io/badge/Python-0D141F?style=for-the-badge&amp;logo=python&amp;logoColor=FBBF24" alt="Python" />
</p>

<p><strong>Databases</strong></p>
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-0D141F?style=for-the-badge&amp;logo=postgresql&amp;logoColor=7CBAFF" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-0D141F?style=for-the-badge&amp;logo=sqlite&amp;logoColor=9CC9FF" alt="SQLite" />
  <img src="https://img.shields.io/badge/MongoDB-0D141F?style=for-the-badge&amp;logo=mongodb&amp;logoColor=5EEAD4" alt="MongoDB" />
</p>

<p><strong>Tools</strong></p>
<p>
  <img src="https://img.shields.io/badge/Linux-0D141F?style=for-the-badge&amp;logo=linux&amp;logoColor=FBBF24" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-0D141F?style=for-the-badge&amp;logo=docker&amp;logoColor=7CBAFF" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-0D141F?style=for-the-badge&amp;logo=git&amp;logoColor=FB927A" alt="Git" />
  <img src="https://img.shields.io/badge/GDB-0D141F?style=for-the-badge" alt="GDB" />
</p>

</div>

**Practical focus:** HTTP APIs · SQL · WAL &amp; streaming replication · shared memory · load testing

<details>
<summary><b>📚 Additional background</b></summary>

C++ and Java through university OOP courses and additional training; algorithms and data structures at NSU.

</details>

## 💼 Experience

### Postgres Professional · Developer Intern

**June — August 2026**

Developed an experimental **PostgreSQL replication testbed** to investigate how replica-side delays affect transaction latency.

- Modified server-side **C code** to introduce configurable delays at the WAL write, flush, and replay stages.
- Implemented runtime configuration through an **HTTP API** and **shared memory**.
- Built workload-generation and visualization tools to investigate behavior under load.
- Presented the project at **PgConf.SummerSchool 2026**.

`C` `PostgreSQL` `Python` `HTTP API` `GDB`

## 📌 Selected work

<table>
<tr>
<td width="50%" valign="top">
<h3>🐘 PostgreSQL Replication Testbed</h3>
<p>Experimental environment for reproducing replication delays and studying their impact on transaction execution.</p>
<p><code>C</code> <code>PostgreSQL</code> <code>HTTP API</code></p>
<p><a href="https://github.com/Borus25/postgres-stand-for-test-synchronous">Explore repository →</a></p>
</td>
<td width="50%" valign="top">
<h3>📊 Monitoring &amp; Visualization</h3>
<p>Tools for collecting experiment results, tracking replication behavior, and visualizing transaction latency as parameters change.</p>
<p><code>Monitoring</code> <code>Load Testing</code> <code>Data Visualization</code></p>
<p><em>Part of the replication testbed project.</em></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🌐 Go Networking Labs</h3>
<p>University networking coursework implemented in Go.</p>
<p><code>Go</code> <code>Computer Networks</code></p>
<p><a href="https://github.com/Borus25/NSU_Networks_5semestr">Explore repository →</a></p>
</td>
<td width="50%" valign="top">
<h3>🔎 TE AI Hack</h3>
<p>Hackathon project: an AI-powered interface for smart search.</p>
<p><code>Python</code> <code>AI</code> <code>Hackathon</code></p>
<p><a href="https://github.com/Borus25/TE_AI_Hack">Explore repository →</a></p>
</td>
</tr>
</table>

## 🏆 Achievements

| Result | Event &amp; project |
| :--- | :--- |
| 🥉 **3rd place** | **Sistema Hack: Novosibirsk** · CDEK track — AI tool for assessing employee and partner burnout |
| 🏅 **Finalist** | **TE AI Hack** · True Engineering &amp; NSU — AI-powered smart search |
| 🎯 **5th place** | **Global ERP learning visualization hackathon** · STIK ecosystem |
| 🎤 **Speaker** | **PgConf.SummerSchool 2026** · Testbed for studying weak synchrony in PostgreSQL replication |

## 🎓 Education

**Novosibirsk State University** · 2024 — present  
Faculty of Information Technology · Software Engineering and Computer Science

<details>
<summary><b>🌱 Courses &amp; additional training</b></summary>

- **Go** — T-Bank T-Academy; currently studying.
- **Python** — Yandex Academy Lyceum.
- **C++** — MIPT &amp; Yandex courses.
- **Java** — SHIFT / CFT.
- **SQL** — Stepik.

</details>

<br />

<div align="center">

🏀 Basketball &nbsp; · &nbsp; 🏒 Hockey &nbsp; · &nbsp; 🪐 Space

<img src="./assets/footer.svg" width="100%" alt="Backend engineering · Database internals · Performance" />

</div>
