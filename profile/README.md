# Welcome to WeKnow! 🚀

## Unraveling the Mysteries of 'whoknows'

We are **WeKnow**, a dedicated team of three students from the DevOps course, committed to tackling the challenges of legacy system modernization and best practices in software development. This organization serves as the central hub for our academic project, where we embark on an exciting journey to understand, transform, and ultimately **master** a critical legacy server dubbed "whoknows."

---

## 🧐 The 'whoknows' Project: From Legacy to Luminary

Our core mission revolves around the "whoknows" server, a fascinating relic that currently acts as a **database for various software tools**. This project is not just about keeping an old system running; it's about a complete and thoughtful overhaul, applying modern DevOps principles every step of the way.

### Our Challenge: The 'whoknows' Transformation

The "whoknows" server, in its current state, is built on a **Flask (Python)** backend. Our primary technical objective is to **migrate this legacy Python application to a Ruby-based solution using the Sinatra framework.** This isn't merely a translation; it's an opportunity to:

*   **Understand and document** every intricate detail of the existing system.
*   **Refactor and redesign** for improved maintainability, scalability, and performance.
*   **Implement robust CI/CD pipelines** to ensure smooth and reliable deployments.
*   **Apply best practices** in infrastructure as code, monitoring, and security.
*   **Ultimately, make this legacy code our own**, transforming it into a well-understood, modern, and efficient service.

