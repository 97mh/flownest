FlowNest

A Local Desktop Application for X Account and Direct Message Management

FlowNest is a personal desktop application designed to manage multiple authorized X (formerly Twitter) accounts from a unified interface.

The project focuses on secure account authentication, direct message management, rule-based automated responses, and conversation workflow automation using the official X API.

Features

The following features are planned or under development:

Multi-Account Management — Connect and manage multiple personally owned X accounts using OAuth 2.0.

Direct Message Management — Retrieve and organize direct message conversations across authorized accounts.

Rule-Based Automated Replies — Respond to incoming messages using predefined rules and configurable templates.

Conversation Workflows — Manage multi-stage conversation flows and message states.

Media Support — Support image messages where permitted by the X API.

Analytics — Track conversation activity, response performance, and workflow outcomes.

Local Data Storage — Store application data locally without requiring a cloud database.

Secure Authentication — Use OAuth 2.0 with PKCE and secure credential storage.

Technology Stack

Backend: Java 21, Spring Boot 3

Desktop: Tauri 2

Frontend: Vue 3, TypeScript

UI: Element Plus

Storage: Local JSON and JSONL files

X API Usage

FlowNest uses the official X API for authorized account management and direct message operations.

Each X account is connected through an explicit OAuth authorization process. API access is limited to the permissions granted by the account owner and supported by the X API.

The application is intended for personal account management and legitimate communication automation.

FlowNest is designed to respect API rate limits, user opt-out requests, privacy requirements, and applicable X platform policies.

Privacy and Security

OAuth credentials and access tokens are stored securely on the local device.

Account passwords are not collected or stored.

Conversation data is processed locally by default.

User data is not sold or publicly redistributed.

Automated messaging is subject to platform permissions and applicable policies.

Project Status

Status: Early Development

FlowNest is currently under development. Features described in this document may not yet be available.

This repository serves as the project's public information page. The application is not currently offered as a public service.

Disclaimer

FlowNest is an independent personal development project and is not affiliated with, endorsed by, or sponsored by X Corp.
