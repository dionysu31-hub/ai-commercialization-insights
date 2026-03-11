# AI in Industrial Mold Design (模具设计) - China Market Research

_Research date: 2026-03-11 | Focus: 2024-2026 developments_

---

## 1. AI Products & Startups in Mold Design

### International Players

| Company | Product | Focus | Funding/Status |
|---------|---------|-------|----------------|
| **Atomic Industries** (US, Michigan) | AI-designed molds platform | AI-optimized mold design + manufacturing; uses 46-sensor LS Mtron machines to gather data | **$25M Series A** (Sept 2025); CB Insights AI 100 2024 |
| **CoLab Software** (Canada) | EngineeringOS + AutoReview | AI-powered design review, DFM checks, drawing review, GD&T verification | **$72M Series C** (Nov 2025); prior $21M Series B (May 2024); 47,000+ engineers on waitlist |
| **Moldex3D / CoreTech Systems** (Taiwan) | Moldex3D 2025 | AI Optimization Wizard, generative AI cooling channels (LLM-based), MoldiBot AI assistant | Established CAE leader |
| **MoldSim** (US) | MoldSim MCP | MCP server for Claude AI with 20+ years injection molding expertise; DFM rules, defect troubleshooting | Early-stage startup |
| **Altair / Siemens** | Inspire Mold | End-to-end injection molding simulation; fill/pack/cool/warp | Altair acquired by Siemens |
| **Autodesk** | Moldflow 2025 | Cooling channel optimization, faster 3D mesh solving | Public company |
| **Siemens** | NX Mold Wizard + DFM Advisor | Automated mold splitting, parting line, cooling simulation; new DFM Advisor in NX 2025 | Public company |
| **Dassault Systemes** | SOLIDWORKS 2025 + xMold + AURA AI | AI agents (Leo for engineering/manufacturing), mold design tools | Public company |
| **Tebis** (Germany) | Tebis SmartOps + ProLeiS MES | End-to-end CAD/CAM automation for mold manufacturing | Established |
| **Hexagon** | VISI Mould Design | Automated parting line, core/cavity splitting | Public company |
| **Werk24** (Germany) | AI Drawing API | OCR/AI extraction of dimensions, tolerances, GD&T from 2D drawings | Startup |
| **AI Review** (Sweden) | AI Review | Automated technical drawing review, GD&T compliance checking | Startup |

### Chinese Players

| Company | Product/Focus | Status |
|---------|---------------|--------|
| **模德宝 Moldbao** (Dongguan) | Smart mold factory (15,000+ sqm); "模云" industrial internet platform; AI for quoting, scheduling, quality inspection | **200M+ RMB funding**; incubated by HKUST Prof. Li Zexiang's Xbot Park; partnered with Huawei Cloud for mold flow simulation platform |
| **迁移科技 TransferTech** (Beijing) | 3D vision systems for mold wear monitoring; AI algorithms for real-time cavity wear compensation | **Tens of millions RMB B-round**; 30% improvement in wear monitoring precision |
| **卓世科技** (Shenzhen/GBA) | Industry-specific AI models; AIGC for mold design validated at auto parts companies; ISO 13090 certified; supports NX, Creo, CATIA | **100M+ RMB funding** (July 2025) |
| **Maker-Ray 创科视觉** (Shenzhen) | AI-powered AOI inspection machines; deep learning defect detection | Established AOI leader in China |

---

## 2. AI Solutions by Mold Design Workflow Stage

### A. DFM Analysis (可制造性分析)

**Current AI capabilities:**
- **Automated wall thickness analysis** with heat-map visualization (Fictiv, CoLab, Altair)
- **Draft angle detection** with color-coded feedback
- **Undercut identification** requiring secondary tooling motions
- **Parting line estimation** showing cavity/core separation
- **AI agents** that apply DFM rules from institutional knowledge, not just flag issues but explain *why* (CoLab AutoReview)
- Fictiv launched "industry-first" fully automated injection molding DFM (Oct 2024)

**Maturity:** Most mature AI application in the mold workflow. Real-time, geometry-based checks are production-ready.

### B. Mold Flow Analysis (模流分析)

**Current AI capabilities:**
- **Moldex3D AI Optimization Wizard**: dynamically adjusts parameters, multi-objective optimization, automatic best-solution recommendation
- **Generative AI cooling channel design** (Moldex3D + LLM): auto-generates cooling channel layouts from CAD files + text descriptions
- **Gate Design Discovery & Mold Design Discovery** (Moldex3D iSLM): rapid estimation of gate positions, machine selection, injection pressure, clamping force
- **Moldflow 2025**: new cooling channel optimization solver
- **NX 2025**: enhanced cooling channel simulation
- **AI surrogate models** achieving 90-95% accuracy vs. traditional FEA for defect prediction

