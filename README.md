# Messaging Infrastructure Design – University Project

**Course**: CCSW311 – Designing with Patterns  
**University**: University of Jeddah  
**Student**: Abdulmalik Alshenawi

---

## Project Overview

This academic project proposes a design for the Messaging Infrastructure Layer of the new Brokerage Information System (BIS) for a real estate company, BizCo.

The goal is to integrate three legacy systems:
- CPS – Commercial Property System  
- RPS – Residential Property System  
- BBS – Brokerage Billing System  

These systems previously operated independently and lacked real-time integration. The solution introduces a Messaging Pattern to enable asynchronous, decoupled communication between systems and services.

---

## Architecture Summary

### Architecture Style:
- Layered Architecture with four layers:
  1. User Interface
  2. Business Logic
  3. Messaging Infrastructure (focus of this project)
  4. Services (CPS, RPS, BBS)

### Design Pattern Used:
- Messaging Pattern  
  Connects services via a message bus allowing asynchronous message exchange.

---

## Key Features

- Asynchronous Messaging for performance and scalability  
- System Decoupling to allow independent service updates  
- Integration without tight coupling  
- Use Case Diagram and actor mapping  
- Supports reporting, request management, billing, and agreements  

---

## Quality Attribute Prioritization

Availability is the top priority to ensure the system runs 24/7 with minimal downtime.

Interoperability is critical for integrating the legacy systems (CPS, RPS, BBS).

Performance matters for fast response times and efficient data processing.

Modifiability is important to allow future changes without disrupting the system.

### Tactics to Improve Availability:
- Ping/Echo Checks  
- Failover Mechanisms  
- Redundancy in Message Bus  

---

## Full Report

The complete project report, including diagrams and utility tree analysis, is available here:  


---

## Author

**Abdulmalik Alshenawi**  
Software Engineering Student  
[LinkedIn](https://www.linkedin.com/in/abdulmalik-alshenawi-351381360/) | [GitHub](https://github.com/Mk-coder10)


