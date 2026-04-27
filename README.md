# retail-churn-pipeline

End-to-end customer churn analysis for a UK e-commerce retailer.

## Overview
Full data pipeline from raw transactional data through to an interactive
Power BI dashboard with ML-based churn predictions.

## Stack
- SQL Server (Azure SQL Edge in Docker)
- Python 3.11
- scikit-learn
- Power BI

## Project phases
1. Data engineering - schema design, loading pipeline, data cleaning
2. Analysis - RFM segmentation, churn definition and validation
3. Machine learning - churn prediction model, score write-back
4. Dashboard - Power BI connected to SQL Server

## Dataset
Online Retail II (UCI / Kaggle) - 1M+ transactional rows, 2009-2011.
See data/raw/README.md for setup.

## Getting started
docker compose up -d