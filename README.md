# OTLedger

**The Master Register for Complex OT Environments.**

OTLedger is a dynamic, centralized master register designed specifically for Industrial Automation and Control Systems (IACS) professionals. In complex Operational Technology (OT) environments, relying on scattered spreadsheets and tribal knowledge introduces unnecessary physical, operational, and financial risks. 

OTLedger bridges the gap between your static **Design Intent** and your **Real-Time Reality**. It structures day-to-day tasks, eliminates rework, and provides the baseline necessary to detect operational drift and make OT IDS actionable.

---

## ⚙️ Core Capabilities

*   **Facility Management:** Hierarchically map physical plants, sub-sites, and control rooms to assign dedicated operational oversight.
*   **Master Inventory:** Track all assets across your environment, including Active (PLCs, HMIs), Silent (air-gapped skids, control valves), and Transient (contractor laptops) devices using a flexible Table-Per-Type (TPT) schema.
*   **Virtual Zones:** Map assets directly to the Purdue Enterprise Reference Architecture to instantly visualize physical connections and logical data flows.
*   **Policy & Conduit Definition:** Establish secure conduits by defining authorized data channels and protocol-level rules (e.g., Modbus TCP, OPC UA) between virtual zones.
*   **Risk Management:** Ditch disconnected Excel files. Attach risk likelihood and impact matrices directly to impacted hardware and track mitigation efforts historically.
*   **Audit & System Change Management (SCM):** A built-in lightweight SCM engine ensures every firmware update, configuration shift, or new asset is documented, reviewed, and approved before execution.
*   **Identity & Access (RBAC):** Safely onboard third-party integrators by restricting visibility to specific sites or asset roles.

## 🛠️ Built With

*   **.NET 8 Blazor** for robust, full-stack component architecture.
*   **PostgreSQL** for reliable, relational data management.
*   **Docker** for secure, containerized deployment (optimized for on-premises/air-gapped OT DMZ environments).

---

## 💡Bug Reports & Feature Requests

OTLedger is actively evolving to better serve the needs of the IACS community. Your feedback is highly encouraged!

If you encounter an issue, spot a bug, or have an idea for a new feature (such as expanding custom attributes, engineering drawing integrations, or IdP syncing), please use the GitHub Issue Tracker.

**How to contribute feedback:**
1. Navigate to the [Issues](../../issues) tab in this repository.
2. Check if your issue or feature request has already been reported.
3. Click **New Issue** and provide as much detail as possible, including:
   * A clear and descriptive title.
   * Steps to reproduce (for bugs).
   * The business case or workflow gap (for feature requests).
   * Screenshots or configuration snippets, if applicable.

---

## 🤝 Beta Trials & Contact

OTLedger is currently undergoing beta trials. If you are interested in participating, exploring its capabilities, or discussing how it can help organize your OT infrastructure, we would love to hear from you.

📧 **Contact us:** [info@otledger.com](mailto:info@otledger.com)

---
*© 2026 OT Labs. All rights reserved.*
