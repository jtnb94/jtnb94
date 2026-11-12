# Installation & Setup Guide

## Prerequisites
- Node.js 18+
- PostgreSQL 14+
- npm or yarn

## 1. Database Setup
Create a PostgreSQL database named `mywebsite`.

## 2. Backend Setup
```bash
cd server
npm install

# Copy environment file and configure
cp .env.example .env
# Edit .env with your database credentials

# Generate Prisma client and push schema
npx prisma generate
npx prisma db push

# Seed database with default roles and admin user
npx prisma db seed

# Start development server
npm run start:dev
```

## 3. Frontend Setup
```bash
cd client
npm install
npm run dev
```

## Running the Application
- **Frontend:** http://localhost:8080 (or https://localhost:8080)
- **Backend API:** http://localhost:6969/api
- **Default Admin Login:** `admin@example.com` / `admin123` (or username `admin`)
