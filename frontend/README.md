# Glycemic Sentinel Frontend

Angular frontend for the Glycemic Sentinel prototype.

## Overview

This app provides a web interface for running simulated T1D scenarios, tracking agent progress in real time (SSE), and viewing generated insights.

## Prerequisites

- Node.js and npm
- Backend API running at `http://localhost:8080`

## Setup

```bash
git clone https://github.com/maverickkamal/Glycemic-Sentinel.git
cd Glycemic-Sentinel/frontend
npm install
```

## Run

```bash
npm run serve -- --backend=http://localhost:8080
```

App URL: `http://localhost:4200`

## Available Scripts

- `npm start` - Start Angular dev server
- `npm run serve -- --backend=<url>` - Start dev server with backend URL injection
- `npm run build` - Build the app
- `npm run test` - Run unit tests

## Notes

- This frontend depends on backend endpoints such as `/scenarios`, `/get-scenario/`, and `/progress/{session_id}`.
- The overall system is a prototype and uses simulated data; it is not for medical decision-making.
