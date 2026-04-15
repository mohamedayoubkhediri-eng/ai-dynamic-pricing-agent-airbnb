# AI Dynamic Pricing Agent (n8n + AI)

## Overview
This project is an AI-powered dynamic pricing system for Airbnb listings.  
It automatically analyzes market demand and competitor prices to recommend optimal pricing.

## Tech Stack
- n8n (workflow automation)
- AI Agent (LLM)
- Tavily API (event detection)
- HasData API (Airbnb competitor data)
- Telegram API (notifications)

## How it works
1. The workflow runs automatically
2. It collects:
   - events in the city (demand)
   - competitor Airbnb listings
3. The AI agent analyzes the data
4. It decides:
   - increase / decrease / keep price
5. The result is sent via Telegram

## Example Output
- Action: Increase
- Suggested Price: 140€
- Reason: High demand due to event + higher competitor prices

## Key Features
- AI-based decision making
- Real-time data integration
- Fully automated workflow
