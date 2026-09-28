# 🏦 FS Banking Customer 360  Platform — Snowflake Data Engineering Project

## 📌 Project Overview

The **FS Banking Platform** is an end-to-end banking data engineering project built using **Snowflake**.

The project demonstrates how raw banking data can be ingested, validated, cleaned, transformed, modeled, secured, automated, and exposed for analytics using Snowflake.

The project also integrates **Snowflake Cortex Analyst** for natural-language analytics and **Streamlit** for a banking analytics dashboard.

---

## 🎯 Objective

To build an end-to-end banking data platform using Snowflake for:

- Data ingestion
- Data validation
- Data cleaning and standardization
- Data transformation
- Dimensional modeling
- Automated data loading
- Data security
- SQL analytics
- AI-powered analytics
- Business dashboard reporting

---

## 🏗️ Project Architecture

```text
SOURCE DATA
    →
INTERNAL STAGE
    →
RAW
    →
DATA VALIDATION
    →
STAGING
    →
CLEANING & STANDARDIZATION
    →
CURATED
    →
FACT & DIMENSION TABLES
    →
STREAMS & TASKS
    →
SECURITY
    →
VIEWS & UDFs
    →
CORTEX ANALYST
    →
STREAMLIT DASHBOARD
