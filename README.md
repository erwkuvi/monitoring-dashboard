# monitoring-dashboard

A frontend-first web product that visualizes system metrics in 2D dashboards + a focused 3D interactive view.

## Simulated Problem

> As a user, I want to monitor the status and performance of a system in real-time, understand anomalies quickly, and interact with a visual representation of the system.

## What does it not solve

> This project is intentionally scoped as a Frontend-focused MVP.
It does not aim to be a production-ready monitoring platform nor a full-stack system.

## Key Features

**A. Application Shell (Frontend Fundamentals)**
- React + TypeScript
- Clean layout (sidebar + main content)
- Routing (2 - 3 pages max)
- Responsive Layout
- Global state for selected system / filters

---

**B. 2D Dashboard (Product Thinking)**
**Metrics Panel**
- System status (Ok / Warning / Critical)
- Key metrics (mocked):
	- Temperature
	- Energy usage
	- Load / performance
**Charts**
- Line chart for historical data
- Filter by time range (last hour / day / week)

**States**
- Loading
- Empty
- Error

---

**C. 3D Interactive View (Your Differentiator)**
A single, focused 3D scene - not a playground.
Example:
- A simplified 3D model of an industrial machine / energy system
- Parts change color based on system state
- Hover or click highlights components
- Selecting a component updates dashboard metrics

Important constraints:
- Only One scene
- No fancy shaders
- No overengineering
Purpose: visual explanation, not eye candy.

---

**D. Data layer (Realistic, Simple)**
- Mock API (JSON or simple service)
- Simulated real-time updates (interval-based)
- Typed data models (TypeScript)

