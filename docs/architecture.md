# System Architecture

## Overview

The AI-Powered Sales Analytics & Business Intelligence Agent is an n8n-based conversational analytics system.

It connects a user-facing chat interface with an AI Data Analyst Agent, Google Sheets sales data, conversational memory, and Gmail reporting.

## Architecture Flow

User
↓
n8n Chat Trigger
↓
AI Data Analyst Agent
├── OpenAI Chat Model
├── Conversational Memory
├── Google Sheets Sales Data
└── Gmail Reporting
↓
Business Analysis
↓
Insights & Recommendations

## Components

### 1. Chat Trigger

Receives natural-language questions from the user and starts the workflow.

### 2. AI Data Analyst Agent

Acts as a Senior Data Analyst and interprets the user's business question.

It is instructed to use actual sales data, validate information, calculate relevant KPIs, identify trends and anomalies, and provide actionable recommendations.

### 3. OpenAI Chat Model

Provides the language-model reasoning capability used by the AI Agent.

### 4. Conversational Memory

Maintains relevant conversation context so follow-up questions can reference previous analysis.

### 5. Google Sheets

Acts as the primary sales-data source for the AI Agent.

### 6. Gmail

Allows the agent to generate and send executive-style sales reports when explicitly requested by the user.

## Data Analysis Capabilities

The agent can analyze:

- Revenue
- Orders
- Units Sold
- Average Order Value
- Profit
- Profit Margin
- Product Performance
- Salesperson Performance
- Trends
- Anomalies
- Returns
- Cancellations
- Business Risks
- Recommendations

## Business Decision Flow

Raw Sales Data
↓
Data Retrieval
↓
Data Validation
↓
KPI Calculation
↓
Trend & Anomaly Analysis
↓
Business Insights
↓
Actionable Recommendations
↓
Optional Executive Report

## Design Principle

The system is designed to go beyond simply reporting numbers.

It follows:

Observation
→ Evidence
→ Business Impact
→ Recommendation
