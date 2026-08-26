# CAAM 2030: UNIFIED AVIATION PORTAL
## Business Development Proposal

**Prepared by:** Project Management Team (PMT)
**Presented to:** Civil Aviation Authority of Malaysia (CAAM)
**Date:** August 2026
**Classification:** Confidential

---

> *"Malaysia's aviation sector carried 97.14 million passengers in 2024 — a 14.3% year-on-year surge. Yet the regulatory infrastructure governing every one of those passengers, pilots, aircraft, and aerodromes still relies on manual, fragmented, paper-based processes. This proposal ends that contradiction."*

---

## TABLE OF CONTENTS

1. Executive Summary
2. Background: CAAM in 2026
3. The Problem — A Regulatory Gap at Scale
4. The Solution — CAAM 2030 Unified Aviation Portal
5. System Architecture & Technical Specification
6. Five Core Modules — Detailed Breakdown
7. Financial Model (Malaysian Ringgit)
8. Implementation Roadmap
9. Risk & Mitigation Register
10. Why This Proposal Now
11. Call to Action

---

## 1. EXECUTIVE SUMMARY

The Civil Aviation Authority of Malaysia (CAAM), now a fully autonomous statutory body following its merger with the Malaysian Aviation Commission (MAVCOM) on 1 August 2025, stands at a defining crossroads. Having shed its dependence on approximately **RM 200 million in annual government subsidies** and transitioned to a fully self-funded revenue model anchored by Route Air Navigation Service (RANS) charges and diversified aviation fees, CAAM now bears the full financial and operational weight of regulating the world's fastest-growing aviation market segment.

Malaysia's aviation growth trajectory is extraordinary:
- **97.14 million passengers in 2024** (source: CAAM Industry Statistics 2024)
- **KLIA alone processed 57.01 million passengers** in 2024, a 20.9% YoY increase
- Monthly traffic hit **9.3 million in July 2025**, trending well above pre-pandemic peaks
- **75 high-risk aviation incidents** recorded across 2022–2023 under legacy oversight systems

Yet CAAM's regulatory infrastructure — the licensing of thousands of aviation professionals, the compliance monitoring of aerodromes and airspace users, the processing of operator certifications — operates on an architecture built for a fraction of today's throughput.

**This proposal presents the CAAM 2030 Unified Aviation Portal**: a single, cloud-native, AI-driven digital platform that consolidates all of CAAM's regulatory, licensing, safety oversight, and public-service functions into one ecosystem. Built on proven Malaysian government digital transformation frameworks (aligned with CAAM's own **Digitalisation Strategic Plan (DSP) 2024–2028**), this platform transforms CAAM from a reactive regulator to a proactive, data-driven aviation authority — capable of sustaining Malaysia's position as Southeast Asia's premier aviation hub through 2030 and beyond.

**The investment pays for itself.** Through the consolidation of CAAM's newly expanded fee-collection mandate (post-MAVCOM merger), digital efficiency gains, and a structured Professional & Industry Digital Services (PIDS) revenue model, we project a net operational saving and revenue enhancement of **RM 18.4 million per annum by Year 3** — generating full cost recovery within **24 months of go-live**.

---

## 2. BACKGROUND: CAAM IN 2026

### 2.1 Institutional Overview

The Civil Aviation Authority of Malaysia (CAAM) is a statutory body under the **Ministry of Transport Malaysia**, established under the **Civil Aviation Authority of Malaysia Act 2017 (Act 771)**. CAAM serves as Malaysia's single aviation safety and technical regulator, responsible for implementing the **Civil Aviation Act 1969 (Act 3)** and ensuring Malaysia's compliance with **ICAO Standards and Recommended Practices (SARPs)**.

As of 1 August 2025, CAAM absorbed the regulatory functions of **MAVCOM** (Malaysian Aviation Commission, established under Act 771), making it the sole regulator for both **technical safety** and **economic/commercial** matters in Malaysian aviation.

**Core Mandate Areas:**
| Function | Description |
|----------|-------------|
| Safety Oversight | Aircraft certification, airworthiness, accident investigation coordination |
| Personnel Licensing | Airline Transport Pilot Licences (ATPL), Aircraft Maintenance Engineer (AME) licences, Air Traffic Controller (ATC) licences |
| Aerodrome Regulation | Aerodrome Operator Licences (AOL), aerodrome certification standards |
| Air Navigation Services | Air traffic management within KL FIR and Kota Kinabalu FIR |
| Economic Regulation | Air Services Licences (ASL), Air Service Permits (ASP), Ground Handling Licences (GHL) |
| Consumer Protection | Dispute resolution, SLA monitoring, public-complaint management |
| International Representation | ICAO, IATA, ASEAN aviation forums |

### 2.2 Financial Transformation

CAAM's financial model underwent fundamental restructuring in 2025:
- **Ended**: ≈ RM 200 million annual government operating subsidy
- **Activated**: Full financial autonomy as a self-funded statutory body (effective 1 August 2025)
- **Primary Revenue**: Revised Route Air Navigation Service (RANS) charges effective 1 January 2025, aligned with ASEAN regional standards; with scheduled incremental adjustments in 2028 and 2031
- **Secondary Revenue**: Expanded licensing fees, certification charges, and economic regulatory fees absorbed from MAVCOM

