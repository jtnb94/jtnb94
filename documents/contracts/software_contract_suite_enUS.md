# SOFTWARE LEGAL & CONTRACT SUITE
*Disclaimer: This document template serves as a foundational guide for business agreements and should be reviewed by a qualified attorney in your jurisdiction before use.*

---

## PART 1: END USER LICENSE AGREEMENT (ON-PREMISE EULA)

This End User License Agreement ("Agreement") is entered into as of `[Effective Date]` ("Effective Date"), by and between `[Your Company Name]`, having its principal place of business at `[Your Address]` ("Provider"), and `[Client Company Name]`, having its principal place of business at `[Client Address]` ("Client").

### 1. GRANT OF LICENSE
Subject to the terms and conditions of this Agreement and payment of applicable fees, Provider hereby grants to Client a non-exclusive, non-transferable, non-sublicensable, perpetual (unless terminated under Section 6) license to install, execute, and run one (1) production instance of the software application known as `[Intranet Software Name]` ("Software") exclusively on hardware infrastructure owned, leased, or controlled by Client for internal business operations only.

### 2. RESTRICTIONS
Client shall not, and shall not permit any third party to:
a. Copy, modify, adapt, translate, or create derivative works of the Software source code.
b. Reverse engineer, decompile, disassemble, or otherwise attempt to derive the source code of the Software.
c. Rent, lease, distribute, sell, sublicense, or commercially exploit the Software or make the Software available as a service bureau or managed service to third parties.
d. Remove, alter, or obscure any proprietary notices, labels, or marks on the Software.

### 3. INTELLECTUAL PROPERTY RIGHTS
Client acknowledges and agrees that the Software, including all core modules, documentation, updates, and associated intellectual property rights, is and shall remain the sole and exclusive property of Provider. Client retains all right, title, and interest in and to all corporate data, documents, trademarks, and user-generated content uploaded to or processed through the Software ("Client Data").

### 4. ENVIRONMENT & SYSTEM REQUIREMENTS
The Software is designed to operate within the specific technical environment defined in the accompanying Statement of Work or technical documentation ("Supported Environment"). Client is solely responsible for procuring, configuring, maintaining, and securing all server infrastructure, operating systems, network connections, databases, and SSL certificates necessary to run the Software. Any modification of core Software source code by Client or unauthorized third parties shall immediately void all warranties and support obligations of Provider.

### 5. FEES AND PAYMENT
Client shall pay Provider the license and setup fees set forth in the applicable Statement of Work (`[SOW Reference]`). All payments are non-refundable once due, unless explicitly stated otherwise.

### 6. TERMINATION
This license is effective until terminated. Provider may terminate this Agreement immediately upon written notice if Client breaches any material provision of this License Agreement. Upon termination, Client shall immediately cease all use of the Software and destroy all physical and digital copies of the Software in its possession or control.

---

## PART 2: STATEMENT OF WORK (SOW) & ACCEPTANCE PROTOCOL

This Statement of Work ("SOW") is issued pursuant to and incorporates by reference the terms of the End User License Agreement entered into between `[Your Company Name]` ("Provider") and `[Client Company Name]` ("Client").

### 1. SCOPE OF INITIAL DEPLOYMENT & SERVICES
Provider agrees to deliver the following initial setup services:
* **Installation Support:** Deployment assistance of the standard Software container/package onto Client-provided server environment.
* **Basic Configuration:** Setup of primary organization branding (logo, brand color palette) and initial administrative user account creation.
* **Core Modules Included:** `[List modules, e.g., Employee Directory, Document Vault, Announcements Board, Internal Wiki]`.

### 2. OUT-OF-SCOPE SERVICES
The following items are explicitly excluded from this SOW and require a separate agreement or billable change order if requested:
* Custom code development, custom API integrations, or bespoke feature creation.
* Migration of data from legacy systems, network shares, or third-party cloud apps.
* Ongoing server administration, security patching, OS maintenance, or routine database backups.

