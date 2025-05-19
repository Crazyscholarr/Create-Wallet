# 🪙 Wallet Generator CLI

Node.js tool to generate different types of blockchain wallets and save them in Excel file + separate files for each type.

## 📦 Support creating wallets for:

- ✅ EVM (Ethereum, BSC, Arbitrum, Optimism, Polygon, Avalanche, ...)

- ✅ Solana
- ✅ Phantom
- ✅ Aptos
- ✅ SUI
- ✅ Bitcoin
- ✅ Cosmos
- ✅ Polkadot
- ✅ NEAR
- ✅ TRON
- ✅ TON
- ✅ Cardano
- ✅ Algorand
- ✅ Hedera

---

## ⚙️ Installation

```bash
npm install
```

---

## 🔧 Configure the number of wallets to create

Edit the `config.json` file:

```json
{
"EVM": 10,
"Bitcoin": 5,
"Cosmos": 5,
"Polkadot": 5,
"Solana": 10,
"NEAR": 5,
"TRON": 5,
"TON": 5,
"Aptos": 10,
"SUI": 10,
"Cardano": 5,
"Algorand": 5,
"Hedera": 5
}
```

> Write `0` if you do not want to create that type of wallet.

---

## ▶️ Run the program

```bash
node index.js
```

---

## 📂 Result

- ✅ Excel file: `wallets.xlsx`
- ✅ Separate files for each type in the `output/` folder:

- `evm_wallets.txt`
- `solana_wallets.txt`
- `aptos_wallets.txt`
- ...

Each line includes:
```
[STT] | Address | Private Key / Mnemonic
```