*(Sources: Malaysian Aviation Industry Association (MAIA), The Vibes, 2025; Civil Aviation Fees and Charges Revision Notice, CAAM, January 2025)*

### 2.3 Digital Transformation Context

CAAM launched its **Digitalisation Strategic Plan (DSP) 2024–2028**, structured across three phases:

| Phase | Focus | Timeline |
|-------|-------|----------|
| Phase 1 | Foundational infrastructure & process digitisation | 2024–2025 |
| Phase 2 | E-licensing (eCLIPSE) & Enhanced Safety Oversight | 2025–2026 |
| Phase 3 | Full ecosystem integration & Data Warehouse | 2027–2028 |

In **February 2025**, CAAM launched **eCLIPSE (e-CAAM Licensing Professional Services)** — an online platform for pilot and AME licence management. This is the first phase of the DSP. However, eCLIPSE covers only **personnel licensing**. The broader regulatory ecosystem — aerodrome operators, airspace users, UTM (Unmanned Traffic Management), consumer complaint management, and economic licensing — remains fragmented.

**The CAAM 2030 Unified Portal is Phase 2 and Phase 3 realised in one integrated platform.**

*(Sources: Astro Awani, May 2024; The Star, February 2025; Vietnam Plus, 2024)*

---

## 3. THE PROBLEM — A REGULATORY GAP AT SCALE

### 3.1 Volume vs. Capacity Mismatch

Malaysia's aviation ecosystem has grown exponentially:

| Metric | Value | Source |
|--------|-------|--------|
| Total passengers (2024) | 97.14 million | CAAM Industry Statistics |
| YoY passenger growth | +14.3% | CAAM |
| International passenger growth | +38.9% | CAAM |
| ASEAN travel growth | +19.8% | CAAM |
| KLIA passenger volume (2024) | 57.01 million | CAAM |
| Monthly traffic peak (July 2025) | 9.3 million | The Sun, 2025 |
| High-risk aviation incidents (2022–2023) | 75 | Ministry of Transport |

Yet the regulatory machinery processing licences, permits, compliance audits, and operator certifications is not scaling at the same rate.

### 3.2 Specific Pain Points

### 3.3 The Manual Form Reality: Over 150 Paper and PDF Forms Still Driving Daily Operations

A critical operational reality confronting CAAM today is the sheer volume of **manual paper forms, static PDF downloads, and email-based applications** that dictate day-to-day regulatory interactions. Despite initial digital initiatives like eCLIPSE, the vast majority of regulatory divisions still operate on manual paperwork, physical counter submissions at Putrajaya Headquarters, manual rubber stamping, and disconnected spreadsheets:

| Regulatory Division | Representative Manual Forms | Current Manual Process & Pain Points |
| :--- | :--- | :--- |
| **Personnel Licensing (PEL)** | `CAAM/PEL/01` (Licence Issue/Renewal)<br>`CAAM/PEL/02` (Medical Exam Report)<br>`CAAM/PEL/04` (Logbook Hours Endorsement)<br>`CAAM/PEL/12` (AME Licence Application) | Physical counter visits, manual handwriting verification, postal delays for physical licences, and 14–30 day turnaround times. |
| **Airworthiness & Certification (AW)** | `CAAM/AW/81` (C of A Renewal Application)<br>`CAAM/AW/84` (Export C of A)<br>`CAAM/AW/92` (Part 145 AMO Approval)<br>`CAAM/AW/95` (Part M CAMO Certification) | Stacks of physical maintenance logs and paper dossiers submitted in binders. Manual cross-referencing against manufacturer service bulletins. |
| **Flight Operations (BOP)** | `CAAM/BOP/01` (AOC Initial / Variation)<br>`CAAM/BOP/05` (Dangerous Goods Permit)<br>`CAAM/BOP/08` (Aircraft Lease Authorisation) | Manual email submissions (`bop@caam.gov.my`), unindexed PDF attachments, no real-time audit trail, and manual approval memos. |
| **Aerodrome & Airspace (AGA)** | `CAAM/AGA/01` (Aerodrome Operator Licence)<br>`CAAM/AGA/04` (Aeronautical Obstacle Clearance)<br>`CAAM/AGA/06` (Obstacle Light Declaration) | Paper development plans submitted by telcos and property developers. Manual manual surveyor checks taking 3–6 weeks per tower. |
| **Unmanned Aircraft Systems (UAS)** | `CAAM/UAS/01` (Authorization to Fly - ATF)<br>`CAAM/UAS/02` (Special UAS Permit)<br>`CAAM/UAS/03` (Drone Pilot Competency) | Manual 14-day email permit processing (`drone@caam.gov.my`), unverified manual PDF submissions, and zero real-time radar correlation. |
| **Economic & Commercial (Post-MAVCOM)** | `MAVCOM/ASL` (Air Service Licence)<br>`MAVCOM/ASP` (Air Service Permit)<br>`MAVCOM/GHL` (Ground Handling Licence)<br>`MAVCOM/MACPC` (Consumer Dispute Filing) | Inherited MAVCOM paper-heavy submission dossiers, manual financial audit reviews, and disconnected complaint spreadsheets. |

---

## 4. THE SOLUTION — CAAM 2030 UNIFIED AVIATION PORTAL

### 4.1 The Two-Horizon Transformation Strategy

