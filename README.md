# Accessibility Baseline & Repository Architecture Audit

## 1. Project Overview

This project is an accessibility and architecture audit of the DigiLocker public service website.

Website audited: https://www.digilocker.gov.in/

The purpose of this audit is to identify accessibility issues using Lighthouse and keyboard-only navigation, document the findings, and create a basic monorepo-style full-stack project structure.

## 2. Audit Scope

The audit focused on:

- Accessibility issues identified by Google Lighthouse
- Keyboard-only navigation
- WCAG-related accessibility requirements
- User impact of accessibility problems
- Recommended remediation
- Basic repository architecture

## 3. Tools Used

- Google Chrome Lighthouse
- Keyboard-only navigation
- GitHub
- GitHub Desktop
- CSV for audit documentation

## 4. Repository Structure

```text
accessibility-baseline-audit/
├── client/
├── server/
├── docs/
│   ├── accessibility-audit.csv
│   └── screenshots/
└── tests/