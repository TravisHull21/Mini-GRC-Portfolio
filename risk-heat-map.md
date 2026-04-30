# Risk Heat Map (5x5 Matrix)

**Risk Score Legend**  
- 🔴 **CRITICAL** (20–25) → Immediate action required  
- 🟠 **HIGH** (15–19) → High priority  
- 🟡 **MEDIUM** (8–14) → Monitor and plan treatment  
- 🟢 **LOW** (1–7) → Acceptable with periodic review  

| Likelihood \ Impact     | Negligible (1)     | Low (2)          | Moderate (3)      | High (4)           | Critical (5)       |
|-------------------------|--------------------|------------------|-------------------|--------------------|--------------------|
| **Almost Certain (5)**  | 🟡 MEDIUM (5)     | 🟠 HIGH (10)    | 🟠 HIGH (15)     | 🔴 CRITICAL (20)  | 🔴 CRITICAL (25)  |
| **Likely (4)**          | 🟢 LOW (4)        | 🟡 MEDIUM (8)   | 🟠 HIGH (12)     | 🟠 HIGH (16)      | 🔴 CRITICAL (20)  |
| **Possible (3)**        | 🟢 LOW (3)        | 🟢 LOW (6)      | 🟡 MEDIUM (9)    | 🟡 MEDIUM (12)    | 🟠 HIGH (15)      |
| **Unlikely (2)**        | 🟢 LOW (2)        | 🟢 LOW (4)      | 🟢 LOW (6)       | 🟡 MEDIUM (8)     | 🟡 MEDIUM (10)    |
| **Rare (1)**            | 🟢 LOW (1)        | 🟢 LOW (2)      | 🟢 LOW (3)       | 🟢 LOW (4)        | 🟡 MEDIUM (5)     |

**How to read it**:  
Your example risk (Ransomware via phishing) has **Inherent Risk = 4 × 5 = 20** → lands in the **🔴 CRITICAL** zone.
After controls it drops to **2 × 4 = 8** → moves to the **🟡 MEDIUM** zone.
