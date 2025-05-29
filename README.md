# 🌊 TinyDrop – Because Every Drop Counts

> “A single drop may seem small, but together, we become a wave of change.”

TinyDrop is a transparent micro-donation platform built to prove that even the smallest acts of kindness can create real-world impact. Whether it’s ₹1 or ₹100, every drop is tracked, pooled, and transformed into food, help, or hope — all while being **fully visible** to the people who made it possible.

---

## ✨ Features

- 💸 **Micro Donations** – Donate as little as ₹1.
- 🔗 **Transparent Tracking** – Every rupee is traceable from donor to impact.
- 🤝 **Milestone Pooling** – Donations are grouped (e.g., ₹70) to perform verified actions like feeding a person in need.
- 📷 **Proof of Good** – Donors receive updates with photo/video proof of how their contribution was used.
- 🌍 **Community Impact** – See your drop merge with others to make real change.

---

## 🔧 Tech Stack

- **Frontend**: HTML, CSS, JavaScript *(optional: React or simple Bootstrap UI)*
- **Backend**: Python + Flask
- **Storage**: JSON or SQLite (for lightweight blockchain ledger)
- **Hashing**: SHA256 for block integrity
- **Optional**: IPFS for media proofs, Razorpay or UPI test mode for donations

---

## 📖 How It Works

1. **Donate** ₹1 or more via the TinyDrop platform.
2. Your donation is added to a **blockchain-like ledger** with its own hash.
3. Once enough drops are pooled (e.g., ₹70), an **action** is taken (e.g., food packet given).
4. The team uploads **proof** (photo, note, location), and a final block is created.
5. **All contributors to that action** can see where their drop went.

---

## 📷 Example Impact Block

```json
{
  "index": 21,
  "timestamp": "2025-05-30 10:43:00",
  "contributors": ["@utkarsh-shadow", "@donor123", "@anjali.vit"],
  "action": "Distributed 1 food packet to needy person near Pune station",
  "proof": "https://ipfs.io/ipfs/QmXk...xyz",
  "previous_hash": "0x78fa4d...",
  "hash": "0x4a3f8c..."
}
