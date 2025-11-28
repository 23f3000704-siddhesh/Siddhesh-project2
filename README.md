metadata
title: LLM Analysis Quiz Solver
emoji: 🏃
colorFrom: red
colorTo: blue
sdk: docker
pinned: false
app_port: 7860
LLM Analysis - Autonomous Quiz Solver Agent
License: MIT Python 3.12+ FastAPI

An intelligent, autonomous agent built with LangGraph and LangChain that solves data-related quizzes involving web scraping, data processing, analysis, and visualization tasks. The system uses Google's Gemini 2.5 Flash model to orchestrate tool usage and make decisions.

📋 Table of Contents
Overview
Architecture
Features
Project Structure
Installation
Configuration
Usage
API Endpoints
Tools & Capabilities
Docker Deployment
How It Works
License
🔍 Overview
This project was developed for the TDS (Tools in Data Science) course project, where the objective is to build an application that can autonomously solve multi-step quiz tasks involving:

Data sourcing: Scraping websites, calling APIs, downloading files
Data preparation: Cleaning text, PDFs, and various data formats
Data analysis: Filtering, aggregating, statistical analysis, ML models
Data visualization: Generating charts, narratives, and presentations
The system receives quiz URLs via a REST API, navigates through multiple quiz pages, solves each task using LLM-powered reasoning and specialized tools, and submits answers back to the evaluation server.

🏗️ Architecture
The project uses a LangGraph state machine architecture with the following components:
