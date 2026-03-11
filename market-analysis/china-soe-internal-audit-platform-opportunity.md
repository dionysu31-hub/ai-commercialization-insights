# AI-Native Internal Audit Platform for Chinese SOEs: Business Opportunity Analysis

**Date:** 2026-03-11
**Focus:** State-Owned Enterprises (国有企业) and Listed Companies (上市公司), 2024-2026 developments

---

## 1. How SOE Internal Audit Departments Currently Work

### 1.1 Workflow Overview

SOE internal audit follows a five-phase cycle mandated by SASAC and the National Audit Office:

1. **Annual Audit Planning (审计计划):** Risk-based prioritization aligned with SASAC strategic requirements. Focus areas for 2025 include major strategy implementation, major project construction, financial revenue/expenditure, internal controls, and risk management.
2. **Audit Preparation (审计准备):** Issue audit notification, assemble team, gather background data from ERP/financial systems, develop audit program.
3. **Fieldwork (现场审计):** Data collection (often manual extraction from ERP), document review, sampling, substantive testing, interviews. Methods include inquiry, confirmation, discussion, calculation, and analytical review.
4. **Audit Reporting (审计报告):** Report compiled based on verified audit evidence. Must be objective, complete, clear, and timely.
5. **Rectification & Follow-up (整改跟踪):** Evaluate whether audited units have implemented corrective actions; conduct follow-up audits.

### 1.2 Tools Currently in Use

| Tool Category | Typical Products | Notes |
|---|---|---|
| **Audit management platforms** | Yonyou ShenYou A7 (审友A7), Inspur Haiyue (浪潮海岳) | Dominant incumbents for large SOEs |
| **Data analytics** | Excel (still dominant), custom SQL queries, some Python/R | Most auditors lack programming skills |
| **ERP data extraction** | Manual exports from SAP, Yonyou U8/NC, Kingdee | Often involves IT department assistance |
| **Document management** | OA systems (泛微, 致远), manual filing | Paper-based processes still common |
| **RPA tools** | 艺赛旗 (i-Search), 金智维, 影刀RPA | Emerging; SOE RPA market = RMB 2.09B (2024) |
| **Emerging AI** | DeepSeek integration (pilot stage), custom models | State Grid Zhejiang, CNOOC are early movers |

### 1.3 Budget

- **Audit informatization overall market:** ~RMB 33.8 billion demand in 2024, growing at 15%+ CAGR.
- **No standardized budget benchmarks disclosed publicly.** The SASAC Central Enterprise Internal Audit Interim Measures require that "enterprises shall guarantee necessary audit work expenses and include them in the annual financial budget" -- but specific amounts are not mandated.
- **Typical project-level indicators from procurement tenders:**
  - Small/mid SOE audit system: RMB 500K-2M for initial implementation
  - Large SOE/central enterprise digital audit platform: RMB 5M-20M+ (multi-year, including data integration)
  - Annual audit service outsourcing: RMB 270K-1.75M per project (based on 2024-2025 tender data)
  - Ganzhou Bank digital audit system: formal tender process, specific budget not disclosed
- **Software-to-total-project cost ratio:** Software typically accounts for only 30-50% of total project cost; implementation, data integration, training, and ongoing maintenance consume the remainder.

---

## 2. SOE Audit Department Structure

### 2.1 Organizational Architecture (Post-2024 Reform)

The 2024 reforms mandate a centralized structure:

```
Party Committee (党委)
  --> Party Committee Audit Work Leading Group (党委审计工作领导小组)
      --> Board of Directors (董事会)
          --> Audit Committee (审计委员会)
              --> Chief Audit Executive / 总审计师 (new mandatory role)
                  --> Audit Center / 审计中心 (centralized HQ unit)
                      --> Regional Audit Sub-Centers (审计分中心) [if needed]
```

**Key structural changes in 2024-2025:**
- **Chief Audit Executive (总审计师) system now mandatory** for all SOEs under SASAC supervision
- **Audit centralization:** Subsidiaries (except listed companies and financial institutions) should NOT maintain separate audit departments; all audit functions consolidated at HQ
- **Dual leadership:** Party Committee Secretary/Chairman directly oversees audit; Chief Audit Executive assists with day-to-day management
- **"Top-down audit" (上审下) model:** HQ audit center audits all subsidiaries

### 2.2 Staffing

| Metric | Requirement |
|---|---|
| **Minimum headcount** | No less than 0.2% of total employees (2 per 1,000) OR no less than 10% of finance personnel |
| **Minimum for small SOEs** | Generally no fewer than 5 people |
| **High-risk / large / international SOEs** | Must increase staffing beyond the 0.2% baseline |
| **Qualifications** | Must possess professional accounting/audit knowledge; department head must hold relevant professional technical title |

**Practical implications for a typical mid-size SOE (5,000 employees):**
- Minimum audit staff: ~10 people
- Typical actual: 10-20 people at HQ audit center
- Large central enterprises (50,000+ employees): 100-200+ audit staff across the group

### 2.3 Key Decision Makers

| Role | Chinese Title | Decision Authority |
|---|---|---|
| **Party Committee Secretary / Chairman** | 党委书记/董事长 | First responsible person for internal audit; approves major audit decisions |
| **Chief Audit Executive** | 总审计师 | Day-to-day audit management; nominated by Audit Committee, appointed by Board |
| **Audit Committee Chair** | 审计委员会主席 | Oversight of audit function; independent director |
| **Head of Audit Center** | 审计中心主任 | Operational management of audit team and technology |
| **CFO / Chief Accountant** | 总会计师 | Budget authority for audit technology investments |
| **CIO / IT Director** | 信息化部门负责人 | IT procurement, system integration, data security compliance |

---

## 3. Procurement Processes for SOE Audit Software

### 3.1 Procurement Framework

SOE software procurement follows strict regulatory requirements:

1. **Central Enterprise Procurement Management Guidance (中央企业采购管理指导意见):** Procurement must adhere to principles of legality, openness, fairness, competitive selection, and efficiency.

2. **Procurement methods by project value:**
   - **Public tender (公开招标):** Required for projects above threshold (typically RMB 4M for goods/services)
   - **Competitive negotiation (竞争性谈判):** For projects below threshold or with fewer than 3 qualified bidders
   - **Inquiry procurement (询比采购):** 3+ qualified suppliers submit quotes; evaluated and selected
   - **Direct procurement (直接采购):** Only for necessary internal group services; requires escalated approval and filing with parent company

3. **Approval chain:** Procurement decisions follow tiered authorization -- department head --> division VP --> CFO --> Board (for major investments)

### 3.2 Typical Timeline

| Phase | Duration |
|---|---|
| Needs identification & budget approval | 2-4 months |
| Tender document preparation | 1-2 months |
| Bidding period | 1-2 months |
| Evaluation & selection | 2-4 weeks |
| Contract negotiation & signing | 1-2 months |
| Implementation | 6-18 months |
| **Total cycle** | **12-30 months from need to go-live** |

### 3.3 Key Decision Makers for Audit Software

**Primary influencer/champion:** Head of Audit Center (审计中心主任) or Chief Audit Executive (总审计师) -- they define requirements and drive the business case.

**Budget holder:** CFO/Chief Accountant -- controls the IT and audit budget lines.

**IT gatekeeper:** CIO/IT department -- must approve from technical architecture, security, and integration perspective.

**Final approval:** Board Audit Committee for strategic investments; Party Committee for politically sensitive technology decisions.

**Procurement execution:** Centralized procurement department (采购部) manages the formal tender process.

---

## 4. Regulatory Requirements Driving SOE Internal Audit

### 4.1 Core Regulations

| Regulation | Year | Key Requirements |
|---|---|---|
| **Central Enterprise Internal Audit Management Interim Measures** (中央企业内部审计管理暂行办法) | 2020 | Establishes framework for central SOE internal audit; annual plan required; risk-based prioritization |
| **SASAC Deep Reform of Central Enterprise Internal Audit** (深化中央企业内部审计监督工作的实施意见) | 2020 | Requires "top-down audit" model; strengthen audit centralization; build "业审一体" integrated platforms |
| **SASAC 2024 IC Building Notice** (国资厅监督〔2024〕20号) | 2024 | Six major tasks for 2024 internal controls; higher, more detailed, and stricter requirements |
| **SASAC 2025 IC Building Notice** | 2025 | Enhanced full-process IC monitoring; pursue penetrating audit of listed subsidiaries; hold units/individuals accountable for unreported IC deficiencies |
| **Shanghai SASAC Internal Audit Centralization** (沪国资委审计〔2024〕101号) | May 2024 | Full centralization of audit institutions, audit matters, and audit personnel; implementation plan by June 2024; organizational adjustment by end of 2024 |
| **MOF/CSRC IC Audit Notice** | Dec 2023 | Starting from 2024 annual reports: ALL listed companies (including ChiNext and BSE) must disclose IC evaluation report AND IC audit report from CPA firm |
| **New Company Law** | Jul 2024 | Listed companies may replace Supervisory Board with Audit Committee; reshapes corporate governance and audit oversight |
| **Listed Company Audit Committee Work Guidelines** (上市公司审计委员会工作指引) | 2025 | Detailed guidance on Audit Committee responsibilities, including oversight of IC and audit |

