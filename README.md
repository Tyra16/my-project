# Smart Claims Assistant

## Overview

Smart Claims Assistant is a mobile-first InsurTech MVP designed to make minor motor insurance claims simpler to submit and easier to track.

The product focuses on reducing friction and uncertainty during the claims journey by guiding policyholders through claim preparation and submission, providing clear claim status updates, and making required follow-up actions easy to understand.

## Problem

Early discovery research indicated that some insurance policyholders experience friction when making and following up on claims, including:

- Unclear requirements and documentation
- Repeated communication with insurers
- Waiting without clear visibility into claim progress
- Difficulty understanding what happens next

The product therefore focuses on improving the experience across:

**PREPARE → SUBMIT → TRACK → RESPOND → RESOLVE**

## Target User

The primary target user is an existing motor insurance policyholder who needs to make a minor claim and wants a simpler way to submit information and understand the progress of their claim.

### Example Persona

**Ada, 30**

A working professional and regular smartphone user who has experienced a minor vehicle incident.

Her key needs are to:

- Understand what information is required
- Submit her claim correctly
- Upload supporting evidence
- Receive confirmation
- Track claim progress
- Understand when action is required
- Receive clear updates without repeated follow-up

## MVP Scope

### Included

- Minor motor claim submission
- Requirements checklist
- Guided incident details
- Photo/evidence upload
- Claim review before submission
- Submission confirmation
- Claim reference number
- My Claims
- Claim status and timeline
- Action Required state
- Additional information submission
- Updated claim status
- Resolution state
- In-app claim notifications

### Out of Scope

The prototype does not include:

- Complex/high-value claims
- Health, life, pension or other insurance products
- AI damage assessment
- Automated claim approval
- Automated settlement or payment
- Fraud detection
- Repair-shop recommendations
- Full policy management
- Premium payments
- Insurance purchasing
- Live insurer backend integration

## Core User Flows

### Flow 1 — Submit a Claim

Home  
→ Select Claim Type  
→ Requirements  
→ Incident Details  
→ Evidence Upload  
→ Review Claim  
→ Submit  
→ Confirmation  
→ Track Claim

### Flow 2 — Track and Manage a Claim

My Claims  
→ Claim Details  
→ Action Required  
→ Provide Information  
→ Updated Status  
→ Resolution

### Notifications

Important claim updates link directly to the relevant claim state:

- Action Required → Action Required
- Claim Under Review → Claim Details
- Additional Information Received → Updated Status
- Claim Resolved → Resolution

## Prototype

The prototype was built as a mobile-first clickable experience using Figma Make.

It contains 14 screens and demonstrates the complete MVP journey from claim preparation through resolution.

**Prototype/Demo:** [INSERT WORKING DEMO LINK]

## Prototype Status Simulation

The prototype uses simulated claim states to demonstrate the intended experience:

**Submitted → Under Review → Action Required → Additional Information Submitted → Under Review → Decision → Resolved**

These status changes are simulated for demonstration purposes.

The prototype is not connected to a live insurer backend and does not process real insurance claims.

## Design System

The prototype uses a consistent mobile-first design system including:

- Primary brand colour: `#2563EB`
- Background: `#F9FAFB`
- White surface cards
- Consistent typography hierarchy
- Primary and secondary buttons
- Form inputs
- Status components
- Cards
- Evidence upload components
- Timeline components
- Bottom navigation
- Default, focused, selected, disabled, error, success and loading states

## Usability Testing

The prototype is designed to be tested with representative users through task-based usability testing.

Key tasks include:

1. Start a minor motor claim
2. Understand the requirements
3. Complete incident details
4. Upload evidence
5. Review and submit the claim
6. Find the claim status
7. Understand the current status
8. Respond to an Action Required request
9. Understand the updated status and final resolution

Key usability measures include:

- Task success rate
- Completion time
- Error rate
- Assistance required
- Status understanding
- Action completion

## Success Metrics

The primary MVP outcome is:

**Successful Claim Journey Completion Rate**

Supporting metrics include:

- Claim Submission Completion Rate
- Task Success Rate
- Status Understanding Rate
- Step Drop-Off Rate
- Median Submission Time
- Evidence Upload Success Rate
- Status View Rate
- Action Completion Rate
- Status-Related Support Enquiries

## Key Product Events

The intended production tracking plan includes events such as:

- `claim_started`
- `requirements_viewed`
- `incident_details_completed`
- `evidence_uploaded`
- `claim_reviewed`
- `claim_submitted`
- `claim_submission_failed`
- `claim_status_viewed`
- `action_required_viewed`
- `additional_info_submitted`
- `claim_resolved`
- `notification_opened`

## Important Prototype Disclaimer

This is an academic MVP prototype created to demonstrate the proposed Smart Claims Assistant experience.

The prototype does not:

- Process real insurance claims
- Make real insurance decisions
- Connect to an insurer's backend
- Process payments or settlements
- Perform automated damage assessment
- Store or process real customer insurance data

All claim information, statuses, dates, references and resolution outcomes shown in the prototype are simulated.

## Project Structure

The prototype is organized around the following product journey:

**PREPARE → SUBMIT → TRACK → RESPOND → RESOLVE**

The experience is designed around one clear MVP problem:

> Making minor motor insurance claims simpler to submit and easier to follow.

## Team

**Product:** Smart Claims Assistant  
**Category:** InsurTech / Digital Insurance Claims  
**MVP Focus:** Minor Motor Insurance Claims  
**Prototype:** Figma Make
