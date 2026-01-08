# x402 Endpoint Tracker

Central tracking for all pbtc21 x402 endpoints.

## Quick Status

| Metric | Count |
|--------|-------|
| Total Endpoints | 17 |
| Deployed | 17 |
| Registered on stx402.com | 15 |
| With Frontend UI | 14 |
| On GitHub | 15 |
| Custom Domain (pbtc21.dev) | 6 |

## Live Products (pbtc21.dev)

| Product | URL | Registered |
|---------|-----|------------|
| Landing | https://pbtc21.dev | - |
| x402 Intelligence | https://x402.pbtc21.dev | ✅ |
| Wallet Intelligence | https://wallet.pbtc21.dev | ✅ |
| sBTC Yield Calc | https://sbtc-yield.pbtc21.dev | ✅ |
| sBTC DeFi Intel | https://sbtc-intel.pbtc21.dev | ✅ |
| Pothole Hunter LA | https://pothole.pbtc21.dev | ✅ |

## Not Yet Registered

These endpoints are deployed but not registered on the x402 registry:

- x402-registry (IS the registry)
- pbtc21-landing (landing page, not API)

## Not Yet on GitHub

- btc-democracy (no local source)

## Files

- `endpoints.json` - Full tracking data with all endpoints
- `README.md` - This file

## Registry

All x402 endpoints should be registered at:
- https://x402-registry.p-d07.workers.dev
- Endpoint: `POST /registry/register`

## Update Process

When creating a new endpoint:
1. Add to `endpoints.json`
2. Push to GitHub (if applicable)
3. Register on x402-registry
4. Update this README