### 4.2 SASAC Audit Centralization Requirements (国资委审计集中化要求)

This is the single most impactful regulatory driver for the SOE audit software market:

- **Three centralizations:** Centralize audit institutions (机构集中), audit matters (事项集中), and audit personnel (人员集中)
- **Eliminate fragmented subsidiary audit departments** (except for listed companies and financial institutions that must maintain independent audit per securities regulations)
- **HQ audit center** manages all audit activities with unified planning, standards, and resource allocation
- **Regional sub-centers** permitted for SOEs with many subsidiaries spread across geographies or industries, but must report to HQ audit center
- **Chief Audit Executive system** mandatory for all SASAC-supervised enterprises
- **Technology requirement:** Build integrated "业审一体" (business-audit integration) information platforms connecting to ERP, finance, investment, internal controls, and other operational systems

### 4.3 Listed Company IC Audit Report Requirements (内控审计报告)

**Expansion timeline:**
- Pre-2024: IC audit report required only for main board companies
- 2024 annual reports onward: ALL listed companies (including ChiNext创业板 and BSE北交所) must provide:
  1. Board-approved Internal Control Evaluation Report (内部控制评价报告)
  2. CPA firm's Financial Reporting Internal Control Audit Report (财务报告内部控制审计报告)
- IC audit reports must be submitted with annual reports by specified deadlines (e.g., April 15 for listed subsidiaries, May 15 for financial enterprises)

**Accountability:** SASAC 2025 requirements explicitly state that failure to identify or disclose material IC deficiencies will result in retroactive accountability for relevant units and individuals.

---

## 5. Biggest Pain Points for SOE Internal Audit Teams

### 5.1 Critical Pain Points (Ranked by Impact)

| # | Pain Point | Details |
|---|---|---|
| 1 | **Limited audit coverage / blind spots** | Manual approaches cannot cover all business processes across large multi-entity SOE groups; creates supervision gaps (监督盲区) |
| 2 | **Weak data processing capability** | SOEs generate massive volumes of financial, operational, and management data across dozens of systems; manual analysis is slow and error-prone |
| 3 | **Reactive (post-facto) audit model** | Most audit is conducted after the fact; risks discovered only after damage occurs; unable to detect issues at the "seedling stage" |
| 4 | **Audit talent knowledge gap** | Auditors trained in traditional financial audit lack skills in data analytics, programming, IT systems, and cross-disciplinary domains |
| 5 | **Cross-department data silos** | Data sharing between audit and other departments (finance, procurement, HR, legal) lacks unified mechanisms; duplication and inefficiency |
| 6 | **Centralization implementation challenges** | The new centralization mandate creates practical challenges: how to remotely audit dispersed subsidiaries effectively |
| 7 | **Resource-demand mismatch** | Increasingly strict external regulatory requirements combined with limited audit resources; staffing cannot keep up with expanding audit scope |
| 8 | **Low standardization of audit processes** | Audit work across subsidiaries uses inconsistent methods, templates, and quality standards |
| 9 | **Repetitive low-value work** | Auditors spend excessive time on data gathering, formatting, classification rather than professional judgment |
| 10 | **Lagging risk early warning** | Traditional audit models cannot provide real-time risk alerts; continuous monitoring is aspirational but rarely implemented |

### 5.2 Quantified Impact (from Case Studies)

- China National Offshore Oil Corporation (CNOOC): Before digital audit platform, data extraction for a single audit could take **2-3 weeks**; after platform deployment, reduced to **hours**
- RSM China audit robot: Reduced per-document review time from **10 minutes to 20 seconds** (30x improvement)
- State Grid Zhejiang multi-technology audit tool chain: **10x efficiency improvement**, false negative rate below 5%
- DeepSeek in audit: Processes millions of structured/unstructured records; **400x faster** than traditional methods for data matching

---

## 6. Existing Products Serving This Market

### 6.1 Tier 1: Dominant Incumbents

| Product | Vendor | Market Position | Key Strengths |
|---|---|---|---|
| **审友A7** (ShenYou A7) | 用友审计 (Yonyou Audit) | Market leader in SOE internal audit software; 100,000+ enterprise/institution clients | 12 subsystems (audit management, data analytics, IC evaluation, remote audit, rectification tracking, engineering audit); ShenYou Cloud with OCR/ASR/blockchain; deep SOE ecosystem |
| **浪潮海岳** (Inspur Haiyue) | 浪潮 (Inspur) | Top market share in government and enterprise audit; 200+ central SOEs and provincial audit organs | Cloud-native architecture; strong government/SOE procurement relationships |
| **金蝶审计** (Kingdee Audit) | 金蝶 (Kingdee) | Top market share in cloud audit informatization | Cloud-native; ERP-integrated audit; mid-to-large enterprise focus |

