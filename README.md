## XDNA mobile wallet for Android
------

[<img src="https://github.com/XDNA-Core/XDNA-android/raw/master/images/icon-google-play.png">](
https://play.google.com/store/apps/details?id=org.XDNA)

### A completely standalone XDNA wallet

Unlike many other wallets, XDNA mobile wallet is a real standalone XDNA
client. There is no server to get hacked or go down, so you can always access
your money. Using
[SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients)
mode, XDNA mobile wallet connects directly to the XDNA network with the fast
performance you need on a mobile device.

### The next step in wallet security

XDNA mobile wallet is designed to protect you from malware, browser security holes,
*even physical theft*. With AES hardware encryption, app sandboxing, and verified boot, XDNA mobile wallet represents a significant security advance over
web and desktop wallets.

### Beautiful simplicity

Simplicity is XDNA mobile wallet's core design principle. A simple backup phrase is
all you need to restore your wallet on another device if yours is ever lost or
broken.  Because XDNA mobile wallet is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki),
your balance and transaction history can be recovered from just your backup
phrase.

### Features

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification

### How to set up the development environment
1. Download and install Java 7 or up
2. Download and Install the latest Android studio
3. Download and install the 15c version of NDK https://developer.android.com/ndk/downloads/older_releases
4. Clone or download this project
5. Open the project with Android Studio and let the project sync
6. Go to SDK Manager and download all the SDK Platforms and SDK Tools
7. Build -> Rebuild Project
