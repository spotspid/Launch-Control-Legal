# Privacy Policy

**Effective Date:** June 7, 2026

**Data Controller:** Elevate Growth Systems, operated by Melillo & Smith Holdings ("we," "us," or "our")

## 1. Scope

This Privacy Policy describes how Launch Control ("the Service") handles data when connected to a Jobber account belonging to a Home Service Experts client. It applies only to data the Service receives through its Jobber integration.

## 2. Data We Receive from Jobber

When connected to your Jobber account, the Service receives webhook payloads from Jobber containing:

- Job lifecycle events (job closed)
- Quote lifecycle events (quote sent, quote approved)
- Client identifiers associated with those events
- Metadata such as job titles, quote amounts, occurrence timestamps, and account identifiers
- Account-level events such as app disconnect

We do not request or store payment card data, full client contact records beyond what is included in webhook payloads, or any data outside the scopes you authorized during OAuth.

The OAuth scopes we request are: `read_clients`, `read_quotes`, `read_jobs`, `read_scheduled_items`, `read_invoices`, `read_jobber_payments`, and `read_users`. These scopes are required to enrich webhook events with the data needed for downstream automation.

## 3. How We Use Data

Received webhook data is processed and forwarded in real time to the GoHighLevel sub-account associated with your Home Service Experts engagement. The forwarded payload contains:

- The event type (job completed, quote sent, or quote approved)
- The associated Jobber client identifier
- The associated Jobber item identifier
- The Jobber account identifier
- Event timestamp
- Item title and amount where applicable

Forwarding events to your designated GoHighLevel sub-account is the sole purpose for which we process this data. We do not sell, rent, or share Jobber data with any third party other than the GoHighLevel destination you designated.

## 4. Data Retention

Webhook payloads are processed in transit and not persisted in long-term storage. OAuth credentials (access tokens and refresh tokens) are stored encrypted at rest until you disconnect the Service from Jobber, at which point they are deleted within seconds of receipt of the disconnect event.

## 5. Security

- Inbound webhooks from Jobber are verified via HMAC-SHA256 signature against our app's client secret before processing. Unsigned or tampered requests are rejected.
- All data transmission between the Service, Jobber, and GoHighLevel occurs over HTTPS.
- OAuth credentials are stored in a managed Supabase database with row-level security enabled.
- Access to the underlying infrastructure is restricted to authorized Elevate Growth Systems personnel.

## 6. Your Rights

At any time you may:

- Disconnect the Service from your Jobber account through Jobber's app management interface. Disconnection triggers immediate deletion of all stored OAuth credentials.
- Request information about what data we hold associated with your account by contacting us at the email below.
- Request deletion of any retained data associated with your account.

If you reside in the European Economic Area, the United Kingdom, or California, you have additional rights under GDPR or CCPA, including the right to access, rectify, port, or restrict processing of your personal data. Contact us to exercise these rights.

## 7. Subprocessors

We use the following subprocessors to deliver the Service:

- **Supabase** — Database and edge function hosting
- **Vercel** — Frontend application hosting
- **GoHighLevel** — Destination platform for forwarded events

Each subprocessor is bound by their own privacy and security commitments. Updates to this list will be reflected here.

## 8. Children's Privacy

The Service is not directed to individuals under the age of 18 and we do not knowingly collect personal information from minors.

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be communicated by email to the address associated with your Home Service Experts account. Continued use of the Service after the effective date of any change constitutes acceptance.

## 10. Contact

For questions about this Privacy Policy, requests regarding your data, or to exercise any of your rights, contact:

**Elevate Growth Systems**
Email: contact@elevategrowthsystems.com
