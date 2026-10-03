# Hi, I'm Chyrus Miguel 👋

**Python Automation & Data Engineering | Software Engineering | Computer Science Undergraduate**

I am a Computer Science student at **Pampanga State University (Bacolor)** who enjoys building practical software that automates repetitive work, processes real-world data, and solves problems through reliable engineering.

My current focus is **Python automation, data processing/ETL, and software engineering**. I enjoy working beyond simply making something "work"—I care about testing, debugging, resource usage, maintainability, and turning personal projects into software that can actually be packaged and shipped.

---

### 🚀 Featured Project

#### 🧹 [CleanSheet – Spreadsheet Data Processing & Automation](https://github.com/Migelitz/CleanSheet)

> **A Python desktop application for combining, inspecting, cleaning, and transforming spreadsheet datasets.**

CleanSheet started as a personal automation project and evolved into a complete desktop application with a focus on practical data-processing workflows and software quality.

* **Data Processing & ETL:** Built workflows for ingesting spreadsheet data, validating datasets, cleaning and transforming records, and exporting processed results.
* **Python Automation:** Automates repetitive spreadsheet-processing tasks that would otherwise require manual manipulation or separate scripts.
* **Resource-Aware Processing:** Implements chunked CSV processing and disk-backed XLSX workflows for larger datasets while monitoring memory and processing behavior.
* **Data Quality Analysis:** Detects missing values, sentinel values, type inconsistencies, duplicates, numerical statistics, correlations, and categorical characteristics.
* **Software Engineering:** Developed a multithreaded Tkinter application with background processing, logging, update checking, diagnostic reporting, and cross-platform packaging.
* **Testing & Validation:** Includes automated functional tests, GUI testing, file-format testing, edge-case validation, and workload benchmarking.
* **Release Engineering:** Packaged and published the application for Windows and Linux using Nuitka and GitHub Actions.

**Status:** First public release — **v1.0.0**

---

### 🧠 Software Engineering Projects

#### 📂 [SortFlow – Automated File Organization Utility](https://github.com/Migelitz/SortFlow)

> **A Python automation utility that continuously organizes files from a user's Downloads directory.**

SortFlow started as a simple file-organizing script and evolved into a background automation service designed around reliability and safe file handling.

* **Filesystem Automation:** Automatically categorizes and moves supported files into organized destination directories based on file type.
* **Background Processing:** Uses filesystem monitoring, worker threads, queues, and synchronization to process files without blocking the application.
* **Reliable File Handling:** Waits for files to become stable before processing and ignores unsupported files and directories.
* **Duplicate Handling:** Prevents overwriting existing files by generating unique destination names when necessary.
* **Structured Logging:** Uses rotating log files to record application activity and failures.
* **Testing:** Includes automated tests covering classification, file organization, duplicate handling, watcher behavior, and edge cases.
* **Linux Integration:** Can run as a `systemd` service for continuous background automation.

#### 🚗 [AutoVal – Full-Stack Car Valuation & ML Analytics Platform](https://github.com/ThreeBytes-Studio/AutoVal)

> **An end-to-end ML web application for predicting second-hand vehicle values.**

* **Role:** Project Lead & Database/Backend Engineer
* **System Architecture:** Designed the data flow between the frontend, FastAPI backend, ML engine, and cloud database.
* **Data Pipeline:** Built a Python/Pandas seeding pipeline that cleaned, filtered, and stratified **100,000+ raw listings** before loading them into the database.
* **Database Engineering:** Designed PostgreSQL schemas and database access modules using `psycopg`.
* **Backend Integration:** Built data-access functionality for serving historical listing data through the API.
* **Team Development:** Managed code reviews and pull requests while verifying database and backend integration.

---

#### 🛡️ [Sentinel Risk Engine](https://github.com/Migelitz/sentinel-risk-engine)

> **A real-time transaction scoring system combining Python machine learning with Java and C++.**

This project represents an earlier step in my software engineering growth, where I explored integrating machine-learning models with compiled systems and backend services.

* Transpiles trained Python XGBoost models into C using `m2cgen`.
* Executes the generated model through a C++ JNI bridge.
* Integrates with a Java 17 transaction-processing service.
* Uses SQLite for transaction auditing.
* Includes a Python retraining pipeline that processes recorded transaction data.

---

### ⚙️ What I Like Building

* **Python automation** — Automating repetitive data and file-processing workflows.
* **Data processing & ETL** — Extracting, validating, transforming, cleaning, and exporting structured data.
* **Desktop utilities** — Building practical tools with Python and Tkinter.
* **Software engineering** — Designing maintainable applications rather than one-off scripts.
* **Testing & debugging** — Writing tests, reproducing edge cases, investigating failures, and validating behavior.
* **Performance & reliability** — Measuring resource usage and considering how applications behave with larger workloads.
* **Developer tooling** — Packaging, logging, CI/CD, configuration, and release workflows.

---

### 🛠 Tech Stack & Tools

**Primary**

![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge\&logo=numpy\&logoColor=white)

**Data & Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge\&logo=postgresql\&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge\&logo=sqlite\&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge\&logo=microsoftexcel\&logoColor=white)

**Python Application Development**

![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge\&logo=pytest\&logoColor=white)

**Software Engineering & Tooling**

![Git](https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge\&logo=github\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=github-actions\&logoColor=white)
![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge\&logo=Linux%20Mint\&logoColor=white)

**Additional Experience**

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge\&logo=c%2B%2B\&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge\&logo=openjdk\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge\&logo=fastapi)

---

### 🧪 Engineering Practices

I try to treat personal projects as opportunities to practice real software engineering workflows.

* Automated testing with `pytest`
* Manual GUI and functional testing
* Edge-case and failure-path validation
* Debugging and root-cause investigation
* Performance and memory measurements
* Structured application logging
* Background processing and concurrency
* Git-based version control
* Continuous integration and automated builds
* Cross-platform application packaging
* Documentation and technical testing reports

---

### 🏆 Achievements & Certifications

* **2nd Runner Up – RAITE Regional Programming Competition (Region 3)**
* *CodeChum Programming Challenge:* Competed as part of a 4-member team solving algorithmic problems against 18 regional universities.
* **Intro to Machine Learning Certificate** – Kaggle
* **Microsoft Office Specialist: Excel Associate** – Microsoft Certified

---

### 📚 Academic & Technical Focus

* **Software Engineering:** Application architecture, testing, debugging, maintainability, and release engineering.
* **Python Automation & Data:** Data processing, ETL workflows, spreadsheet automation, validation, and transformation.
* **Systems:** Multithreading, resource-aware processing, native integration, and Linux development.
* **Machine Learning:** Model development, data preparation, and ML system integration.
* **Mathematics:** Differential Calculus, Linear Algebra, and Discrete Mathematics.

---

### 📫 Let's Connect

* 📧 **Email:** [macalla.chyrusmiguel@gmail.com](https://www.google.com/search?q=mailto%3Amacalla.chyrusmiguel%40gmail.com)

---

> **I build it, test it, debug it, and ship it.**
