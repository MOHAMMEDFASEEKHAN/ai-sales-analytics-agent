# Interview Questions & Answers

## 1. What problem does this project solve?

This project reduces the manual effort required to analyze sales data and prepare business reports. Users can ask business questions in natural language and receive data-driven insights from the connected sales dataset.

## 2. Why did you use n8n?

n8n was used to orchestrate the AI agent, data source, memory, and reporting workflow without building the entire integration layer from scratch.

## 3. How does the AI Agent access sales data?

The AI Agent uses a connected Google Sheets tool as the primary source of sales data.

## 4. What KPIs can the agent calculate?

The agent can calculate metrics such as:

- Total Revenue
- Total Orders
- Units Sold
- Average Order Value
- Total Profit
- Profit Margin
- Return Rate
- Cancellation Rate

## 5. How does the agent detect anomalies?

The agent is instructed to identify unusual sales values, discounts, negative profit, returns, cancellations, sudden sales increases or decreases, and unusual salesperson performance.

## 6. How do you prevent the AI from inventing data?

The agent is explicitly instructed to use the actual available sales data and never fabricate numbers, customers, trends, causes, or unavailable information.

## 7. How does conversational memory help?

Memory allows the agent to maintain relevant context across messages so that follow-up questions can refer to previous analysis.

## 8. Why is profit analysis important?

Revenue alone does not show business profitability. A high-revenue product may have a low profit margin because of discounts or costs.

## 9. What happens when the user asks for an email report?

The agent can generate an executive-style sales report and use the connected Gmail tool when the user explicitly requests an email or report.

## 10. What is the main business value of the project?

The project converts raw sales data into understandable business insights and actionable recommendations, helping users make data-driven decisions faster.

## 11. What would you improve in the future?

Potential future improvements include adding automated dashboards, scheduled reporting, stronger data-validation pipelines, database integration, role-based access, and additional analytics capabilities.
