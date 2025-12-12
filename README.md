[![Build Status](https://github.com/EmilioLucena/VaultGuard/actions/workflows/android.yaml/badge.svg)](https://github.com/EmilioLucena/VaultGuard/actions)

# VaultGuard

**The KeePass for crypto seed phrases**  
100% offline · open-source · zero custody · Android (Kotlin + Jetpack Compose)

<img src="https://github.com/EmilioLucena/VaultGuard/blob/main/screenshots/preview.png?raw=true" width="300" alt="VaultGuard preview" />

### What it is
VaultGuard is an Android app for anyone who takes self-custody seriously.  
It securely generates, validates, encrypts, backs up and recovers BIP-39 seed phrases (12/18/24 words) for Bitcoin, Ethereum, Solana, Polygon and 50+ other chains — everything runs locally, no servers, no accounts, no internet required.

Think of it as **KeePass, but built exclusively for your multi-million dollar private keys**.

### Roadmap & Progress (Dec 2025 → Mar 2026)
| Week | Feature                                          | Status            |
|------|--------------------------------------------------|-------------------|
| 1–2  | Project setup + secure BIP-39 seed generation    | ✅ Done           |
| 3–4  | Encrypted local storage (Jetpack Security)       | 🔄 In progress    |
| 5–6  | Multi-chain address derivation (BTC, ETH, SOL…)  | ⏳ Planned         |
| 7–8  | Shamir Secret Sharing – SLIP-39 (2-of-3, 3-of-5)  | ⏳ Planned         |
| 9–10 | Encrypted QR + beautiful PDF export              | ⏳ Planned         |
| 11–12| Recovery verification + final polish + Play Store| ⏳ Planned         |

### Tech Stack (2025-ready & recruiter-friendly)
- Kotlin 2.0 + Jetpack Compose + Coroutines + Flow  
- Material You design  
- Jetpack Security (AES-256-GCM + biometric-bound keys)  
- BIP-39 / BIP-32 / BIP-44 / SLIP-39 implementations  
- Room + Proto DataStore  
- 100% offline · zero analytics · zero third-party SDKs

### How to run
```bash
git clone https://github.com/EmilioLucena/VaultGuard.git
# Open in Android Studio → Run on device/emulator