To ensure immediate operational success without overwhelming CAAM officers, the CAAM 2030 Unified Portal is architected as a **Two-Horizon Evolutionary Journey**:

* **HORIZON 1 (Immediate Operational Workhorse & Foundation): National Aviation e-Form Engine (FormFlow 360)**  
  Eliminates 100% of physical counter queues, paper applications, and static PDF downloads by converting all 150+ CAAM forms into intelligent, self-service web forms with OCR legacy document extraction, MyKad bio-data auto-fill, Act 560 compliant digital signatures, and direct FPX e-payment integration.
* **HORIZON 2 (Scale & Predictive Intelligence): Unified Smart Aviation Ecosystem**  
  Layers automated 3D CAD 14 spatial ray-tracing, nationwide drone UTM geofenced corridors, machine learning fleet risk scoring, and unified economic regulatory analytics on top of the structured digital data captured in Horizon 1.

### 4.2 Core Architecture Vision

**One Portal. Every CAAM Form Digitised. Fully Automated. Fully Sovereign.**

The CAAM 2030 Unified Aviation Portal is a cloud-native, AI-powered, single-window regulatory platform that brings every CAAM stakeholder — aviation professionals, aerodrome operators, airlines, drone operators, structure owners, and the flying public — into one integrated digital ecosystem, governed by enterprise-grade Single Sign-On (SSO) and Role-Based Access Control (RBAC).

### 4.2 Strategic Alignment

| CAAM Priority | Portal Response |
|---------------|-----------------|
| DSP 2024–2028 Phase 2 & 3 | Direct accelerator — delivers the full DSP vision in one integrated rollout |
| Financial self-sufficiency | Digital fee collection, automated invoicing, real-time RANS charge tracking |
| ICAO USOAP compliance | Centralised, audit-ready safety data with automated EI reporting |
| Post-MAVCOM integration | Unified consumer complaint and economic licensing module |
| Safety oversight enhancement | AI-powered predictive safety, real-time incident correlation |
| Obstacle compliance enforcement | IoT-ready AOL monitoring dashboard for proactive surveillance |

### 4.3 Core Architecture Principles

1. **Malaysian-Hosted** — All data stored in Google Cloud region `asia-southeast1 (Singapore)`, fully compliant with Malaysia's **Personal Data Protection Act 2010 (PDPA)**.
2. **Zero-Trust Security** — Every user, device, and API call authenticated and authorised per RBAC policy.
3. **ICAO-Aligned Data Model** — Data schema built to ICAO Annex standards for instant audit export.
4. **API-First Design** — Open APIs allow future integration with airlines (IATA NDC), airport systems (AODB), and Ministry of Transport databases.
5. **Mobile-First UX** — Responsive web application accessible from any device, with progressive web app (PWA) capability for field officers.

---

## 5. SYSTEM ARCHITECTURE & TECHNICAL SPECIFICATION

### 5.1 High-Level Architecture

```
┌──────────────────────────────────────────────────────────────────┐
│                    STAKEHOLDER ACCESS LAYER                      │
│  Aviation Professionals │ Operators │ Airlines │ Public │ CAAM  │
└──────────────────────┬───────────────────────────────────────────┘
                       │  HTTPS / TLS 1.3
┌──────────────────────▼───────────────────────────────────────────┐
│              UNIFIED PORTAL FRONTEND (React + Vite SPA)          │
│  • Role-Based Dashboards      • Progressive Web App (PWA)        │
│  • Real-time Notifications    • Multilingual (BM / English)      │
└──────────────────────┬───────────────────────────────────────────┘
                       │  REST / GraphQL APIs
┌──────────────────────▼───────────────────────────────────────────┐
│                  API GATEWAY + SSO / RBAC LAYER                  │
│  • OAuth2 / SAML 2.0 SSO     • Rate Limiting & Threat Detection  │
│  • Role-Based Access Control  • API Versioning & Audit Logging   │
└──────┬────────┬────────┬────────┬────────┬────────────────────────┘
       │        │        │        │        │
┌──────▼──┐ ┌──▼──┐ ┌───▼──┐ ┌───▼──┐ ┌───▼─────────────────────┐
│ MODULE 1 │ │ M2  │ │  M3  │ │  M4  │ │         MODULE 5         │
│ INFRA   │ │PROF │ │ASPACE│ │  OPS  │ │        PUBLIC            │
│ OLS/AOL │ │LIC  │ │ UTM  │ │ SMS  │ │   Consumer / Complaint   │
└──────┬──┘ └──┬──┘ └───┬──┘ └───┬──┘ └──────────────┬───────────┘
       │        │        │        │                    │
┌──────▼────────▼────────▼────────▼────────────────────▼───────────┐
│                  SHARED SERVICES LAYER                            │
│  • Notification Engine (Email/SMS/WhatsApp)                      │
│  • Document Management (e-Certificates, Digital Signatures)      │
│  • Payment Gateway (FPX / Online Banking / JomPAY)               │
│  • Audit Trail & Compliance Logger                               │
└──────────────────────────────────────────────────────────────────┘
┌──────────────────────────────────────────────────────────────────┐
│                    DATA & INTELLIGENCE LAYER                     │
│  • Data Warehouse (BigQuery)  • AI/ML Engine (Vertex AI)         │
│  • Real-time Telemetry (IoT)  • Geospatial Engine (GIS/CesiumJS) │
│  • Immutable Audit Ledger     • Analytics Dashboards             │
└──────────────────────────────────────────────────────────────────┘
┌──────────────────────────────────────────────────────────────────┐
│                  INFRASTRUCTURE LAYER                            │
│  Cloud Run (Containerised Microservices) │ VPC Service Controls  │
│  Cloud SQL (PostgreSQL) │ Cloud Storage  │ Pub/Sub Streaming      │
│  Cloud Armor (WAF/DDoS) │ IAM (Least-Privilege) │ PDPA-Compliant │
└──────────────────────────────────────────────────────────────────┘
```

