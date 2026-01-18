# Earnexx

Earnexx is a Solana-based rewards and engagement platform that enables users to earn tokens for completing verifiable on-chain and community-driven tasks. The protocol supports transparent reward distribution, wallet-based identity, and scalable campaign execution for Web3 projects.

## Features
- **Task-based rewards for users:** Users earn tokens by completing verifiable tasks within campaigns.
- **On-chain verification of task completion:** All task completions are validated on-chain to prevent fraud.
- **Automatic SPL token distribution:** Rewards are automatically distributed to users without manual intervention.
- **Scalable campaigns with low fees:** Campaigns can run at scale on Solana with minimal transaction costs.
- **Transparent reward tracking:** Users and project teams can verify rewards and completion records on-chain.

## Getting Started / Installation (Developer Mode)
1. Clone or download this repository.
2. Navigate to the project folder: `cd earnexx`
3. Install dependencies:
   - Frontend: `cd frontend && npm install`
   - Backend: `cd backend && npm install`
4. Start local servers:
   - Frontend: `npm run dev`
   - Backend: `npm run start`
5. Connect a Solana wallet (Phantom, Solflare) to the local frontend.
6. Earnexx will now be running locally and ready for testing and development.

## How It Works
1. Connect your wallet to Earnexx.
2. Browse active campaigns and available tasks.
3. Complete tasks, such as joining communities, testing features, or providing feedback.
4. Earn rewards automatically; Earnexx verifies completion on-chain.
5. Check your dashboard to see:
   - Tasks completed
   - Rewards earned
   - Verification status
   - Token balance

Use this information to track your progress and claim rewards safely and transparently.

## On-Chain Elements
Earnexx leverages Solana programs to manage reward distribution, task verification, and authority controls. Key programs include:
- Core reward distribution program
- Task verification logic
- Authority and upgrade mechanisms
- SPL token interactions

## Why a Security Audit Is Required
A security audit ensures:
- Access control and authority models are safe
- Prevention of reward manipulation or double-claim exploits
- Secure handling of SPL tokens and campaign funds
- Readiness for ecosystem adoption and scaling

## Current Status
- MVP complete
- Internal testing in progress
- Preparing for public beta

## Tech Stack
- Solana, Rust, Anchor framework
- SPL Token Program
- Frontend: React, Tailwind CSS
- Backend: Node.js for API and off-chain services

## Repository Structure
- `programs/` – Solana programs
- `tests/` – Program tests
- `frontend/` – Web app interface
- `backend/` – Off-chain APIs and scripts
- `ARCHITECTURE.md` – System design and flow
- `SECURITY.md` – Security considerations and audit scope
- `ROADMAP.md` – Development roadmap
- `LICENSE` – MIT License
- `CONTRIBUTING.md` – Contribution guidelines
- `CHANGELOG.md` – Release history

## Who It’s For
- Web3 projects running community, testnet, or growth campaigns
- DAOs and protocols that need verifiable on-chain engagement
- Early-stage Solana teams preparing for public launch or token distribution

## Contributing
We welcome contributions from developers, designers, and community builders. See `CONTRIBUTING.md` for guidelines on how to contribute.

## Roadmap
See `ROADMAP.md` for detailed milestones.

## Links
- GitHub: https://github.com/bullsniperr/earnexx
- X :https://x.com/earnexx
- Demo: TBD

## Contributors
- Bullsniperr – Founder & Product Lead
- TBD – Development team

## License
MIT License – See `LICENSE` for details.

## Disclaimer
This project is under development. Use at your own risk.