**Maturity:** AI augments but does not replace traditional simulation. Hybrid AI + FEA approaches yield best results. Traditional methods still superior for complex multi-physics scenarios.

### C. Mold Splitting / Parting (分模)

**Current AI capabilities:**
- **NX Mold Wizard**: automated shutoffs, parting surface generation, core/cavity splitting, interference checking
- **VISI Mould Design**: automated split line extraction, parting surface management
- Largely rule-based automation rather than deep learning

**Maturity:** Least AI-penetrated stage. Current tools are parametric/rule-based automation. True AI-driven parting (learning optimal split strategies from data) is still a research frontier.

### D. Drawing Review (图纸审查)

**Current AI capabilities:**
- **CoLab AutoReview**: AI reads 2D drawings "like an engineer" -- checks DFM, GD&T, BOM mismatches, cross-sheet consistency, missing tolerances
- **Werk24 API**: AI extraction of title blocks, dimensions, tolerances, thread specs, surface roughness from engineering drawings
- **AI Review (Sweden)**: GD&T compliance against ISO GPS and ASME Y14
- **Automated balloning**, inspection plan generation (AS9102, PPAP)
- **GPT-based approaches** showing promise for drawing QC but not yet production-grade

**Maturity:** Rapidly maturing. CoLab's waitlist of 47,000+ engineers signals strong demand. Most tools focus on 2D drawings; 3D PMI review is still emerging.

### E. AOI Inspection (自动光学检测)

**Current AI capabilities:**
- ~35% of new AOI installations in 2024 featured ML algorithms with self-improving defect detection (up to 20% accuracy improvement)
- China has 21,000+ operational AOI systems (largest market globally)
- Micron-level defect detection at production speeds
- Applied to molded plastic parts: surface imperfections, dimensional errors, misalignments
- **迁移科技**: 3D vision + AI for mold cavity wear monitoring, achieving 30% precision improvement
- Global AOI market: $1.05B (2024) projected to $6.17B by 2034 (19.4% CAGR)

**Maturity:** Production-ready and widely deployed in China. Deep learning has transformed accuracy; main challenges are in complex 3D surface inspection and small-batch variability.

---

## 3. Technical Barriers

### Data Challenges
- **Training data scarcity**: 3D CAD datasets for ML are limited, especially construction histories and constrained sketches critical for mold design
- **Proprietary data silos**: mold factories guard design IP; no shared datasets for AI training
- **Data quality**: historical mold trial data is often unstructured, inconsistent, or paper-based

### AI Model Limitations
- **Weak spatial/geometric reasoning**: LLMs and diffusion models struggle with precise 3D geometry, edge loops, UV layouts
- **Mode collapse in GANs**: repetitive outputs, limited design diversity
- **GAN training instability**: requires significant compute and expert intervention
- **Validation gap**: AI-generated designs require extensive manual validation by engineers
- **GenAI for CAD underdeveloped** compared to text/image generation -- not production-ready

### Domain-Specific Barriers
- **Multi-physics complexity**: mold flow involves coupled thermal-fluid-structural problems; AI surrogates reach 90-95% but fall short for edge cases
- **Parting strategy reasoning**: requires understanding of undercuts, slider mechanisms, ejection -- hard to encode
- **Material variability**: resin behavior varies by grade, lot, and processing conditions
- **Tolerance precision**: mold design requires micron-level accuracy (0.002mm machining, 0.001mm inspection) that AI cannot yet guarantee

