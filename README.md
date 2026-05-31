# Smart Hotel Reservation Agent

## Overview

Smart Hotel Reservation Agent is an AI-powered hotel discovery and booking assistant that combines Large Language Models (LLMs), workflow automation, and conversational interfaces to simplify hotel search and reservation workflows.

The application enables users to search hotels, compare prices across booking platforms, and complete reservations through a multi-step conversational experience.

Built using Python, Streamlit, Google ADK, and Gemini LLM.

---

## Problem Statement

Travelers often need to compare hotel prices across multiple booking platforms and manually navigate complex booking workflows.

This project streamlines the process by providing:

* Conversational hotel search
* AI-powered recommendations
* Booking workflow automation
* Price comparison aggregation
* Guided reservation assistance

---

## System Architecture

```text
User
 │
 ▼
Streamlit Frontend
 │
 ▼
Gemini LLM Agent
 │
 ├───────────────┐
 │               │
 ▼               ▼
Hotel Search     Booking Agent
Agent            Workflow Agent
 │               │
 ▼               ▼
Price Engine     Booking State
Comparison       Management
 │
 ▼
Structured Response
Generation
```

---

## Key Features

### Conversational Hotel Search

* Natural language hotel search
* Location-based recommendations
* AI-assisted filtering

### Price Comparison Engine

* Aggregates hotel pricing
* Compares multiple booking platforms
* Identifies lowest-cost options

### Multi-Step Reservation Workflow

* Room selection
* Date selection
* Guest information collection
* Booking confirmation

### State Management

* Tracks booking progress
* Maintains user workflow state
* Supports cancellation and restart functionality

### Structured AI Responses

* JSON-based hotel data generation
* Typed validation using Pydantic
* Consistent response formatting

---

## AI Engineering Components

### LLM Integration

* Gemini 2.0 Flash
* Google ADK
* LiteLLM

### Prompt Engineering

* Structured prompts
* Guided booking interactions
* Hotel recommendation generation

### Agent-Based Workflow Design

* Hotel Search Agent
* Booking Workflow Agent
* State-aware conversation handling

---

## Technology Stack

### AI Layer

* Gemini 2.0 Flash
* Google ADK
* LiteLLM

### Backend

* Python
* Pydantic

### Frontend

* Streamlit

---

## Repository Structure

```text
smart_hotel_agent/
│
├── agent.py
├── requirements.txt
├── README.md
```

---

## Sample User Queries

```text
Find hotels in Miami under $200 per night

Show luxury hotels in New York

Book The Leela Palace for 2 guests

Confirm booking
```

---

## Engineering Highlights

* Designed an agent-based AI workflow using Gemini LLM
* Implemented conversational reservation workflows
* Built structured hotel search and recommendation system
* Developed state-aware booking management process
* Integrated tool-driven hotel search functionality
* Used Pydantic models for structured AI outputs

---

## Future Improvements

* RAG-based travel recommendations
* Real hotel API integrations
* Persistent booking storage
* Authentication and user accounts
* Email booking confirmations
* Multi-agent orchestration using LangGraph

---

## Author

Aryanmouli Cherupalli

Software Engineer | Java | Spring Boot | AI Applications | Cloud
