<div align="center">

# Fintrivx-WorldBanks360: Loan Comparison & AI Advisory Platform

A smart global bank comparison platform that helps users compare loan products across the world’s top 300 banks. It provides detailed information on home loans, car loans, and credit cards, including interest rates, required documents, EMI calculations, official bank redirects, and AI-powered assistance.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Flow](#api-flow)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Author](#author)

---

## Overview

**fintrivx-WorldBanks360** is a full-stack financial advisory platform built to simplify bank and loan comparison.  
Users can explore the top 300 global banks, compare loan offers, review required documents, calculate EMI, and get redirected to the official bank pages for further action.

The platform also includes AI chatbot integration to assist users with loan-related queries and product discovery.

---

## Features

- Compare loan products across 300 global banks.
- View home loan, car loan, and credit card details in one place.
- Compare interest rates, eligibility, and required documents.
- Calculate EMI instantly using a built-in EMI calculator.
- Redirect users to the official bank page for trusted next steps.
- AI chatbot integration for guided assistance and recommendations.
- Backend support with middleware and webhook handling.
- PostgreSQL database for structured financial data management.
- React Hooks-based frontend for dynamic and responsive UI.
- Fast and scalable API-driven architecture.

---

## Tech Stack

- **Frontend:** React, React Hooks
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Integration:** Webhooks, Middleware
- **AI:** Chatbot integration
- **Other:** REST APIs, EMI calculator logic

---

## Project Structure

```bash
fintrivx-WorldBanks360/
├── frontend/
├── backend/
├── database/
├── middleware/
├── webhooks/
├── public/
├── src/
├── README.md
└── package.json

## Run and Deploy

## Run Locally

**Prerequisites:**  Node.js

1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
