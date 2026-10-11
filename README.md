# Habit Tracker

Command-line tool in Python that analyses daily habits (study, training, sleep) from a CSV file and generates statistics and charts.

> Status: **v0.1 — in development**

## Goals
- Read daily habit data from a CSV file
- Compute statistics: averages, totals, best/worst days, streaks
- Generate charts with matplotlib
- Run everything from the command line

## Roadmap
- [ ] Sample data and CSV format
- [ ] Load and validate the CSV (OOP)
- [ ] Basic statistics
- [ ] Charts (sleep vs. study, weekly training volume)
- [ ] Command-line interface with argparse
- [ ] Report export (Markdown / PDF)
- [ ] v0.2 — weekly summary in natural language with a local LLM (Ollama)

## CSV format
| column | type | description |
|---|---|---|
| date | YYYY-MM-DD | day |
| study_hours | float | hours studied |
| training_minutes | int | minutes of training |
| sleep_hours | float | hours slept |

## Tech
Python 3 · pandas · matplotlib · argparse

## License
MIT
