# multi-sig-payroll-app
Next.js decentralized application (dApp) providing an administrative dashboard for wallet connections, CSV roster uploads, and visual multi-sig tracking.

# Multi-Sig Payroll Router Dashboard

A user-facing decentralized application (dApp) built to provide multi-sig coordinators and corporate administrators with a visual interface to manage corporate funds, propose payroll distribution rosters, authorize active payroll proposals, and execute payouts seamlessly.

## Features
- **Wallet Connection:** Deep integration with top Stellar wallets (Freighter, Albedo, Hana) for secure on-chain transaction signing.
- **Multi-Sig Proposal Dashboard:** A visual tracking interface showing which administrators have signed a payroll execution payload and how many more authorizations are required.
- **Roster File Processing:** Drag-and-drop CSV parser allowing admins to upload employee wallet addresses and distribution amounts instantly.

## Tech Stack
- Next.js (App Router)
- React
- Tailwind CSS
- Freighter Wallet API

## Development Setup
Copy the environment template and configure your network:
```bash
cp .env.example .env.local
