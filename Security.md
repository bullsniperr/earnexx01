# Security Policy for Earnexx

## Overview
Earnexx is a Solana-based rewards and engagement platform. Security is critical because the protocol manages token distribution, task verification, and on-chain reward tracking. This document outlines our security practices, audit scope, and risk considerations.

## Supported Versions
- Solana programs built with Rust and Anchor framework
- SPL Token Program interactions
- Frontend: React, Tailwind CSS
- Backend: Node.js for off-chain services

## Audit Scope
The security audit should cover the following areas:

1. **Core Programs**
   - Reward distribution logic
   - Task verification
   - Authority and upgrade mechanisms
   - SPL token transfers and handling

2. **Access Control**
   - Admin authority and program upgrade keys
   - Wallet authentication and task claim verification

3. **Data Integrity**
   - Verification of task completion and reward calculations
   - Protection against double claims or reward manipulation

4. **On-Chain Security**
   - Cross-program invocations (CPI)
   - Safe handling of lamports and token accounts
   - Event logging for transparency

5. **Off-Chain Components**
   - Backend APIs and scripts
   - Frontend interactions and wallet connections

## Risk Considerations
- Improper authority management could allow unauthorized token distribution
- Logic errors may allow double claims or reward misallocation
- Off-chain services must not compromise on-chain reward integrity

## Reporting Vulnerabilities
If you discover a security issue, please report it immediately via our official contact channels:

- Email: security@earnexx.io (TBD)
- Telegram: @EarnexxOfficial

We take all reports seriously and will respond promptly.

## Disclaimer
Earnexx is under active development. All contributors, auditors, and users should exercise caution when interacting with the platform. Use at your own risk.
