# 🌱 Payflow

Gasless subscriptions, streaming, and micropayments in USDC — built for Arc.

## ✨ Overview

Payflow is a smart-contract protocol that enables recurring payments, streaming payments,
and pay-per-use billing where users pay exclusively in USDC — including gas fees.

No ETH. No friction. No trust.

## 🔑 Features

- USDC-only payments
- Gas paid in USDC
- Pull-based subscriptions
- Cancel anytime
- Human-readable transaction descriptions
- Streaming & usage-based billing

## 🧱 Architecture

Smart Wallet (AA)
  ↓
SubscriptionManager
  ↓
USDC (ERC20)

## 🧪 Contracts

- SubscriptionManager.sol
- SubscriptionVault.sol
- MockUSDC.sol (testing)

## 🧪 Testing

### Hardhat
```bash
npx hardhat test
