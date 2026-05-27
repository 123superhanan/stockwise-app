# StockWise - AI-Powered Inventory Management

**Smart receipt scanning + demand forecasting for small businesses**

## Overview

StockWise helps small business owners automate inventory tracking by scanning receipts. The AI extracts products, quantities, and prices, then updates stock levels automatically. A demand forecaster predicts future sales and sends reorder alerts.

## Problem Solved

Small business owners waste hours manually entering receipts into spreadsheets. Stockouts cost sales. Overstock ties up cash. StockWise solves both.

## Features

| Feature | Description |
| :--- | :--- |
| Receipt Scanner | Take photo → AI extracts items, prices, date, total |
| Inventory Tracking | Auto-updates stock levels from receipts |
| Demand Forecast | Predicts next week's sales using LSTM/Prophet |
| Low Stock Alerts | Push notification when stock falls below threshold |
| Sales Analytics | Dashboard with trends and insights |

## Tech Stack

| Layer | Technology |
| :--- | :--- |
| Frontend | React Native (Expo) |
| Backend | Node.js + Express |
| AI Service | FastAPI (Python) |
| Database | Supabase (PostgreSQL) |
| ML Models | YOLOv8, LayoutLM, LSTM |
| OCR | PaddleOCR |
| Deployment | Render + Hugging Face |

## Architecture