**[Dependency graph](https://dreampuf.github.io/GraphvizOnline/?engine=dot#digraph%20%22Legacy_System_Dependencies%22%20%7B%0D%0A%20%20%20%20%2F%2F%20---%20Global%20Graph%2C%20Node%2C%20and%20Edge%20Attributes%20---%0D%0A%20%20%20%20graph%20%5B%0D%0A%20%20%20%20%20%20%20%20rankdir%3D%22TB%22%2C%20%2F%2F%20Top-to-Bottom%20is%20better%20for%20showing%20operational%20layers%0D%0A%20%20%20%20%20%20%20%20bgcolor%3D%22transparent%22%2C%0D%0A%20%20%20%20%20%20%20%20fontname%3D%22Helvetica%22%2C%0D%0A%20%20%20%20%20%20%20%20fontsize%3D16%2C%0D%0A%20%20%20%20%20%20%20%20label%3D%22Best%20Practice%20System%20Dependency%20Graph%22%2C%0D%0A%20%20%20%20%20%20%20%20splines%3Dortho%0D%0A%20%20%20%20%5D%3B%0D%0A%20%20%20%20node%20%5B%0D%0A%20%20%20%20%20%20%20%20style%3D%22filled%2Crounded%22%2C%0D%0A%20%20%20%20%20%20%20%20shape%3D%22box%22%2C%0D%0A%20%20%20%20%20%20%20%20fontname%3D%22Helvetica%22%2C%0D%0A%20%20%20%20%20%20%20%20fontsize%3D11%0D%0A%20%20%20%20%5D%3B%0D%0A%20%20%20%20edge%20%5B%0D%0A%20%20%20%20%20%20%20%20fontname%3D%22Helvetica%22%2C%0D%0A%20%20%20%20%20%20%20%20fontsize%3D9%2C%0D%0A%20%20%20%20%20%20%20%20color%3D%22%23444444%22%0D%0A%20%20%20%20%5D%3B%0D%0A%0D%0A%20%20%20%20%2F%2F%20---%20Layer%201%3A%20Operational%20Environment%20---%0D%0A%20%20%20%20subgraph%20%22cluster_environment%22%20%7B%0D%0A%20%20%20%20%20%20%20%20label%20%3D%20%22Operational%20Environment%22%3B%0D%0A%20%20%20%20%20%20%20%20style%20%3D%20%22filled%22%3B%0D%0A%20%20%20%20%20%20%20%20color%20%3D%20%22%23f5f5f5%22%3B%0D%0A%20%20%20%20%20%20%20%20node%20%5Bshape%3D%22tab%22%2C%20fillcolor%3D%22%23e0e0e0%22%5D%3B%0D%0A%0D%0A%20%20%20%20%20%20%20%20%22Unix-like%20OS%20(e.g.%2C%20Linux)%22%3B%0D%0A%20%20%20%20%20%20%20%20%22Python%202%20Interpreter%22%3B%0D%0A%20%20%20%20%7D%0D%0A%0D%0A%20%20%20%20%2F%2F%20---%20Layer%202%3A%20Execution%20%26%20Orchestration%20---%0D%0A%20%20%20%20subgraph%20%22cluster_execution%22%20%7B%0D%0A%20%20%20%20%20%20%20%20label%20%3D%20%22Execution%20%26%20Orchestration%22%3B%0D%0A%20%20%20%20%20%20%20%20style%3D%22filled%22%3B%0D%0A%20%20%20%20%20%20%20%20color%3D%22%23f5f5f5%22%3B%0D%0A%20%20%20%20%20%20%20%20node%20%5Bshape%3D%22note%22%2C%20fillcolor%3D%22%23ffe082%22%5D%3B%0D%0A%0D%0A%20%20%20%20%20%20%20%20%22Makefile%22%3B%0D%0A%20%20%20%20%20%20%20%20%22run_forever.sh%22%3B%0D%0A%20%20%20%20%20%20%20%20%22Flask%20Dev%20Server%22%20%5Bshape%3D%22component%22%2C%20fillcolor%3D%22%23ffcdd2%22%5D%3B%0D%0A%20%20%20%20%7D%0D%0A%0D%0A%20%20%20%20%2F%2F%20---%20Layer%203%3A%20Application%20%26%20Dependencies%20---%0D%0A%20%20%20%20subgraph%20%22cluster_application%22%20%7B%0D%0A%20%20%20%20%20%20%20%20label%20%3D%20%22Application%20Layer%22%3B%0D%0A%20%20%20%20%20%20%20%20style%3D%22filled%22%3B%0D%0A%20%20%20%20%20%20%20%20color%3D%22%23f5f5f5%22%3B%0D%0A%0D%0A%20%20%20%20%20%20%20%20%2F%2F%20Application%20Source%20Code%0D%0A%20%20%20%20%20%20%20%20%22app.py%22%20%5Bfillcolor%3D%22%23c5e1a5%22%5D%3B%0D%0A%20%20%20%20%20%20%20%20%22app_tests.py%22%20%5Bfillcolor%3D%22%23c5e1a5%22%5D%3B%0D%0A%20%20%20%20%20%20%20%20%22requirements.txt%22%20%5Bshape%3D%22note%22%2C%20fillcolor%3D%22%23ffe082%22%5D%3B%0D%0A%0D%0A%20%20%20%20%20%20%20%20%2F%2F%20External%20Python%20Libraries%0D%0A%20%20%20%20%20%20%20%20subgraph%20%22cluster_libraries%22%20%7B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20label%20%3D%20%22External%20Libraries%22%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20style%20%3D%20%22filled%2Cdashed%22%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20color%20%3D%20%22%23b3e5fc%22%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20node%20%5Bfillcolor%3D%22%23ffd180%22%5D%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20%22Flask%22%3B%20%22Jinja2%22%3B%20%22Werkzeug%22%3B%20%22setuptools%22%3B%0D%0A%20%20%20%20%20%20%20%20%7D%0D%0A%20%20%20%20%7D%0D%0A%0D%0A%20%20%20%20%2F%2F%20---%20Layer%204%3A%20Data%20%26%20Assets%20---%0D%0A%20%20%20%20subgraph%20%22cluster_data%22%20%7B%0D%0A%20%20%20%20%20%20%20%20label%20%3D%20%22Data%20%26%20Presentation%20Layer%22%3B%0D%0A%20%20%20%20%20%20%20%20style%3D%22filled%22%3B%0D%0A%20%20%20%20%20%20%20%20color%3D%22%23f5f5f5%22%3B%0D%0A%0D%0A%20%20%20%20%20%20%20%20%22whoknows.db%22%20%5Bshape%3D%22cylinder%22%2C%20fillcolor%3D%22%23b0bec5%22%5D%3B%0D%0A%20%20%20%20%20%20%20%20%22schema.sql%22%20%5Bshape%3D%22note%22%2C%20fillcolor%3D%22%23ffe082%22%5D%3B%0D%0A%0D%0A%20%20%20%20%20%20%20%20subgraph%20%22cluster_templates%22%20%7B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20label%20%3D%20%22Templates%22%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20node%20%5Bfillcolor%3D%22%23ffccbc%22%5D%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20%22layout.html%22%3B%20%22about.html%22%3B%20%22login.html%22%3B%20%22register.html%22%3B%20%22search.html%22%3B%0D%0A%20%20%20%20%20%20%20%20%7D%0D%0A%20%20%20%20%20%20%20%20subgraph%20%22cluster_static%22%20%7B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20label%20%3D%20%22Static%20Files%22%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20node%20%5Bshape%3D%22rect%22%2C%20style%3D%22filled%22%2C%20fillcolor%3D%22%23cfd8dc%22%5D%3B%0D%0A%20%20%20%20%20%20%20%20%20%20%20%20%22style.css%22%3B%20%22monkgroup.png%22%3B%0D%0A%20%20%20%20%20%20%20%20%7D%0D%0A%20%20%20%20%7D%0D%0A%0D%0A%20%20%20%20%2F%2F%20---%20Dependency%20Edges%20---%0D%0A%0D%0A%20%20%20%20%2F%2F%20Execution%20Flow%20(Control)%20-%20Dashed%20Arrows%0D%0A%20%20%20%20%22Unix-like%20OS%20(e.g.%2C%20Linux)%22%20-%3E%20%22run_forever.sh%22%20%5Bstyle%3Ddashed%2C%20label%3D%22%20executes%20shell%20script%22%5D%3B%0D%0A%20%20%20%20%22run_forever.sh%22%20-%3E%20%22Python%202%20Interpreter%22%20%5Bstyle%3Ddashed%2C%20label%3D%22%20invokes%22%5D%3B%0D%0A%20%20%20%20%22Makefile%22%20-%3E%20%22Python%202%20Interpreter%22%20%5Bstyle%3Ddashed%2C%20label%3D%22%20invokes%22%5D%3B%0D%0A%20%20%20%20%22Python%202%20Interpreter%22%20-%3E%20%22Flask%20Dev%20Server%22%20%5Bstyle%3Ddashed%2C%20label%3D%22%20runs%20(via%20app.py)%22%5D%3B%0D%0A%20%20%20%20%22Flask%20Dev%20Server%22%20-%3E%20%22app.py%22%20%5Bstyle%3Ddashed%2C%20label%3D%22%20hosts%22%5D%3B%0D%0A%0D%0A%20%20%20%20%2F%2F%20Code%20%26%20Logic%20Dependencies%20(Solid%20Arrows)%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22Flask%22%20%5Blabel%3D%22%20uses%20framework%22%2C%20style%3Dbold%2C%20color%3Dred%5D%3B%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22layout.html%22%20%5Blabel%3D%22%20renders%22%5D%3B%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22about.html%22%20%5Blabel%3D%22%20renders%22%5D%3B%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22login.html%22%20%5Blabel%3D%22%20renders%22%5D%3B%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22register.html%22%20%5Blabel%3D%22%20renders%22%5D%3B%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22search.html%22%20%5Blabel%3D%22%20renders%22%5D%3B%0D%0A%20%20%20%20%22app_tests.py%22%20-%3E%20%22app.py%22%20%5Blabel%3D%22%20tests%22%5D%3B%0D%0A%0D%0A%20%20%20%20%2F%2F%20Specification%20%26%20Configuration%20(Dotted%20Arrows)%0D%0A%20%20%20%20%22requirements.txt%22%20-%3E%20%22Flask%22%20%5Bstyle%3Ddotted%2C%20label%3D%22%20specifies%22%5D%3B%0D%0A%20%20%20%20%22requirements.txt%22%20-%3E%20%22Jinja2%22%20%5Bstyle%3Ddotted%2C%20label%3D%22%20specifies%22%5D%3B%0D%0A%20%20%20%20%22requirements.txt%22%20-%3E%20%22Werkzeug%22%20%5Bstyle%3Ddotted%2C%20label%3D%22%20specifies%22%5D%3B%0D%0A%20%20%20%20%22requirements.txt%22%20-%3E%20%22setuptools%22%20%5Bstyle%3Ddotted%2C%20label%3D%22%20specifies%22%5D%3B%0D%0A%20%20%20%20%22Flask%22%20-%3E%20%22Jinja2%22%20%5Bstyle%3Ddotted%2C%20label%3D%22%20uses%22%5D%3B%0D%0A%20%20%20%20%22Flask%22%20-%3E%20%22Werkzeug%22%20%5Bstyle%3Ddotted%2C%20label%3D%22%20uses%22%5D%3B%0D%0A%0D%0A%20%20%20%20%2F%2F%20Data%20Flow%20(Bold%20Arrows)%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22whoknows.db%22%20%5Bstyle%3Dbold%2C%20label%3D%22%20queries%2Fupdates%22%5D%3B%0D%0A%20%20%20%20%22app.py%22%20-%3E%20%22schema.sql%22%20%5Bstyle%3Dbold%2C%20label%3D%22%20initializes%20with%22%5D%3B%0D%0A%20%20%20%20%22layout.html%22%20-%3E%20%22style.css%22%20%5Bstyle%3Dbold%2C%20label%3D%22%20links%22%5D%3B%0D%0A%20%20%20%20%22layout.html%22%20-%3E%20%22monkgroup.png%22%20%5Bstyle%3Dbold%2C%20label%3D%22%20displays%22%5D%3B%0D%0A%7D)**

![Dependency graph](/.github//graphviz.svg)

This semester-long endeavor, guided by our teacher, ANDL, is a deep dive into the practicalities of system architecture, migration strategies, and the art of working with existing, undocumented codebases.

### Expected Technologies & Goals

*   **Legacy Stack (Current):** Flask (Python)
*   **Target Stack (Modern):** Ruby (Sinatra)
*   **DevOps Tooling:** Git, GitHub Actions/Jenkins/GitLab CI, Docker

Our goal is a harmonious blend of revitalization, modernization, and a robust understanding of the system's inner workings. We aim to deliver a fully functional, well-documented, and easily deployable "whoknows" successor that reflects cutting-edge DevOps methodologies.

---

## 🧑‍💻 Meet the Team

We are a tight-knit team of three dedicated students, all pulling in the same direction to conquer the "whoknows" challenge. Our intermediate-level programming experience, combined with two years of focused study, forms the foundation of our collaborative efforts.

*   **[MetteMunch](https://github.com/MetteMunch)** - Datamatiker
*   **[NikoKiru](https://github.com/NikoKiru)** - It-Arkitekt
*   **[SpaceMasterCarlsen](https://github.com/SpaceMasterCarlsen)** - Datamatiker

---

## ✨ Our Philosophy: Innovative Best Practices

At WeKnow, we believe in **innovation through best practices**. Our approach to the "whoknows" project is characterized by:

*   **Continuous Learning:** Embracing new tools and methodologies to solve complex problems.
*   **Collaboration:** Working closely, leveraging each other's strengths to overcome obstacles.
*   **Documentation First:** Ensuring that every discovery and decision is meticulously recorded.
*   **Automate Everything:** Striving to automate repetitive tasks, from testing to deployment.
*   **Code Quality:** Writing clean, maintainable, and testable code.

---

## 📚 Resources & Learning

<p align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white" alt="Ruby" />
  <img src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/sinatra-%23000.svg?style=for-the-badge&logo=sinatra&logoColor=white" alt="Sinatra" />
  <img src="https://img.shields.io/badge/devops-%23007BFF.svg?style=for-the-badge&logo=azure-devops&logoColor=white" alt="DevOps" />
</p>

This organization is also a place for us to share our learning journey. We encourage others (and ourselves!) to explore:

*   [![Syllabus](https://img.shields.io/badge/Course-Syllabus-blue?style=for-the-badge)](https://link-to-your-syllabus.com)
*   [![Learning Resources](https://img.shields.io/badge/Learning-Resources-orange?style=for-the-badge)](https://link-to-your-resources.com)
*   [![Project Docs](https://img.shields.io/badge/Project-Documentation-informational?style=for-the-badge)](https://link-to-your-docs.com)

[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=flat-square)](https://github.com/your-org/your-repo/issues)
---

## 💬 Connect With Us

We're always open to discussions, insights, and feedback from fellow students and the wider community. Feel free to open an issue in one of our repositories or follow our progress!

---

**WeKnow: Demystifying 'whoknows', one commit at a time.**
