# Latency Logger CLI Tool

A simple command-line tool to measure and log the network latency (in milliseconds) for any given URL. Uses HTTP GET requests to benchmark response times over multiple attempts and outputs both a terminal report and a CSV log file.

---

##  Features

- Measure HTTP latency for a given URL
- Display formatted results in the terminal using [Rich](https://github.com/Textualize/rich)
- Log each attempt's latency with timestamps into `logs/latency_log.csv`
- Handle timeouts gracefully
- Easily configurable from the command line

---

##  Tech Stack

- Python 3
- `requests` – for HTTP requests
- `argparse` – for CLI argument parsing
- `rich` – for terminal table display
- `csv`, `time`, `datetime` – for logging and timestamps

---

##  How to Run

### 1. Install requirements

```bash
pip install requests rich
