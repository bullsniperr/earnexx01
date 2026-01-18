# Earnexx Architecture

## Overview
Earnexx is a Solana-based rewards and engagement platform. It connects users, projects, and Solana programs to provide task-based rewards with on-chain verification.

## System Components

### 1. Frontend
- React application with Tailwind CSS
- User wallet connection (Phantom, Solflare)
- Campaign and task dashboard
- Reward tracking and display

### 2. Backend
- Node.js API server
- Task validation logic
- Off-chain data processing (if needed)
- Communication with Solana programs

### 3. Solana Programs
- Reward Distribution Program
- Task Verification Program
- Authority & Upgrade Control Program
- SPL Token Management

## Data Flow
1. User connects wallet to frontend.
2. User completes tasks displayed on dashboard.
3. Backend records completion (if necessary) and interacts with Solana programs.
4. Solana programs verify task completion and distribute rewards.
5. Frontend updates dashboard with reward status.

## Security Considerations
- Access control enforced by authority program
- Double-claim and reward manipulation prevention
- SPL token safety

## Deployment
- Programs deployed on Solana mainnet/testnet
- Frontend hosted via web platform
- Backend hosted via Node.js server

## File Structure
- `programs/` – On-chain programs
- `frontend/` – Web interface
- `backend/