### Integration Barriers
- **CAD platform fragmentation**: solutions must work across NX, Creo, CATIA, SOLIDWORKS
- **Legacy workflows**: many Chinese mold shops still use paper-based or semi-digital processes
- **Workforce resistance**: experienced mold designers skeptical of AI recommendations
- **Cost of transition**: SME mold shops (majority of China's 1,500+ Dongguan enterprises) lack capital for digital transformation

---

## 4. China Mold Industry Market Size

| Metric | Value |
|--------|-------|
| **China mold market (2023)** | 358.9 billion RMB (~$50B USD) |
| **China mold market (2022)** | 346.8 billion RMB, +12.6% YoY |
| **Growth trajectory** | 293.7B RMB (2017) to 358.9B RMB (2023); CAGR ~3.4% |
| **Global share** | China accounts for >35% of global mold output |
| **China plastic mold segment** | ~45% of total mold market; injection molds are the largest subsegment |
| **China plastic mold projection** | ~600B RMB (2022) to 1 trillion RMB by 2030 (6-8% CAGR) |
| **Global industrial mold market** | $54B (2024), projected $59B (2025) |
| **Mold exports (China, 2023)** | $8.01B USD (up from $5.49B in 2017) |
| **Mold imports (China, 2023)** | $1.025B USD (down from $2.051B in 2017) -- import substitution trend |
| **Enterprise concentration** | Eastern coastal regions dominate; Dongguan = "Mold Capital of the World" with 1,500+ mold enterprises |
| **Digital transformation** | Dongguan: 8,448 enterprises digitally transformed (60% of industrial firms); 120 smart factories certified |

---

## 5. Key Players and Software Ecosystem

### CAD/CAM Software Usage in China's Mold Industry

| Software | Vendor | Role in Mold Design | China Presence |
|----------|--------|---------------------|----------------|
| **NX (UG)** | Siemens | Dominant for complex mold design; Mold Wizard for parting/splitting | Very strong in automotive, consumer electronics mold shops |
| **Moldflow** | Autodesk | Industry standard for injection molding simulation | Widely used for mold flow analysis |
| **Moldex3D** | CoreTech (Taiwan) | Advanced 3D mold flow simulation; AI features | Strong in Greater China |
| **CATIA** | Dassault | High-end mold design, especially automotive | Used by Tier 1 automotive suppliers |
| **SOLIDWORKS** | Dassault | Mid-range 3D CAD with mold tools | Widespread in SME mold shops |
| **Creo (Pro/E)** | PTC | Mold design with Expert Moldbase Extension | Legacy user base in China |
| **Tebis** | Tebis AG | CAD/CAM + MES for mold manufacturing | Active in China market |
| **VISI** | Hexagon | Specialized mold/die design | Niche but growing |
| **Cimatron** | 3D Systems | Integrated mold design + CAM | Mold-specific player |

### Notable Chinese Mold Enterprises

- **模德宝 Moldbao** (Dongguan/Songshan Lake) -- AI smart factory pioneer
- **银宝山新 Shenzhen Silver Basis** -- listed company, precision molds
- **东江集团 Tongjiang Group** -- Hong Kong listed, precision mold maker
- **昌红科技 Changhong Technology** -- listed, precision molds for medical/automotive
- **群达模具 Qunda Mold** -- large-scale mold manufacturer

---

## 6. Recent Funding & Notable Developments (2024-2026)

### Funding Rounds

| Company | Round | Amount | Date | Focus |
|---------|-------|--------|------|-------|
| **CoLab Software** | Series C | $72M USD | Nov 2025 | AI engineering design review + DFM |
| **CoLab Software** | Series B | $21M USD | May 2024 | AI design collaboration |
| **Atomic Industries** | Series A | $25M USD | Sept 2025 | AI-designed injection molds |
| **卓世科技** | Undisclosed | 100M+ RMB | July 2025 | Industry AI models for mold design |
| **模德宝 Moldbao** | Multiple rounds | 200M+ RMB cumulative | Earlier rounds | Smart mold factory + industrial internet |
| **迁移科技 TransferTech** | B Round | Tens of millions RMB | 2024 | 3D vision for mold inspection |

### Key Product Launches (2024-2026)

- **Fictiv Automated Injection Molding DFM** (Oct 2024) -- first fully automated DFM for injection molding
- **Moldex3D 2025** (2025) -- AI Optimization Wizard, generative AI cooling channels, MoldiBot
- **Siemens NX 2025** -- DFM Advisor, enhanced Mold Wizard, cooling simulation
- **SOLIDWORKS 2025** -- AURA AI assistant, xMold integration
- **Tebis SmartOps Technology** -- end-to-end CAD/CAM process automation
- **MoldSim MCP** (2025) -- AI-native injection molding intelligence via MCP protocol
- **Moldflow 2025** -- cooling channel optimization analysis

### Policy Support (China)

- Dongguan offers up to **1M RMB rewards** for enterprises developing AI applications on registered large model frameworks
- National-level: industrial AI adoption in Chinese enterprises surged from **9.6% (2024) to 47.5% (2025)**
- "Made in China 2025" continues to drive smart manufacturing investment

---

## Summary Assessment

**Where AI is ready now:**
- DFM checks (wall thickness, draft, undercuts) -- automated and production-grade
- AOI/visual inspection -- deep learning deployed at scale in China
- Drawing review -- rapidly maturing (CoLab leading)
- Process parameter optimization -- AI surrogates augmenting simulation

**Where AI is emerging:**
- Mold flow simulation acceleration via AI surrogate models
- Generative design for cooling channels
- Automated quoting and scheduling (Moldbao)

**Where AI is still early/research-stage:**
- Automated mold splitting/parting strategy
- Full generative mold design from part geometry
- End-to-end AI replacing experienced mold engineers

**Market opportunity:** China's 358.9B RMB mold market with 35%+ global share, combined with government-backed digital transformation push and severe shortage of experienced mold designers, creates a large addressable market for AI mold design tools. The funding signals from CoLab ($72M), Atomic ($25M), and Chinese players like 卓世科技 (100M RMB) confirm growing investor interest.
