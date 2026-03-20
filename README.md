# AI-Email-Prioritization-System-Local-LLM-based-
Built a local AI-powered email assistant that automatically filters and summarizes important emails using a hybrid rule-based and LLM approach, with scheduled execution via cron.

# AI Email Assistant (Local LLM)

## Overview
This project is a local AI-powered email assistant that:
- Fetches emails via Gmail API
- Filters important messages using rule-based scoring
- Summarizes key emails using a local LLM (Qwen2.5)
- Runs automatically via cron

## Features
- Smart email prioritization (Interview / School / Finance)
- Deduplication system (avoid repeated notifications)
- Lightweight local inference (CPU-only)
- Scheduled execution (3 times daily)

## Tech Stack
- Python
- Gmail API (OAuth2)
- Ollama (Qwen2.5 1.5B)
- Cron (Linux scheduling)

## Architecture
Gmail → Rule Filter → LLM → Output → Seen DB
