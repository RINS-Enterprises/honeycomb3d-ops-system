# 🐝 HoneyComb 3D Operations System

An internal management system for handling 3D printing products, orders, and profit tracking.

---

## 🧠 Overview

This system is built to streamline HoneyComb's internal workflow by replacing manual tracking and spreadsheets with a structured, scalable solution.

---

## ⚙️ Tech Stack

- Frontend: Appsmith  
- Database: Baserow  
- Mobile Packaging: PWABuilder  

---

## 📦 Core Features

- Product management system  
- Multi-item order creation  
- Automatic profit calculation  
- Category-based product organization  
- Filament usage tracking  
- Mobile-ready interface  

---

## 🧱 System Architecture

Products → Order Items → Orders

- Products define what is sold  
- Order Items connect products to orders with quantity and profit  
- Orders group multiple items into a single transaction  

---

## 💰 Profit Logic

Profit is calculated in the frontend (Appsmith):

Profit = (Price × Quantity) - (Cost × Quantity)

The calculated value is stored and aggregated at the order level.

---

## 📱 Mobile App

Appsmith App → PWA → Android APK (via PWABuilder)

---

## 🎯 Purpose

This is an internal operations tool, not a customer-facing application.

It is designed to:
- Improve efficiency  
- Reduce manual errors  
- Track business performance  

---

## 🚀 Status

Actively used for internal operations  
Continuously improving  

---

## 🔗 Related Project

HoneyComb 3D Ecommerce System (customer-facing website)

---

## 📌 Future Improvements

- Dashboard (profit, analytics)  
- Inventory tracking system  
- Order history interface  
- Mobile UI optimization  

---
