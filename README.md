# LapShop Database

This repository contains the SQL Server database schema for **LapShop**, a sample inventory & sales management system for laptop retail.

## Table of Contents

- [Overview](#overview)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Database Schema](#database-schema)  
  - [Core Tables](#core-tables)  
  - [Identity Tables](#identity-tables)  
  - [Relationships](#relationships)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)

---

## Overview

The **LapShop** database supports:
- Product categorization (categories, item types, OS).
- Inventory tracking (items with stock/price).
- Sales & purchase invoicing.
- User authentication & authorization via ASP.NET Identity.

---

## Prerequisites

- **SQL Server** (2016+)
- **SQL Server Management Studio** (or `sqlcmd` CLI)

---

## Installation

1. **Clone this repo**  
   ```bash
   git clone https://github.com/YourUsername/LapShopDatabase.git
   cd LapShopDatabase
