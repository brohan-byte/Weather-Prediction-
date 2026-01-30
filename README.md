# Real-Time Weather Prediction Pipeline

This project implements a **real-time weather data streaming and prediction system** using **Apache Kafka** for ingestion and **Apache Spark ML** for machine learning–based forecasting.

## Overview
Weather data is continuously streamed through Kafka topics, processed in real time using Spark, and fed into a machine learning pipeline to generate weather predictions. The system is designed to be **scalable, fault-tolerant, and efficient**, making it suitable for large-scale streaming workloads.

## Features
- Real-time ingestion of weather data using **Apache Kafka**
- Stream processing with **Apache Spark Structured Streaming**
- Machine learning models built with **Spark ML**
- Scalable, distributed architecture
- Fault-tolerant streaming pipeline

## Tech Stack
- **Apache Kafka** – distributed streaming platform
- **Apache Spark** – stream processing and analytics
- **Spark ML / MLlib** – machine learning models
- **Python / Scala** (update based on implementation)

## Machine Learning
- Feature extraction from streamed weather data
- Model training using historical data
- Real-time inference on streaming inputs
- Supports regression-based prediction (e.g., temperature, rainfall, humidity)

## How It Works
1. Weather data is published to Kafka topics.
2. Spark consumes data using Structured Streaming.
3. Incoming data is transformed and cleaned.
4. Spark ML models perform real-time predictions.
5. Predictions are output to a sink (console, file, database, or Kafka topic).
