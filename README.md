# PeerLend Protocol

PeerLend is a P2P lending protocol designed for Starknet. It allows users to lend funds with their own interest rates and enables borrowers to get loans with a 150% fixed collateral ratio—without relying on any oracles.

## 🔍 Key Features

- 🏦 Lenders set their own interest rates.
- 🧾 Borrowers choose available offers.
- ⏳ No fixed loan duration—interest grows over time.
- 🛡️ Oracle-free design, resistant to manipulation.
- 🚨 Rescue market replaces liquidation.

## ⚙️ How It Works

- Loans are issued with 150% collateral.
- As time passes, the loan amount grows with interest.
- If collateral ratio drops below 135%, the loan is opened to a public rescue market.
- Rescuers can pay off the debt and claim interest + a user-defined reward.
- Protocol takes a small cut from rescue actions and matchings.

## 📄 Whitepaper

- [Whitepaper (EN)](whitepaper/PeerLend_Whitepaper_EN.docx)
- [Whitepaper (TR)](whitepaper/PeerLend_Whitepaper_TR.docx)
- ![Collateral Ratio Graph](whitepaper/PeerLend_Teminat_Oranı_Grafiği.png)

## ⚠️ Risks & Mitigations

- ❗ No oracle means no price crash detection → clearly stated in UI.
- ❗ Rescue market may lack incentive → solution: flexible reward system.
- ❗ Bots may dominate rescue → solution: throttling planned in upgrades.
- ❗ Debt growth must be accurate → solution: open testing & audits.

## 👷 Roadmap

- ✅ MVP development (in progress)
- 🧪 Testnet launch
- 🔐 Security audits
- 🌐 UI frontend integration
- 📣 Community launch
- 🗳 Governance & DAO evolution

## 💬 Feedback

Feel free to create issues or fork the repo to collaborate.

---

Built for Starknet — Trustless. Oracle-Free. P2P.
