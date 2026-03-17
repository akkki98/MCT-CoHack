# 🚀 Co-Hack by Pax

## 💡 Idea: Expense Management System

---

# 📌 Problem Statement

Organizations often struggle with managing employee expense claims efficiently. Employees submit expenses through emails or spreadsheets, which leads to:

* Lack of visibility into request status
* Delays in approvals
* Manual tracking and errors
* No centralized system for records

There is a need for a **centralized, automated Expense Management System** that streamlines submission, approval, and tracking of expense requests.

---

# 🎯 Objective

Build a **Power Platform-based Expense Management Solution** using:

* Dataverse
* Model-Driven App
* Power Automate

The solution should allow employees to submit expenses and managers to approve/reject them with automated notifications.

---

# 🛠️ Tasks

## 1. Create Dataverse Table

* Create a table named **Expense Claims**
* Include fields such as:

  * Expense Title
  * Description
  * Amount
  * Expense Date
  * Category
  * Submitted By
  * Manager
  * Approval Status (Pending, Approved, Rejected)
* Use Copilot to assist in table creation
* Create views:

  * Approved Expenses
  * Rejected Expenses
  * Pending Expenses
* Design forms with relevant fields

---

## 2. Build Model-Driven App

* Create a Model-Driven App using the Dataverse table
* Ensure users can:

  * Submit new expense requests
  * View status of submitted requests
* Customize navigation and layout for better usability

---

## 3. Create Power Automate Flow

* Trigger: When a new expense request is created
* Send approval request to Manager
* Manager can:

  * Approve or Reject
* Update Approval Status in Dataverse based on response
* Send notification to employee with the decision

---

# ✅ Success Criteria

* Dataverse table is created with all required fields
* Approval Status column is properly implemented
* Views for Approved, Rejected, and Pending are created
* Forms are user-friendly and complete
* Model-Driven App is functional and connected to data
* Users can submit and track expense requests
* Power Automate flow triggers correctly
* Approval email is sent to Manager
* Manager can approve/reject successfully
* Status updates correctly in the system
* Notification is sent back to the user
* End-to-end solution works seamlessly

---

# 🏆 Judging Criteria

## 1. Functionality (30%)

* Complete working solution (App + Flow + Dataverse)
* Approval workflow functions correctly

## 2. User Experience (20%)

* Clean and intuitive UI
* Easy navigation and usability

## 3. Automation & Logic (20%)

* Effective use of Power Automate
* Proper handling of approval scenarios

## 4. Data Modeling (15%)

* Well-structured Dataverse schema
* Proper use of fields, views, and forms

## 5. Innovation & Enhancements (10%)

* Additional features like:

  * Attachments
  * Multi-level approvals
  * Dashboards

## 6. Presentation (5%)

* Clear demo and explanation
* Ability to answer questions

---
