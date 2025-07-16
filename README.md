#  STOCKX – Stock Exchange Database System

**Contributors:**
- Ram Kulkarni
- Krushnadev Rayjada   
- Sharvil Oza 
- Kushang Chhabria 
- Aditya Iyer 

---

##  Objective

The aim of this project is to build a comprehensive database system for a stock exchange platform. STOCKX helps users:
- Trade equities
- Invest in IPOs
- Explore mutual fund options

The platform provides transparency, secure data management, and detailed stock/company insights, catering to both retail investors and government agencies.

---

##  Motivation

We are passionate about free markets and financial inclusivity. This project is inspired by our belief in giving everyone equal access to a secure, scalable, and fast-performing investment database. STOCKX promotes financial literacy and encourages broader participation in the stock market.

---

##  System Overview

### Key Features:
- **Customer Registration:** Using PAN and DEMAT details.
- **Dedicated Wallet:** Linked with a stock account for easy transactions.
- **Watchlist:** Track your favorite stocks in real-time.
- **Transaction History:** Full transparency on past activities.
- **Portfolio Tracking:** Real-time profit/loss analytics on owned stocks.
- **Investment Options:** IPOs, Mutual Funds, and Stock Market instruments.
- **Company Insights:** Detailed data including HQ location, valuation, and shareholding.

---

##  Database Structure

### Key Entities and Tables:
- `Customer`: Stores customer info (PAN, DOB, DEMAT, etc.)
- `Bank`: Linked to the customer for funding
- `Stock_Account`: Manages user stock activities
- `Wallet`: Tracks account balance
- `Transaction_History`: Tracks each transaction
- `IPO`: Info on Initial Public Offerings
- `Mutual_Funds`: Fund details with returns, locking period, etc.
- `Stock_Details`: Stock info including exchange and growth
- `Watchlist`: Tracks stocks the customer follows
- `Portfolio`: User’s invested stocks and returns
- `Company_Details`: Info on companies listed
- `Holdings`: Major shareholders and their stakes

---

##  Database Design

- **ER Diagram & Relational Diagram:**  
  *Refer to the attached PDF for visual design representations.*

- **Normalization:**
  - All major relations are normalized to **BCNF**.
  - **Minimal Functional Dependencies** were calculated and ensured for all relations.

---

##  Included Scripts

- **DDL Scripts:** Table creation queries  
- **Data Insertion Scripts:** Sample data population  
- **SQL Queries:** Real-world query implementations  



---

##  Technologies Used

- **DBMS:** MySQL / PostgreSQL (based on implementation)
- **Modeling:** ER diagrams and relational schemas
- **Normalization:** BCNF with minimal FD verification

---

##  Sample Queries

- Track user portfolio with real-time profit/loss  
- Get IPO listings by company  
- Explore mutual funds with the best returns  
- View company shareholding structure  
- Filter stocks by growth & dividends  



---

##  Getting Started

1. Import the DDL script to your SQL DB to create tables.
2. Run the data insertion script to populate tables.
3. Execute SQL queries to interact with the STOCKX database.

---

