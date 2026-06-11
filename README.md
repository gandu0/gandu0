# Portfolio
- offensive security researcher [halbornSecurity](https://www.halborn.com/)
- Immunefi All Star : [Gandu](https://immunefi.com/allstars/)
- External Auditor at [Pashov Audit Group](https://www.pashov.com/)
- External Auditor at [shieldify](https://www.shieldify.org/)
## Immunefi

| Protocol | Category | Findings | Details |
|----------|----------|----------|----------|
| [Lyra V1](https://www.derive.xyz/) | Options AMM Protocol | Identified a miscalculation in base and quote assets leading to a liquidity token rebase | [Writeup](https://gist.github.com/gandu0/2a55c9477b9df1e5f831867a26b26ab0)|
| [Sovryn Finance](https://sovryn.com/) | Bitcoin Trading & Lending | Discovered that dust amounts could manipulate the share token price | [Writeup](https://gist.github.com/gandu0/0fb6de1589847c36daa7bd5d45080027) |
| [2PI Network](https://2pi.network/) | Automated Vault Strategy | Every pool's first deposit could be stolen | |
| [KogeCoin](https://kogecoin.io/) | Farming Vaults | Inflation attack due to rounding error | |
| [Gains Network](https://gains.trade/) | Trading Platform | Manipulation of mintToken leading to first deposit loss |  |
| [Alchemix](https://alchemix.fi/) | Self-Repaying Loans | A single token holder could reset the token price to 1:1 | [Writeup](https://gist.github.com/gandu0/ebf23f644aebb001f216f275b68c3b8d) |
| [Beanstalk](https://bean.money/) | Stablecoin Protocol | Permit-based griefing attack | [Writeup](https://gist.github.com/gandu0/ab7efd97b63251d08c8963ca16f75f63) |

## Direct Disclosures

| Protocol | Category | Findings | Details |
|----------|----------|----------|----------|
| [Panoptic](https://panoptic.xyz/) | Options on Uniswap V3 | Internal fee accounting accumulation could create bad debt leading to user fund loss | [Writeup](https://gist.github.com/gandu0/59975ea2476d10387259a80cdfd298aa) |
| Infrared | Berachain Staking | Staking token rewards could permanently lock user funds in wrapped vaults |  |
| [Onyx Protocol](https://onyx.org/) | Lending Protocol | Share inflation on empty vaults leading to a Hundred Finance-style attack | [Writeup](https://x.com/gandu_whitehat/status/1811041165573038174) |
| [Sonne Finance](https://sonne.finance/) | Compound Fork | Share inflation on empty vaults leading to a Hundred Finance-style attack | |
| [Across Protocol](https://across.to/) | Cross-Chain Bridge | Internal bridge accounting inflation leading to user fund loss | [Writeup](https://x.com/gandu_whitehat/status/1811041165573038174) |
| [Lyra V2](https://www.derive.xyz/) | Options AMM Protocol | Griefing attack through permitAndSubmitTransfer() message replay |  |
| Ethos | Reputation Protocol | marketFunds incorrectly updated in buyVote() |  |

## Group Audits

| Protocol | Feature | Findings | Details |
|----------|----------|----------|----------|
| [Gains Network](https://gains.trade/) | Perpetual Trading | 1C, 4H, 6M, 12L | [Report](https://github.com/pashov/audits/blob/master/team/pdf/GainsNetwork-security-review_2025-05-26.pdf) |
| [EtherSpot](https://etherspot.io/) | Session Keys in Account Abstraction | 8C, 4H, 2M, 9L |  |
| Credifi | Lending with On-Chain Credit Scores | 1M, 4L, 4I | [Report](https://github.com/shieldify-security/audits-portfolio-md/blob/main/Credifi-Security-Review.md) |
| Multipli | RAW with FlashRedeem | 1H, 3M, 1L | [Report](https://github.com/shieldify-security/audits-portfolio-md/blob/main/Multipli-Vault-Security-Review.md) |

## Private Audits

| Protocol | Feature | Findings | Details |
|----------|----------|----------|----------|
| [Saffron Finance](https://www.saffron.finance/) | Zero-Coupon Swap | 1H, 1M, 4L | [Report](https://drive.google.com/file/d/1rwQI4ihkbSKDx_dGi6j_itn-QYnpWQxl/view?usp=sharing) |
| [Maga Trump](http://magamemecoin.com/) | Tax Token to Tax-Free Token Migration | 1L | [Report](https://drive.google.com/file/d/1PTCyHqUYxI-S1f86L5ccZ98Dp-nS56KG/view?usp=sharing) |







