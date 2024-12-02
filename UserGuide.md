# ProfitPro User Manual

## Table of Contents
1. Introduction
2. System Requirements
3. Using the Application
4. Troubleshooting
5. Frequently Asked Questions (FAQ)


## 1. Introduction

Welcome to the Real-Time Bus Tracking System! This application allows you to monitor bus locations and speeds in real-time. The system consists of a backend that simulates bus movements and processes data, and a frontend that displays this information on an interactive map.

## 2. System Requirements

- 
- 

## 3. Using the Application


## 4. Troubleshooting

- If the map doesn't load, check your internet connection and ensure you have a valid Mapbox API key.
- If bus positions aren't updating, verify that the WebSocket connection is established (check browser console for messages).
- For database connection issues, double-check your MySQL connection string in `main.py`.

## 5. Frequently Asked Questions (FAQ)

Q: How often do bus positions update?
A: Bus positions update in real-time as events are received from the Kafka stream.

Q: Can I track multiple buses simultaneously?
A: Yes, the system is designed to handle multiple assets (buses) concurrently.

Q: Is historical data available?
A: The current version focuses on real-time data. Historical data features may be added in future updates.

## 8. Contact Support

