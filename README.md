🛡️ Florida AI Insurance Compliance Auditor (HB 527)
Automated Governance & Regulatory Guardrails for Insurance AI

📊 The High-Stake Problem
In 2025/2026, Florida’s insurance market is under intense scrutiny. Florida House Bill 527 (and SB 202) mandates that AI cannot be the sole basis for denying or adjusting a claim. Insurers must now demonstrate Human-in-the-Loop (HITL) oversight, detailed record-keeping, and explicit disclosure to policyholders.

Failing to comply doesn't just mean a technical bug—it means Unfair Trade Practice violations and massive regulatory fines.

🎯 The Solution
This project provides a Python-based Audit Layer that intercepts AI-generated insurance outputs (quotes, claim adjustments, or denials) and subjects them to a rigorous regulatory check. It ensures that every automated decision is vetted against:

FL HB 527 Standards: Mandating human review for all claim denials.

Florida Insurance Code: Preventing "algorithmic drift" into illegal or discriminatory pricing.

NIST AI RMF: Mapping AI activities to the 'Measure' and 'Manage' functions of the federal framework.

🛠️ Core Features
Automated Regulatory Scanning: Uses the Gemini Pro API to audit content for prohibited "solely-automated" language.

Compliance Reporting: Generates a PASS/FAIL audit trail including specific statutory citations.

Human-in-the-Loop Enforcement: Explicitly flags any output that fails to identify a "Qualified Human Professional" as required by Florida law.

🚀 Technical Implementation
Python

# The Auditor acts as the 'Qualified Human Professional' Supervisor
audit_logic = {
    "framework": "NIST AI RMF 1.0",
    "statute": "FL House Bill 527 / Section 626.9541",
    "checkpoints": ["HITL Disclosure", "Bias Detection", "Fiduciary Alignment"]
}
💼 Professional Authority
Developed by a 2-15 Licensed Insurance Professional & Finance Specialist (Series 7/63). This tool bridges the gap between technical AI innovation and the rigid fiduciary requirements of the Florida Insurance market.

🛡️ Disclaimer
This tool is a prototype for governance and auditing purposes and should be integrated into a broader Enterprise Risk Management (ERM) strategy.
