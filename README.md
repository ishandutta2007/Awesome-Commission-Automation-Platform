# Awesome-Commission-Automation-Platform

## Top Commission Automation Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Sales Compensation, Incentive Management, Quota Attainment & Payout Processing*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Commission Automation**. These tools help revenue operations teams calculate sales commissions accurately, manage incentive compensation plans, track quota attainment, and process payouts—replacing error-prone spreadsheets with auditable, automated workflows.



**Examples** include CaptivateIQ, Spiff, Everstage, Xactly, Performio, Qobra, QuotaPath, SalesCookie, Varicent, and Compass (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom commission logic, and transparent payout data—ideal for finance teams that need full control over sensitive compensation data without per-seat SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[CaptivateIQ](https://www.captivateiq.com/)**

  No-code commission platform that replaces spreadsheets with flexible, auditable incentive compensation management. Features customizable commission plans, automated calculations, real-time visibility for reps, and integration with CRM and ERP systems .



- **[Spiff](https://www.spiff.com/)**

  Commission automation platform focused on real-time visibility and accuracy. Provides automated commission calculations, quota tracking, and rep-facing dashboards that update as deals close.



- **[Everstage](https://www.everstage.com/)**

  No-code sales commission and incentive compensation platform. Enables RevOps teams to build complex commission plans without engineering support, with automated calculations and dispute management.



- **[Xactly](https://www.xactlycorp.com/)**

  Enterprise incentive compensation management platform. Provides comprehensive sales performance management, data-driven insights, and scalability for large sales organizations .



- **[Performio](https://www.performio.co/)**

  Sales commission and incentive compensation software with comprehensive reporting, automation, and scalability. Designed for mid-market to enterprise organizations .



- **[Qobra](https://www.qobra.co/)**

  No-code commission automation platform with real-time dashboards and dispute management. Popular among European scale-ups.



- **[QuotaPath](https://www.quotapath.com/)**

  Commission tracking and quota attainment platform. Provides free tier for basic commission calculation, with automated calculations, integration capabilities, and customizable plans .



- **[SalesCookie](https://salescookie.com/)**

  Web-based sales commission management software with a comprehensive free plan. Handles commission plans, quotas, and payout calculations.



- **[Varicent](https://www.varicent.com/)**

  Enterprise sales performance management and incentive compensation platform. Provides comprehensive incentive management, scalability, advanced analytics, and automation .



- **[Compass](https://www.compass.com/)**

  Commission management platform for real estate and sales organizations. Provides commission calculation, tracking, and payout processing.



## Open-Source GitHub Projects



### Laravel Packages (Production-Grade)



- **[Laravel Sales Commission (ayangzy)](https://github.com/ayangzy/laravel-sales-commission)**

  **Enterprise-grade commission calculation and management package for Laravel applications.** Handles the **entire commission lifecycle**: calculation → clawbacks (refunds) → payout processing. Features **multi-tier structures** with automatic tier progression (Bronze → Silver → Gold), **team split commissions** with role tracking (primary closer, supporting rep, manager override), **clawback support** with configurable grace periods, **payout management** with approval workflows and configurable schedules, **performance bonuses**, and an **extensible rule engine** supporting percentage-based, flat-rate, tiered, and conditional commissions. Event-driven architecture with hooks for `CommissionEarned`, `CommissionClawedBack`, `PayoutProcessed`, and `TierAchieved`. PHP 8.2+, Laravel 10/11. **31 tests, CI/CD, documented** .



- **[Laravel Commission (mkeremcansev)](https://github.com/mkeremcansev/laravel-commission)**

  Flexible package to calculate and log commissions in Laravel. Supports **multiple commission types** (percentage, fixed amount, or combination), **dynamic calculation** based on original or total price, **history tracking**, **Eloquent model integration**, and **extensibility** for custom commission logic .



### TypeScript/JavaScript Engines



- **[@lacspace/commission](https://www.npmjs.com/package/@lacspace/commission)**

  **Zero-dependency TypeScript commission and payout calculation engine.** Handles **flat fees, percentages, marginal-tier and progressive-slab rules** with min/cap bounds, composite rules, and per-category rates. Key differentiator: **exact marketplace splits** using integer minor units (cents) to eliminate rounding drift. Features tax on commission (GST/tax inclusive/exclusive), explicit rounding modes (half-up, banker's, ceil, floor, trunc), and **conserving splits** where parts always sum to the total. Isomorphic—works in Node, edge runtimes, and browsers. 375K+ weekly downloads .



- **[Seller Earnings Calculator](https://github.com/esdecode/seller-earnings-calculator)**

  **Open-source TypeScript engine for calculating marketplace seller earnings, fees, VAT, refunds, and net revenue.** Handles marketplace commissions, payment-processing fees (percentage + fixed), VAT modes (included, added on top, or none), refund estimates, affiliate commissions, and other selling costs. Returns net revenue, net revenue per sale, effective cost percentage, and seller-retention percentage. Includes unit tests and implementation examples. **MIT License** .



### Python & Full-Stack Platforms



- **[ZhuaTech COMM](https://jihulab.com/zhihua-tech/zhuatech-commission)**

  **Enterprise commission and sales incentive management system** from Shanghai Rujing Zhihua Information Technology. Covers the full lifecycle: incentive plans, eligibility, targets, attribution, commission calculation, adjustment/appeals, multi-level review, payout, and clawback audit. Features **persisted commission run batches** with beneficiary, effective performance, base rate, acceleration bands, and caps; server-side tiered calculation returning gross commission, payable commission, and cap-triggered status; **multi-person split attribution** with beneficiary uniqueness, 100% ratio validation, and amount conservation; **review gates** validating plan pre-approval, performance data lock, compliance check, and unresolved attribution disputes. Enterprise controls include ADMIN/OPERATOR role separation, organization/period isolation, governance dashboards, idempotent creation, JPA optimistic locking, and attachment SHA-256 metadata. Java 21 + Spring Boot + Vue 3 + MySQL 8 + Docker Compose. **Personal study and non-commercial use only**—commercial use requires written authorization .



- **[Sales Tracker (tebwritescode)](https://hub.docker.com/r/tebwritescode/sales-tracker)**

  **Modern web application for sales tracking and commission analytics.** Features **employee management** with commission rates and draw amounts, **manual and bulk CSV sales data entry** with automatic commission calculation, **analytics dashboard** with Chart.js (bar, pie, line charts), **goals tracking** by time period, and **multi-level permission system**. Database schema includes Employee, Sales, Settings, and Goals tables. Flask + SQLAlchemy + SQLite + Bootstrap 5 + Docker. Default admin credentials: `admin` / `admin` .



- **[CommissionPro (Estevan-Z)](https://github.com/Estevan-Z/CommissionPro)**

  **Intuitive sales commission management platform.** Features product registration and management, sales tracking and transaction monitoring, **automatic commission calculation**, and a user-friendly interface. Python/Django-based with SQLite. Spanish-language project .



### Affiliate & Marketplace Commission



- **[Affiliate Management System](https://github.com/prathammahajan13/affiliate-management-system)**

  **Production-ready affiliate management system for Node.js** with commission tracking, multi-tier programs, payment processing, fraud detection, and analytics. Supports **multi-tier commission structures** (Bronze 10% → Silver 15% → Gold 20% → Platinum 25%), **volume bonuses**, **fraud detection** with monitoring and alerts, **campaign management**, and **payment processing** (Razorpay, monthly schedule, minimum threshold). Designed for e-commerce, SaaS, and digital marketplaces .



- **[Shopee Commission Order Calculator](https://github.com/Nguyen-Anh-Don/Shopee-Commission-Order-Calculator)**

  Chrome extension for Shopee Affiliate commission tracking. Features **Click Overview** with detailed statistics (clicks, orders, commission, EPC, CVR), **Sub ID analysis** across 5 levels, **CPC configuration** for profit calculation (Commission − Click × CPC), and **effectiveness evaluation** (Profitable, Loss, Potential, Ineffective). Vietnamese-language project .



- **[XCloud Multi-Cloud Reconciliation Platform](https://github.com/2hot4you/XCLOUD)**

  **Automated reconciliation web platform for public cloud resellers.** Supports Tencent Cloud, Alibaba Cloud, Huawei Cloud, and AWS. Features **real-time commission calculation** with cloud platform API integration (hourly sync), **commission rule engine** based on contract terms, customer tier management, contract management with pricing/discount/commission ratios, and settlement cycle management. Go + Gin/Fiber + PostgreSQL + Redis + RabbitMQ. Microservices architecture with unified API adapter layer for multi-cloud data normalization .



### Additional Strong Open-Source Options



- **Full Lifecycle Management**: **Laravel Sales Commission (ayangzy)** (team splits, clawbacks, payouts, 31 tests) , **ZhuaTech COMM** (enterprise-grade, Java 21, review gates, audit) .

- **Calculation Engines**: **@lacspace/commission** (integer minor units, exact splits, progressive slabs) , **Seller Earnings Calculator** (marketplace fees, VAT, refunds) .

- **Affiliate/Marketplace**: **Affiliate Management System** (multi-tier, fraud detection) , **XCloud** (multi-cloud reconciliation) .

- **Sales Tracking**: **Sales Tracker** (draw amounts, CSV import, analytics dashboard) , **CommissionPro** (Django, automatic calculation) .

- **Laravel Packages**: **mkeremcansev/laravel-commission** (flexible types, history tracking) .



**Frameworks for building custom systems**: Combine **Laravel Sales Commission** or **ZhuaTech COMM** for full lifecycle commission management with team splits and clawbacks, **@lacspace/commission** or **Seller Earnings Calculator** for precise calculation engines, and **Affiliate Management System** for affiliate/marketplace commission tracking. Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Commission automation platforms handle sensitive compensation and financial data; ensure compliance with internal policies and relevant labor regulations.

- **Open-source reality**: The open-source ecosystem for commission automation is **developing but fragmented**. **Laravel Sales Commission (ayangzy)** provides the most complete full-lifecycle package for Laravel applications with team splits, clawbacks, and payout processing . **ZhuaTech COMM** delivers enterprise-grade commission management with review gates and audit trails (non-commercial license) . **@lacspace/commission** offers a rigorous calculation engine with exact splits and integer minor units . For **enterprise-grade platforms** with deep CRM integrations, complex plan modeling, and global support, commercial platforms (CaptivateIQ, Xactly, Varicent, Everstage) remain the primary choice.



---



**Made for revenue operations teams, sales finance managers, and compensation analysts.**

Let's make commission automation more open, transparent, and accurate.