### 5.2 Technology Stack

| Layer | Technology | Rationale |
|-------|-----------|-----------|
| Frontend | React 18 + Vite | Component-based, fast, PWA-ready |
| API Gateway | Cloud Endpoints / Apigee | Rate limiting, versioning, auth |
| Identity | Keycloak (Self-Hosted) + OAuth2 | Full control over CAAM user identities |
| Backend Services | Java 21 + Spring Boot 3 | Enterprise-grade, battle-tested in government systems |
| Database | Cloud SQL (PostgreSQL) | Relational data, ACID compliance |
| Data Warehouse | BigQuery | Petabyte-scale analytics, ICAO reporting |
| Real-time Messaging | Pub/Sub | IoT telemetry, event-driven safety alerts |
| AI/ML | Vertex AI | Predictive maintenance, risk scoring, anomaly detection |
| Geospatial | CesiumJS + Google Maps API | 3D airspace visualisation, OLS mapping |
| Document Management | Google Cloud Storage + DocuSign API | e-Certificates with digital signatures |
| Payment | FPX / JomPAY integration | Malaysian e-payment ecosystem compliant |
| Security | Cloud Armor, VPC-SC, IAM | Zero-trust, DDoS protection, PDPA |
| DevOps | Cloud Build + Cloud Deploy | CI/CD, automated testing, rollback |
| Monitoring | Cloud Monitoring + Cloud Logging | 24/7 uptime SLA, incident detection |

### 5.3 Integration Points

| External System | Integration Method | Purpose |
|-----------------|-------------------|---------|
| MyGovt Shared Services (eKYC) | REST API | Identity verification for licence applicants |
| AAIB (Air Accident Investigation Bureau) | Secure File Transfer | Incident data correlation |
| ICAO USOAP Portal | Automated XML/JSON export | EI score reporting |
| Malaysia Airports Holdings Berhad (MAHB) | API | Real-time aerodrome status |
| Inland Revenue Board (LHDN) | API | Fee payment reconciliation |
| PDRM / AVSEC | Encrypted Data Channel | Security clearance cross-reference |

---

### Module 1: CAD-14 Aerodrome Standards & Obstacle Compliance Engine (AeroShield CAD-14)
*The National Digital Vetting, Spatial Ray-Tracing, and IoT Monitoring Suite for CAAM CAD 14 Vol I & Act 3 Section 24O*

**Statutory & Regulatory Basis:**
* **Civil Aviation Directive 14 Volume I (CAD 14 Vol I — Standards for Aerodromes)**
* **Civil Aviation Act 1969 (Act 3), Section 24O & Section 24O(2)**
* **Civil Aviation (Aerodrome Operations) Regulations 2016 (CAR(AO) 2016)**
* **ICAO Annex 14 Volume I (Aerodrome Design and Operations)**

**Problem It Solves:**
Since CAAM revoked the manual Obstacle Light Certificate in July 2022, statutory compliance rests entirely on structure owners under CAD 14 and CAR(AO) 2016. However, CAAM has suffered an **enforcement monitoring vacuum**: over 60,000 telecommunication towers, 21,000 high-rises, 210,000 power transmission pylons, and 12,000 construction cranes operate across Malaysia with zero live status tracking. Thousands of obstacle lights are uninstalled or dead, and building height vetting takes 3–6 weeks of manual paper map cross-referencing.

**The AeroShield CAD-14 Core Subsystems:**

#### Subsystem 1.1: Automated 3D Obstacle Limitation Surface (OLS) Ray-Tracing Engine (CAD 14 Chapter 4)
* **All 8 CAD 14 Surfaces Calculated in 3D Space:**
  1. **Take-Off Climb Surface:** 2.0%, 2.5%, 4.0%, or 5.0% slope extending up to 15,000m.
  2. **Approach Surface:** Non-instrument, non-precision, and Cat I/II/III precision approach corridors.
  3. **Transitional Surface:** 14.3% / 20.0% side-slopes extending from runway strip edges.
  4. **Inner Transitional Surface:** 33.3% slope protecting the Obstacle Free Zone (OFZ).
  5. **Inner Horizontal Surface:** Racetrack plane at 45m above aerodrome elevation (2km to 4km radius).
  6. **Conical Surface:** 5.0% upward slope extending from Inner Horizontal up to 100m elevation.
  7. **Balked Landing Surface:** Missed approach protection zones.
  8. **Outer Horizontal Surface:** 15km regional aerodrome surveillance buffer.
* **Sub-2-Second Automated Vetting:** When a telco (Maxis, CelcomDigi, U Mobile, edotco) or developer inputs $(X,Y)$ coordinates and structure height $(Z)$, the PostGIS 3D spatial engine intersects the structure with CAD 14 surfaces and terrain models (LiDAR/SRTM) in **under 2 seconds**, issuing an instant CAD-14 Height Clearance Certificate or Rejection Report.

