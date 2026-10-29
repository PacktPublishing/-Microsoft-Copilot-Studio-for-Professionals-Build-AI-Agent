# Lecture 11: How to Take Action Using Agent Flows to Log Requests and Post Updates to Microsoft Teams

**In this folder:** Agent-Flow-Input-Output-Mapping-Worksheet.docx, Agent-Flow-Input-Output-Planning-Sheet.docx, Teams-Message-Template-Customer-Care.docx, Pashun-Return-Request-Adaptive-Card.json, Log-Return-Request-Flow-Build-Checklist.docx

Start with the Agent Flow Input/Output Mapping Worksheet: it holds the exact inputs and outputs for Post Return Request To Teams (CustomerName, RequestType, OrderNumber, ReturnReason in; PostStatus and PostedAt out) and for Log Return Request. Use the Teams Message Template for the message wording (and the adaptive card JSON if you prefer a card), then follow the Log Return Request Flow Build Checklist for the second build. The Planning Sheet is for your own flow in the Your Turn exercise. If a flow fails, check its Run history first.

The Log Return Request flow writes to the Returns Log list. Use `Resources/Pashun Sports – Returns Log (list schema and sample rows).xlsx` for the column definitions (Title, OrderNumber, RequestType, CustomerEmail, Reason, OrderValue, Status, SubmittedOn) and sample rows.

## To follow along exactly
Have the Pashun Sports T-Shirts team (channel Customer Care), the Returns Log list and the Customer Care Planner plan ready, or use a test channel and list that you own.
