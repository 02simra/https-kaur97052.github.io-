# 🚨 Life Saver - Emergency Monitoring System

A comprehensive real-time emergency monitoring and alert system with Super Admin and User dashboards.

## Features

✅ **Super Admin Dashboard**
- Real-time alert monitoring
- Device management across all users
- User management
- Emergency map view

✅ **User Dashboard**
- Personal device monitoring
- SOS emergency button
- Alert history

## Quick Start

```bash
npm install
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000)

## Key API Endpoints

- `POST /api/auth/login` - User login
- `POST /api/auth/register` - User registration
- `POST /api/alerts` - Create alert
- `POST /api/webhook/esp32` - ESP32 webhook

## Dashboards

- **User:** `/dashboard/user`
- **Admin:** `/dashboard/admin`
