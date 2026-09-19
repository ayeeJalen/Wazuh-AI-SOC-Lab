# 🛡️ Wazuh AI-Assisted SOC Alert Triage Lab

## Overview

This project demonstrates an end-to-end Security Operations Center (SOC) workflow using **Wazuh**, **Atomic Red Team**, **MITRE ATT&CK**, **PowerShell**, and **AI-assisted alert triage**.

The goal of this lab was to simulate suspicious activity on a monitored Windows endpoint, detect that activity using Wazuh, use AI to assist with the initial investigation, and then manually verify the AI's conclusions.

A major focus of this project was understanding how AI can assist SOC analysts while also identifying why **human validation is still necessary before making a final decision on a security alert**.

---

## 🔬 Lab Workflow

```text
Atomic Red Team
      │
      ▼
Windows Endpoint
      │
      │ Wazuh Agent
      ▼
Wazuh Manager / SIEM
      │
      ▼
Security Alert
      │
      ▼
AI-Assisted Triage
      │
      ▼
Human Verify & Correct