### 6.2 Tier 2: Vertical/Specialized Players

| Product | Vendor | Market Position | Key Strengths |
|---|---|---|---|
| **远光DAP** | 远光软件 (Ygsoft) | 80%+ market share in power sector financial informatization; expanding to audit | Energy/power SOE specialization (State Grid, China Southern Power Grid); 2025 revenue RMB 2.59B (+8.12% YoY) |
| **鼎信诺7000** | 鼎信诺 (DXN) | 80+ of China's Top 100 CPA firms; 145,000+ users | External audit focus (CPA firms); 20-year track record; strong data extraction capabilities |
| **财智共享 Audit365** | 财智共享 | SOE-focused big data audit platform | Specifically targets SOE pain points; freemium model (basic tools free, premium modules paid); supports private deployment; ISO 27001, 等保三级 certified |

### 6.3 Tier 3: Emerging AI-First Players

| Product/Initiative | Description |
|---|---|
| **致同AI科技平台** (Grant Thornton China) | LLM-integrated platform with 7 modules including AI Knowledge Base, regulation search, document translation; launched March 2025 |
| **容诚数智** (RSM Digital Intelligence) | Audit robot (RPA), text mining for contracts, "Three-Core" digital methodology |
| **CNOOC审计数智化平台** | In-house SOE platform: Phase 2 completed late 2024; "数智化+业务" dual-audit-lead model |
| **State Grid "AI+Audit"** | Zhejiang, Shanghai, Gansu provincial companies passed China's first "AI+Audit" capability assessment (2025); exploring DeepSeek integration |

### 6.4 Market Size and Growth

| Metric | Value |
|---|---|
| China audit informatization market (2024) | ~RMB 33.8 billion demand |
| Audit informatization market (2026 projected) | Expected to exceed RMB 50 billion |
| CAGR during 15th Five-Year Plan | 15%+ |
| SOE RPA market (2024) | RMB 2.09 billion, growing 51.3% |

### 6.5 CPAS (Legacy Product) Pricing Reference

Yonyou's entry-level CPAS audit system: **RMB 3,000/permanent license** (+ 15% annual maintenance from Year 2). This is for small-scale CPA use; enterprise SOE solutions like ShenYou A7 are priced dramatically higher (project-based, not publicly disclosed, estimated RMB 1-10M+ depending on scope).

---

## 7. Price Points and Business Models for SOE IT Procurement

### 7.1 Pricing Tiers (Estimated from Market Data)

| Tier | Target Customer | Price Range | Typical Model |
|---|---|---|---|
| **Entry** | Small SOEs, district-level state enterprises | RMB 200K-800K | Perpetual license + annual maintenance (15-20%) |
| **Mid-range** | Provincial SOEs, mid-size central enterprise subsidiaries | RMB 1M-5M | Project-based implementation + annual subscription |
| **Enterprise** | Large central enterprises (央企), major listed SOEs | RMB 5M-20M+ | Multi-year contract, phased delivery, customization included |
| **Platform** | SASAC-level or industry-wide deployment | RMB 20M-50M+ | Strategic partnership, revenue sharing, ongoing development |

### 7.2 Business Models That Work for SOE Procurement

1. **Project-based implementation (项目制):** Most common for initial deployment. Fixed scope, fixed price. SOEs prefer predictable costs.

2. **Annual license + maintenance (年费制):** Typical for ongoing software: 15-20% of initial license fee per year for maintenance and updates.

3. **Subscription/SaaS (订阅制):** Growing but faces resistance. SOEs prefer on-premise/private cloud deployment for data security. Cloud ERP adoption growing (65% globally by 2025), but SOE audit tools strongly favor private deployment.

4. **Freemium + upsell:** Audit365 model -- basic tools free, premium analytics and AI modules paid. Lower barrier to entry, but SOEs may distrust "free" offerings.

5. **Strategic partnership:** For very large central enterprises: co-development model where the SOE gets customized solution and the vendor gets reference customer + IP.

### 7.3 Critical Procurement Considerations

