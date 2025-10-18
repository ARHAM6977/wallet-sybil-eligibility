# wallet-sybil-eligibility
A Sybil prevention concept using Ethereum Mainnet transaction history + KYC verification for real user filtering.
# 🛡️ Wallet Sybil Eligibility + KYC Verification

## 🎯 Goal
This project proposes a Sybil-prevention system that ensures only real users become eligible for rewards or airdrops.

By combining Ethereum Mainnet transaction activity with a KYC verification step, the system filters out bot wallets and reward farmers.

---

 💡 Core Idea

1. Eligibility Filter (ETH Mainnet)
   - Only wallets with 10 or more transactions on the Ethereum Mainnet are considered eligible.
   - This ensures that the user is active on-chain and not a freshly created or farmed wallet.
   - Real users usually perform ETH transactions because of gas fees — bots typically avoid this.

2. KYC Requirement
   - Once a wallet passes the eligibility filter, the user must complete a KYC verification step.
   - Only verified users will be able to claim rewards.
   - This adds a human verification layer that blocks multi-wallet or fake account farming.

3. Sybil Resistance Logic
   - Wallets without sufficient ETH activity are excluded.
   - Multiple wallets from the same user can be detected through repeated KYC data.
   - On-chain history + off-chain identity = stronger Sybil protection.

---

🧠 Future Improvements
- Integrate on-chain data APIs (e.g. Etherscan, Alchemy) to automate wallet activity checks.
- Add machine learning filters to detect suspicious wallet patterns.
- Connect with decentralized KYC providers for seamless verification.

---

## 📂 Repository Structure
## 🧾 License
MIT License

## 👤 Author
ARHAM6977  
_Pond Bounty Submission – Wallet Sybil Prevention Idea
