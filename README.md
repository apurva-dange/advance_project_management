## TLDR

> **What:** Full-scale smart building retrofit of a 4-story ASU academic building, replacing a
> manual legacy BMS with a unified, cloud-based Building Management System spanning HVAC,
> lighting, security, access control, and fire safety.
>
> **Why:** The current system costs ~$120,000/year in excess energy and burns 15-20 staff hours
> per week on manual operations. Physical-key access control and absent fire automation create
> unacceptable security and safety exposure.
>
> **How:** 16-week implementation across 5 phases: Initiation, Procurement, Installation,
> Testing (FAT + SAT), and Deployment. External systems integrator engaged for 10 weeks during
> peak execution. Governed by 6 formal stage-gates requiring sponsor sign-off.
>
> **Cost:** $375,000 total budget (includes 10% contingency reserve).
>
> **Return:** $36,000-$45,000 in annual operational savings. 4-5 year payback. 10-year NPV
> estimated at $150,000-$200,000 at a 6% discount rate.
>
> **Team:** 5-person Group Quantile: Apurva Dange (PM), Aryan Bisht (Finance), Shubham Raut
> (Technical), Ankush Harishchandre (Procurement) and Yarasi Reddy (Compliance) reporting to
> Project Sponsor James Carter.


# Smart Building Automation System
### Integrated Project Management Plan · v1.0 · Enterprise Edition