- **信创 (Xinchuang) compliance is mandatory:** All SOE IT procurement must prioritize domestic products. SASAC Document 79 requires 100% domestic IT system replacement by 2027. Audit software MUST run on domestic tech stack: domestic CPU (Loongson, Kunpeng), domestic OS (openEuler, Kylin), domestic DB (GaussDB, DM, KingbaseES).
- **Private deployment preferred:** SOEs strongly prefer on-premise or private cloud. "Data must not leave the enterprise" (数据不出企) is a common requirement.
- **等保三级 (Level 3 information security protection) certification** is typically required for audit systems handling sensitive financial data.
- **ISO 27001 certification** expected.
- **All operations must leave audit trails** -- even data queries, not just exports.
- **Support for 国密算法 (Chinese national cryptographic algorithms)** for data encryption.

---

## 8. Case Studies of AI Audit Implementations in Chinese SOEs

### 8.1 China National Offshore Oil Corporation (中国海油)

**Timeline:** Phase 2 completed late 2024
**Scope:** Comprehensive audit digital intelligence platform
**Key features:**
- Broad data infrastructure with multiple analysis tools and rich audit models
- "全面培养+重点攻关" (comprehensive training + focused R&D) two-dimensional talent cultivation
- "数智化+业务" dual-audit-lead model -- pairing digital technology leads with business domain leads for every audit engagement
- February 2025: Integrated DeepSeek-R1 671B (full and distilled versions) via private deployment on "海能" (HaiNeng) AI platform
- DeepSeek API interfaces opened to ERP, procurement mall, and other enterprise systems
- Service available via web and mobile ("海能智问")

### 8.2 State Grid Zhejiang Electric Power (国网浙江省电力)

**Achievement:** One of four enterprises to pass China's first "AI + Audit" capability assessment (信通院 "5层26维" evaluation framework), 2025
**Key innovations:**
- Multi-technology audit tool chain: OCR + ASR + RPA + Large Language Model
- DeepSeek-based exploration of LLM applications in audit questioning (审计问数)
- Audit risk insight intelligent agents (审计风险洞察智能体)
- Results: **10x efficiency improvement**, false negative rate below 5%
- Transformed employee compliance auditing from manual to AI-driven

### 8.3 State Grid Shanghai / Gansu Electric Power

**Achievement:** Also among the four to pass "AI + Audit" capability assessment (2025)
**Context:** Part of broader State Grid system-wide digital audit transformation

### 8.4 China Mobile (中国移动)

**Achievement:** Fourth enterprise to pass "AI + Audit" capability assessment (2025)
**Context:** Telecommunications SOE applying AI to internal audit across massive, geographically distributed operations

### 8.5 National Pipeline Network Group (国家管网集团)

**Focus:** Digital audit transformation built on "data empowerment, platform support, scenario-driven, and team building" as four core capabilities
**Context:** Oil and gas pipeline infrastructure SOE with complex asset audit requirements

### 8.6 Unnamed Central Enterprise (145 Risk Models)

**Implementation:** Embedded 145 risk indicator models into ERP/MRP systems
**Capability:** 24/7 continuous audit monitoring across procurement, production, and sales
**Shift:** From periodic post-facto audit to continuous real-time monitoring

### 8.7 Anhui Banking Institution (AI + Internal Audit)

**Technology:** DeepSeek large model-based internal audit application
**Capability:** Processing of millions of structured and unstructured records (contracts, invoices, transaction flows); ERP-to-bank-statement dual-direction verification; 400x speed improvement over traditional methods

---

## 9. Typical IT Infrastructure in SOEs

### 9.1 ERP Systems

| ERP Vendor | SOE Market Position | Details |
|---|---|---|
| **SAP** | 24.7% market share in manufacturing; dominant in large central enterprises | Being actively replaced under 信创 policy; many SOEs still running SAP ECC/S4HANA |
| **Oracle** | 16% market share; strong in finance sector SOEs | Also facing 信创 replacement pressure |
| **Yonyou NC/BIP** | 30% market share among Chinese SMEs; serves 70% of central enterprises | Cloud version (BIP) is "业财税金档一体化"; fastest growing domestic ERP |
| **Kingdee EAS/Cloud** | 13% market share; strong in mid-market | 24% cloud ERP growth in 2025 |
| **Inspur GS/PS** | 12% market share | Strong in government and industrial SOEs |
| **Huawei MetaERP** | Surged to 35% of central enterprise ERP market share in H1 2024 | Full-stack domestic (openEuler OS + GaussDB + self-developed app layer); integrates Pangu LLM for "intelligent finance assistant" and "supply chain risk prediction" |

### 9.2 Financial Systems

- **Core financial accounting:** Yonyou NC, Kingdee EAS, SAP FI/CO, Oracle Financials
- **Treasury management:** Bank-enterprise direct connection systems, cash pooling platforms
- **Tax management:** 航天信息 (Aisino) tax systems, 百望云 (Baiwang) e-invoicing
- **Shared services:** 中兴新云 financial shared services platform (200+ large enterprise clients including CNPC, FAW, China Southern Airlines)

