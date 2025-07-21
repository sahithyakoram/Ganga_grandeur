# Technical Documentation: The Ganga Grandeur

This document details the technical architecture, APIs, and data models for the AI Concierge project.

## 1. System Architecture

*(We will add a diagram and description here showing how the Frontend, Backend, and LLM API connect.)*

## 2. API Endpoints

*(We will document our FastAPI endpoints here as we create them.)*

### `POST /chat`
* **Description:** Main endpoint for communicating with the AI agent.
* **Request Body:** `{"user_id": "string", "message": "string"}`
* **Response Body:** `{"response": "string", "sentiment": "string"}`

## 3. Database Schema

*(Details of our SQLite database tables.)*

### `bookings` table
* `id` (INTEGER, PRIMARY KEY)
* `user_id` (TEXT)
* `room_type` (TEXT)
* `booking_date` (TEXT)
* `timestamp` (DATETIME)

## 4. Deployment

*(Instructions and notes on deploying the frontend and backend services.)*
