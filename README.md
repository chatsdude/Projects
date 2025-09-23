# Prompts to Insights for Manufacturing Alarms

This project enables users to ask natural language questions about **alarm events in a manufacturing plant**, and automatically generates relevant **SQL queries**, **aggregations**, and **visual dashboards** — without needing technical expertise.

## Demo

[![Watch the demo](NL2SQLDemo.gif)
---

## What It Does

- Converts **natural language questions** into **SQL queries** over a manufacturing alarm database.
- Automatically generates **interactive dashboards** (bar charts, bar drilldowns etc.) for visualization.
- Uses **LangGraph** and **LangChain** to create an **agentic workflow**, handling multi-step reasoning such as:
  - Query interpretation
  - Metadata awareness
  - Chart type suggestion
  - Response summarization

---

## Features

- **NL → SQL**: Schema-aware LLM prompting to convert plain English to valid SQL queries.
- **Auto Dashboards**: Renders charts based on query intent using `Plotly` and `Streamlit`.
- **LangGraph-based Agent**: Multi-node agent handles parsing, querying, rendering, and responding.
- **Hallucination Reduction**: Implements schema-anchored prompting and few-shot examples to improve fidelity.
- **Configurable Backend**: Works with SQLite based alarm datasets.

---

## 💻 Tech Stack

| Layer           | Tools & Libraries              |
|----------------|---------------------------------|
| LLM Framework   | `LangChain`, `LangGraph`        |
| LLMs Tested     | `GPT-4o-mini`, `LLaMA`                |
| Visualization   | `Plotly`, `Matplotlib`, `Streamlit` |
| Backend DB      | `SQLite` (demo) |
| Language        | Python 3.10+                    |

---

## 📊 Example Queries

- “What were the top 5 alarms by total duration last week?”
- “Show me the daily alarm count trend for Machine 4.”
- “Compare alarm resolution time for Line A vs. Line B.”
- “Visualize the distribution of alarms by type.”

---

# Sales Assistant for Mercedes Benz Electric Vehicles

- Used llama-index and Cohere Command R+ model.
- Utilized RAG operations to enrich the knowledge base with data from Mercedes and the company's official website.
- Scraped up-to-date information from the Mercedes sales website, ensuring access to the latest data on electric vehicles and their capabilities.

[![Watch the demo](https://github.com/chatsdude/Projects/blob/main/Sales%20Chatbot.gif)

# FitKI
- Built a personalized AI based fitness coach application that provides instant feedback on exercise form and gauges its efficiency
- Helps users attain their fitness objectives and tracks their workout regime
- Deployed REST API endpoints on a cloud server to provide visual analytics to the users to keep track of their progress

- ## 💻 Tech Stack

| Layer           | Tools & Libraries              |
|----------------|---------------------------------|
| Pose Estimation   | Quick Pose SDK/Mediapipe       |
| Backend Framework | Flask |
| Backend DB      | `SQLite`|
| Language        | Python 3 for backend and Swift for Mobile UI |

[![Watch the demo](FitKIDemo.gif)

# Computer Vision and Deep Learning (Project)
### Superpixel Clustering and Post-Hoc correction to improve the performance of cloud segmentation from satellite images

#### Abstract:
We implement a 1D-SEUNet model on Superpixel vectors of satelite images to segment out the cloud from the background. Our method aims to reduce the parameters and increase the speed of a conventional segmentation model.

#### Main Libraries used
- Pytorch
- Fast-SLIC
- Rasterio
- Sklearn (MDS and PCA)

#### Model
<img src="https://github.com/SAint7579/ComputerVision_CloudSegmentation/blob/ef8924f6bc06541a6202479526b7824877457dfa/Images/Model.png" alt="Alt Text"></img>

#### Results
<img src="https://github.com/SAint7579/ComputerVision_CloudSegmentation/blob/ef8924f6bc06541a6202479526b7824877457dfa/Images/Results.png" alt="Alt Text" width="800" height="150"></img>

