# Hi, I'm Vinicius 👋

I'm a **Full Stack Software Engineer** in Belo Horizonte, Brazil, with over 4 years of experience building and maintaining a multi-tenant SaaS platform in the clinical engineering sector, used by more than 4,000 hospitals.

I enjoy building systems end to end, from architecture to implementation and documentation. I work mainly with **Python, Django, FastAPI, PostgreSQL and AWS**, plus **JavaScript, TypeScript and Node.js**.

I'm in the final year of a **B.Sc. in Systems Engineering at UFMG** (Federal University of Minas Gerais).

## 🔌 Main project: [Wiredex](https://github.com/vinicius-cardoso/wiredex)

A system to manage inventory, BOMs, pinouts, wiring and firmware for my hardware lab. Live at **[wiredex.vinilabs.cc](https://wiredex.vinilabs.cc)**.

* FastAPI, SQLAlchemy, PostgreSQL and TypeScript
* Integration tests with Testcontainers and E2E tests with Playwright
* Deploys with automatic rollback
* Runs on a VM with 2 cores and less than 1 GB of RAM, a constraint that drove almost every architectural decision

I also write about my projects, lessons learned and tutorials on my blog: **[vinilabs.cc](https://vinilabs.cc)**.

## 🚀 Professional highlights

* Fixed N+1 queries in the Django ORM with eager loading: an equipment listing went from **1 min 30 s to 3 s**, 30 times faster, on one of the product's most used APIs
* Traced a PostgreSQL write bottleneck where listing endpoints rewrote the Django session on every request, cutting writes to the session table from **28 million to 3 million**
* Built a configurable registry that lets any print button call an external webhook (HTTP method, headers and body), enabling integration with automation tools like n8n
* Provisioned a new production environment on AWS Elastic Beanstalk with Terraform, migrating from Classic to Application Load Balancer
* Identified **four critical vulnerabilities** and followed the fixes through code reviews and testing
* Refactored and fully modernized core modules (data structures, backend and interface)
* Code reviews and onboarding of interns and junior developers

## 💻 What I work with

* **Languages:** Python, JavaScript/TypeScript, C/C++, SQL, Bash
* **Backend:** Django, FastAPI, Node.js
* **Frontend:** JavaScript, jQuery, Angular
* **Databases:** PostgreSQL, SQLite
* **Infra & DevOps:** AWS, Terraform, Docker, Ansible, Git, CI/CD (GitHub Actions), Linux

## 🛠️ Selected tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square\&logo=django\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-339933?style=flat-square&logo=Node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonwebservices\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)

## 🔧 Outside work

I like projects that join software and hardware. My favorite so far is a sumo robot I built end to end: 3D modeling, 3D printing, PCB design in KiCad and ESP32 firmware.

## 🎓 Education

**B.Sc. in Systems Engineering**, Federal University of Minas Gerais (UFMG), 2020 – 2026 (final year)

**Technical Degree in Mechatronics**, CEFET-MG, 2017 – 2019

## 🌎 Languages

* Portuguese: native
* English: intermediate
* Italian: intermediate
* German: basic

## 📫 Contact

<a href="mailto:vinicius.mct17@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

<a href="https://www.linkedin.com/in/vinicius-c/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
