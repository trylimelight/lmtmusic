# lmtmusic

The official Limelight (LMLT) app — a Flutter mobile client paired with on-chain artist NFT and staking contracts.

## What it does

- Flutter mobile app (`lmltmusic/`) for the Limelight music platform, targeting Android and iOS
- Ships the artist NFT smart contracts that back the platform's on-chain features
- `NFTStakingPerToken` contract for per-token NFT staking rewards
- Standard ERC-20 / ERC-721 interfaces for token and NFT interactions

## Stack

- Flutter (Dart) for the mobile app
- Solidity smart contracts (`contracts/ArtistNFT`) — ERC-20 / ERC-721, NFT staking
- Compiled with Solidity build artifacts checked into the repo

## Getting started

Mobile app:

```bash
cd lmltmusic
flutter pub get
flutter run
```

Smart contracts live under `contracts/ArtistNFT`.

## About Limelight

Limelight (LMLT) was a location-based music-discovery platform for independent artists, with an LMLT ERC-20 token for staking, rewards, and artist NFTs.

---

Built by [Bilal Khalid](https://github.com/bizlal).
