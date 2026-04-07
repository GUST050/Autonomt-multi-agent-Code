# multi-agent-code-reviewer
**A multi-agent AI system built with LangGraph that automatically reviews code, finds issues, and fixes them.**

![Python](https://img.shields.io/badge/Python-3.11%2B-blue)
![LangGraph](https://img.shields.io/badge/LangGraph-0.2+-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## What it does

This project creates an autonomous AI review team that:

- Analyzes pull requests and code changes
- Performs professional code reviews (security, quality, performance, bugs)
- Automatically suggests and applies fixes when possible
- Runs tests and iterates until issues are resolved
- Provides clear feedback and full audit trails

Built with **LangGraph** for advanced multi-agent orchestration and stateful workflows.

---

## Key Features

- Multi-agent architecture (Supervisor + specialized agents)
- Security & quality analysis (OWASP, code smells, performance)
- Automated remediation with GitHub integration
- Human-in-the-loop support
- Token usage and cost tracking
- LangSmith observability

---

## Quick Start

```bash
git clone https://github.com/GUST050/Autonomt-multi-agent-Code.git
cd Autonomt-multi-agent-Code

cp .env.example .env
pip install -e .

Add your API keys in .env, then run:
Bashpython src/main.py