### 3. ACCEPTANCE PROTOCOL (14-DAY UAT WINDOW)
a. Upon completion of initial deployment to Client's designated staging or production environment, Provider shall notify Client in writing that the Software is ready for User Acceptance Testing ("UAT").
b. Client shall have fourteen (14) calendar days from the date of notification ("UAT Period") to test the Software against functional specifications.
c. If Client discovers any reproducible defect in the unmodified core Software, Client shall provide a detailed written bug report to Provider within the UAT Period.
d. If no written bug report is received by Provider within the 14-day UAT Period, the Software shall be deemed fully accepted by Client, and the project milestone shall be marked complete.

### 4. PAYMENT SCHEDULE
Client agrees to pay the total project fee of `[$ Total Amount]` according to the following milestone schedule:
* **Milestone 1:** 50% (`[$ Amount]`) due upon execution of this SOW and Agreement.
* **Milestone 2:** 50% (`[$ Amount]`) due upon initial deployment or upon expiration of the 14-day UAT Period, whichever occurs first.

---

## PART 3: SUPPORT, MAINTENANCE, & ENVIRONMENT LIABILITY DISCLAIMER

### 1. LIMITED INITIAL WARRANTY
Provider warrants that for a period of thirty (30) days following the initial deployment date ("Warranty Period"), the unmodified core Software will perform in all material respects according to its standard documentation. Provider’s sole obligation, and Client’s exclusive remedy, for any breach of this warranty shall be Provider's commercially reasonable efforts to correct or workaround reproducible core software defects.

### 2. RESPONSIBILITY MATRIX
Because the Software is deployed and hosted entirely within Client's internal infrastructure, the parties agree to the following operational division of responsibilities:

| Operational Area | Provider (You) | Client IT Team |
| :--- | :--- | :--- |
| **Core Software Bugs** (during 30-day warranty) | Primary Responsibility | None |
| **Server Hardware & OS Maintenance** | None | Primary Responsibility |
| **Data Backups & Disaster Recovery** | None | Primary Responsibility |
| **SSL Certificates & Network/Firewall Security** | None | Primary Responsibility |
| **User Access Control & Identity Management** | None | Primary Responsibility |

### 3. POST-WARRANTY SUPPORT & AD-HOC SERVICES
Following the expiration of the 30-day Warranty Period, Provider provides **no ongoing maintenance or support** unless a separate, active Maintenance Agreement is executed. Any ad-hoc troubleshooting, environment re-configuration, or upgrade assistance requested by Client and accepted by Provider shall be billed at Provider's standard hourly rate of `[$ Rate per hour]` (with a 1-hour minimum billing increment).

### 4. LIMITATION OF LIABILITY & DATA LOSS DISCLAIMER
a. **Disclaimer of Consequential Damages:** To the maximum extent permitted by applicable law, Provider shall not be liable for any indirect, incidental, special, punitive, or consequential damages, including loss of profits, data, revenue, or business interruption, arising out of or in connection with this Agreement or the use of the Software.
b. **Liability Cap:** Provider's total aggregate liability arising out of or related to this Agreement shall be strictly limited to the total fees actually paid by Client to Provider under the applicable SOW in the preceding six (6) months.
c. **Server Environment and Backup Acknowledgment:** Client acknowledges that Provider has no administrative control over or ongoing access to Client's internal server environment. **Client is solely responsible for maintaining robust, regular automated backups of the application database and stored files.** Provider assumes no liability whatsoever for data loss, system corruption, downtime, or security breaches resulting from hardware failures, unbacked-up database crashes, OS updates, or Client server misconfigurations.

---
*IN WITNESS WHEREOF, the parties have executed this Contract Suite as of the Effective Date.*

**PROVIDER:** `[Your Company Name]`  
Signature: _______________________  
Name: ___________________________  
Title: ___________________________  
Date: ___________________________  

**CLIENT:** `[Client Company Name]`  
Signature: _______________________  
Name: ___________________________  
Title: ___________________________  
Date: ___________________________  