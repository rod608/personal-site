---
date: '2'
title: 'Bank Failure Warehouse'
cover: './demo.jpg'
github: 'https://github.com/rod608/svb-data-warehouse'
external: 'https://github.com/rod608/svb-data-warehouse'
tech:
  - Python
  - SQL
  - Beautiful Soup
  - AWS S3
  - AWS Redshift
---

A data warehouse that data analysts can use for predicting bank failures.

It was built via an ETL pipeline and consists of stock data, financial statements/ratios, and basic company background information. The data was extracted from 1,178 companies in python via web scraping and the Yahoo Finance API. The extracted raw data was then transformed into processed data via transposing and cleaning with Pandas. The processed data was then loaded into Amazon S3 and housed in Amazon Redshift.
