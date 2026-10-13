 Student Enrollment & Course Management System

> **SECMS** — A Salesforce-based academic group project for managing student enrollment, course administration, instructor assignment, automated approvals, and reporting in a unified cloud platform.

---
Project Overview

The **Student Enrollment & Course Management System (SECMS)** is a declarative Salesforce application built on a **Salesforce Developer Edition** org. It replaces scattered spreadsheets and manual processes with a single, automated, rule-enforced system.

| Detail | Value |
|---|---|
| **Platform** | Salesforce Developer Edition (Lightning Experience) |
| **Type** | Academic Group Project |
| **Project Workspace** | Skill Wallet |
| **Team Lead** | I SAIF ALI |
| **Team Members** | T MOHAMMED RAZI , S MOHAMMED ZABIULLAH|
| **Prepared** | September 2026 |
| **Phases** | 5 Phases (Requirement Analysis → Deployment) |

---

 Problem Statement

| Area | Challenge |
|---|---|
| **Students** | Details stored in different files — records duplicated or outdated |
| **Courses** | No single reliable list for names, categories, fees, durations |
| **Enrollments** | Hard to track which student joined which course; duplicates occur |
| **Instructors** | Manual allocation with no consistent category-to-instructor rule |
| **Approvals** | Paper/message-based — delayed, lost, or fee-unchecked approvals |
| **Payments** | Fee status tracked separately — unpaid students approved by mistake |
| **Reports** | Manually prepared, time-consuming, error-prone |

> **Goal:** One controlled Salesforce system where students, courses, instructors, enrollments, approvals, and payments are recorded consistently, validated by rules, and reported automatically.

---

 Objectives

- Provide a single centralized system for student, course, instructor, and enrollment data
- Create four custom Salesforce objects with defined fields and lookup relationships
- Enforce data quality with active validation rules
- Automate enrollment processing with record-triggered flows
- Implement an approval process routed to a Training Manager
- Build a Lightning app with tabs, page layouts, and record types
- Deliver reports and a management dashboard for administrative visibility
- Plan data migration, testing, security configuration, and deployment

---
Solution

| Layer | Salesforce Tool | Role in SECMS |
|---|---|---|
| **Data** | Custom Objects + Fields | Stores students, courses, instructors, enrollments |
| **Integrity** | Validation Rules | Blocks invalid emails and unapproved fee-free enrollments |
| **Relationships** | Lookup Fields | Links Enrollment to Student, Course, and Instructor |
| **Automation** | Record-Triggered Flows | Sets dates, assigns instructors, creates tasks, reacts to approvals |
| **Approval** | Approval Process | Routes requests to Training Manager for decision |
| **UI** | Lightning App + Page Layouts + Record Types | Tab-based navigation with role-appropriate forms |
| **Reporting** | Reports + Dashboard | Real-time visibility via four reports and a dashboard |
