#  Mbudzi Tshena Financial Solutions: User Manual
<img width="840" height="840" alt="Container (1)" src="https://github.com/user-attachments/assets/e7aa77c4-d63c-4a52-915e-13ee33648a68" />

Welcome to the **Mbudzi Tshena Financial Solutions** Loan Management Platform. This manual is designed for Loan Officers, Loan Managers, and System Administrators. It provides comprehensive instructions on navigating the system, managing borrower requests, tracking payments, and leveraging our proprietary AI Risk Engine.

---

## Table of Contents

1. [Getting Started](#1-getting-started)
2. [Navigating the Dashboard](#2-navigating-the-dashboard)
3. [Managing Loan Requests](#3-managing-loan-requests)
4. [Tracking Payments](#4-tracking-payments)
5. [Borrower Management](#5-borrower-management)
6. [How to Use the AI Risk Engine](#6-how-to-use-the-ai-risk-engine)
7. [Troubleshooting & Support](#7-troubleshooting--support)

---

## 1. Getting Started

### Accessing the Admin Portal
1. Navigate to the Admin Portal login page (e.g., `https://[your-domain]/admin/login`).
2. Enter your authorized **Email address** (e.g., `name@microfin.ai`) and **Password**.
3. Click **Sign in securely**. 
4. *Note: Only authorized staff members can access the backend dashboard. If you cannot log in, please contact your IT Administrator.*

---

## 2. Navigating the Dashboard
<img width="1195" height="1140" alt="admin page" src="https://github.com/user-attachments/assets/6e9de698-10e0-49b1-bcda-8a1ddbe4b545" />
Upon logging in, you will land on the **Overview** page. The sidebar (or the mobile hamburger menu) provides access to the four core modules:

*   **Overview:** High-level metrics, AI system status, loan processing trends, and active fraud alerts.
*   **Loan Requests:** The queue of all incoming loan applications.
*   **Payments:** A ledger of all disbursements and incoming repayments.
*   **Borrowers:** A directory of profiled customers and batch analysis tools.

### Key Performance Indicators (KPIs)
At the top of your overview, you will see real-time KPIs:
*   **Total Active Loans:** Total monetary value currently disbursed.
*   **Reliable Borrowers:** Count of users identified by AI as low-risk.
*   **Avg. AI Risk Score:** The platform-wide average risk score.
*   **Fraud Alerts Detected:** Number of suspicious activities flagged by the AI.

---

## 3. Managing Loan Requests
<img width="1195" height="817" alt="loan request" src="https://github.com/user-attachments/assets/40eefdc4-55f7-46bb-8751-9372e4f0cecc" />

The **Loan Requests** tab is where Loan Officers will spend the majority of their time. 

### Searching and Filtering
*   **Search:** Use the search bar to find a specific request by Applicant Name or ID (e.g., `REQ-9012`).
*   **Quick Filters:** Click the pill buttons at the top to filter by status:
    *   `All`
    *   `Pending Review`
    *   `Auto-Approved`
    *   `Flagged`

### Reviewing an Application
Each row in the table provides an immediate snapshot of the applicant:
1.  **Applicant Info:** Name and Request ID.
2.  **Amount:** The requested loan value.
3.  **AI Risk Score:** A visual bar and a number from **0 to 100** (Lower is better/safer).
4.  **AI Action:** The system's recommendation (e.g., Auto-Approve, Flagged, Manual Review).
5.  **Status:** The current legal status of the loan (Approved, Pending, Rejected).

> 💡 **Tip for Loan Officers:** Focus
 your manual efforts on applications marked as **"Manual Review"** or **"Flagged"**. Let the AI handle the "Auto-Approve" and "Decline" decisions to maximize your efficiency.

---

## 4. Tracking Payments
<img width="1195" height="987" alt="payments" src="https://github.com/user-attachments/assets/b2c3d519-1126-47b2-8e2f-70f8b15f5779" />

The **Payments** tab acts as your daily ledger.

*   **Summary Cards:** Quickly view *Total Collected Today*, *Total Disbursed Today*, and *Failed Transactions*.
*   **Transaction Ledger:** Displays individual transactions (Repayments vs. Disbursements).
*   **Exporting Data:** Click the **"Export CSV"** button at the top right to download the ledger for use in Excel or external accounting software.

---

## 5. Borrower Management
<img width="1195" height="695" alt="borrowers" src="https://github.com/user-attachments/assets/502f81e9-afee-4f43-b11a-9f4513c38990" />

The **Borrowers** tab allows you to view the directory of all users on the platform.
*   **Pre-approved Offers:** View users who the AI has identified as highly reliable.
---

## 6. How to Use the AI Risk Engine

Mbudzi Tshena utilizes an advanced AI Risk Engine to assess borrowers instantly. Here is how Loan Officers and Managers should interpret and utilize the AI:

### Understanding the 0-100 Score
The AI assigns a score to every application based on financial history, income consistency, and alternative data.
*   🟢 **0 - 30 (Low Risk):** Excellent candidates. Usually eligible for premium rates (e.g., Prime + 1.5%).
*   🟡 **31 - 60 (Medium Risk):** Average candidates. May require standard rates or shorter terms.
*   🔴 **61 - 100 (High Risk):** Risky profiles. Often requires collateral or results in a declined application.

### Understanding AI Actions
The AI will automatically tag applications with an action state:
1.  **Auto-Approve (Shield Check):** The AI has verified all identity documents and the risk score is excellent. No human intervention is required.
2.  **Decline (Red Alert):** The risk score is exceptionally high or severe discrepancies were found. 
3.  **Manual Review (Clock):** The AI found the application to be borderline. **Action Required:** A Loan Officer must open this file, review the provided documents, and make a final human decision.
4.  **Flagged (Red Alert):** The AI detected potential fraud.

### Handling Fraud Alerts
On your main **Overview** dashboard, you will see a **Recent Fraud Alerts** panel. The AI actively monitors for:
*   *Identity Mismatches* (e.g., ID document does not match selfie).
*   *Unusual Application Locations* (IP address anomalies).
*   *Inconsistent Income History.*
*   *Multiple Concurrent Requests.*

**What to do:** If an application is flagged for fraud, a Loan Manager should review the specific alert reason. Do not approve flagged loans without contacting the applicant for additional verification.

---

## 7. Troubleshooting & Support

*   **Data not refreshing?** Try clearing your browser cache or pressing `Ctrl + R` (`Cmd + R` on Mac).
*   **Blank screens or routing errors?** Ensure you have a stable internet connection. The app is fully responsive, so try logging in via your mobile device if your desktop is unavailable.
*   **AI Engine offline?** Check the "System Status" banner on the Overview page. If it reads anything other than "Active", escalate to the IT support team immediately.

For further assistance, please contact the internal helpdesk at `Mbuzi Financial`.
