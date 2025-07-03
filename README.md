# ☁️ Oracle Cloud Infrastructure (OCI) Foundations  
### Study Notes & Summaries  
_A comprehensive guide based on the official Oracle OCI Foundations Course._

---

## 📘 Course Overview _(To complete after course completion)_

- **Platform:** Oracle Learning
- **Goal:** Understand the core services and architecture of Oracle Cloud Infrastructure
- **Final Test:** Skill Checks after each module (score 80% or higher to pass)

---

## 🧭 Course Structure

### 1. Course Introduction
- [x] OCI Overview *(6 min)* – _No notes_
- [x] Introduction *(2 min)* – _No notes_

### 2. OCI Introduction
- [x] OCI Architecture *(7 min)* – ✅ [See Summary](#oci-introduction--class-oci-architecture)
- [x] Demo: OCI Console Walkthrough *(8 min)* – _No notes_
- [x] Skill Check: OCI Introduction – ✅ [See Answers](#-skill-check-oci-introduction)

### 3. Identity and Access Management (IAM)
- [ ] IAM Introduction *(6 min)* – _Notes pending_
- [ ] Compartments *(5 min)* – _Notes pending_
- [ ] Demo: Compartments and Identity Domains *(7 min)* – _Notes pending_
- [ ] AuthN and AuthZ *(7 min)* – _Notes pending_
- [ ] Demo: AuthN and AuthZ *(9 min)* – _Notes pending_
- [ ] Tenancy Setup *(5 min)* – _Notes pending_
- [ ] Skill Check: Identity and Access Management (IAM) – _Not Attempted_

### 4. Networking
- [ ] VCN Introduction *(5 min)* – _Notes pending_
- [ ] Demo: VCN Creation Using Wizard *(6 min)* – _Notes pending_
- [ ] VCN Routing *(6 min)* – _Notes pending_
- [ ] VCN Security *(4 min)* – _Notes pending_
- [ ] Load Balancer *(5 min)* – _Notes pending_
- [ ] Demo: Load Balancing *(10 min)* – _Notes pending_
- [ ] Skill Check: Networking – _Not Attempted_

### 5. Compute
- [ ] Compute Introduction *(5 min)* – _Notes pending_
- [ ] Instance Basics *(4 min)* – _Notes pending_
- [ ] Demo: Getting Started with Cloud Shell *(3 min)* – _Notes pending_
- [ ] Demo: Creating a Compute Instance *(12 min)* – _Notes pending_
- [ ] Scaling *(5 min)* – _Notes pending_
- [ ] Oracle Container Engine for Kubernetes (OKE) *(10 min)* – _Notes pending_
- [ ] Container Workloads in OCI *(3 min)* – _Notes pending_
- [ ] Serverless with Oracle Functions *(5 min)* – _Notes pending_
- [ ] Skill Check: Compute – _Not Attempted_

### 6. Storage
- [ ] Storage Introduction *(5 min)* – _Notes pending_
- [ ] Object Storage *(8 min)* – _Notes pending_
- [ ] Demo: Object Storage *(6 min)* – _Notes pending_
- [ ] Block Volume *(5 min)* – _Notes pending_
- [ ] Demo: Block Volume *(9 min)* – _Notes pending_
- [ ] File Storage *(4 min)* – _Notes pending_
- [ ] Skill Check: Storage – _Not Attempted_

### 7. Security
- [ ] Security Introduction *(9 min)* – _Notes pending_
- [ ] Cloud Guard *(5 min)* – _Notes pending_
- [ ] Security Zones and Security Advisor *(4 min)* – _Notes pending_
- [ ] Demo: Security Zone and Security Advisor *(6 min)* – _Notes pending_
- [ ] Encryption Basics *(11 min)* – _Notes pending_
- [ ] Vault *(8 min)* – _Notes pending_
- [ ] Demo: Vault *(7 min)* – _Notes pending_
- [ ] Skill Check: Security – _Not Attempted_

### 8. Governance and Administration
- [ ] Pricing *(5 min)* – _Notes pending_
- [ ] Cost Management *(4 min)* – _Notes pending_
- [ ] Demo: Cost Management *(9 min)* – _Notes pending_
- [ ] Demo: Cloud Advisor *(7 min)* – _Notes pending_
- [ ] Tagging *(6 min)* – _Notes pending_
- [ ] Support Rewards *(4 min)* – _Notes pending_
- [ ] Skill Check: Governance and Administration – _Not Attempted_
---

## 📂 Lesson Notes

### OCI Introduction → Class: **OCI Architecture**

#### 🧱 OCI Physical Architecture

**Key Concepts:**

- **Region:** A localized geographic area that contains one or more *Availability Domains (ADs)*.  
  Choose based on:
  - Proximity to users (low latency)
  - Data residency/compliance
  - Service availability

- **Availability Domain (AD):**  
  Independent, fault-tolerant data centers within a region.  
  - Do **not share** power, cooling, or network
  - A region typically has 3 ADs

- **Fault Domain (FD):**  
  Logical groupings of hardware within an AD  
  - Each AD contains 3 FDs  
  - Help avoid single points of failure  
  - Only one FD is actively updated at a time

#### 🛠️ Best Practices

- Distribute resources across multiple FDs and ADs
- Use Oracle Data Guard to replicate and sync databases
- Even in single-AD regions, use FDs for redundancy

#### ✅ Summary

- **Region → Availability Domains → Fault Domains**
- Use these constructs to build **highly available**, **resilient** architectures

---

## 🧪 Skill Check: OCI Introduction

This section summarizes the questions and correct answers for the Skill Check quiz in Module 2.

---

### **1. Which statement about regions and availability domains is true?**

**✅ Correct Answer:**  
**An OCI region has one or more availability domains.**

**Explanation:**  
Each region is a localized geographic area with one or more ADs. Fault domains provide protection **within** an AD, not across regions.

---

### **2. Which capability can be used to protect against failures within an OCI availability domain?**

**✅ Correct Answer:**  
**Fault Domain**

**Explanation:**  
Fault Domains isolate hardware within a single AD. Distributing resources across FDs reduces the impact of failures within that AD.

---

### **3. Which Oracle Cloud Infrastructure service is NOT intended for a multicloud solution?**

**✅ Correct Answer:**  
**Oracle Roving Edge Infrastructure**

**Explanation:**  
This is used for **edge computing** in remote environments, not for multicloud.  
Multicloud services include:
- Oracle Database Service for Azure  
- Oracle Interconnect for Azure  
- Oracle MySQL HeatWave on AWS

---

### **4. Which statement about OCI is NOT true?**

**✅ Correct Answer:**  
**A single fault domain can be associated with multiple availability domains within a region.**

**Explanation:**  
Fault Domains are scoped to a **single AD**. They do not span ADs.

---

### **5. You have subscribed to an OCI region with one availability domain. You want to deploy a highly available application with two servers and a 2-node database. How would you place the components?**

**✅ Correct Answer:**  
**Place one server and a DB node in one fault domain, and the second server and DB node in another fault domain.**

**Explanation:**  
When limited to one AD, the best way to increase availability is to **spread components across multiple fault domains** within that AD.

---
