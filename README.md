# AI Agent Prototype for Financial Data Analysis (FutureData)

## Overview

This repository contains a technical prototype of an AI-assisted system designed for exploratory financial data analysis, anomaly detection, and KPI interpretation.

The system demonstrates how large language models can be combined with classical data processing techniques to support financial analysts in reviewing structured datasets and generating analytical insights.

This project is an experimental implementation and should be considered a research prototype rather than a production system.


## Objectives

The main goal of this prototype is to explore the integration of:

- Natural language interaction with financial datasets
- Automated data analysis pipelines
- Statistical anomaly detection methods
- AI-assisted explanation of financial metrics


## Core Capabilities

- Natural language interface for querying financial data using LLMs (OpenAI API)
- Automated data processing using Pandas and NumPy
- KPI computation and exploratory data analysis
- Anomaly detection using statistical methods (Z-score based approach)
- Generation of Python code for ad-hoc analytical tasks
- Interactive web interface (Flask / Streamlit-based prototype)
- Logging of analysis steps for interpretability

## Live Demo

 https://github.com/AnniRanok/FutureData-AI-Agent/blob/main/static/videos/future-data.mp4


## System Architecture

The system consists of the following components:

<h3>📁 Project Structure</h3>
<pre>
FutureData-AI-Agent/
├── future_data_app/                 # Core application
│   ├── app.py                      # Main logic (OpenAI + Pandas)
│   ├── components/                 # UI components
│   ├── data/                       # Example datasets
│   ├── utils/                      # Helper functions
│   └── requirements.txt            # App dependencies
├── static/                         # Frontend assets
│   ├── js/
│   ├── css/
│   └── videos/
├── templates/
│   └── index.html                  # Landing page
├── app.py                          # Flask / Streamlit entry point
├── main.py                         # Optional CLI / launcher
├── README.md
└── ...
</pre>


## Methodology

The prototype combines:

- Large Language Models (OpenAI GPT-based APIs) for natural language understanding
- Pandas / NumPy for structured data processing
- Scipy statistical methods for anomaly detection
- Rule-based logic for KPI derivation
- Web interface layer for interaction and visualization


## Example Use Case

The system is designed for exploratory financial analysis scenarios such as:

- Loading structured financial datasets
- Identifying outliers and inconsistencies
- Computing basic KPIs and derived metrics
- Generating explanations for observed patterns
- Supporting ad-hoc analytical queries in natural language


## Limitations

This prototype has the following limitations:

- Not connected to live financial systems (e.g. SAP, Oracle, Tagetik)
- No production-grade security or access control
- Limited scalability and performance optimization
- Designed for experimentation and demonstration purposes only


## Status

This project is currently in a **research / prototype stage**.

It is intended for:
- Proof-of-concept validation
- Internal experimentation
- Demonstration of AI-assisted financial analytics workflows


## Tech Stack

- **OpenAI GPT-4 / GPT-3.5** — natural language interface and reasoning layer for financial data queries  
- **Python (Pandas, NumPy, Matplotlib)** — data processing, analysis, and visualization  
- **SciPy (Z-score statistics)** — statistical anomaly detection and outlier analysis  
- **Flask / Streamlit** — interactive web interface and prototype dashboard layer  
- **Web Speech API** — browser-based speech synthesis for user feedback (experimental feature)  

### Data & Integration Layer (experimental)

- **PostgreSQL** — relational data storage (optional / experimental integration)  
- **Airbyte** — data ingestion layer (conceptual integration)  
- **FPDF** — report generation (PDF export)  
- **LangChain** — orchestration experiments with LLM workflows  








