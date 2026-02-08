# System Definition Document / Business Requirements Specification (BRS)

 

Sometimes known as the **User Requirements Document** or **Concept of Operations (ConOps)** or **Vision and Scope Document**

---

## A predecessor to the SRS

---

## Description

This is a document for users, while the SRS is for developers. It should not be overly technical or formal. It may be written by a business analyst, the user (a domain expert), the developer, or a combination (maybe with help of RE consultants).

The Business Requirements Specification (BRS) describes the organization’s motivation for why the system is being developed or changed, defines processes and policies/rules under which the system is used and documents the top-level requirements from the stakeholder perspective including expressing needs of users/operators/maintainers as derived from the context of use in a specific, precise and unambiguous manner. In a business environment, the BRS describes how the organization is pursuing new business or changing the current business in order to fit a new business environment, and how to utilize the system as a means to contribute to the business. The description includes, at the organization level, the organizational environment, goals and objectives, the business model, and the information environment, and, at the business operation level, the business operation model, business operation modes, business operational quality, organizational formation and concept of the proposed system. It is very important that the business management level should actively participate or lead the development of the business requirement specification.

The information elements of the BRS should be specified by the business. Business management should be responsible for the content of the specification. The BRS serves as the basis of the stakeholders' active participation in the requirement processes. For example, a business analyst or representative user from the business can review the BRS and discuss the business model or operation, business management can revise the BRS, or a system analyst can review the BRS and discuss potential technical solutions. Typical types of requirements included in the BRS are organizational requirements and business requirements.

**29148-2018 8.2.1**

---

## Relationship to IEEE 29148-2018

As it relates to Standard 29148-2018, this should follow **9.3 Business requirement specification (BRS)**. This document is sometime created instead of, and sometimes created in addition to, the **9.4 Stakeholder requirements specification (StRS)**, **9.5 System requirements specification (SyRS)**, and **Annex B Concept of operations (ConOps)**. 29148 notes that the StRS is often identified with the business requirement specification (BRS) in many industries. Users of this document can combine the StRS with the BRS according to the users’ environment.

---

## Relationship to SWEBOK

As it relates to SWEBOK, this is the **System Definition Document (SDD)**.

---

## From SWEBOK Ch. 1 Section 5.1

### System Definition Document

This document (sometimes known as the user requirements document or concept of operations document) records the system requirements. It defines the high-level system requirements from the domain perspective. Its readership includes representatives of the system users/customers (marketing may play these roles for market-driven software), so its content must be couched in terms of the domain. The document lists the system requirements along with background information about the overall objectives for the system, its target environment, and a statement of the constraints, assumptions, and nonfunctional requirements. It may include conceptual models designed to illustrate the system context, usage scenarios, and the principal domain entities, as well as workflows.

---

## From IEEE Std 1362-1998

**Definition:** A Concept of Operations (CONOPS) is a user-oriented document that "describes systems characteristics for a proposed system from a user's perspective. A CONOPS also describes the user organization, mission, and objectives from an integrated systems point of view and is used to communicate overall quantitative and qualitative system characteristics to stakeholders."

It should not be overly technical or formal. The user, developer, or both may write CONOPS. The main objective of a CONOPS is to "communicate with the end user of the system during the early specification stages to assure the operational needs are clearly understood and incorporated into the design decisions for later inclusion in the system and segment specifications."

---

## From Software Requirements Textbook

Some organizations create a project charter (Wiegers 2007) or a business case document that serves a similar purpose. Organizations that build commercial software often create a market (or marketing) requirements document (MRD). An MRD might go into more detail about the target market segments and the issues that pertain to commercial success.

Useful and interesting information about software engineer vs. business analyst

---

## Key Resources

- 29148-2018 Sections 7, 8, 9 and Annex B
- 15288:2015 6.4.2 Stakeholder needs and requirements definition process
- MITRE Systems Engineering Guide: Concept Development including Operational Needs Assessment, Concept of Operations, Operational Requirements, and High-Level Conceptual Definition - pages 275-300. VERY USEFUL. READ! Especially Best Practices
- Eliciting, Collecting, and Developing Requirements - pages 304-313
- Stakeholder Needs and Requirements sebokwiki
- Software Requirements Engineering by Richard H. Thayer and Merlin Dorfman Details Access Chapter 1 sections III and IV pages 12-19 (PDF pages 9-18)