### 9.3 IT Infrastructure Stack

| Layer | Domestic (信创) Options | Legacy/Foreign |
|---|---|---|
| **CPU** | Kunpeng (华为), Loongson (龙芯), Phytium (飞腾) | Intel, AMD |
| **OS** | openEuler, Kylin (银河麒麟), UOS (统信) | Windows Server, RHEL |
| **Database** | GaussDB (华为), DM (达梦), KingbaseES (金仓), OceanBase | Oracle DB, SQL Server, MySQL |
| **Middleware** | TongWeb (东方通), Apusic (金蝶天燕) | WebLogic, WebSphere |
| **Cloud** | Huawei Cloud, Alibaba Cloud (政务版), Tencent Cloud | AWS, Azure (limited SOE use) |
| **Office** | WPS Office (金山), 永中Office | Microsoft Office |

### 9.4 Key Infrastructure Trends for Audit Software Design

1. **信创 replacement is non-negotiable:** By 2027, 100% of SOE IT systems must be domestic. Audit software must be certified to run on the entire domestic stack.
2. **Hybrid deployment:** Most large SOEs operate both legacy (SAP/Oracle) and new domestic systems simultaneously during transition. Audit tools must integrate with BOTH.
3. **Data isolation:** SOE data must stay within enterprise boundaries. SaaS/public cloud models face strong resistance. Private deployment or dedicated cloud instances are standard.
4. **Multiple ERP environments:** Large SOE groups often have different ERPs across subsidiaries (e.g., HQ on SAP, subsidiaries on Yonyou). Audit tools must handle heterogeneous data sources.

---

## 10. Data Security and Compliance Requirements

### 10.1 Regulatory Framework

| Regulation | Requirement for Audit Tools |
|---|---|
| **Cybersecurity Law (网络安全法)** | Information systems must comply with network security requirements; mandatory vulnerability assessments |
| **Data Security Law (数据安全法)** | Data classification and grading (分类分级) mandatory; important data handling requires risk assessment; data localization for critical information infrastructure |
| **Personal Information Protection Law (个人信息保护法)** | Audit data containing personal information must comply with PIPL requirements; consent, minimization, and purpose limitation principles |
| **等保2.0 (Classified Protection of Cybersecurity 2.0)** | Audit systems typically require **Level 3 certification** (等保三级); involves access control, audit logging, data encryption, intrusion detection, backup/recovery |
| **GB/T 43697-2024 Data Classification and Grading Rules** | National standard for data classification; SOE audit data must be classified by sensitivity level |
| **SASAC Document 79 (信创79号文)** | 100% domestic IT stack by 2027; quarterly progress reporting to SASAC |
| **Industrial Data Security Standards** | New standards effective 2025 (工业企业数据安全防护要求, 工业领域数据安全风险评估规范) covering full data lifecycle |

### 10.2 Specific Requirements for Audit Software