#### Subsystem 1.2: Real-Time IoT Aviation Obstacle Light (AOL) Telemetry Hub (CAD 14 Chapter 6 & Section 24O)
* **Coverage of 9 Tall Structure Classes:**
  1. **Telco / 5G Towers** (60,000+ sites nationwide)
  2. **High-Rise Buildings & Condominiums** (21,000+ structures)
  3. **Electrical Transmission Towers / Pylons** (210,000+ TNB assets)
  4. **Construction Tower Cranes** (12,000+ temporary dynamic assets)
  5. **Aviation Warning Light Units** (300,000+ fixtures monitored individually)
  6. **Wind Measurement Masts**
  7. **Industrial Chimneys & Smokestacks**
  8. **Heliports & Hospital Helidecks**
  9. **Radar Installations**
* **IoT Sensor Integration & Telemetry:** Monitors light status (Active, Inactive, Flashing, Degraded), Lux/Candela intensity (Low-Intensity Type A/B/C/D, Medium-Intensity Type A/B/C, High-Intensity Type A/B), and battery/mains power health.
* **Automated Section 24O(2) Statutory Enforcement:** If an obstacle light in an approach path fails for >60 minutes, the system immediately generates an ATC NOTAM alert and automatically issues a statutory compound notice to the structure owner.

#### Subsystem 1.3: National Structure Legalization ("Program Pemutihan") Portal
* **Brownfield Regularization:** Provides a national amnesty/legalization portal for unregistered towers and buildings.
* **Bulk Enterprise Ingestion:** Telco infrastructure firms (edotco, EdgePoint, DNB) upload thousands of sites via GeoJSON/KML.
* **80:20 PPP Revenue Sharing Engine:** Direct FPX/DuitNow fee collection collecting up to **RM 163.5 Million annually** in statutory fees with **80% remitted to CAAM and 20% to the Solution Provider/PMT**.

#### Subsystem 1.4: Aerodrome Physical Geometry & Emergency Operations Suite (CAD 14 Chapters 2, 3, 5, 8, 9, 10)
* **Runway Safety & RESA Verification:** Digital inspection checklists for Runway Strips and Runway End Safety Areas (RESA) under Chapter 3.
* **Aeronautical Ground Lighting & Power SLA:** Monitored compliance of PAPI glide-path lights, runway centerlines, and 1-second / 15-second secondary power switchover under Chapter 8.
* **RFFS Emergency Response Logger:** Real-time tracking ensuring Airport Fire & Rescue services achieve the **sub-2-minute emergency response time** mandate under Chapter 9.
* **Pavement Friction & Rubber Deposition Tracker:** Logs periodic runway friction tests and de-rubberizing maintenance under Chapter 10.

### Module 2: Professional Licensing Hub (PLH)
*Extending and deepening the eCLIPSE foundation*

**Problem It Solves:** eCLIPSE (launched February 2025) digitised basic licence applications but does not cover renewal automation, medical fitness tracking, endorsement management, or foreign licence validation. Maintenance engineers, drone pilots, and ground handling personnel are also not yet integrated.

**What the Module Delivers:**
- **Unified Licence Lifecycle Management**: End-to-end digital processing for ATPL, CPL, PPL, AME, ATC, UAS (drone) operator licences — application, assessment, issuance, renewal, suspension, reinstatement
- **Blockchain-Backed Credential Registry**: Every licence issued carries a tamper-proof blockchain hash — enabling instant verification by airlines, foreign authorities, and employers without calling CAAM
- **Medical Fitness Integration**: Direct API link with CAAM-approved Aviation Medical Examiners (AME) clinics; medical fitness status auto-updates the pilot's licence record
- **Automated Renewal Alerts**: 90/60/30-day automated reminders via SMS, email, and WhatsApp; grace-period tracking; suspension automation upon expiry
- **Foreign Licence Validation**: Streamlined workflow for validation of ICAO-compliant foreign licences — reducing processing time from current 4–6 weeks to 5 business days
- **QR Verification**: Each licence generates a unique QR code; a ramp inspector or airline HR can scan and receive real-time status in under 3 seconds

---

### Module 3: Future Airspace Management Hub (FAMH)
*Building Malaysia's UTM infrastructure*

**Problem It Solves:** Malaysia has no unified Unmanned Traffic Management (UTM) system. Drone flight authorisations are handled via manual NOTAM submissions and email-based approvals — wholly inadequate for the projected exponential growth in commercial UAS operations.

**What the Module Delivers:**
- **UAS Operator Registration & Licensing**: Digital registration of all drone operators (recreational and commercial); integration with CAAM's Civil Aviation Directive on UAS
- **Dynamic Geofencing Engine**: Real-time 3D airspace map with defined zones (restricted, conditional, free flight); automatically updated when NOTAMs or special operations are active
- **Digital Flight Authorisation System (FAS)**: Drone operators submit flight plans; the system auto-checks against airspace rules, weather restrictions, and restricted zones; issues automated authorisation or conditional approval within minutes
- **UAS Traffic Monitoring**: Real-time tracking of authorised UAS flights via Remote ID telemetry, with alerts for unauthorised airspace incursions
- **AI Conflict Detection**: Machine learning model that predicts potential UAS-manned aircraft conflicts based on trajectory data, alerting CAAM Air Traffic Management and the UAS operator simultaneously

