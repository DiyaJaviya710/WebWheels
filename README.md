# WebWheels
[![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://python.org)
[![Flask Version](https://img.shields.io/badge/flask-2.0+-green.svg)](https://flask.palletsprojects.com)
[![SQLite Version](https://img.shields.io/badge/sqlite-3-blue.svg)](https://sqlite.org)
[![License](https://img.shields.io/badge/license-MIT-red.svg)](LICENSE)

WebWheels - Vehicle Marketplace Platform A comprehensive online vehicle marketplace built with Flask that enables users to buy, sell, and rent vehicles with integrated AI assistance, OTP verification, and custom car building features.

## Features

### User Features
- Authentication - Register/Login with email, phone, or username
- OTP Verification - Email-based OTP for registration and password reset
- Password Reset - Secure forgot password functionality
- Profile Management - Update personal information

### Vehicle Marketplace
- Buy Vehicles - Browse, search, and filter cars for sale
- Sell Vehicles - List vehicles with image uploads and smart pricing
- Rent Vehicles - Hourly, daily, weekly, and monthly rental options
- Wishlist - Save favorite vehicles for later
- Advanced Search - Filter by brand, price, year, fuel type, transmission

### AI Assistant
- Chatbot Interface - Powered by Groq's Llama 3.3 model
- Indian Rupees Pricing - All prices displayed in INR (Lakhs/Crores format)
- Marketplace Statistics - Real-time vehicle statistics
- Buying Guide - Step-by-step purchase assistance

### Custom Car Builder
- Custom Requests - Users can request custom-built vehicles
- Admin Pricing - Admins set prices for custom requests
- Email Notifications - Users notified when price is set
- Accept/Reject - Users can accept or reject admin pricing

### Admin Panel
- Dashboard - Overview of platform statistics
- Vehicle Approval - Approve or reject seller listings
- User Management - View all registered users
- Transaction History - Track all platform transactions
- Custom Request Management - Set prices for custom car requests
- Reports - View revenue and platform metrics

### Payment and Invoicing
- Secure Checkout - Multiple payment methods supported
- Auto-generated Invoices - PDF-style invoices with email delivery
- Number to Words - Amount in words (Indian format)
- Email Invoices - Invoices sent to user email automatically

### Feedback System
- Rate and Review - Users can submit feedback with ratings (1-5)
- Public Display - Approved feedback shown on homepage
- Admin Moderation - Feedback approval system

## Tech Stack

| Category | Technologies |
|----------|-------------|
| Backend | Python 3.8+, Flask |
| Database | SQLite3 |
| AI/ML | Groq API (Llama 3.3 70B) |
| Email | SMTP (Gmail) |
| Security | SHA-256 Hashing, Session Management |
| Frontend | HTML5, CSS3, Jinja2 Templates |
| File Upload | Image upload with validation |

## Prerequisites

- Python 3.8 or higher
- Gmail account for OTP/Invoice emails
- Groq API key (free tier available)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/webwheels.git
cd webwheels

