# Learning-Resources

# ⚡ 2-Month Python + GitHub Copilot Curriculum

A structured 8-week plan to take you from **basic Python** to **professional software development** with GUIs, APIs, modularity, and Copilot mastery.  

---

## 📍 Week 1 — Setup & Python Refresh
**Goals**  
- Set up development environment  
- Enable GitHub Copilot in VS Code  
- Refresh Python syntax & basics  
- Learn Git basics  

**Topics**  
- Python: variables, functions, loops, data types  
- Git: clone, branch, commit, push/pull  
- Copilot setup in VS Code  

**Resources**  
- [Python Official Tutorial](https://docs.python.org/3/tutorial/index.html)  
- [GitHub Copilot Quickstart](https://docs.github.com/copilot/quickstart)  
- [Copilot in VS Code: Getting Started](https://code.visualstudio.com/docs/copilot/getting-started)  
- [GitHub Skills: Intro to GitHub](https://skills.github.com/)  

**Deliverable**  
A CLI script (e.g., calculator or JSON parser) with type hints + docstrings, version-controlled in Git.  

---

## 📍 Week 2 — Professional Python Practices
**Goals**  
- Write code with professional structure & standards  
- Learn error handling, logging, testing  

**Topics**  
- OOP (classes, inheritance, composition)  
- Error handling & logging (`logging` module)  
- Virtual environments (`venv`, pip)  
- Unit testing with `pytest`  

**Resources**  
- [PEP 8 Style Guide](https://peps.python.org/pep-0008/)  
- [Logging HOWTO (Python Docs)](https://docs.python.org/3/howto/logging.html)  
- [pytest Getting Started](https://docs.pytest.org/en/stable/getting-started.html)
- [Python Docs — venv](https://docs.python.org/3/library/venv.html)  
- [Installing Packages with pip and venv (Python Packaging Guide)](https://packaging.python.org/en/latest/tutorials/installing-packages/)  
- [RealPython: Python Virtual Environments Primer](https://realpython.com/python-virtual-environments-a-primer/)  

**Deliverable**  
A Python package (e.g., math utilities) with logging + pytest test suite.  

---

## 📍 Week 3 — PyQt5 Fundamentals
**Goals**  
- Build basic desktop GUIs  
- Structure GUIs for maintainability  

**Topics**  
- PyQt5: widgets, layouts, signals/slots  
- Qt Designer → `.ui` → Python code  
- Threads & timers for background tasks  

**Resources**  
- [PyQt5 Tutorial (Python GUIs)](https://www.pythonguis.com/tutorials/pyqt5/)  
- [RealPython: PyQt GUI Programming](https://realpython.com/pyqt-gui-tutorial/)  
- [Qt for Python Model/View Tutorial](https://doc.qt.io/qtforpython/tutorials/datavisualize/index.html)  

**Deliverable**  
A PyQt5 “Dashboard” app with buttons to start/stop a process and a live counter.  

---

## 📍 Week 4 — APIs & Async Programming
**Goals**  
- Connect apps to external APIs  
- Handle async tasks properly  

**Topics**  
- REST APIs: GET/POST with `requests`  
- JSON parsing  
- Async tasks (`threading`, `asyncio`)  
- Data visualization (matplotlib, PyQtGraph)  

**Resources**  
- [Requests: HTTP for Humans](https://docs.python-requests.org/en/latest/)  
- [RealPython: API Integration in Python](https://realpython.com/api-integration-in-python/)  
- [asyncio Official Docs](https://docs.python.org/3/library/asyncio.html)  

**Deliverable**  
A GUI that fetches live data from a public API (e.g., weather or crypto) and plots results.  

---

## 📍 Week 5 — Modular Projects & Plugins
**Goals**  
- Structure larger projects cleanly  
- Implement plugin/extension systems  

**Topics**  
- Modular architecture (packages, imports)  
- Plugin/extension patterns (dynamic loading)  
- Config files (JSON, YAML)  
- Writing documentation (README, docstrings)  

**Resources**  
- [Python Packaging Tutorial (PyPA)](https://packaging.python.org/tutorials/packaging-projects/)  
- [RealPython: Plugin Architecture in Python](https://realpython.com/python-plugins/)  
- [MkDocs for Documentation](https://www.mkdocs.org/)  

**Deliverable**  
Extend Week 4 project with a plugin system that adds new “panels” or features dynamically.  

---

## 📍 Week 6 — Copilot Mastery & Code Quality
**Goals**  
- Use Copilot effectively for scaffolding & refactoring  
- Enforce maintainability & readability  

**Topics**  
- Copilot prompt engineering (Context → Task → Constraints)  
- Copilot Chat for debugging, tests, docs  
- Code formatting (`black`, `flake8`)  
- Auto-generating docs/tests with Copilot  

**Resources**  
- [Prompt Engineering for Copilot (GitHub Docs)](https://docs.github.com/en/copilot/concepts/prompting/prompt-engineering)  
- [Write Tests with Copilot](https://docs.github.com/en/copilot/tutorials/write-tests)  
- [Black Code Formatter](https://black.readthedocs.io/en/stable/)
- [Best practices for using GitHub Copilot](https://docs.github.com/en/copilot/get-started/best-practices)  
- [Prompt engineering for GitHub Copilot Chat](https://docs.github.com/en/copilot/concepts/prompting/prompt-engineering)  
- [5 Tips for Writing Better Custom Instructions for Copilot (GitHub Blog)](https://github.blog/ai-and-ml/github-copilot/5-tips-for-writing-better-custom-instructions-for-copilot/)  
- [Best practices for using Copilot to work on tasks (Coding Agent)](https://docs.github.com/copilot/how-tos/agents/copilot-coding-agent/best-practices-for-using-copilot-to-work-on-tasks)  
- [Microsoft Learn: Introduction to Prompt Engineering with GitHub Copilot](https://learn.microsoft.com/en-us/training/modules/introduction-prompt-engineering-with-github-copilot/)  

**Deliverable**  
Refactor earlier projects with Copilot → enforce PEP-8, add tests, auto-generate README/docs.  

---

## 📍 Week 7 — Advanced Python & Collaboration
**Goals**  
- Apply advanced design practices  
- Work in GitHub workflows like a professional  

**Topics**  
- Design patterns (Observer, Factory, Singleton)  
- Async/parallel programming patterns  
- Packaging & distribution with Poetry/setuptools  
- GitHub workflows: PRs, reviews, CI/CD  

**Resources**  
- [RealPython: Python Design Patterns](https://realpython.com/tutorials/design-patterns/)  
- [Poetry Official Docs](https://python-poetry.org/docs/)  
- [GitHub Actions: Python CI](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python)  

**Deliverable**  
A modular GUI app with at least 2 plugins, tested + CI workflow on GitHub.  

---

## 📍 Week 8 — Capstone Project
**Goals**  
- Apply everything in one end-to-end project  

**Capstone Project:**  
**Modular Control Suite**  
- PyQt5 UI with multiple panels (status, logs, control)  
- API integration (fetch + send data)  
- Plugin system for extensibility  
- Logging + error handling  
- Tests + GitHub repo with CI/CD + documentation  

**Deliverable**  
A polished GitHub repository with:  
✅ PyQt5 GUI  
✅ API integration  
✅ Plugins/extensions  
✅ Tests & CI/CD  
✅ Documentation  

---

# 🎯 Outcomes After 2 Months
By the end of this program, you will be able to:  
- Write clean, modular Python code with tests & docs  
- Build professional GUIs in PyQt5  
- Integrate REST APIs with error handling  
- Create plugin/extension systems  
- Use Copilot effectively for prompting, debugging, and refactoring  
- Work with GitHub workflows like a professional developer  
