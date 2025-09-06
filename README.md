# 📑 Finance Reports – TechSphere Treasury Case

Welcome, Investigator.

This repository contains **financial records** related to the TechSphere Treasury breach.  
Your task is to carefully analyze the provided files and determine if any transactions stand out as unusual or fraudulent.

---

## 📂 Repository Contents

1. **funds_movement.csv**  
   - A chronological list of transactions from **25th Aug 2025 → 31st Aug 2025**.  
   - Each entry records the **timestamp, transaction ID, and source/target accounts**.  
   - At first glance, all entries appear valid, but one may not belong.

2. **receipts/**  
   - Individual text receipts for each transaction.  
   - Every receipt follows the same format:  
     - Transaction ID  
     - Date & Time  
     - From Account → To Account  
     - Department & Description  
     - Amount + Signature  

   - If a transaction in the CSV feels **“off”**, cross-check its receipt here.  
   - Look for **missing details, altered fields, or suspicious metadata**.

---

## 🎯 Your Objective

1. Start with **funds_movement.csv**.  
   - Review each transaction carefully.  
   - Check **timestamps, accounts, and patterns across the week**.

2. Identify any **fishy or out-of-place transfer**.  

3. Once you spot a suspicious transaction:  
   - Locate the corresponding **receipt** in the `/receipts` folder.  
   - Verify whether it looks authentic or tampered.

---

## 🕵️ Pro Tips

- Not all large amounts are suspicious — context matters.  
- Pay attention to **midnight timestamps** and **Treasury transfers**.  
- Some receipts contain subtle **anomalies** (e.g., missing signatures, blurred stamps, altered notes).  

---

🔎 Only a keen eye will uncover the truth hidden in these financial trails.  
Good luck, Detective.
