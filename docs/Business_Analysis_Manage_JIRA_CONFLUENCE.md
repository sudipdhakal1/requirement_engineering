## Assignment 1 – Business Analysis

- [Part 1 – Prepare for and Perform Business Analysis](Business_Analysis.md)
- [Part 2 – Define the Problem](Business_Analysis_Describe_A_Problem.md)
- [Part 3 – Characterize the Solution Space](Business_Analysis_Characterize_Solution_Space.md)
- [Part 4 – Manage the Business Analysis (Jira)](Business_Analysis_Manage_JIRA_CONFLUENCE.md)
## Manage the Business Analysis

**Use Jira, document business objectives and business constraints**

---

## Overview

Set up Jira

Start Tool Presentation

Add goals / objectives

Add operational policies and business rules

Describe and create BRS / ConOps / System Definition Document

Complete Business Analysis Report

---

## Details

### Read

29148-2018 6.2.3.6

[OKRs: goal setting that focuses on outcomes](https://www.atlassian.com/agile/agile-at-scale/okr)

[Business Rules: An Agile Introduction](https://agilemodeling.com/artifacts/businessRule.htm)

[Jira page on course web site](https://sites.google.com/site/profvanselow/swebok/software-requirements-ch-1/7-8-management-and-tools/jira)

---

## Tasks

Maintain traceability of business or mission analysis.

Provide key [artifacts and] information items that have been selected for baselines.

---

## Task 1 – Maintain Traceability

Related to the task of maintaining traceability:

"Requirements traceability should be established and maintained to document how the business needs and requirements are intended to meet the business problems and opportunities and how they are related to preferred alternative solution classes and stakeholder needs and requirements. Business and mission needs and requirements need to be captured, traced, and maintained throughout the system life cycle and beyond. Use of a requirements management tool can facilitate this process."

The requirements management tool we are going to use in this class is **Jira**. Jira is an extremely popular tool so learning it will help you in the future.

---

### Jira and Confluence Setup

Create a page in your OneNote for **Jira Notes**. Document what you do in Jira and take notes about what Jira can do.

Sign up for the **Free Plan for Jira** and the **Free Plan for Confluence**.  
Do **not** do the Free Trial of the Standard Plan.

In Jira:

- Click **Create project**
- Create a **team-managed project**
- The project name can be your solution name (if you have one) or just the business or organization name
- Choose a descriptive and easy to type **project key**
- Use the **Kanban template**
- Turn on the following features:
  - Roadmap
  - Backlog
  - Sprints
  - Pages

---

### Using Jira and Confluence

You will use **Pages** for all "real" project related artifacts that you would share with a client / sponsor.

Copy and paste your **Business Specification** into **Confluence**.

You will use the **Blog** for all meta / course related artifacts that you will share with the instructor and will serve as a resource for you when you have to do these activities in the future, like your notes.

You could also take the mindset that you could share your Blog with potential employers to demonstrate your methodology and skillset or that your blog is to help teach other people.

---

### Create Custom Issue Types in Jira

Add the following new issue types in Jira:

- Objective
- Constraint

This can be done from:

Project Settings → Issue types → + Add issue type → Create issue type  
https://confluence.atlassian.com/adminjiracloud/adding-editing-and-deleting-an-issue-type-844500747.html

Choose the **grey and white O icon** for the Objective issue type.

Choose the **lock icon** for the Constraint issue type.

These are not standards, they are just to make grading easier.

---

### Populate Jira with Objectives and Constraints

Dissect your Business Specification document and notes you took when researching and meeting with your sponsor to add objectives and constraints to Jira.

When you add them, type a brief sentence for each issue in the **Backlog** page where it says  
"What needs to be done?".  
This is the **Summary** field of the issue.

Optionally, click on the issue to bring up its fields. From here you can add:

- A longer description
- Identify the source
- Add an attachment
- Add links
- And more

---

### Replace Sections in Business Specification with Jira Tables

Replace the content in the **Mission, goals, and objectives** section in your Business Specification with a Jira table.

- Use `/jira` to add a table
- Use `type = objective` to filter issues
- Delete the number in the **Maximum issues** box to get all issues
- In **Display options**, choose to show:
  - Key
  - Summary
  - Description  
  (in that order)

Replace the content in the **Constraints** section in your Business Specification with a Jira table.

- Use `/jira` to add a table
- Use `type = constraint` to filter issues
- Delete the number in the **Maximum issues** box to get all issues
- In **Display options**, choose to show:
  - Key
  - Summary
  - Description  
  (in that order)

---

## Task 2 – Provide Key Information Items

At this point, you have completed the **Business or mission analysis process (29148 6.2)**. For projects you work on in the future, a business analyst may do this process and just give you a BRS or something like it.

---

### Complete the BRS Assignment (IMPORTANT)

Create a **Blog post** in Confluence named **Specification Notes**.

Create a heading 1 named **Introduction** using the dropdown box at the top left.

You can leave this section empty for now.

---

### Business Requirements Specification (BRS) – General Description

Create a heading 1 named **Business Requirements Specification (BRS) General Description**.

Create a heading 2 for each of the following and provide the corresponding information (REQ.rsd.1):

- General description – identify other names this type of document could be called
- Audience
- Structure
- Attributes
- Standards

---

### My Business Specification Review

Create a heading 1 named **My Business Specification Review**.

Describe what you did to create your BRS.

Clearly describe your proficiency in writing skills and how you used techniques from the Writing page on the course web site.

---

### Instructor Access (IMPORTANT)

While logged in to Atlassian, go to:

https://admin.atlassian.com/

Invite **soodepdhakal7@gmail.com** as a team member so I can access your site for grading.

You should only need to do this once but might need to do it for Jira and Confluence.

---

### Customize the Confluence Overview Page

Customize the **Overview** page by clicking on it at the top left within Confluence and following the provided instructions.

Delete the provided welcome text box.

Read the linked pages.

Make this a professional looking landing page for your project.

---

### Required Content on Overview Page

In your overview page, add:

- A heading 1 for **Information Items / Specifications**
  - A link to your BRS (your polished up Business Specification page)

- A heading 1 for **Requirements Activity Notes**
  - A link to your Business Analysis Notes
  - A link to your Specification Notes

- A heading 1 for **Requirements Activity Reports**
  - A link to your Business Analysis Report (your polished up Business Analysis Notes)

- A heading 1 for **Practical Considerations and Software Requirements Tools**
  - A link to your Jira Notes

---

## Submission

Submit a link to your **Overview page**.

It will look like:

https://username.atlassian.net/wiki/spaces/projectkey/overview
