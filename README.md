# CRM Management System

A comprehensive Customer Relationship Management (CRM) system with mobile and web applications, built for lead management, order tracking, sales processing, and vendor/truck management.

## 🚀 Features

- **Leads Management**: Track leads with contact info, status, and assignment
- **Orders Management**: Create and manage orders with real-time status updates
- **Sales Tracking**: Process payments and track sales transactions
- **Client Management**: Maintain detailed client information
- **Vendor Management**: Manage vendors and services
- **Truck Management**: Track trucks and drivers
- **User Management**: Role-based access control
- **Dashboard**: Real-time analytics and KPIs
- **Real-time Notifications**: Stay updated on important events
- **Bulk Import/Export**: CSV import and export functionality
- **Search, Filter & Sort**: Advanced data filtering capabilities
- **Automated Workflows**: Auto-update statuses and assignments
- **Multi-channel Integration**: WhatsApp and WeChat integration

## 📱 Tech Stack

### Frontend
- **Web**: React.js with Material-UI
- **Mobile**: React Native with Expo

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT + bcrypt
- **Real-time**: Socket.io
- **File Upload**: Multer

## 📁 Project Structure

```
crm-app/
├── backend/              # Express.js backend API
├── web/                  # React web application
├── mobile/               # React Native mobile app
├── docker-compose.yml    # Docker configuration
├── .env.example          # Environment variables template
└── README.md            # This file
```

## 🛠️ Quick Start

### Prerequisites
- Node.js (v16+)
- PostgreSQL (v12+)
- npm or yarn

### Backend Setup

```bash
cd backend
npm install
cp .env.example .env
npm run migrate
npm start
```

### Web App Setup

```bash
cd web
npm install
npm start
```

### Mobile App Setup

```bash
cd mobile
npm install
npm start
```

## 📖 API Documentation

Base URL: `http://localhost:5000/api`

### Main Modules

1. **Leads** - `/api/leads`
2. **Orders** - `/api/orders`
3. **Sales** - `/api/sales`
4. **Clients** - `/api/clients`
5. **Vendors** - `/api/vendors`
6. **Trucks** - `/api/trucks`
7. **Drivers** - `/api/drivers`
8. **Users** - `/api/users`
9. **Dashboard** - `/api/dashboard`

## 🔐 Security Features

- JWT-based authentication
- Password hashing with bcrypt
- Role-based access control (RBAC)
- Input validation and sanitization
- SQL injection prevention
- CORS configuration

## 📝 Database Tables

- users, leads, clients, orders, sales
- vendors, trucks, drivers, notifications, audit_logs

## 📄 License

MIT License

---

**Created for efficient business management and sales operations**