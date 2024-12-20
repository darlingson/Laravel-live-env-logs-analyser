# Laravel Live Environment Logs Analyzer

## **Project Overview**

The **Laravel Live Environment Logs Analyzer** is a tool designed to analyze logs from live Laravel applications in real-time. It scans log files to identify recurring errors, exceptions, and frequently used features. By providing insights into your app’s log data, it helps to pinpoint problem areas, track usage trends, and improve performance.

### **Key Features**

- **Log Error Detection**: Automatically identifies and highlights recurring errors and exceptions in your Laravel application's log files.
- **Feature Usage Tracking**: Analyzes logs to detect which features are being used most frequently by your users.
- **Live Monitoring**: Continuously monitors log files for new data, providing real-time insights into the health and usage of your app.
- **AI-Powered Analysis**: Leverages Gemini AI to provide intelligent analysis of your app's log data, offering actionable insights for optimization.

---

## **Motivation**

When managing a live Laravel application, keeping track of errors and feature usage is crucial for maintaining a smooth user experience. While Laravel provides robust logging capabilities, manually sifting through log files can be time-consuming and inefficient. This tool automates the process, offering developers an easy way to stay on top of app performance and quickly identify areas for improvement.

---

## **Getting Started**

### **Prerequisites**
Before you start, ensure you have the following installed on your machine:

- **Go** (version 1.XX or later)
- **Git**
- **Laravel application with logging enabled**

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/darlingson/Laravel-live-env-logs-analyser.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Laravel-live-env-logs-analyser
   ```
3. Install the dependencies:
   ```bash
   go mod download
   ```
4. Build the project:
   ```bash
   go build -o laravel-live-env-logs-analyser
   ```
5. Run the tool:
   ```bash
   ./laravel-live-env-logs-analyser
   ```
