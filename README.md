# NFTopia

React Native NFT marketplace built with Expo. Browse collectibles, search by name, and inspect bids and creator info on a detail screen. Uses custom Inter typography loaded via expo-font.

[![React Native](https://img.shields.io/badge/React%20Native-0.64-61DAFB?style=flat&logo=react&logoColor=black)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-SDK%2044-000020?style=flat&logo=expo&logoColor=white)](https://expo.dev/)

---

## Screens

**Home** — header with greeting, logo, and search bar. FlatList of NFT cards below. Search filters results in real time as you type.

**Details** — full-bleed NFT image, creator and owner info, description, and a chronological bid history showing bidder, ETH price, and date. "Place a Bid" button at the bottom.

## Components

```
components/
├── NFTCard.js          # image, creator, name, ETH price, bid CTA
├── HomeHeader.js       # search bar, logo, user profile
├── SubInfo.js          # creator/owner chip row
├── DetailsDesc.js      # title and description
├── DetailsBid.js       # single bid row
├── FocusedStatusBar.js # status bar colour per screen
└── Button.js           # shared CTA button
```

## Stack

React Native 0.64, Expo SDK 44, React Navigation (Stack), expo-font (Inter), react-native-safe-area-context

## Structure

```
nftopia/
├── screens/
│   ├── Home.js
│   └── Details.js
├── components/
├── constants/
│   ├── theme.js
│   ├── assets.js
│   └── dummy.js
├── App.js
└── package.json
```

## Run it

```bash
git clone https://github.com/ifeanyimuogbo/nftopia.git
cd nftopia
npm install
expo start
```

Scan the QR with Expo Go, or press `i` / `a` for simulator.
