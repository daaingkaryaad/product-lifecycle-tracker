# Comparison of Existing Systems and Industry Solutions

## 1. Overview

To define the scope and competitive position of the **Product Lifecycle Tracking Platform** («Разработка платформы для отслеживания жизненного цикла продукции»), four existing commercial and research-based solutions were analyzed:
* **RepairDesk:** A specialized management platform for repair shops focusing on repair workflows, spare parts, and internal operations.
* **Phonecheck:** A device diagnostics, testing, and data erasure solution tailored for mobile device refurbishers.
* **CheckMEND:** A comprehensive risk management and history database for detecting stolen or lost mobile electronics.
* **Circularise:** A Digital Product Passport (DPP) platform emphasizing material traceability, supply chain information sharing, and access control.

---

## 2. Comparative Analysis Matrix

The following matrix compares the existing platforms across key technical and functional criteria:

| Comparison criterion | RepairDesk | Phonecheck | CheckMEND | Circularise |
|---|---|---|---|---|
| **1. Device identification** | Links devices to repair records using IMEI or serial numbers. | Reads device identifiers and model information during testing. | Searches connected databases using IMEI or serial numbers. | Links a digital product passport to a product identifier, accessible through a data carrier such as a QR code. |
| **2. Information recorded** | Repair requests, replaced parts, and progress of repair work. | Test results, battery condition, parts checks, and certification records. | Available records of loss, theft, network blocks, and insurance claims. | Material origins and supply-chain records. A solar-panel prototype also includes lifecycle information, with repair history covered by its data model. |
| **3. Repair management** | Creates repair jobs, tracks their progress, and manages spare parts. | Testing and data erasure. | Main focus is checking device risks. | Supports repair-related information in digital product passports. Creating repair jobs, assigning technicians, and tracking repair tasks are not confirmed in the reviewed sources. |
| **4. Access permissions** | Controls what employees can access through roles and permissions. | Detailed employee roles and permissions require verification. | Account access is available; permissions for different employees require verification. | Controls which product information is shared with different participants. |
| **5. Reports** | Business and financial reports for repair-shop operations. | Device test reports and data-erasure records. | Device-check reports showing risks found in the available databases. | Generates PDF reports and digital product passports with selected product and supply-chain information. |
| **6. Integration and export** | Provides an API for connecting with other software. | Provides an API and machine-readable JSON reports. | Provides an API for automated device checks. | Provides APIs for automated data exchange with other systems and generates PDF reports. |

---

## 3. Position and Advantages of the Proposed Platform

Based on this comparative study, the proposed **Product Lifecycle Tracking Platform** addresses specific gaps in existing systems:
1. **Unified Lifecycle Record:** Unlike single-purpose tools (such as CheckMEND for risk checks or RepairDesk for shop operations), our platform integrates device identification, chronological event history, and role-based access in a single unified web prototype.
2. **Flexible Product Domain:** While existing commercial solutions target specific niches (e.g., mobile repair or supply chain origin tracking), our domain model remains generic enough to support various product categories without locking into a single operational workflow.
3. **Multi-Organization Access Control:** Following the principles seen in Circularise, our platform incorporates multi-role permissions (FR-01, FR-06) allowing authorized external parties and internal staff to view only permitted lifecycle history segments.