---

## Other Resources

- Concept of Operations (ConOps) (glossary) sebokwiki
- Concept of operations wikipedia
- Concept of Operations (ConOps) (PDF). Department of Health & Human Services
- Multiple CONOPS guidelines, models, and methodologies are available that can be tailored as needed for particular environments or situations. See their basic outline and description.
- Example from Lockheed Martin (PDF)
- Vision and Scope Document for Cafeteria Ordering System (in Wiegers book downloads)
- NASA Systems Engineering Handbook - Appendix S: Concept of Operations Annotated Outline
- Arcade Game Maker example product line
- EuTravel Stakeholder Requirements Specification - EuTravel Project
- User Requirements Document (URD)
- https://www.ifi.uzh.ch/dam/jcr:05621b9a-b077-4849-951d-677829401ce6/RE_I_Slides_Part_II_(5-7).pdf

---

## Contents

### 1. Introduction

#### 1.1 Business purpose
Describe at the organization level the reason and background for which the organization is pursuing new business or changing the current business in order to fit a new management environment. In this context it should describe how the proposed system will contribute to meeting business objectives.

#### 1.2 Business scope
Define the business domain under consideration by:

a) identifying the business domain by name;

b) defining the range of business activities included in the business domain concerned. The scope can be defined in terms of divisions in the organization and external entities that relate directly to the business activities, or functions to be performed by the business activities. It is helpful to show environmental entities that are outside of the scope;

IBISWorld may be helpful with trusted industry research to help companies and institutions of all sizes make better business decisions, fast. You should auto-login when signed in to FGCU.

c) describing the scope of the system being developed or changed. The description includes assumptions on which business activities are supported by the system.

https://www.bridging-the-gap.com/new-business-domain/

#### 1.3 Business overview

Describe major internal divisions and external entities of the business domain concerned and how they are interrelated. A diagrammatic description is recommended.

#### 1.4 Definitions

#### 1.5 Major stakeholders

List the stakeholders or the classes of stakeholders and describe how they will influence the organization and business, or will be related to the development and operation of the system.

A stakeholders is an "Individual or organization having a right, share, claim, or interest in a system or in its possession of characteristics that meet their needs and expectations" (ISO/IEC/IEEE 2015).

From SWEBOK: Typical examples of software stakeholders include (but are not restricted to) the following:

- Users
- Customers
- Market analysts
- Regulators
- Software engineers

Include an Org Chart.

---

### 2. References

Provide a complete list of all documents referenced elsewhere;

Identify each document by title, report number (if applicable), date and publishing organization;

Specify the sources from which the references can be obtained.

This information may be provided by reference to an appendix or to another document. The references information should be subdivided into a **Compliance** section and a **Guidance** section.

---

### 3. Business management requirements

#### 3.1 Business environment

#### 3.2 Mission, goals, and objectives

#### 3.3 Business model

#### 3.4 Information environment

---

### 4. Business operational requirements

#### 4.1 Business processes

#### 4.2 Business operational policies and rules

#### 4.3 Business operational constraints

#### 4.4 Business operational modes

#### 4.5 Business operational quality

#### 4.6 Business structure

---

### 5. Preliminary operational concept of proposed system

#### 5.1 Preliminary operational concept

#### 5.2 Preliminary operational scenarios

---

### 6. Other preliminary life-cycle concepts

#### 6.1 Preliminary acquisition concept

#### 6.2 Preliminary deployment concept

#### 6.3 Preliminary support concept

#### 6.4 Preliminary retirement concept

---

### 7. Project Constraints

Describe constraints to performing the project within cost and schedule.

Project Constraints

---

### 8. Appendix

#### 8.1 Acronyms and abbreviations

---

## Sample Business Analysis Questions

1. What would be a reasonable or acceptable response time for retrieval of a typical patent application in response to a query?
2. What would users consider an unacceptable response time for a typical query?
3. How many simultaneous users do you expect on average?
4. What’s the maximum number of simultaneous users that you would anticipate?
5. What times of the day, week, month, or year have much heavier usage than usual?

Sending a list of questions like these to elicitation participants in advance gives them an opportunity to think about or research their answers so they don’t have to answer a barrage of questions off the tops of their heads. A good final question to ask during any such elicitation discussion is:

> “Is there anything I haven’t asked you that we should discuss?”

Weigers, Beatty Ch. 14
