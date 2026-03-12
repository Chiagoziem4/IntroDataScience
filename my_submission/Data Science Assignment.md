# Week 1 Learning Summary
## By Egbogu Chiagoziem

## Python
Python is a beginner-friendly, readable programming language widely used in data science, automation, web development, and AI. Its clean syntax, extensive standard library, and massive community make it one of the most in-demand skills across tech and research.

## Marimo
Marimo is a reactive Python notebook that stores notebooks as plain `.py` files instead of JSON (`.ipynb`). Key advantages over Jupyter: cells auto-update when dependencies change, no hidden state, fully reproducible top-to-bottom execution, and native Git compatibility.

## Git Version Control
Git is a distributed version control system where every developer holds a full copy of the project history. Core concepts: **commit** (snapshot of changes), **branch** (isolated development line), **merge** (combining branches), and **push/pull** (syncing with a remote). Git is the tool; GitHub/GitLab are simply platforms that host Git repos online.

## Plotly Visualization
Plotly is an interactive visualization library (Python, R, JavaScript) that produces browser-ready charts supporting hover, zoom, pan, and filter. It offers three layers: **Plotly Express** (quick one-liners), **Plotly Graph Objects** (full customization), and **Dash** (complete dashboard/web app framework).

## Polars Data Wrangling
Polars is a high-performance DataFrame library and a faster, more memory-efficient alternative to Pandas. It uses lazy evaluation to optimize queries before execution and can handle datasets larger than available RAM — ideal when Pandas starts to slow down.

## VS Code
VS Code is a free, lightweight yet powerful code editor by Microsoft that sits between a basic text editor and a full IDE. Standout features: IntelliSense (autocomplete + error detection), integrated terminal, built-in Git panel, a vast extension marketplace, and Live Share for real-time collaboration.

## UV Package Management
`uv` is a blazing-fast (10–100× faster than `pip`) Python package and project manager that replaces `pip`, `pip-tools`, and `virtualenv` in one tool. Key features: automatic virtual environments, a lockfile (`uv.lock`) for reproducible installs, built-in Python version management, and `uvx` for running one-off tools without global installs.

## Data Science
Data science extracts insights from data using statistics, programming, and domain knowledge. The standard workflow: **Collect → Clean → Explore (EDA) → Model → Communicate**.

**Core Python toolkit:**

| Task | Libraries |
|---|---|
| Data Wrangling | Pandas, Polars |
| Numerics | NumPy |
| Visualization | Matplotlib, Plotly |
| Machine Learning | Scikit-learn |
| Deep Learning | PyTorch, TensorFlow |

Applied across healthcare, business, research, public sector, and climate science.

## Markdown
Markdown is a lightweight markup language that formats plain text using simple symbols, rendering cleanly as HTML. It's the universal standard for developer documentation — used in GitHub READMEs, Jupyter notebooks, docs sites (MkDocs, Docusaurus), and platforms like Slack, Discord, and Reddit. Core syntax covers headings, lists, links, images, code blocks, tables, and blockquotes.