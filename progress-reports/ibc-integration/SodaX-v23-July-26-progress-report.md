# SodaX - July 2026 Progress Update

## Intro
This progress report is for SodaX related development work by Venture23 Team.
The next phase of the project will focus on SodaX Phase 1 development and deployment. The report is from  1-Jul-2026 to 31-Jul-2026

## Summary
For more details please see : <br>

https://github.com/icon-project/intent-relay<br>
https://github.com/icon-project/sodax-contracts<br>
https://github.com/icon-project/sodax-frontend<br>
https://github.com/icon-project/sodax-solver-v2<br>
https://github.com/icon-project/sodax-backend<br>
https://github.com/icon-project/go-sodax-monitor-be<br>
https://github.com/icon-project/intent-contracts

## Milestones
Milestone 1 - SodaX Mainnet - Phase1 - TBD


## Deliverables Ready

| Name | Development State | Notes | Source / location |
|:----- |:------------------ | :----| :----------------|
| Smart Contract Security Audit Remediation (7 findings) | Completed | Contracts | https://github.com/icon-project/sodax-contracts/issues/682 |
| JitoSOL LST as Collateral | Completed | Contracts | https://github.com/icon-project/sodax-contracts/issues/649 |
| Relay Verifier Config & Setup — All Chains | Completed | Relay | https://github.com/icon-project/intent-relay/issues/435 |
| Relay Reverted Delivery Tx Fix (dst_tx_hash) | Completed | Relay | https://github.com/icon-project/intent-relay/issues/478 |
| Failover RPC Manager — All Liquidity Feeders (Solana, NEAR, SUI, Stellar, EVM, Hub, Stargate) | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/622 |
| ETH LST Token Integrations | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/561 |
| Flying Tulip Solver Integration | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/528 |
| CCIP — Liquidity Feeder | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/673 |
| Hedera DEX Liquidity Feeder (SaucerSwap V2) | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/763 |
| xSTOCK Pools in Solana Raydium CLMM | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/766 |
| Path Splitting — Near Intent Implementation | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/638 |
| Execution Module V2 | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/531 |
| Solver Observability — Logging & Visualisation | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/856 |
| Near Solver Performance Metrics | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/905 |
| Liquidity Feeders Dashboard Management | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/906 |
| Legacy Executor Cleanup & ICON Chain Removal | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/749 |
| Security Hotfixes (Rate-Limit Bypass, Slippage, Port Clash) | Completed | Solver | https://github.com/icon-project/sodax-solver-v2/issues/959 |
| EPIC: Status Page Backend (Summary, Asset Health, Reserve Config, Notices, 90-Day Uptime) | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/996 |
| Gasless API | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/929 |
| Leverage Yield API v2 | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/985 |
| Partner Portal Endpoints V1 | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/932 |
| EPIC: Shared Stateful MongoDB — Phase 5 Prod Cutover | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/826 |
| Automatic DB Backup Deployment & Missed-Backup Watcher | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/904 |
| Swaps API Production Hardening (Terminal Status, Drainer, Solver-FAILED Recovery) | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/882 |
| MM Liquidator Give-Up Latch + Dashboard Surface | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/1003 |
| Oracle Outage Alert + Candles TTL | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/946 |
| Incident Re-Notifier (Hourly Re-Page for Unresolved Incidents) | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/957 |
| Sonic RPC Failover + Provider Health Alerting | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/784 |
| Faster Event Processing (Tick-Cadence + Configurable Confirmations) | Completed | Backend | https://github.com/icon-project/sodax-backend/issues/700 |
| Frontend Security Audit Remediation — All 6 Phases (XSS/CSP, SDK, Financial UX, API Abuse Controls, Secret Hygiene, CMS Auth) | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1556 |
| SODAX Solana Landing Page + Integration Guide + Animations | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1563 |
| B2B World — Design System & Homepage Build | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1492 |
| Hedera DAppKit & Wallet SDK Support | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1382 |
| SDK v2 Swap Component & Partner Claim Fee Migration | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1497 |
| SODAX Assets Page — Filters Update | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1522 |
| SODAX Homepage — Full Design + B2B World + Mobile + Infographic Videos | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1526 |
| Nonce-Based Strict Script-src CSP | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1580 |
| Rotating News Bar in Navbar | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/1534 |
| Web Analytics Setup (sodax.com) | Completed | Frontend | https://github.com/icon-project/sodax-frontend/issues/444 |
| Solana Token Account Creation Fee Alert | Completed | Monitor | https://github.com/icon-project/go-sodax-monitor-be/issues/119 |
| Hub Pause / Unpause Feature | Completed | Monitor | https://github.com/icon-project/go-sodax-monitor-be/issues/117 |
| Hardcoded God API Key Security Fix | Completed | Monitor | https://github.com/icon-project/go-sodax-monitor-be/issues/127 |


## In Progress

| Name | Development State | Notes | Source / location |
|:----- |:------------------ | :----| :----------------|
| TRON-RELAY — Hot-Wallet Signer + Listener | In Progress | Relay | https://github.com/icon-project/intent-relay/issues/466 |
| TRON-SOLVER — Coordinator, Executor & Liquidity Modules | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/908 |
| TRON-FRONTEND — Tron Support in Frontend + SDK | In Progress | Frontend | https://github.com/icon-project/sodax-frontend/issues/1500 |
| TRON-BACKEND — Tron Monitor, Indexer & Solver-Balance Tracking | In Progress | Monitor | https://github.com/icon-project/go-sodax-monitor-be/issues/111 |
| 0G Chain — Intent Relay / MPC-Relay Support | In Progress | Relay | https://github.com/icon-project/intent-relay/issues/455 |
| 0G Chain — Backend Indexing & Data Support | In Progress | Backend | https://github.com/icon-project/sodax-backend/issues/716 |
| CCIP — Coordinator, Executor, Ops & Docs (Full Integration) | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/674 |
| Meteora (DLMM + DAMM v2) — Solana Liquidity Source | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/841 |
| Balancer V2 — Liquidity Source Integration | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/840 |
| HyperEVM — HyperSwap V3 / Project X / Ramses Liquidity Sources | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/843 |
| PancakeSwap Infinity (CLAMM) on BSC | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/923 |
| Li.Fi — Liquidity / Bridge Adapter Integration | In Progress | Solver | https://github.com/icon-project/sodax-solver-v2/issues/784 |
| EPIC: Partner-Ready Swap Provider API (Bitcoin.com Spec) | In Progress | Backend | https://github.com/icon-project/sodax-backend/issues/740 |
| Partner API Keys + Critical Endpoint Gating | In Progress | Backend | https://github.com/icon-project/sodax-backend/issues/864 |
| In-House USD Analytics Data Pipeline | In Progress | Backend | https://github.com/icon-project/sodax-backend/issues/865 |
| Wallet HW Support — Ledger + Trezor (EVM), Phase 1 | In Progress | Frontend | https://github.com/icon-project/sodax-frontend/issues/1361 |
| apps/web Test Foundation + CI Test Gate | In Progress | Frontend | https://github.com/icon-project/sodax-frontend/issues/1484 |


## Sample of docs
https://github.com/icon-project/sodax-frontend