---

### Module 4: Operator Certification & Safety Hub (OCSH)
*Digitising airworthiness, SMS, and operator oversight*

**Problem It Solves:** Air Operator Certificates (AOC), Ground Handling Licences (GHL), and continuing airworthiness management are processed through separate CAAM divisions with no unified operator view. Safety Management Systems (SMS) are self-reported with limited CAAM audit capability.

**What the Module Delivers:**
- **Digital AOC & GHL Lifecycle Management**: Application, renewal, and variation of Air Operator Certificates and Ground Handling Licences; CAAM inspectors assigned and tracked within the system
- **Airworthiness Tracking**: Digital maintenance schedules linked to aircraft registration; maintenance event logging with mandatory sign-off by licensed AMEs recorded in the blockchain registry
- **Predictive Safety Management System (PSMS)**: AI model trained on CAAM's historical MOR/VOR data identifies airlines and operators showing early indicators of safety deterioration — enabling proactive CAAM intervention before incidents occur
- **Operator SMS Dashboard**: Airlines and operators submit mandatory SMS reports through the portal; CAAM safety analysts can benchmark, trend, and correlate across operators
- **ICAO USOAP Reporting Engine**: Automated generation of ICAO-standard safety oversight evidence packages — reducing USOAP audit preparation time from months to days

---

### Module 5: Public Services & Consumer Protection Hub (PSCPH)
*Delivering on CAAM's post-MAVCOM consumer mandate*

**Problem It Solves:** Post-MAVCOM merger, CAAM now handles consumer protection for the aviation sector. The inherited MAVCOM consumer platform (AeroLicence, bi-annual consumer reports) was not designed to integrate with CAAM's technical regulatory systems.

**What the Module Delivers:**
- **Aviation Consumer Portal**: Public-facing interface for passengers to file complaints against airlines, airports, and ground handlers; real-time case tracking with SLA visibility
- **SLA Dashboard**: Publicly visible dashboard showing airline on-time performance, complaint resolution rates, and service quality metrics — driving accountability through transparency
- **Public Airspace Awareness**: Flight status, NOTAM summaries in plain language, and airspace closures for the general public
- **AI-Powered Chatbot (Powered by Local LLM)**: 24/7 multilingual (BM/English) chatbot for public FAQs on licensing, fees, complaints, and airspace; escalates complex queries to CAAM officers
- **Rural Air Service (RAS) Monitoring**: Special dashboard for PSO (Public Service Obligation) route performance in Sabah and Sarawak — tracking frequency compliance and passenger load factors

---

## 7. FINANCIAL MODEL (MALAYSIAN RINGGIT)

### 7.1 Revenue Enhancement from Digital Efficiency

By digitising CAAM's fee-collection processes and expanding the regulatory scope post-MAVCOM merger, the portal creates measurable revenue uplift:

| Revenue Stream | Current Annual (Estimated) | Post-Portal (Year 3 Projected) | Basis |
|----------------|---------------------------|-------------------------------|-------|
| RANS Charges (Digital Collection) | ~RM 180M | ~RM 195M | Reduced leakage, automated billing, +scheduled 2028 rate revision |
| Aviation Personnel Licensing Fees | ~RM 8M | ~RM 12M | Faster processing = higher renewal compliance; drone pilot licensing added |
| Aerodrome & Operator Licensing | ~RM 5M | ~RM 9M | Digital AOL/AOC applications; new categories (UAS operators, eVTOL) |
| Economic Licensing (Post-MAVCOM) | ~RM 6M | ~RM 10M | ASL/ASP/GHL consolidated; reduced evasion |
| Consumer Protection Services | ~RM 1M | ~RM 3M | Digital complaint processing fees; SLA dashboard subscriptions for airlines |
| **Total Revenue** | **~RM 200M** | **~RM 229M** | |

*Note: RANS charge baseline sourced from MAIA Report 2025. Other figures estimated from CAAM fee schedules (revised Jan 2025) and post-MAVCOM function absorption.*

### 7.2 Cost Structure — Platform Investment (All in RM)

#### One-Time Capital Expenditure (CapEx)

| Item | Year 1 (RM) |
|------|-------------|
| System Design & Architecture | RM 850,000 |
| Software Development (Frontend, Backend, APIs) | RM 3,200,000 |
| Data Migration & Integration (Legacy systems, MAVCOM) | RM 480,000 |
| Cloud Infrastructure Setup (Google Cloud, 3-yr commit) | RM 720,000 |
| Security & Compliance Setup (PDPA, ISO 27001) | RM 320,000 |
| User Acceptance Testing (UAT) & Quality Assurance | RM 280,000 |
| Training & Change Management | RM 220,000 |
| **Total CapEx (Year 1)** | **RM 6,070,000** |

#### Annual Operating Expenditure (OpEx)

