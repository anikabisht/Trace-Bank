**TraceBank 🏦🔍**
Making Bank AI Decisions Explainable, Accountable, and Trustworthy


**
🚨 Problem**

Banks rely heavily on black-box ML models for fraud detection and transaction risk scoring.

While accurate, these systems:

Block genuine users without explanation

Create regulatory and audit friction

Increase customer churn and support costs

Offer no insight into why or how a decision was made

Accuracy alone is not enough. Banking AI must be explainable.


**💡 Solution — TraceBank**

TraceBank is an Explainable AI (XAI) layer that sits on top of existing banking ML systems and converts opaque decisions into clear, role-aware, and audit-ready explanations.

Instead of replacing bank models, TraceBank explains them.


**✨ Key Features**

🔐 Hybrid Risk Engine

Combines predictive ML, behavioural signals, and contextual risk to assess transactions more accurately.

🧠 Behavioural Biometrics

Detects anomalies in user interaction patterns to reduce false fraud blocks.

🕸️ Fraud Ring Detection

Uses graph/network analysis to identify coordinated fraud across accounts, devices, and IPs.

🔁 Counterfactual Engine (MVP)

Explains what minimal change would have altered the decision:

Bank view: Feature-level decision shifts

Customer view: Privacy-safe actionable guidance

👁️ Role-Aware Mode Toggle

Different explanations for different stakeholders:

Bank: Full decision trace

Regulator: Audit-ready reasoning

Customer: Simple, trust-preserving explanations

**🧩 Why TraceBank is Different
**
Solves the black-box AI problem

Preserves model secrecy while enabling explainability

Reduces false positives → lower churn & support load

Enables regulatory-compliant automation

Improves trust without sacrificing accuracy
**
🛠️ Tech Stack**

Backend

Python

Flask

Scikit-learn

ML Components

Behavioural anomaly detection

Fraud ring detection (graph-based analytics)

Hybrid risk scoring

Counterfactual explanation engine

Frontend

HTML

CSS

JavaScript

Dashboard with role-based toggles

**System Architecture**
User / Transaction
        │
        ▼
 ┌───────────────────┐
 │ Data Ingestion    │
 │ (Txn, Device,     │
 │ Behaviour)        │
 └───────────────────┘
        │
        ▼
 ┌───────────────────┐
 │ Behavioural       │
 │ Anomaly Model     │
 └───────────────────┘
        │
        ▼
 ┌───────────────────┐
 │ Fraud Ring Model  │
 │ (Graph Analytics) │
 └───────────────────┘
        │
        ▼
 ┌───────────────────┐
 │ Hybrid Risk       │
 │ Scoring Engine    │
 └───────────────────┘
        │
        ▼
 ┌───────────────────┐
 │ Counterfactual    │
 │ Explanation Layer │
 └───────────────────┘
        │
        ▼
 ┌──────────────────────────────┐
 │ Role-Aware Output Layer      │
 │ • Bank View (Deep)           │
 │ • Regulator View (Audit)     │
 │ • Customer View (Simple)     │
 └──────────────────────────────┘

Speeds up compliance and audits

Enables safer, explainable automation in banking
