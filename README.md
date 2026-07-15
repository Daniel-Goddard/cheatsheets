# 📚 Cheat Sheets

A small collection of single-page, dark-themed quick references — each one a self-contained HTML file styled like a poster, easy to skim, print, or keep open in a tab while you work.

![style: dark](https://img.shields.io/badge/style-dark-0A0E17)
![type: reference](https://img.shields.io/badge/type-cheat--sheet-F2C14E)

**🔗 Live index:** [daniel-goddard.github.io/python_cheatsheet](https://daniel-goddard.github.io/python_cheatsheet/)

## 📋 What's included

### 🐍 [Python Cheat Sheet](python_libraries_cheatsheet.html)
Covers the core language plus the most-used data & ML libraries.

- **Python Core** — Basics, Control Flow, Functions & Classes, Errors, Files & JSON, Comprehensions, Async & Modules, Typing & Debugging, Operators, Time/Datetime, Statistics, Strings, Collections (Set/Dict/List), OS & File I/O, Random & Math, method examples (Input → Method → Output), handy one-liners, a mini password-generator project, and a data type comparison matrix
- **Libraries** — Pandas, NumPy, Matplotlib, Scikit-learn, Seaborn, TensorFlow/Keras, PyTorch, XGBoost

Each section is color-coded and grouped into logical categories (creation, cleaning, training, plotting, evaluation, etc.), formatted as function → description tables or runnable code blocks.

### 🐘 [PostgreSQL Cheat Sheet](postgresql_cheatsheet.html)
Covers core SQL syntax through to advanced query patterns.

- **SQL Fundamentals** — Core Syntax (SELECT/WHERE/ORDER BY), Conditions (LIKE/IN/BETWEEN/CASE), Joins & Unions, Grouping (GROUP BY/HAVING/EXISTS), CTEs & Subqueries, Data Modification (INSERT/UPDATE/DELETE)
- **Dates** — every date format and filter pattern for the SELECT and WHERE clauses (`to_char`, `EXTRACT`, `date_trunc`, rolling windows, exact period matches)
- **Aggregates & Window Functions** — sums/ratios/averages, a window functions overview (`OVER`, `PARTITION BY`, frame clauses), running totals, `LAG`/`LEAD`/`RANK`, period-over-period growth calculations
- **Procs & Operators** — stored procedures/functions, comparison/logical/arithmetic operators, conditional aggregation & string building

### 📐 [Math for Data Science, ML & AI](math_ds_ml_ai_cheatsheet.html)
Covers the math that actually shows up in data science and machine learning, tiered by level.

- **Beginner / Intermediate / Advanced** sections spanning linear algebra, calculus, probability, statistics, optimization, and information theory
- Each concept ties back to where it's actually used (PCA, backprop, attention, regularization, etc.) with a runnable Python snippet underneath

## 🚀 Usage

**View them live:** [daniel-goddard.github.io/python_cheatsheet](https://daniel-goddard.github.io/python_cheatsheet/)

Or run any of them locally — they're plain HTML files with no build step or dependencies.

1. Download the file you want (e.g. `python_libraries_cheatsheet.html`)
2. Open it in any browser — double-click it, or:
   ```bash
   open python_libraries_cheatsheet.html      # macOS
   start python_libraries_cheatsheet.html     # Windows
   xdg-open python_libraries_cheatsheet.html  # Linux
   ```

## 🌐 Hosting on GitHub Pages

This repo is already set up with GitHub Pages, serving `index.html` (a small landing page linking to each cheat sheet) from the `main` branch root.

If you fork this repo or set it up elsewhere:
1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set the source branch (e.g. `main`) and root folder.
3. Your cheat sheets will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## 🛠️ Built with

- Plain HTML/CSS — no frameworks, no build tools
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter), and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to use, modify, and share it, just keep the copyright notice.

## 🤝 Contributing

Spot an error or want to add a cheat sheet? Pull requests are welcome — just keep the existing color/section structure consistent when adding new content.