| Item | Year 1 (RM) | Year 2 (RM) | Year 3 (RM) |
|------|-------------|-------------|-------------|
| Cloud Hosting & Infrastructure | RM 720,000 | RM 650,000 | RM 600,000 |
| Platform Maintenance & Support (PMT) | RM 960,000 | RM 960,000 | RM 960,000 |
| AI/ML Model Operations & Retraining | RM 240,000 | RM 180,000 | RM 160,000 |
| Cybersecurity & Compliance (Annual Audit) | RM 180,000 | RM 180,000 | RM 180,000 |
| Licensing & SaaS Subscriptions | RM 120,000 | RM 120,000 | RM 100,000 |
| Customer Support (Helpdesk, Training) | RM 180,000 | RM 150,000 | RM 120,000 |
| **Total Annual OpEx** | **RM 2,400,000** | **RM 2,240,000** | **RM 2,120,000** |

### 7.3 Return on Investment Summary

| | Year 1 | Year 2 | Year 3 |
|--|--------|--------|--------|
| Revenue Enhancement (vs. baseline) | RM 5M | RM 20M | RM 29M |
| Total Investment (CapEx + OpEx) | RM 8.47M | RM 2.24M | RM 2.12M |
| **Net Benefit / (Cost)** | **(RM 3.47M)** | **RM 17.76M** | **RM 26.88M** |
| Cumulative Net | (RM 3.47M) | RM 14.29M | **RM 41.17M** |

**Full cost recovery: Month 18 of operation.**
**Cumulative net benefit at end of Year 3: RM 41.17 million.**

### 7.4 Profit-Sharing & Commercial Model

The platform is delivered under a **Public-Private Partnership (PPP)** structure:

| Party | Role | Revenue Share |
|-------|------|--------------|
| **CAAM** | Platform owner, regulator, fee collector | **80% of net platform revenue** |
| **PMT (Project Management Team)** | Development, hosting, 24/7 maintenance | **20% of net platform revenue** |

This structure ensures:
- CAAM retains full data sovereignty and ownership
- PMT has commercial incentive to maximise platform uptime and adoption
- CAAM bears zero risk of cost overrun — PMT absorbs development risk
- No government budget allocation required beyond policy approval

---

## 8. IMPLEMENTATION ROADMAP

### Phase 0: Mobilisation (Month 1–2)
- Cloud tenancy provisioning on Google Cloud `asia-southeast1`
- CAAM IT team onboarding and knowledge transfer
- Stakeholder workshops with CAAM divisional heads
- Data catalogue and migration planning
- Deliverable: **Architecture Sign-Off Document**

### Phase 1: Foundation & Module 2 (Month 3–8)
- API Gateway, SSO/RBAC, shared services layer
- Professional Licensing Hub (PLH) — extending eCLIPSE
- Payment Gateway integration (FPX/JomPAY)
- Pilot: 500 selected licence holders on UAT
- Deliverable: **Live PLH; CAAM officer training complete**

### Phase 2: Infrastructure & Safety (Month 9–14)
- Infrastructure Compliance Hub (ICH) — structure registry + IoT framework
- Operator Certification & Safety Hub (OCSH) — AOC/GHL digital workflow
- Predictive SMS AI model (trained on 2022–2024 MOR/VOR data)
- Integration with AAIB, MAHB
- Deliverable: **Live ICH + OCSH; first IoT-connected structures**

### Phase 3: Airspace & Public Services (Month 15–18)
- Future Airspace Management Hub (FAMH) — UAS registration + FAS
- Public Services & Consumer Protection Hub (PSCPH) — consumer portal
- ICAO USOAP reporting engine
- Public launch and national communications campaign
- Deliverable: **Full portal live; national press launch**

### Phase 4: Optimisation (Month 19–24)
- AI model refinement based on live data
- Advanced analytics dashboards for CAAM leadership
- Integration with ASEAN aviation authorities (bilateral data exchange)
- Deliverable: **CAAM 2030 Dashboard — real-time national aviation KPI view**

---

## 9. RISK & MITIGATION REGISTER

| # | Risk | Probability | Impact | Mitigation |
|---|------|-------------|--------|-----------|
| 1 | Resistance from CAAM staff to new digital workflows | Medium | Medium | Dedicated change management programme; CAAM champion network; phased rollout |
| 2 | Data migration complexity from legacy systems | Medium | High | Parallel running (dual-system) for 3 months; automated data validation scripts |
| 3 | Low adoption by structure owners for ICH self-declaration | High | Medium | Outreach campaign; compliance incentives; enforcement actions as backstop |
| 4 | Cybersecurity breach / data leak | Low | Critical | Cloud Armor WAF, VPC-SC isolation, ISO 27001, annual penetration testing, PDPA DPO appointment |
| 5 | ICAO/PDPA regulatory change requiring system redesign | Low | Medium | API-first architecture enables module-level updates without full rebuild |
| 6 | Internet connectivity in rural areas (Sabah/Sarawak) | Medium | Medium | PWA offline capability; mobile data fallback; RAS module designed for low-bandwidth |
| 7 | Vendor lock-in (Google Cloud) | Low | Medium | Container-based deployment (Docker/Kubernetes) enables migration to any cloud provider |

---

## 10. WHY THIS PROPOSAL NOW

### 10.1 The Window is Now

Three factors converge in 2026 to make this the optimal moment:

1. **CAAM's newly expanded mandate** (post-MAVCOM merger) requires digital infrastructure to manage both technical and economic regulatory functions under one roof — which currently does not exist.

