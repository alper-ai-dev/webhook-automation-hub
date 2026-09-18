# Webhook Automation Hub

Event-driven automation portfolio project for receiving, validating and routing business webhook events through a serverless API.

## Features
- Real POST webhook endpoint: `/api/webhook`
- Event-type validation
- JSON payload validation
- Event ID generation
- Event-to-workflow routing
- HTTP error handling
- Interactive webhook tester
- Automation event log
- Response-time measurement
- Responsive dashboard

## Supported Events
- `lead.created` → CRM pipeline
- `order.completed` → Fulfillment workflow
- `support.requested` → Support queue
- `invoice.paid` → Finance workflow

## Architecture
Browser Dashboard → POST /api/webhook → Validation → Event Router → Workflow Result → Dashboard Log

The serverless endpoint performs real request validation and routing. The workflow destinations are intentionally simulated for this public portfolio demo; no external client systems or credentials are used.

## Stack
HTML5, CSS3, JavaScript, Vercel Serverless Functions, REST/JSON, Web Storage API.

## Portfolio
Built by Alper Sancar to demonstrate webhook integrations, event-driven backend logic, API validation, automation routing and dashboard development.