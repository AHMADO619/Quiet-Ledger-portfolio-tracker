[README.md](https://github.com/user-attachments/files/32203145/README.md)
# Quiet Ledger — Portfolio Tracker

A Flask-based web app for tracking an investment portfolio: holdings, transactions, and overall performance, backed by a local SQLite database.

## Features

- **Dashboard** — at-a-glance stat cards, a net worth line chart, and a portfolio allocation donut chart
- **Holdings** — view current positions and their values
- **Transactions** — log and review buy/sell activity over time
- **Data visualization** — interactive charts built with Chart.js
- **News** — integration to surface relevant financial news for held assets

## Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** HTML/CSS, Chart.js
- **Tooling:** Built with the help of Claude Code, using prompt engineering to scaffold features and speed up debugging

## Project Structure

```
quiet_app.py     # Main Flask application and routes
sql.py           # Database layer (SQLite queries)
charts.py        # Chart data preparation
news.py          # News/API integration
templates/       # HTML templates
static/          # CSS/JS/assets
```

## Getting Started

```bash
git clone https://github.com/AHMADO619/Quiet-Ledger-portfolio-tracker.git
cd Quiet-Ledger-portfolio-tracker
pip install -r requirements.txt
python quiet_app.py
```

Then open `http://localhost:5000` in your browser.

## Status

This is an active learning/portfolio project, built to practice full-stack Python development, database design, and API integration.

## Author

**Ahmad Obeidat**
[LinkedIn](https://www.linkedin.com/in/ahmad-obeidat-937112310/) · [GitHub](https://github.com/AHMADO619)