- **Institution:** Arizona State University
- **Course:** Advanced Project Management
- **Team:** Group Quantile
- **Document Status:** For Board Review and Approval
- **Classification:** Internal Use Only
> **Read the full report:** [ASU Smart Building Automation Project Plan v1.0](https://github.com/apurva-dange/advance_project_management/blob/main/ASU_SmartBuilding_ProjectPlan_v1.pdf)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Strategic Objectives](#strategic-objectives)
- [Team and Governance](#team-and-governance)
- [Scope](#scope)
- [System Architecture and Key Features](#system-architecture-and-key-features)
- [Technologies and Hardware](#technologies-and-hardware)
- [Work Breakdown Structure](#work-breakdown-structure)
- [Project Schedule](#project-schedule)
- [Budget Summary](#budget-summary)
- [Risk Register](#risk-register)
- [Key Performance Indicators](#key-performance-indicators)
- [Deliverables](#deliverables)
- [Governance Gates](#governance-gates)
- [Referenced Standards](#referenced-standards)

---

## Project Overview

Arizona State University's four-story academic building currently operates on a legacy Building Management System (BMS) reliant on manual interventions. This outdated infrastructure produces annual energy costs exceeding **$120,000**, introduces significant security vulnerabilities through physical-key access control, and demands approximately **15-20 hours per week** of manual facilities staff time for routine system adjustments.

The **Smart Building Automation System** project is a **$375,000 strategic capital investment** to modernise this facility through the design, procurement, installation, integration, testing, and deployment of a fully integrated, cloud-based BMS spanning HVAC automation, intelligent lighting, advanced security, access control, and fire safety subsystems. The expected outcome is a **20% annual reduction in energy consumption**, generating **$36,000-$45,000 in operational savings per year** with a projected **4-5 year payback period** and an estimated **10-year NPV of $150,000-$200,000** at a 6% discount rate.

---

## Strategic Objectives

| # | Objective | Target Metric |
|---|-----------|---------------|
| 1 | Reduce building energy consumption through automated controls and real-time optimisation | 20% annual reduction |
| 2 | Enhance physical security via integrated access control, CCTV, and incident response | Zero unauthorised access incidents |
| 3 | Improve occupant comfort through occupancy-based intelligent climate control | 95% of spaces within +/-3 degrees F of setpoint |
| 4 | Enable data-driven operations via centralised BMS monitoring and analytics dashboard | 99.5% system uptime (30-day post-deployment) |
| 5 | Support ASU's sustainability commitments and net-zero carbon reduction targets | Verified over 60-day measurement period |

---

## Team and Governance

| Role | Name | Responsibilities | Approval Authority |
|------|------|------------------|--------------------|
| Project Sponsor | James Carter | Project success, scope/schedule/budget approval, escalation resolution | Final authority on all project decisions |
| Project Manager | Apurva Annasaheb Dange | Day-to-day execution, schedule management, budget control, risk mitigation | Costs under $5K; minor scope clarifications |
| Technical Lead | Shubham Bharat Raut | Technical architecture, system integration, quality standards, vendor coordination | Technical decisions; testing and acceptance criteria |
| Finance Manager | Aryan Bisht | Budget tracking, cost control, financial reporting, vendor payments | Payment authorisation under $10K; variance analysis |
| Procurement and Vendor Manager | Ankush Sanjay Harishchandre | Vendor selection, contract negotiation, supply chain management | Vendor selection; contract terms within approved budget |
| Regulatory Compliance Officer | Yarasi Bhuvaneswar Reddy | Regulatory compliance, cybersecurity standards, risk oversight | Compliance approvals; security waivers |

### RACI Summary

| Activity | Sponsor | PM | Tech Lead | Finance | Procurement | Compliance |
|----------|---------|----|-----------|---------|-------------|------------|
| Project Charter Approval | A | R | C | C | C | C |
| Budget Approval | A | R | C | C | C | I |
| Risk Assessment and Mitigation | A | R | C | I | C | R |
| Vendor Selection | C | R | C | C | A/R | C |
| Technical Design Approval | C | C | A/R | I | I | C |
| Testing and Acceptance | A | R | A/R | I | I | C |
| Project Go-Live Decision | A | R | A | I | I | A |

> Legend: R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## Scope

### In Scope

**HVAC System Automation**
- Smart thermostats and temperature sensors (20 units)
- Variable Air Volume (VAV) boxes with automated dampers (8 units)
- CO2 and humidity sensors for air quality monitoring
- Actuators and controls for airflow optimisation
- Integration with existing HVAC mechanical systems

**Lighting System Automation**
- LED smart lighting fixtures with integrated controls (60 units)
- Occupancy sensors and daylight sensors
- Smart switches, dimmers, and lighting control hub
- Zonal control for independent floor and wing management

**Security and Access Control**
- High-resolution CCTV cameras with night vision (25 units)
- Biometric access control terminals (10 units)
- Magnetic door sensors for access point monitoring
- Motion sensors for intrusion detection
- Smart fire alarms integrated with smoke detection
- Panic buttons and emergency exit devices

**Building Management System (BMS)**
- Cloud-based BMS platform with remote web and mobile accessibility
- Real-time monitoring, alerting, and historical data analytics
- Predictive maintenance capabilities
- Centralised single-pane-of-glass dashboard

**Networking and Infrastructure**
- Network servers, switches, routers, and structured cabling
- Firewall and cybersecurity protection aligned with ISO 27001
- Uninterruptible Power Supply (UPS) for critical systems
- Data backup and disaster recovery systems

### Out of Scope

- Structural or building envelope modifications
- Permanent electrical infrastructure upgrades beyond control-point connections
- HVAC equipment replacement or major mechanical system redesign
- Buildings other than the designated four-story academic building
- Custom software development or proprietary system extensions
- Integration with other campus buildings or systems (reserved for a future phase)
- Operational support beyond the initial 30-day post-deployment monitoring period

---

## System Architecture and Key Features

### 1. Intelligent HVAC Control
Automated regulation of heating and cooling using temperature and CO2 sensors. VAV boxes adjust airflow dynamically by zone, responding to real-time occupancy and weather data. Integration with the cloud-based BMS enables remote setpoint adjustments and predictive maintenance scheduling.

### 2. Smart Lighting System
LED fixtures with embedded occupancy and daylight sensors automatically adjust brightness levels across all four floors. Zonal controls allow independent management per floor or wing, minimising energy waste during unoccupied periods.

### 3. Advanced Security Integration
Biometric access control terminals replace physical-key systems across all access points. AI-powered CCTV cameras with night vision and motion detection provide comprehensive surveillance coverage. Smart fire detection and alarm systems are integrated with the BMS for automated emergency response and real-time alerting.

### 4. Centralised Building Management System
A cloud-based platform provides a unified, single-pane-of-glass view across all subsystems. Facilities staff access real-time dashboards and historical analytics via web and mobile interfaces. Automated alerting, incident ticketing integration, and predictive maintenance reduce unplanned downtime and extend asset lifecycle.

---

## Technologies and Hardware

| Category | Components |
|----------|------------|
| HVAC Sensors | Smart thermostats, temperature sensors (20 units), CO2 sensors, humidity sensors |
| HVAC Controls | VAV boxes with automated dampers (8 units), actuators, airflow controllers |
| Lighting | LED smart fixtures (60 units), occupancy sensors, daylight sensors, dimmers, lighting control hub |
| Security | AI-powered CCTV cameras with night vision (25 units), biometric access terminals (10 units), magnetic door sensors, motion sensors |
| Safety | Smart fire alarms, integrated smoke detection, panic buttons, emergency exit devices |
| Networking | Network servers, managed switches, routers, structured cabling, firewall, UPS systems |
| BMS Platform | Cloud-based BMS (3-year licence), mobile application, analytics and energy optimisation software |
| Project Management | ProjectLibre, earned value analysis tooling |

---

## Work Breakdown Structure

| WBS | Phase | Key Activities | Duration |
|-----|-------|----------------|----------|
| 1.0 | Project Initiation and Planning | Charter approval, stakeholder engagement, requirements documentation | 2 weeks |
| 1.1 | Requirements Analysis | Site survey, stakeholder interviews, system requirements definition | 1 week |
| 1.2 | Project Planning | Schedule development, budget finalisation, risk assessment | 1 week |
| 2.0 | Procurement and Vendor Management | Equipment procurement, software licensing, vendor coordination | 3 weeks |
| 2.1 | RFP Development | Technical specifications, vendor evaluation criteria | 1 week |
| 2.2 | Equipment Acquisition | Purchase orders, delivery coordination, quality inspection | 2 weeks |
| 3.0 | Installation and Integration | Hardware installation, network deployment, BMS configuration | 6 weeks |
| 3.1 | Hardware Installation | Sensors, controllers, cameras, switches, panel mounting | 3 weeks |
| 3.2 | Network Infrastructure | Cabling, switches, routers, server setup | 2 weeks |
| 3.3 | BMS Configuration | Software setup, system integration, database configuration | 1 week |
| 4.0 | Testing and Commissioning | FAT, SAT, performance testing, optimisation | 3 weeks |
| 4.1 | Factory Acceptance Test (FAT) | Component testing, vendor verification at factory | 1 week |
| 4.2 | Site Acceptance Test (SAT) | On-site testing, performance validation, issue resolution | 2 weeks |
| 5.0 | Deployment and Training | Staff training, system handover, operational readiness | 2 weeks |
| 5.1 | Training Delivery | Facilities staff training, competency validation | 1 week |
| 5.2 | System Handover | Documentation delivery, knowledge transfer, go-live support | 1 week |

---

## Project Schedule

**Total Duration:** 16 weeks | **Critical Path Buffer:** 2 weeks (~12.5% of total duration)

```
CRITICAL PATH:
Requirements Gathering > Procurement Planning > Hardware Lead Time
> Installation > Integration and Testing > Training > Deployment
```

| Phase | Weeks | Key Milestones |
|-------|-------|----------------|
| Initiation and Planning | 1-2 | Charter Approved (End Week 1) |
| Procurement | 2-4 | All Purchase Orders Issued (Week 2); Vendor Selection Confirmed (Week 3) |
| Hardware Lead Time | 4-7 | First Shipments Arrive (Week 5) |
| Installation Phase 1 | 6-9 | Hardware Installation 50% Complete (Week 7) |
| Installation Phase 2 | 9-11 | Hardware Installation 100% Complete (Week 10) |
| Factory Acceptance Test | 11-12 | FAT Sign-Off (Week 12) |
| Site Testing and Integration | 12-14 | SAT Sign-Off (Week 14) |
| Training and Deployment | 14-15 | Staff Training Complete (Week 14); Go-Live (Week 15) |
| Post-Deployment Support | 15-16 | Project Close-Out (Week 16) |

> Any delay in critical path activities directly impacts the project completion date. Non-critical activities carry limited schedule flexibility (slack time).

---

## Budget Summary

**Total Authorised Budget: $375,000**

| Cost Category | Amount | % of Budget |
|---------------|--------|-------------|
| Labour Costs (Internal) | $104,940 | 28% |
| Installation Labour (External Systems Integrator) | $45,000 | 12% |
| Building Modifications | $25,000 | 7% |
| Integration and Testing | $28,000 | 7% |
| Software and BMS Platform | $32,500 | 9% |
| Hardware and Sensors | $37,125 | 10% |
| Training and Documentation | $22,500 | 6% |
| Project Management | $20,000 | 5% |
| Network Infrastructure | $8,080 | 2% |
| Contingency Reserve (10%) | $37,500 | 10% |
| **TOTAL** | **$375,000** | **100%** |

**Financial Returns**

| Parameter | Value |
|-----------|-------|
| Annual Operational Savings | $36,000-$45,000 |
| Energy Savings Component | $28,000-$35,000/year (20% consumption reduction) |
| Labour Efficiency Savings | $8,000-$10,000/year |
| Payback Period | 4-5 years |
| 10-Year NPV (6% discount rate) | $150,000-$200,000 |
| Ongoing Annual Maintenance | $15,000-$18,000/year |

**Budget Controls:** Project Manager approved for costs under $5,000. Sponsor approval required for purchases exceeding $5,000. Change Control Board review triggered by cumulative variances exceeding 5% of total budget.

---

## Risk Register

| Risk | Probability | Impact | Priority | Mitigation Strategy |
|------|-------------|--------|----------|---------------------|
| Hardware procurement delays exceeding 2 weeks | Medium | High | HIGH | Order immediately post-approval; use multiple vendors; maintain buffer stock |
| Software integration incompatibilities between subsystems | Medium | High | HIGH | Pre-integration compatibility testing; engage specialist integrator |
| Cost overrun exceeding budget by more than 10% | Medium | High | HIGH | Detailed cost tracking; monthly earned value analysis; scope freeze |
| Schedule slippage during installation phase | Medium | High | HIGH | Dedicated external installation team; granular project schedule |
| Cybersecurity vulnerabilities in BMS | Low | Critical | HIGH | Security hardening; penetration testing; ISO 27001 controls |
| Staff resistance to operational changes | Low | Medium | MEDIUM | Early stakeholder engagement; comprehensive training; change champions |
| HVAC system integration failures | Low | High | MEDIUM | Vendor pre-testing; parallel operation period; specialist technician on call |
| Key personnel unavailability during critical phases | Low | High | MEDIUM | Backup roles identified; cross-training; documentation maintained |
| Power supply disruptions affecting systems | Very Low | Critical | MEDIUM | UPS for critical systems; generator backup for extended outages |
| Regulatory or compliance issues discovered late | Low | Medium | MEDIUM | Early compliance review; regulatory expert consultation |

**Contingency Reserve:** $37,500 (10% of budget). Release requires formal change management process documentation and triggers re-baselining of project forecast.

---

## Key Performance Indicators

| KPI | Baseline | Target | Measurement Method |
|-----|----------|--------|--------------------|
| Energy Consumption | ~$120,000/year | Reduced by 20% ($96,000/year) | Monthly utility meter readings, normalised for weather |
| System Uptime | Variable (manual system) | 99.5% over 30-day period | Automated BMS monitoring logs |
| Staff Response Time (HVAC issues) | 2-4 hours (manual diagnosis) | Under 5 min alert; under 30 min resolution | Incident ticketing system |
| Occupant Comfort Compliance | No baseline | 95% of spaces within +/-3 degrees F of setpoint | Temperature sensor logging; occupant surveys |
| Security Incidents | Unable to detect/respond | Zero unauthorised access during business hours | Access log review; incident records |
| Staff Training Completion | N/A | 100% of facilities staff complete programme | Training records; competency assessments |
| Schedule Variance | Target: 16 weeks | Delivery within +/-2 weeks | Gantt chart tracking; milestone completion dates |
| Budget Variance | Target: $375,000 | Final cost within +/-10% | Monthly earned value analysis |

---

## Deliverables

1. **Project Charter and Integrated Management Plan** - Comprehensive documentation including scope, schedule, budget, risk register, and governance framework
2. **System Requirements Specification (SRS)** - Detailed technical and functional requirements, performance parameters, interface specifications, and acceptance criteria
3. **Procurement Documentation** - Vendor contracts, equipment specifications, delivery certifications, and quality inspection reports
4. **Installation and Integration Plan** - Installation procedures, network architecture diagrams, system integration points, and sequencing of work activities
5. **Factory Acceptance Test (FAT) Report** - Vendor-conducted testing documentation confirming all equipment functions correctly before shipment to ASU
6. **Site Acceptance Test (SAT) Report** - Independent verification that all systems meet specifications in the deployed environment, including issue logs and resolution documentation
7. **As-Built System Documentation** - Complete technical documentation of the deployed system including network diagrams, hardware configurations, software settings, and maintenance procedures
8. **Performance Metrics and Baseline Report** - Energy consumption baseline, security audit results, and system performance metrics for ongoing comparison
9. **Staff Training Programme and Materials** - Comprehensive curriculum, operation manuals, troubleshooting guides, and training completion records
10. **Final Project Report and Lessons Learned** - Executive summary of project execution, actual vs. planned performance, financial reconciliation, and recommendations for future phases

---

## Governance Gates

| Gate | Timing | Prerequisites | Authority |
|------|--------|---------------|-----------|
| Gate 1: Project Charter Approval | Week 1 | Requirements review validated by all key stakeholders | Project Sponsor |
| Gate 2: Procurement Authorisation | Week 2 | Vendor evaluations complete; contracts negotiated within budget | Sponsor and Finance Manager |
| Gate 3: Installation Go-Ahead | Week 6 | Hardware delivered; site ready; team mobilised; technical lead sign-off | PM and Technical Lead |
| Gate 4: Testing Authorisation | Week 11 | FAT plan finalised; testing environment prepared | Project Manager |
| Gate 5: Deployment Approval | Week 15 | SAT signed off; staff training complete; support plan in place | Project Sponsor |
| Gate 6: Project Closeout | Week 16 | 30-day monitoring period complete; lessons learned captured; all deliverables accepted | Project Sponsor |

---

## Referenced Standards

| Standard | Application |
|----------|-------------|
| PMI PMBOK Guide (6th Edition) | Overall project management methodology |
| PRINCE2 | Governance gates and stage-gate controls |
| ISO 31000 | Risk management principles and guidelines |
| ASHRAE 90.1 | Energy standard for buildings |
| NFPA Standards | Fire safety and life-safety systems |
| BACnet Protocol | Building automation and control interoperability |
| ISO 27001 | Information security management systems |

---

> *Smart Building Automation Project v1.0 | Group Quantile | Arizona State University | Advanced Project Management*

