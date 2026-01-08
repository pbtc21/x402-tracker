# x402 Endpoint Tracker

Central tracking for all pbtc21 x402 endpoints.

## Quick Status

| Metric | Count |
|--------|-------|
| Cloudflare Workers | 27 |
| Custom Domains (pbtc21.dev) | 42 |
| Partner Landing Pages | 13 |
| Core Products | 15 |

## Core Products (pbtc21.dev)

| Product | URL | Type |
|---------|-----|------|
| Landing | https://pbtc21.dev | Hub |
| x402 Intelligence | https://x402.pbtc21.dev | x402 API |
| Alpha Intelligence | https://alpha.pbtc21.dev | x402 API |
| Wallet Intelligence | https://wallet.pbtc21.dev | x402 API |
| sBTC Yield Calc | https://sbtc-yield.pbtc21.dev | x402 API |
| sBTC DeFi Intel | https://sbtc-intel.pbtc21.dev | x402 API |
| sBTC Yield Vault | https://vault.pbtc21.dev | x402 API |
| Agent Registry | https://agents.pbtc21.dev | x402 API |
| x402 Registry | https://registry.pbtc21.dev | Registry |
| STX402 Jobs | https://jobs.pbtc21.dev | Jobs Board |
| Partner Portal | https://partners.pbtc21.dev | BD Portal |
| Endpoint Showcase | https://showcase.pbtc21.dev | Directory |
| Meme Generator | https://meme.pbtc21.dev | x402 API |
| Wallet ID Card | https://id.pbtc21.dev | x402 API |
| Bitcoin Faces | https://faces.pbtc21.dev | NFT Tool |
| sBTC Print | https://print.pbtc21.dev | Tool |
| Coin Refill | https://refill.pbtc21.dev | Tool |
| BTC Democracy | https://democracy.pbtc21.dev | Voting |
| Pothole Hunter | https://pothole.pbtc21.dev | Civic App |

## Partner Landing Pages (13)

All partner sites show **100% revenue to partners** - no rev share.

| Partner | URL | Tier |
|---------|-----|------|
| HeyElsa AI | https://heyelsa.pbtc21.dev | AI |
| Daydreams | https://daydreams.pbtc21.dev | AI |
| Heurist AI | https://heurist.pbtc21.dev | AI |
| Phala Network | https://phala.pbtc21.dev | Infra |
| Lit Protocol | https://lit.pbtc21.dev | Security |
| ChainSafe | https://chainsafe.pbtc21.dev | Infra |
| Audius | https://audius.pbtc21.dev | Infra |
| Livepeer | https://livepeer.pbtc21.dev | Infra |
| Akash Network | https://akash.pbtc21.dev | Infra |
| Render Network | https://render.pbtc21.dev | Infra |
| Fleek | https://fleek.pbtc21.dev | Infra |
| Nodepay | https://nodepay.pbtc21.dev | Infra |
| Saturn Network | https://saturn.pbtc21.dev | Infra |

## Other Partner Sites (Legacy)

| Site | URL |
|------|-----|
| Gaianet | https://gaianet.pbtc21.dev |
| CreatorBuddy | https://creatorbuddy.pbtc21.dev |
| Dexter | https://dexter.pbtc21.dev |
| Cronos | https://cronos.pbtc21.dev |
| Cashie | https://cashie.pbtc21.dev |
| CyberCentry | https://cybercentry.pbtc21.dev |
| RGB | https://rgb.pbtc21.dev |
| Noble | https://noble.pbtc21.dev |
| BluePay | https://bluepay.pbtc21.dev |
| Zauth | https://zauth.pbtc21.dev |

## Cloudflare Workers (27)

```
bitcoin-faces-nft     pbtc21-landing        stx402-endpoint
bloombrush            pool-cigars           stx402-jobs
btc-democracy         pothole-api           stx402-preview
coin-refill           pothole-reporter      wallet-id-card
gentle-sun-4336       sbtc-defi-intel       wallet-intel
nichols-dynasty       sbtc-print            x402-meme
                      sbtc-yield-vault      x402-partner-sites
                      sbtc-yield-x402       x402-partners
                      stx-arb-bot           x402-registry
                      stx402-agents         x402-showcase
                      stx402-alpha
```

## Open PRs

| Repo | PR | Status |
|------|-----|--------|
| whoabuddy/stx402 | [#18](https://github.com/whoabuddy/stx402/pull/18) | Wallet intelligence endpoints |

## Update Process

When creating a new endpoint:
1. Deploy to Cloudflare Workers
2. Add DNS record (AAAA 100:: proxied)
3. Add worker route
4. Update this README
5. Register on x402-registry (if x402 endpoint)
