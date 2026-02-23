

# 🏦 RBI Hackathon — Money Mule Account Detection using Behavioral Banking Analytics

## 📌 Overview

Financial institutions continuously face risks from **money mule accounts**, which are used to transfer and launder illegally obtained funds. Detecting such accounts is a critical component of modern **Anti-Money Laundering (AML)** and fraud prevention systems.

This project presents an **Exploratory Data Analysis (EDA)** of a large-scale multi-table banking dataset provided as part of the **Reserve Bank Innovation Hub Hackathon**.

The objective is to identify **behavioral, transactional, and network-based patterns** that distinguish mule accounts from legitimate banking customers.

---

## 🎯 Problem Statement

Money mule accounts typically exhibit abnormal transaction behavior such as:

- Rapid fund movement
- High counterparty interaction
- Sudden activity bursts
- Structuring of transactions
- Short operational lifespan

The goal of this analysis is to:

- Understand banking transaction behavior
- Identify mule account indicators
- Engineer model-ready behavioral features
- Prepare data for downstream machine learning models

---

## 📊 Dataset Description

The dataset represents approximately **5 years of banking activity (July 2020 – June 2025)** and consists of multiple relational tables:

| Dataset | Description |
|----------|-------------|
| Customers | Demographics & KYC information |
| Accounts | Account-level attributes |
| Transactions | ~7.4M transaction records |
| Customer-Account Linkage | Customer–Account mapping |
| Product Details | Financial product holdings |
| Train Labels | Mule vs Legitimate accounts |
| Test Accounts | Accounts for prediction |

Due to confidentiality and hackathon restrictions, datasets are **not included** in this repository.

---

## 🔗 Data Relationships
