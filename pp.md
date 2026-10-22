# Privacy Policy for PiColino

**Last Updated:** October 20, 2026

## 1. Executive Summary & Scope

This Privacy Policy governs the software architecture, cryptographic storage protocols, and data minimization standards for **PiColino** (referred to as "the Application", "we", "us", or "our"). 

PiColino operates as a decentralized, open-source remote SSH management and telemetry control client for Raspberry Pi single-board computers. The Application is designed with a strict **Privacy-by-Design** and **Data Minimization** philosophy.

---

## 2. Zero Data Collection & Storage Architecture

### Local Execution & No Remote Servers
- **No Personal Data Collection:** PiColino does not collect, track, log, or sell any personal data, usage analytics, or device identifiers.
- **No External Data Transmission:** The Application does not transmit any user credentials, telemetry metrics, or host information to external third-party servers or developer servers.
- **Encrypted Local Storage:** All SSH configuration parameters (including host addresses, port numbers, usernames, authentication passwords, and SSH server host key fingerprints) are stored exclusively on your local device using hardware-backed encrypted storage modules (`EncryptedSharedPreferences` on Android / `FlutterSecureStorage`).
- **Complete User Control:** All configuration data can be permanently erased at any time by selecting the *"Delete Configuration"* option inside the Application's Setup menu or by uninstalling the Application.

---

## 3. European Union Data Protection (GDPR / EU 2016/679)

PiColino complies strictly with the principles of the European General Data Protection Regulation (GDPR - Regulation EU 2016/679):

- **Lawfulness & Transparency (Art. 5 & 6 GDPR):** Data processing occurs exclusively on your local device for the explicit purpose of establishing user-initiated SSH terminal sessions.
- **Data Minimization (Art. 5(1)(c) GDPR):** Only the minimal parameters required to establish an SSH connection are processed locally.
- **Data Subject Rights (Art. 15–22 GDPR):** Because no personal data is stored on remote servers or databases, you retain full ownership and control of your data on your physical device.

---

## 4. US & International Privacy Frameworks

For international users, including those in the United States:
- **US Privacy Compliance (CCPA / CPRA & VCDPA):** Data governance aligns with local privacy laws, including the California Consumer Privacy Act (CCPA/CPRA) and Virginia Consumer Data Protection Act (VCDPA). We do not "sell" or "share" personal information as defined by California or federal standards.
- **Cryptographic Export Governance (Wassenaar Arrangement):** PiColino utilizes open-source AES-256 GCM cryptographic routines for secure SSH key storage, complying with global open-source software exemptions under the Wassenaar Arrangement and US Export Administration Regulations (EAR).

---

## 5. European & German National Statutory Standards

- **Digitale-Dienste-Gesetz (DDG):** Service provider information and digital utility standards adhere to German and European digital service provisions.
- **Cybersecurity & Data Espionage Protection (StGB § 202a):** Hardware-backed local key encryption and host key verification protocols protect against unauthorized network intrusion and data interception.
- **International Digital Trade (CISG):** Cross-border software distribution adheres to the UN Convention on Contracts for the International Sale of Goods (CISG Art. 1 & 14) and the EU Consumer Rights Directive (Directive 2011/83/EU).

---

## 6. Contact Information

If you have any questions or inquiries regarding this Privacy Policy or the security architecture of PiColino, please open an issue in the official repository or contact us:

- **Repository:** [https://github.com/tiggiflaus/picolino](https://github.com/tiggiflaus/picolino)
- **Maintainer:** PiColino Open Source Project (`tiggiflaus`)
- **Email Contact:** `support@picolino.app`
