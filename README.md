# Awesome-Financial-Management-ERP

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.

Here is the complete, ready-to-paste README.md for **Awesome-Financial-Management-ERP**.

---

# Awesome-Financial-Management-ERP

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on General Ledger, Accounts Payable/Receivable, Multi-Currency & Financial Reporting*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Financial Management & ERP**. These tools help organizations manage their general ledger, track payables and receivables, handle multi-currency transactions, and generate audit-ready financial reports.

**Examples** include Microsoft Dynamics 365 Finance, SAP S/4HANA Finance, Oracle NetSuite, Workday Financial Management, Sage Intacct, Infor CloudSuite Financials, Acumatica, Epicor ERP, FinancialForce, and BlackLine (the category leaders).

**Open-source emphasis**: The open-source financial management ecosystem is **exceptionally mature and production-proven**. **ERPNext v16** leads with a formula-driven custom financial report builder, IFRS-ready statements, and automated closing stock postings . **Lambda ERP** takes an AI-native approach with chat-driven company setup, localization packs (Switzerland, Germany SKR03/SKR04), and sector profiles . **Bizuno** (successor to PhreeBooks) delivers a battle-tested self-hosted ERP with built-in audit trails and US shipping integrations . **IOTA SDK** provides a modern Go-based modular ERP explicitly positioned as an alternative to SAP, Oracle, and Odoo .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global financial management ERP market is estimated at **~$30B in 2026**, growing toward **~$65B by 2032**. The sector is **moderately concentrated** — **SAP S/4HANA Finance** and **Oracle NetSuite** lead the enterprise tier, **Microsoft Dynamics 365 Finance** leverages Microsoft 365 distribution, and **Sage Intacct** dominates the mid-market for subscription businesses. **Pricing varies dramatically**: **Sage Intacct** starts at **~$400/month** (billed annually) for core financials, **Oracle NetSuite** starts at **~$999/month** plus **$99/user/month**, and **Microsoft Dynamics 365 Finance** runs **$180/user/month** for the Premium tier. **Workday Financial Management** requires enterprise-level contracts typically starting at **$150K+/year**. No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Dynamics 365 Finance](https://dynamics.microsoft.com/en-us/finance/)** | **Microsoft's enterprise financial management.** General ledger, AP/AR, budgeting, and fixed assets within Dynamics 365. | **$180/user/month** (Premium tier). **Essential tier**: ~$70/user/month . | **None** — 30-day trial via Dynamics 365 trial. | **~$281B revenue (Microsoft FY2025)** |
| **[SAP S/4HANA Finance](https://www.sap.com/)** | **SAP's flagship ERP finance module.** Universal journal, real-time analytics, and advanced financial close. | **Custom enterprise pricing** — quote required. Typically **$150K+/year** for mid-size deployments. | **None** — enterprise demo required. | **~$35B revenue (SAP FY2025)** |
| **[Oracle NetSuite](https://www.netsuite.com/)** | **Cloud ERP with strong financials.** GL, AP/AR, revenue recognition, and multi-currency consolidation. | **~$999/month** base + **$99/user/month** (standard). **SuiteSuccess editions**: Higher. | **None** — free product tour available. **No perpetual free tier**. | **~$53B revenue (Oracle FY2025)** |
| **[Workday Financial Management](https://www.workday.com/)** | **Enterprise financials unified with HCM.** Adaptive planning, accounting center, and revenue management. | **Custom enterprise pricing** — quote required. Typically **$150K+/year** for mid-size. | **None** — enterprise demo required. | **~$8B revenue (Workday FY2025 est.)** |
| **[Sage Intacct](https://www.sageintacct.com/)** | **Mid-market ERP for subscription businesses.** Strong multi-entity consolidation and revenue recognition. | **~$400/month** (billed annually) for core financials. Scales with modules and users . | **None** — demo required. **No perpetual free tier**. | **~$2B revenue (Sage FY2025 est.)** |
| **[Infor CloudSuite Financials](https://www.infor.com/)** | **Industry-specific cloud ERP.** Financials with strong healthcare, public sector, and manufacturing focus. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **Part of Infor (~$3B revenue est.)** |
| **[Acumatica](https://www.acumatica.com/)** | **Cloud ERP with consumption-based pricing.** Financials, distribution, manufacturing, and construction editions. | **$1,800/month** base + **$2,000/year** per named user (average across editions). **Volume discounts** available. | **None** — 30-day trial available. | **Private (~$500M+ valuation est.)** |
| **[Epicor ERP](https://www.epicor.com/)** | **Industry-specific ERP.** Financials with manufacturing, distribution, and retail focus. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **~$1B revenue (Epicor FY2025 est.)** |
| **[FinancialForce](https://www.financialforce.com/)** | **ERP built on Salesforce platform.** Financials, PSA, and supply chain within Salesforce. | **Custom pricing** — quote required. **Bundled with Salesforce** licensing. | **None** — demo required. | **Part of Certinia** |
| **[BlackLine](https://www.blackline.com/)** | **Financial close automation.** Account reconciliation, task management, and intercompany. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **~$600M revenue (BlackLine FY2025 est.)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[ERPNext v16](https://github.com/frappe/erpnext)** — **The leading open-source full-suite ERP with enterprise-grade financials.** **100% open source (GPL-3.0)** with **zero per-user fees** . **v16** (December 2025) is the biggest release in two years with **600+ contributors** and **50+ new features** . **Key financial additions**: **Custom Financial Report Templates** (formula-driven, IFRS-ready statements), **Automatic Closing Stock Posting** (one-click "Get Balance" replacing manual month-end entries), **Consolidated Trial Balance Report** (auto-converts and merges multi-subsidiary reports), and **Purchase Expense Booking** for faster COGS validation . Covers accounting, procurement, sales, CRM, inventory, manufacturing, projects, POS, and quality management in **one unified codebase** . | [![Stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers) | ~30,000 |
| **[Lambda ERP](https://pypi.org/project/lambda-erp/)** — **The AI-native ERP: chat with your books.** Built AI-native from the first commit with **the assistant as the primary interface** . **Set up your books by describing your business** in chat — pick a country and sector, preview the exact chart of accounts, confirm, and it's booked . **Localization packs**: Generic/International, **Switzerland** (Kontenrahmen KMU in German/CHF), **Germany** (DATEV SKR03/SKR04 in German/EUR) . **Sector profiles**: Services, retail/POS, hospitality, wholesale, import/export, manufacturing, construction . **Full sales and purchase cycles**, returns/credit notes, moving-average stock ledger, double-entry GL with cancellation reversal, and preset reports (Trial Balance, P&L, Balance Sheet, GL, AR/AP Aging) . **Tech**: FastAPI + SQLite/Postgres + React . | [![Lambda](https://img.shields.io/badge/Lambda-ERP-blue)](https://pypi.org/project/lambda-erp/) | N/A |
| **[Bizuno](https://github.com/phreesoft/bizuno)** — **Trusted evolution of PhreeBooks since 2007.** **Self-hosted freedom** — your server, your data, no subscriptions . **Comprehensive ERP**: accounting, sales, purchasing, inventory, banking . **Built-in audit trails**, process documentation, and compliance-friendly workflows make certification faster and audits easier . **Multi-warehouse, multi-location, multi-business** from one instance . **US tax calc via API** and full integration with USPS, FedEx, UPS for real-time quotes, labels, tracking, and freight reconciliation . **WordPress plugin** or standalone install . | [![Stars](https://img.shields.io/github/stars/phreesoft/bizuno?style=social&color=white)](https://github.com/phreesoft/bizuno/stargazers) | ~100 |
| **[IOTA SDK](https://github.com/iota-uz/iota-sdk)** — **Open-source modular ERP positioned as an alternative to SAP, Oracle, and Odoo.** **Written in Go** with modern look & feel . **Modular architecture** with configurable components . **Industry-specific modules**: Finance, manufacturing, warehouse management . **GraphQL API** for data management . **Finance & Accounting module** on the roadmap with GL, AP/AR, and payroll . **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/iota-uz/iota-sdk?style=social&color=white)](https://github.com/iota-uz/iota-sdk/stargazers) | ~280 |
| **[FacturaScripts](https://github.com/NeoRazorX/facturascripts)** — **Comprehensive open-source ERP & accounting for SMBs.** **Built on modern PHP 8.1+ and Bootstrap 5** . **Features**: Invoice & quote management, complete accounting module, inventory management, CRM, reports & analytics, plugin system, multi-language, responsive design . **MySQL/MariaDB or PostgreSQL** . **GPL-3.0**. | [![Stars](https://img.shields.io/github/stars/NeoRazorX/facturascripts?style=social&color=white)](https://github.com/NeoRazorX/facturascripts/stargazers) | ~1,000 |
| **[PyGtk-Posting](https://github.com/benreu/PyGtk-Posting)** — **Native Linux desktop ERP for accounting and business management.** **Double-entry accounting** with GL, bank reconciliation, account management, budget tracking, financial reports (P&L, net worth, sales tax), and check writing . **Customer management**: invoices, payments, credit memos, customer statements, job sheets . **Vendor management**: purchase orders, payments, statements . **Inventory**: product catalog, barcode, stock tracking, adjustments, locations . **Manufacturing**: assembly management, work orders, serial numbers, BOM . **Payroll**: employee management, pay stubs, time tracking . **Tech**: Python 3, GTK+ 3, PostgreSQL . | [![Stars](https://img.shields.io/github/stars/benreu/PyGtk-Posting?style=social&color=white)](https://github.com/benreu/PyGtk-Posting/stargazers) | ~500 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[webERP](https://github.com/webERP/webERP)** — Complete web-based open-source accounting and ERP. Flexible taxation for Canada, US, South Africa, UK, Australia, NZ, and most countries. AR overdues inquiry with delivery days and payment terms. Unlimited warehouses . |
| **[OliveERP](https://github.com/shajeebsh/olive_erp)** — Modular ERP built with Python 3.11+, Django 4.2 LTS, and Wagtail CMS. Full double-entry ledger, hierarchical chart of accounts, multi-currency support, tax engine with country engines . |
| **[Viet-ERP](https://github.com/nclamvn/Viet-ERP)** — Open-source ERP tailored for the Vietnamese market. VAS (TT200) accounting, e-invoice integration (VNPT, Viettel, FPT, BKAV), VAT 0%/5%/8%/10%, personal income tax (7 progressive levels), corporate income tax, social insurance, VietQR, 20 Vietnamese banks, VNPay/MoMo/ZaloPay, GHN/GHTK/Viettel Post shipping . |
| **[FinTrack](https://github.com/FinTrackhq/Fintrack)** — Accounting web application similar to SAP/1C. PHP/Laravel-based . |
| **[ERP Microservice](https://github.com/Edison0621/erp-microservice)** — Production-ready, cloud-native ERP built with .NET 10 and DDD. Double-entry GL, hierarchical chart of accounts, trial balance, AP/AR, auto journal entries, asset management with depreciation . |
| **[Open Mercato](https://github.com/open-mercato/open-mercato)** — Open-source ERP with a financial module spec. Country plugins for tax calculation, invoice formats, payment formats (SEPA, ACH, WIRE), bank statement parsing (MT940, CAMT053, BAI2), and e-invoicing. Functional programming architecture with type contracts and pure functions . |
| **[Dolibarr](https://github.com/Dolibarr/dolibarr)** — Modular ERP/CRM for SMEs. Double-entry accounting, general and auxiliary accounting, country-specific taxation (Spanish RE/IRPF, French anti-fraud TVA, Canadian double taxes, Indian GST), e-invoicing (FacturX, Peppol, ZATCA barcode), and structured payment references for Belgium and Finland . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Financial management ERP platforms handle sensitive financial data; ensure compliance with GAAP/IFRS, SOX, and applicable financial regulations.
- **Open-source reality**: The open-source ecosystem for financial management ERP is **exceptionally mature and production-proven**. **ERPNext v16** delivers enterprise-grade financials with **formula-driven custom report templates**, **IFRS-ready statements**, and **automated closing stock postings** — all with **zero per-user fees** . **Lambda ERP** brings an **AI-native chat-driven setup** with localization packs for Switzerland and Germany . **Bizuno** provides a **battle-tested self-hosted ERP** with built-in audit trails and US shipping integrations . **IOTA SDK** offers a modern Go-based modular ERP . However, **commercial platforms** (SAP S/4HANA, Oracle NetSuite, Microsoft Dynamics 365, Workday) provide **enterprise-scale consolidation, regulatory compliance certifications, and dedicated support** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with strong IT capacity or a reliable implementation partner.
- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Sage Intacct starts at ~$400/month** for core financials . **Oracle NetSuite starts at ~$999/month** plus **$99/user/month** . **Acumatica uses consumption-based pricing** at **$1,800/month base + $2,000/user/year** . **Workday and SAP require enterprise quotes** typically starting at **$150K+/year**. Always request a formal quote for accurate budgeting.

---

**Made for CFOs, controllers, finance managers, and ERP implementation teams.**
Let's make financial management ERP more open, transparent, and accessible.
