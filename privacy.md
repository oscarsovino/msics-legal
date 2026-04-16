# Privacy Policy — miAcademia

**Last updated:** March 4, 2026
**Effective date:** March 4, 2026
**App name:** miAcademia
**Developer:** MSICS (com.msics.miacademia)

---

## 1. Introduction

miAcademia ("we", "our", or "the App") is a mobile application for managing academies, gyms, and educational institutions. This Privacy Policy describes how we collect, use, store, and protect your personal information when you use our App.

By using miAcademia, you agree to the collection and use of information as described in this policy. If you do not agree, please do not use the App.

---

## 2. Information We Collect

### 2.1 Information You Provide

| Data Type | Examples | Purpose |
|-----------|----------|---------|
| **Account Information** | Email address, full name, password | Authentication and profile management |
| **Profile Information** | Display name, avatar photo, phone number, date of birth | Personalization, identification within academies, and age verification |
| **Academy Data** | Academy name, location, programs, courses | Core functionality of academy management |
| **Attendance Records** | Check-in/check-out timestamps, QR scan data | Attendance tracking |
| **Booking Data** | Session reservations, cancellations, waitlist positions | Session booking management |
| **Financial Data** | Invoice records, payment status, credit balances | Billing and financial management (owner/admin only) |

### 2.2 Information Collected Automatically

| Data Type | Purpose |
|-----------|---------|
| **Device Information** | OS version, device model — for compatibility and debugging |
| **App Usage Data** | Screens visited, features used — for improving the App |
| **Authentication Tokens** | Session management and security |

### 2.3 Information We Do NOT Collect

- We do **not** collect advertising identifiers (IDFA/GAID)
- We do **not** use third-party analytics or tracking SDKs
- We do **not** sell or share personal data with third parties for advertising purposes
- We do **not** track users across other apps or websites

---

## 3. How We Use Your Information

We use collected information exclusively for:

1. **Providing core App functionality** — authentication, academy management, scheduling, attendance, booking
2. **Account security** — password hashing, session management, access control
3. **Communication** — notifications about bookings, attendance, and academy updates
4. **Financial management** — invoicing, payment tracking (visible only to authorized roles)
5. **Improving the App** — bug fixes, performance optimization, feature development

---

## 4. Data Storage and Security

### 4.1 Where Data Is Stored

- **Server-side data** is stored in Supabase (PostgreSQL) with Row-Level Security (RLS) enforced on all tables
- **Local data** is stored on-device using MMKV storage (app-sandboxed, not accessible by other apps)
- **All data transmission** uses HTTPS/TLS encryption

### 4.2 Security Measures

- Row-Level Security ensures users can only access data they are authorized to see
- Multi-tenant architecture isolates data between academies
- Role-based access control (owner, admin, teacher, guardian, student)
- Password hashing via industry-standard algorithms
- QR codes for attendance use rotating cryptographic signatures

---

## 5. Children's Privacy (COPPA Compliance)

miAcademia supports minor accounts for students under 13 years of age, with the following safeguards:

### 5.1 Minor Account Types

| Account Type | Description | Created By |
|-------------|-------------|------------|
| `minor_managed` | No personal email, username + PIN | Guardian/parent |
| `minor_supervised` | Has email, supervised access | Guardian/parent with notifications |

### 5.2 Parental Consent

- **All minor accounts are created by an authenticated guardian/parent**
- Guardians must be verified users with a standard account
- Minors cannot create their own accounts
- Every minor login is recorded in audit logs and the guardian is notified

### 5.3 Restrictions for Minor Accounts

Minor accounts **cannot**:
- View financial data (invoices, payments, credits)
- Change academy affiliation
- Unlink from their guardian
- Access administrative functions

### 5.4 Parental Rights

Guardians can at any time:
- View their minor's activity and attendance records
- Modify or delete their minor's account
- Revoke access to the App
- Request export or deletion of their minor's data

---

## 6. Data Sharing

We share personal data only in the following circumstances:

| Recipient | Data Shared | Purpose |
|-----------|-------------|---------|
| **Academy administrators** | Name, attendance, enrollment status | Academy management |
| **Teachers/instructors** | Student name, attendance for assigned classes | Class management |
| **Guardians** | Their minor's attendance, grades, enrollment | Parental oversight |
| **Supabase (infrastructure)** | All server-side data | Cloud hosting and database services |

We do **not** sell personal data to third parties.

---

## 7. Your Rights

Depending on your jurisdiction, you may have the following rights:

- **Access:** Request a copy of your personal data
- **Correction:** Request correction of inaccurate data
- **Deletion:** Request deletion of your account and associated data
- **Portability:** Request your data in a machine-readable format
- **Withdrawal of consent:** Stop using the App at any time

To exercise any of these rights, contact us at the email below.

---

## 8. Data Retention

- **Active accounts:** Data is retained for the duration of account activity
- **Deleted accounts:** Personal data is deleted within 30 days of account deletion request
- **Attendance and financial records:** May be retained for up to 7 years for legal/regulatory compliance, anonymized where possible
- **Minor access logs:** Retained for 1 year, then automatically purged

---

## 9. Third-Party Services

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Supabase | Database, authentication, storage | [supabase.com/privacy](https://supabase.com/privacy) |
| Expo | App distribution, OTA updates | [expo.dev/privacy](https://expo.dev/privacy) |

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify users of significant changes through in-app notifications or email. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 11. Contact Us

For privacy-related questions, data requests, or concerns:

- **Email:** privacy@msics.com
- **Subject line:** "miAcademia Privacy Request"

---

**miAcademia** — MSICS
Version 1.0.0
