---
title: Workflows
nav_order: 2
permalink: /workflows
---

## On this page
{:.no_toc}

* TOC
{:toc}

## Ticket/Request Submissions

A list of places to submit various types of tickets/requests within the LF. 

* [LF Support Center (Jira Service Desk)](https://jira.linuxfoundation.org/plugins/servlet/theme/portals/category/4)
    * Central location for submitting tickets related to Project Services, LFX Support, Training & Certification, Member Support, and LF Events
* [Membership Ops Desk](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/25)
    * Membership operations support for items such as Auto Join, Billing Address/Contact Changes, Custom Salesforce Reports, Membership Cancellations/Upgrades/Downgrades, Quote Requests, and Invoice Changes
    * [Membership Ops Desk FAQ](https://docs.google.com/document/d/1P1K3kzuhaRIoOwj117XB_5SOMjqj2r-ZwZFCFyal6W0/edit)
* [Marketing Services Requests](https://linuxfoundation.org/marketing-requests/)
    * Requests for Design, Website, PR/Communications, and Digital Marketing
* [Legal Requests](https://legaljira.linuxfoundation.org/servicedesk/customer/portal/1)
    * Requests for legal requests related to Contracts, Trademark, Export Control, and Other
* [Project Formation Intake Form](https://docs.google.com/forms/d/e/1FAIpQLSeO1bDGHUP-ZpCo1uynm94YOxZlek6RhCH7o3FnX1lZSXXfSQ/viewform)
   * Submission form to spin up a new project with formation team

## How to set up a third party contract vendor

These steps apply to either agencies or individuals.

1. The vendor either: 
   1. Creates a scope of work (SOW) outlining what they will be doing and what it will cost. This is the preferred method. 
   1. Creates a legal agreement that includes a SOW. This method requires the LF Legal team to review the contract before approving it for LF to sign. 
1. The vendor sends either their SOW or their legal agreement to the LF internal contact, usually the Program Manager. 
1. The LF internal contact goes to [staff.linuxfoundation.org](staff.linuxfoundation.org) and opens the ‘[HR Finance Ops](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/21)’ portal.
1. Inside the HR Finance Ops portal, click the ‘[Contractor & Vendor Requests](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/21/create/462)’ option and fill out the form. In order to complete the form you will need this information from the contractor:
   - Vendor name
   - Name of signatory for contract
   - Email address of signatory for contract
   - Contractor’s physical mailing address
   - Contractor start date
   - Contractor duration
   - Contractor type: individual or agency
   - New contract or extension to an existing contractor agreement (requires LF Legal review)
   - Standard LF contract (preferred) or 
   - LF department or Project the contractor will be working for
   - Description of work to align it with the correct budget code (ex: Marketing)
   - Compensation type: hourly, salary, other
   - Compensation amount
   - Compensation max budget
   - Name of LF internal manager
   - Scope of work provided by the vendor (provided as an attachment)
1. You will receive a notification from Jira that your form has been submitted. 
1. Your request will be reviewed by the LF Finance team to ensure the department or project’s budget has enough revenue to cover the new expense.
1. Once approved by LF Finance, The LF HR Finance Ops team will create a Docusign agreement. You will receive a notification that the agreement is “out for signature” when it is sent to the first signatory. 
   - The Docusign agreement is first sent to the Finance lead for that department or project for them to sign. 
   - It is then routed to the LF internal manager (who will manage the contractor) for them to sign.
   - Finally it is sent to the contract vendor for them to sign.
1. Once all three parties have signed the document you will receive a copy of it from Docusign. The three parties who signed it will also receive a copy.  
1. When it's time to pay, the vendor emails their invoice to the LF internal manager for them to review it. Once they approve payment on the invoice they forward it to [AP@Linuxfoundation.org](mailto:AP@Linuxfoundation.org) notifying them that the invoice is approved for payment. 
1. The LF Accounts Payable department will pay the invoice. 

## How to Change Member Roles

1. Project members should use the [Member Support Desk](https://docs.google.com/document/d/1NHPRGfcyg8FVNlRC9-HX-hOIYbafXxtu5Bie3wNCvSg/edit?usp=sharing) to report changes in project roles.  If there are exceptions, and you feel like you need to do this yourself, please add the use case to this section of the handbook. To process a role change on behalf of a member organization (not recommended), open a Jira in the [Staff portal](https://staff.linuxfoundation.org/) and go to Membership and Sales Ops.
2. LF Operations will update the CRM (Customer Relationship Management, currently Salesforce, moving to Hubspot.) 
3. After LF Operations updates the CRM, they will notify the Project Administrator on the Jira. The Project Administrator updates the Project Control Center ([PCC](https://docs.linuxfoundation.org/lfx/project-control-center-pre-release)) and the [Organization Dashboard](https://docs.google.com/document/d/1i_0rHkjOzpqUOW5kTA4y_Y5taFR8-oRjwvmU3ME3VJ0/edit?usp=sharing). 
4. Make sure that everywhere else, outside of the PCC and Organization Dashboard, is also updated. Examples include calendar invitations, and email lists not managed within the PCC. 
5. Best practice is to refresh all the roles for the organization in that project to keep all contacts up to date.

## Membership renewals

### Outreach e-mail template

```
Thank you for being a [Platinum/Gold/Silver/etc] Member in [Project name]. 

As we head into the [Year] membership year no action is required on your part. Your [Project name] membership will renew automatically, and you will receive an invoice from The Linux Foundation for $[...].

[Add some positive stuff about the project that would make them want to renew. Big projects will have more, generally. Bullet points or paragraphs are fine. I prefer to write it out, but do it as you like]

We would also like to take this opportunity to ensure we have the right contacts for [Project name] activities within your organization. Please email operations@[project domain.org] if any of the following need to be updated.

Voting contact: [...]

Technical contact: [...]

Marketing contact: [...]

Legal contact: [...]

Billing contact: [...]

Finally, if you have any questions about membership or the [Project name] in general, you can always email operations@[project domain.org].

On behalf of [Project name] and The Linux Foundation, we thank you for your continued support.

Best,
[Your Name]
```
