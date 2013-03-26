exit_interview
==============

A regional talent retention tool

# Problem

Talented people who are frustrated with their current employers are leaving the region before they can be connected with employers who are a better fit.
These are people who are near the top of their field and feel like they can no longer advance in the local market.
They are the mentors to your junior staff and the architects of your products, and they are invaluable to local economic development.

# Proposal

Help local talent find other local companies who are a better fit.

# Rationale

While local companies are competitors when it comes to hiring talented people, their fates are intertwined.
When a talented employee leaves the region, there is very little the company can do to bring that person back.
It is far better to lose talent to a local competitor.
Talented and experienced employees mentor entry level employees.
The employee you lost to another local company may be training the employee you will hire in 6 months.
The employee you lost to another local company may come back when you've made positive changes.
The employee you lost to another region? That person will not likely return.

# Overview

The web application will be written in Rails to ensure maximum participation from NOLA Hack Night members.
A person who wishes to participate in the online exit interview process will visit the web site and fill out a form.
This form will in turn be delivered to participating local employers.
These employers will be able to reply to an anonymized email address or similar.
Potential employees will then be able to non-anonymously engage these employers if they so choose.

# Requirements

## Feedback form

Ask relevant questions about why an employee wishes to leave their employer and why they would consider leaving the region:

* What is your next career goal?
* Why do you feel that you can't accomplish this with your current employer?
* Are you considering relocation? To where, and why?
* Name each company you believe might hire you, and state your concerns about engaging them.

## Employee privacy

Employee feedback must protect the employee's privacy as much as possible.
Features to accomplish this goal should include:

* Employer blacklists. The employee should be allowed to select employers to whom their feedback will not be distributed.
* Anonymized employer reply. Give the employers a way to reach out without disclosing the employee's identity.
* Strong warnings to employees to be diligent about not disclosing personally identifiable details.

## Employer concerns

Data must be collected and distributed in a way that is respectful of employers' reputations and competitive positions.
To that end, features should include:

* Anonymization of employer-specific feedback. For the "name each company" section, only report the name of the company to that particular company.
* Curation of feedback reports. Do not distribute feedback forms from people who attempt to circumvent protections and identify employers.







