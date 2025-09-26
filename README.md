# ReactorTrade Core ⚛️

**ReactorTrade Core** is the central backend engine for the ReactorTrade platform. It provides a high-performance, event-driven architecture for trade execution, order management, real-time market data processing, and risk management. This repository contains API documentation, and developer guides for the core service.

The system is designed to be a robust, scalable, and low-latency foundation for building sophisticated trading strategies and connecting with various liquidity providers and exchanges.

## Key Features

  * **High-Throughput Order Matching Engine:** Built for speed and reliability.
  * **RESTful & WebSocket APIs:** Provides flexible options for both request-response and real-time streaming interactions.
  * **Multi-Asset Support:** Designed to handle RWA, cryptocurrencies, and perpetual pairs.
  * **Extensible Connector Architecture:** Easily integrate with new exchanges and market data providers.
  * **Robust Risk Management:** Real-time position monitoring.

-----

## 🚀 Getting Started :WIP

Follow instructions within each supporting repositories to get a local instance of ReactorTrade tools running for development and testing. 

## 🔌 API Documentation

The ReactorTrade API provides access to all core trading and data functionalities.

**Base URL:** `TBA`

### Authentication

All API bot requests must be authenticated using wallet signing instructions (will provided with the version 0.9.0 beta public release). The signature must be sent with every action request.

Requests made without a valid pr expired signature will result in a `401 Unauthorized` error.

### API Endpoints :WIP

Below are examples of core endpoints. For a complete list and detailed specifications, please refer to our OpenAPI/Swagger documentation.

-----

## 📈 Integration Guide

This section provides guidance on how external clients and services can integrate with ReactorTrade Core.

-----

## 🧑‍💻 Developer Guide :WIP

Information for developers contributing to the ReactorTrade Core codebase.

-----

## 🤝 Contributing & Issue Logging

Contributions are welcome\! We are always looking for improvements and new features.

### Contribution Workflow for tooling repositories

1.  **Fork** the repository.
2.  Create a new feature branch: `git checkout -b feature/MyNewFeature`.
3.  Make your changes and commit them: `git commit -m 'Add: MyNewFeature'`.
4.  Push your changes to your fork: `git push origin feature/MyNewFeature`.
5.  Open a **Pull Request** against the `main` branch of this repository.

### Logging Issues

If you encounter a bug or have a feature request, please use the **Issues** tab on GitHub.

  * **For Bug Reports:** Please use the "Bug Report" template and provide detailed steps to reproduce the issue, including logs, environment details, expected behavior, and actual behavior.
  * **For Feature Requests:** Please use the "Feature Request" template and describe the problem you are trying to solve and your proposed solution.

-----
