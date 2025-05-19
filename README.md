# 🪙 Ví Generator CLI

Công cụ Node.js để tạo nhiều loại ví blockchain khác nhau và lưu vào file Excel + file riêng từng loại.

## 📦 Hỗ trợ tạo ví cho:

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

## ⚙️ Cài đặt

```bash
npm install
```

---

## 🔧 Cấu hình số lượng ví cần tạo

Sửa file `config.json`:

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

> Ghi `0` nếu không muốn tạo loại ví đó.

---

## ▶️ Chạy chương trình

```bash
node index.js
```

---

## 📂 Kết quả

- ✅ File Excel: `wallets.xlsx`
- ✅ File riêng từng loại trong thư mục `output/`:
  - `evm_wallets.txt`
  - `solana_wallets.txt`
  - `aptos_wallets.txt`
  - ...

Mỗi dòng gồm:
```
[STT] | Address | Private Key / Mnemonic
```