2. **CAAM's DSP 2024–2028** creates the institutional readiness and political will for digital transformation. Phase 2 (now) is precisely where this platform accelerates CAAM's own declared strategy.

3. **Malaysia's aviation growth** — 97.14 million passengers in 2024 trending to 120 million by 2028 — means the regulatory burden is about to intensify dramatically. A manual, siloed system that is already straining at 97 million cannot sustain 120 million without structural change.

### 10.2 Opportunity Cost of Inaction

Every month of delay means:
- Continued manual processing of licences, creating backlogs that degrade Malaysia's competitiveness as an aviation hub
- No proactive AOL compliance enforcement — a silent safety risk
- ICAO USOAP evidence gathered manually — risk to Malaysia's EI score
- Consumer complaints post-MAVCOM merger handled on mismatched systems
- Revenue leakage from non-automated fee collection

**Estimated cost of inaction: RM 5–8 million per year in operational inefficiency and uncollected fees.**

### 10.3 Regional Competitive Context

| Country | Digital Aviation Platform | Launch Year |
|---------|--------------------------|-------------|
| Singapore (CAAS) | WINGS (Workforce & Industry Networking for Growth of Singapore aviation) | 2021 |
| Australia (CASA) | AVCREG (Aviation Credential Registry) | 2020 |
| UAE (GCAA) | GCAA Digital Transformation Programme | 2022 |
| **Malaysia (CAAM)** | **CAAM 2030 Unified Portal (proposed)** | **2026–2027** |

Malaysia is not leading — but this proposal can close the gap decisively.

---

## 11. CALL TO ACTION

### CAAM 2030 Unified Aviation Portal — Approval Request

We respectfully request CAAM's approval to proceed with **Phase 0: Mobilisation**, including:

1. **Execution of a Memorandum of Understanding (MOU)** between CAAM and the Project Management Team (PMT) governing data sovereignty, IP ownership, and profit-sharing structure
2. **Formation of a Joint Steering Committee (JSC)** comprising CAAM divisional heads (Licensing, Aerodrome, Safety, ICT) and PMT leadership to govern the rollout
3. **Allocation of a dedicated CAAM Project Champion** from the ICT Division with authority to coordinate cross-divisional data access and stakeholder engagement
4. **Phase 0 commencement** within 30 days of MOU signing

---

## ANNEXURES

### Annexure A — References & Citations

1. CAAM Industry Statistics 2024: Passenger Traffic Data — [caam.gov.my](https://www.caam.gov.my)
2. CAAM Financial Autonomy & Fee Revision (Jan 2025) — Malaysian Aviation Industry Association (MAIA), maia.my, 2025
3. CAAM + MAVCOM Merger (Aug 2025) — The Vibes, thevibes.com, 2025; Wikipedia CAAM article
4. CAAM Digitalisation Strategic Plan 2024–2028 — Astro Awani, astroawani.com, May 2024; Vietnam Plus, 2024
5. eCLIPSE Launch (Feb 2025) — The Star, thestar.com.my, February 2025
6. AOL Certification Revocation (Jul 2022) — CAD 14 Vol I; CAAM Advisory, scribd.com (CAAM document)
7. High-Risk Aviation Incidents (2022–2023) — Ministry of Transport Malaysia, mot.gov.my
8. Malaysia Passenger Growth 2024 (+14.3%) — CAAM Monthly Statistics, caam.gov.my
9. KLIA Passengers 2024 (57.01M) — CAAM Industry Statistics, caam.gov.my
10. Monthly Traffic Jul 2025 (9.3M) — The Sun Malaysia, thesun.my, 2025
11. CAAM Annual Government Subsidy (~RM200M ended) — MAIA, maia.my, 2025
12. ICAO USOAP Framework — icao.int; CAAM compliance documentation
13. PDPA 2010 (Act 709) — Malaysia Personal Data Protection Act 2010
14. Civil Aviation Authority of Malaysia Act 2017 (Act 771) — parlimen.gov.my

### Annexure B — Glossary

| Term | Definition |
|------|-----------|
| ATPL | Airline Transport Pilot Licence |
| AME | Aircraft Maintenance Engineer |
| ATC | Air Traffic Controller |
| AOL | Aerodrome Operator Licence / Aviation Obstruction Lighting |
| AOC | Air Operator Certificate |
| ASL | Air Service Licence |
| ASP | Air Service Permit |
| CAD | Civil Aviation Directive |
| DSP | Digitalisation Strategic Plan |
| FIR | Flight Information Region |
| GHL | Ground Handling Licence |
| ICAO | International Civil Aviation Organization |
| MOR | Mandatory Occurrence Report |
| PDPA | Personal Data Protection Act 2010 |
| PSO | Public Service Obligation |
| RANS | Route Air Navigation Service |
| RAS | Rural Air Service |
| RBAC | Role-Based Access Control |
| SMS | Safety Management System |
| SSO | Single Sign-On |
| UAS | Unmanned Aerial System |
| UTM | Unmanned Traffic Management |
| VOR | Voluntary Occurrence Report |
| USOAP | Universal Safety Oversight Audit Programme |

---

*This proposal is prepared in good faith based on publicly available information and CAAM's published strategic frameworks. All financial projections are estimates and subject to refinement during Phase 0 due diligence. The PMT commits to transparency in all financial reporting under the proposed profit-sharing arrangement.*

**END OF PROPOSAL**
