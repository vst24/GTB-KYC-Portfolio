# GTB KYC Due Diligence Portfolio

Independent portfolio project simulating the corporate KYC onboarding 
workflow of a GTB Due Diligence analyst at a Schedule I Canadian bank.

## Regulatory Framework

- PCMLTFA (R.S.C. 1991, c. 26)
- FINTRAC Risk-Based Approach Guidance (2023)
- OSFI Guideline B-8
- FATF Recommendations 10, 12, 24

---

## Project 1 — Corporate KYC Risk Scoring Model

**File:** GTB_KYC_RiskScorecard.xlsx

A weighted five-dimension risk scoring model covering 10 fictional 
corporate GTB clients.

**What it includes:**
- Five FINTRAC-aligned risk dimensions: geographic, industry/sector, 
  product/channel, UBO complexity, adverse media/sanctions
- Each dimension mapped to published FINTRAC indicator codes (GR-01, 
  IS-02, UB-04, etc.)
- Composite scores auto-calculate via Excel formula and output 
  color-coded Low / Medium / High / Unacceptable risk ratings
- Disposition decisions with PCMLTFA regulatory citations for each 
  rating level
- Perpetual KYC (pKYC) review schedule with trigger-event log 
  demonstrating out-of-cycle review logic

**Client range:** Domestic professional services firm (Low Risk) through 
to a Money Services Business with prior FINTRAC penalty (Unacceptable).

---

## Project 2 — KYC Investigation Memo Package

**File:** GTB_KYC_InvestigationMemos_Vishal.pdf

Two full corporate KYC due diligence investigation memos simulating 
VP Due Diligence sign-off workflow.

**Case 1 — Maple Leaf Trading Corp. | Medium Risk | Approved**
- Import/export client with TBML sector risk and Mexico geographic 
  exposure
- Five-dimension risk assessment with FINTRAC indicator citations
- Complete KYC document checklist (all 10 items received)
- Recommendation memo with enhanced SWIFT monitoring conditions

**Case 2 — Golden Bridge Capital Partners LP | High Risk | Escalated**
- Confirmed Politically Exposed Foreign Person (PEFP) identified 
  among beneficial owners
- Mandatory Enhanced Due Diligence triggered under PCMLTFA s.9.3(1)
- Two outstanding mandatory EDD documents identified
- Escalation memo to VP DD and High Risk Client Management with full 
  regulatory rationale

---

## Disclaimer

All client names, individuals, and entities are entirely fictional. 
No real client data was used. Regulatory citations are drawn from 
publicly available FINTRAC, PCMLTFA, and FATF guidance documents.
