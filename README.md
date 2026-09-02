# InfraFlow frontend

Premium role-based infrastructure-finance demo UI built with React, TypeScript and Vite.

## Run locally

```bash
npm install
npm run dev
```

Start at `/` to choose a portal. Every role route is available through the responsive sidebar.

## Contract integration

`src/main.tsx` includes an `InfraFlowService` interface and a mock implementation. Replace that adapter with an Arbitrum Sepolia integration when smart-contract and wallet functionality are available; all UI actions currently remain local/demo-only.
