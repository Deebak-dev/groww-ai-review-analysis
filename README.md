# Groww AI Customer Review Analysis

## Project Overview
An AI-powered workflow built with n8n to analyze Groww customer reviews, identify recurring user issues, and generate a Weekly Product Pulse with actionable product recommendations.

## Prototype
[Open the n8n workflow](https://deebak2001.app.n8n.cloud/webhook/b00c9824-ea1f-4749-8c87-8bcd32ae7483/chat)

## How to Run
1. Open the prototype link.
2. Follow the workflow's prompts and provide the review data as requested.
3. Review the generated Weekly Product Pulse.
4. Check the connected Google Docs and Gmail steps for their results.

Availability and successful completion of every integration may vary.

## MCP and Human Approval
The workflow uses an MCP connection to update the Google Docs report. The Gmail step uses a human-approval process before an email is sent. Confirm the actual execution and approval status in n8n rather than assuming both actions succeeded.

## Key Finding: Customer Fee Complaints
Some customer reviews report unexplained deductions, MTF charges, and delays in getting support. These are customer-reported concerns and should not be treated as verified billing errors without further investigation.

Official reference pages:
- [Groww Pricing](https://groww.in/pricing)
- [Groww Help: Where to see fees charged](https://groww.in/help/payments-%26-withdrawals/payments-charges/where-can-i-see-the-fees-i-ve-been-charged--43)

## Project Deliverables
- Weekly Product Pulse
- Google Docs update evidence
- Email draft or approval evidence
- Sample customer reviews CSV
- Source list

## Known Limitations
The workflow may intermittently fail to complete both the Google Docs update and Gmail action in the same run. Check each step's execution status before relying on the outputs.

## Sources
See the accompanying source list for the URLs used in the project.
