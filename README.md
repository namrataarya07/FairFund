**🌊 FairFund**
Built on proofs, not promises.

Transparency infrastructure for NGO donations — ensuring funds move only against verified proof.

---

**🚀 Overview**

FairFund is a transparency and accountability platform designed for NGOs and donors.
It ensures that donated funds are used strictly for their intended purpose by linking withdrawals to verified receipts, geo-tagged evidence, and immutable blockchain records.

Unlike traditional donation platforms that rely on trust, FairFund creates verifiable trust through system design.

---

**🎯 Problem Statement**

Donation ecosystems suffer from a fundamental trust gap:

Donors cannot verify how their funds are actually used

NGOs receive lump-sum donations without structured accountability

Fraud cases damage trust across the entire ecosystem

Trust is demanded — but rarely proven.

This reduces donation participation and increases skepticism, ultimately harming social impact.

---

**💡 Our Solution**

FairFund introduces Proof-Gated Fund Release.

Instead of releasing funds upfront:

NGOs upload purchase receipts (bulk procurement)

Receipts are validated (time, geo, metadata checks)

Verification status is assigned

Only the verified amount becomes withdrawable

Receipt hash is stored immutably on blockchain

Money moves only when proof exists.

FairFund does not assume perfection.
It makes fraud visible, risky, and unsustainable.

---

**⭐ Key Innovation**

1️⃣ Bills

bills are used as proof of purchase

2️⃣ Layered Verification Stack

Time-stamp validation

Geo-tagged images of products

Metadata consistency checks

Manual + API verification

Pattern-based anomaly detection

3️⃣ Immutable Transparency

Blockchain stores cryptographic hashes of:

Donation records

Receipt submissions

Withdrawal approvals

Blockchain locks evidence. The system enforces logic.

4️⃣ QR-Based Public Verification

Each donor receives a unique QR code.
Scanning it reveals:

Campaign lifecycle

Receipts uploaded

Withdrawals made

Blockchain verification link

---

**🏗️ System Architecture**
Frontend (React / Next.js)
        ↓
Backend (Node.js + Express)
        ↓
MongoDB (Campaigns, Receipts, Users)
        ↓
Verification Engine
(Time + Geo + Pattern + Auditor Review)
        ↓
Blockchain Layer (Polygon / Ethereum Testnet)
        ↓
Public Verification Interface

---

**Blockchain Usage**

✔ Stores hashes only
✔ Ensures immutability
✔ Prevents revision or deletion
✖ Does NOT store documents or personal data

We store proofs on blockchain, not data.

---

**🗄️ Database Structure (Simplified)
Users**

id

role (NGO / Donor / Auditor)

verification_status

Campaigns

id

NGO_id

goal_amount

funds_raised

funds_withdrawn

status

Donations

id

donor_id

campaign_id

amount

blockchain_hash

Receipts

id

campaign_id

invoice_file

geo_metadata

timestamp

verification_status

blockchain_hash

Withdrawals

id

campaign_id

approved_amount

receipt_reference

blockchain_hash

---

**🔄 User Flow**
NGO Flow

Register & verify

Create campaign

Upload bulk purchase receipt

Submit geo-tagged proof

Await verification

Withdraw verified amount

Donor Flow

Explore verified campaigns

Donate via Razorpay or Wallet (Polygon/Ethereum)

Receive confirmation + QR

Track full campaign journey

Auditor Flow

Review flagged receipts

Approve / Request clarification

Public status updated

---

**🛠️ Tech Stack**
Frontend

React / Next.js

Frosted teal + white minimalist UI

Responsive & accessible

Backend

Node.js + Express

Receipt validation logic

Role-based access control

Database

MongoDB

Payments

Razorpay (UPI, GPay, etc.)

Web3 Wallet (Polygon / Ethereum testnet)

Blockchain

Polygon / Ethereum

Stores receipt & donation hashes

---

**🎨 UI / UX Philosophy**

FairFund is designed with:

Frosted teal & white theme

Calm, NGO-fintech aesthetic

Clear instructional tooltips

No intimidation, no aggressive warnings

Transparency without fear

Transparency without increasing friction.

🛡️ How We Handle Fake Bills

FairFund does not rely on a single verification method.

Instead, it uses:

Proof-gated withdrawal logic

Time & campaign window validation

Geo-tag consistency

Pattern detection over time

Auditor oversight

Immutable history logging

Fraud thrives in silence. FairFund removes silence.

---

**🌍 Impact**

Restores donor confidence

Protects honest NGOs

Prevents misuse at the source

Encourages disciplined reporting

Reduces audit friction

FairFund upgrades the ecosystem instead of policing it.

---

**🔮 Future Scope**

CSR compliance dashboards

NGO reputation scoring (pattern-based)

Government welfare integration

Smart contract-based escrow automation

National NGO accountability index

---

**📦 Market Readiness**

FairFund is built for real-world adoption:

Hybrid on-chain + off-chain architecture

Scalable backend logic

Role-based access system

Clear UX for mass usability

This is infrastructure, not a prototype gimmick.

---

**🏁 Final Note**

FairFund does not promise a fraud-free world.

It builds a system where:

Fraud becomes visible

History cannot be rewritten

Trust becomes measurable

Built on proofs, not promises.