1. **Data must not leave the enterprise (数据不出企):** Private deployment mandatory; no data transmission to external servers.
2. **Full audit trail of all operations:** Every action -- including data queries, report views, exports -- must be logged with user identity, timestamp, and action type.
3. **Role-based access control down to field level:** Permissions must specify who can view, edit, or export at the individual data field and report level.
4. **支持国密算法 (National cryptographic algorithms):** SM2/SM3/SM4 encryption algorithms must be supported for data at rest and in transit.
5. **Regular log archiving and traceability:** All operation logs must be automatically archived and available for compliance audits.
6. **Data backup and disaster recovery:** Must support multi-site backup including remote disaster recovery (as demonstrated by Ganzhou Bank's three-center architecture).
7. **ISO 27001 and 可信云 (Trusted Cloud) certification** typically required.
8. **Annual data compliance audit:** Regular risk assessments for important data handling activities.
9. **No foreign vendor backend access:** Eliminates consideration of most international SaaS audit tools.

### 10.3 AI-Specific Data Security Considerations

- **LLM deployment must be private:** SOE audit data cannot be sent to public AI APIs (no OpenAI, no public DeepSeek API). Must use privately deployed models (CNOOC's approach: DeepSeek-R1 private deployment on internal "海能" platform).
- **Model training data governance:** If using audit data to fine-tune models, data classification and grading rules apply.
- **AI output audit trail:** AI-generated recommendations and reports must be traceable to source data and model version.
- **Human-in-the-loop requirement:** AI audit findings must be reviewed and approved by qualified human auditors before becoming official.

---

## Summary: Market Opportunity Assessment

### Tailwinds

1. **Regulatory mandates creating forced demand:** SASAC audit centralization (2024), mandatory IC audit for ALL listed companies (2024), 信创 replacement (2027 deadline), Chief Audit Executive system
2. **Massive market:** ~RMB 33.8B audit informatization market (2024), 15%+ CAGR, on track to exceed RMB 50B by 2026
3. **Technology gap:** 76% of audit leaders are GenAI novices; no dominant AI-native audit platform exists in China
4. **Pain points are acute and quantifiable:** 10-30x efficiency gains demonstrated in early AI audit deployments
5. **信创 creates opportunity for domestic players:** International tools (TeamMate+, AuditBoard) are effectively locked out of the SOE market
6. **Centralization mandate demands new tools:** Remote audit of dispersed subsidiaries from HQ requires digital platforms -- this is new demand
7. **National "AI+" initiative:** State Council mandating AI integration across all sectors by 2027

### Headwinds

1. **Long procurement cycles (12-30 months):** SOE decision-making is slow and bureaucratic
2. **Relationship-driven sales:** Incumbent vendors (Yonyou, Inspur) have deep SOE relationships built over decades
3. **Data security requirements limit deployment models:** Must support full private deployment on domestic tech stack
4. **Conservative adoption culture:** SOE auditors are risk-averse; prefer proven solutions over innovative ones
5. **Integration complexity:** Must work with heterogeneous ERP environments (SAP + Yonyou + Kingdee + legacy systems)
6. **Talent gap:** End users (SOE auditors) lack digital skills; product must be extremely usable

### Strategic Entry Points

1. **AI layer on top of existing audit platforms:** Rather than replacing ShenYou A7 or Inspur Haiyue, build AI-powered analytics, anomaly detection, and report generation that INTEGRATES with them
2. **Target the centralization pain point:** Purpose-built solution for remote subsidiary audit from HQ -- this is a new need with no dominant solution
3. **Partner with 信创 ecosystem:** Certify on domestic tech stack (Kunpeng + openEuler + GaussDB); become a reference implementation
4. **Start with specific SOE verticals:** Energy (State Grid ecosystem), oil & gas (CNOOC model), telecommunications (China Mobile) -- sectors with demonstrated AI audit interest
5. **Land with pilot, expand with results:** SOEs respond to demonstrated ROI; offer pilot programs with clear metrics (audit coverage increase, time savings, risk detection improvement)

---

## Sources

### Regulatory & Policy
- [SASAC Central Enterprise Internal Audit Interim Measures](https://www.gov.cn/zhengce/2022-01/13/content_5718592.htm)
- [SASAC Deep Reform of Central Enterprise Internal Audit](http://wap.sasac.gov.cn/n2588030/n2588959/c15661368/content.html)
- [Shanghai SASAC Internal Audit Centralization](https://www.gzw.sh.gov.cn/zcwj_gzjgwj/20240613/34baefaa3bcd43d79e45e9090a3c1ee0.html)
- [Shanghai SASAC 2024 Deployment Conference](https://www.gzw.sh.gov.cn/shgzw_xwzx_gzyw/20240531/c730859d0cf8471096e3c326af3f9d4e.html)
- [Shanghai SASAC Centralization Q&A](https://www.gzw.sh.gov.cn/shgzw_fzjs_zcjd/20241023/54653f58b8d64df091edb1ff92eb750d.html)
- [SASAC 2024 IC Building Notice - RSM Interpretation](https://www.rsm.global/china/zh-hans/news/xiangjie2024nianyangqineikongjiansheyujiandugongzuoliudarenwu)
- [SASAC 2025 IC Building Notice](http://www.zhongtaihexin.com/policy/Nationalpolicies/1304)
- [MOF/CSRC 2023 IC Audit Notice - 反舞弊联盟](https://www.fanwubi.org/Item/205184.aspx)
- [Listed Company Audit Committee Work Guidelines 2025](https://capcofile.oss-cn-beijing.aliyuncs.com/2025/file/%E5%85%B3%E4%BA%8E%E5%8F%91%E5%B8%83%E3%80%8A%E4%B8%8A%E5%B8%82%E5%85%AC%E5%8F%B8%E5%AE%A1%E8%AE%A1%E5%A7%94%E5%91%98%E4%BC%9A%E5%B7%A5%E4%BD%9C%E6%8C%87%E5%BC%95%E3%80%8B%E7%9A%84%E9%80%9A%E7%9F%A5.pdf)
- [SASAC Document 79 - Xinchuang Mandate](https://www.wosign.com/News/news_2023051801.htm)
- [Jiangsu SASAC Internal Audit Strengthening Notice](https://www.jiangsu.gov.cn/art/2024/1/22/art_84323_11141869.html)
- [Shenzhen SASAC Internal Audit Regulations](http://gzw.sz.gov.cn/zwgk/zcfgjzcjd/zcfg/content/post_7366586.html)
- [Audit Law of the PRC (English)](https://english.www.gov.cn/services/doingbusiness/202102/24/content_WS6035f053c6d0719374af97af.html)

### Market & Industry Analysis
- [China Internal Audit Association - Digital Intelligence Cases](https://www.ciia.com.cn/cndetail.html?id=79290)
- [CAICT Internal Audit Digital Transformation Report 2025](https://www.hulianhutongshequ.cn/detail/b2fecfb4ad3b46dd9ce4a618541e79f2)
- [Shanghai National Accounting Institute - 2025 Internal Audit Insight Report](https://www.snai.edu/2025/0331/85933.shtml)
- [2025 Audit Software Authority Guide](https://finance.sina.com.cn/tech/roll/2026-01-20/doc-inhhxqwx6201775.shtml)
- [Internal Audit Software Market Report (chinabgao)](https://www.chinabgao.com/report/17514158.html)
- [Audit Software Market Share Analysis](https://m.gelonghui.com/p/2049489)
- [SOE Big Data Audit Platform (Audit365)](https://www.audit365.cn/news/202601070001.html)
- [Audit Software Market Forecast (Fortune Business Insights)](https://www.fortunebusinessinsights.com/audit-software-market-103745)
- [People's Forum - SOE Internal Audit High-Quality Development](https://www.rmlt.com.cn/2025/0702/734268.shtml)

### Technology & Case Studies
- [CNOOC DeepSeek Deployment](https://www.cpnn.com.cn/news/zngc/202502/t20250228_1776641.html)
- [DeepSeek Audit Applications Guide](https://www.fanwubi.org/Item/207252.aspx)
- [Anhui Bank AI Audit Application](https://www.53ai.com/news/AIjinrong/2025030839285.html)
- [Digital Intelligence Audit Methods & Practice (CAICT)](https://px.gooann.com/Uploads/File/2025-05-08/681c6b17f2532.pdf)
- [Deloitte China - AI in Audit](https://finance.sina.com.cn/wm/2025-03-09/doc-inenzyap7452915.shtml)
- [2025 AI Empowering Enterprise Audit (简道云)](https://www.jiandaoyun.com/news/article/685d029a229b892d52dda47f)
- [Audit365 Big Data Audit Tools](https://www.audit365.cn/news/202601120001.html)

### ERP & IT Infrastructure
- [2024 Central Enterprise ERP Market Share Analysis](https://blog.csdn.net/HeartForever2025/article/details/150438635)
- [2025 Domestic vs Foreign ERP Comparison](https://www.snpgroup.cn/newsblog/9859.html)
- [ERP Nationalization Trends 2025](https://www.finereport.com/blog/article/68b1583ed2527e0eb70f9136)
- [Xinchuang Policy Impact on Enterprise Software](https://www.eet-china.com/mp/a421111.html)
- [FineReport - National Cryptography Compliance](https://www.finereport.com/blog/article/692991f1d2527e0eb70afd20)

### Corporate Governance
- [PwC China SOE Internal Audit Transformation](https://www.pwccn.com/en/issues/risk-regulation/managing-risk-from-risk-perspective.html)
- [New Company Law Impact on SOE Governance](https://www.crhcc.com/gzyyts/2024/3/86bd10c78f46434baa740b805b75facc.htm)
- [Audit Committee as Supervisory Board Replacement](https://www.dehenglaw.com/CN/tansuocontent/0008/031918/7.aspx?MID=0902)
- [ACGA - CCP Modern Corporate System](https://www.acga-asia.org/blog-detail.php?id=103)
- [EY China - SOE Reform Approach](https://www.ey.com/en_cn/insights/china-opportunities/how-is-china-approaching-soe-reform)

### Data Security
- [China Data Security Regulation Trends 2025](https://www.allbrightlaw.com/SH/CN/10475/fc875145c68dc6b1.aspx)
- [GB/T 43697-2024 Data Classification Rules](https://www.secrss.com/articles/73983)
- [等保2.0 2025 Updates](https://zhuanlan.zhihu.com/p/1918666128286287156)
- [Industrial Data Security Standards 2025](https://www.secrss.com/articles/81544)
- [Enterprise Data Compliance Audit - FineReport](https://www.finereport.com/blog/article/68b7f55fd2527e0eb75055bf)
