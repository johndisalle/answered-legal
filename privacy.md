---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Last updated: April 22, 2026**

This Privacy Policy describes how Answered ("we," "us," or "our") collects, uses, and protects information when you use the Answered mobile application. Answered is operated by John DiSalle, a Wisconsin resident doing business as Answered.

We take privacy seriously because the documents you upload — summonses, complaints, contracts, financial records — are some of the most sensitive information a person handles. This policy is written to be readable in plain English, not lawyer jargon.

## What we collect

**Documents you upload.** When you scan or import court papers, the photos and extracted text are stored so the app can process them, show them back to you, and generate documents for you.

**Case data.** The structured information the app extracts from your documents — case number, court, parties, dates, amounts — is stored alongside the documents it was extracted from.

**Anonymous account identifier.** When you open the app, we create an anonymous account for you. This is a random identifier. We do not ask for your name, email, phone, or any other identifying information to use the app.

**Purchase records.** If you purchase Answered Pro, Apple handles the transaction. We receive a confirmation that the purchase occurred, but we do not see or store your payment card details. Apple's own privacy policy governs how they handle your payment information.

**Basic technical data.** Like almost all apps, we log technical information that helps us fix crashes and security issues — device type, operating system version, app version, and generic error messages. We do not log the contents of your documents in these technical logs.

**Mail Filing Service data.** If you purchase the Mail Filing Service (described in our [Terms of Service](https://johndisalle.github.io/answered-legal/terms) Section 5), we additionally collect and store:

- Your **hand-drawn signature** as an image, which you draw on screen during the service wizard. We store this so we can print it on the Answer and the Certificate of Service. A non-identifying audit record -- device model, OS version, and timestamp -- is stored alongside the signature.
- Your **defendant name** as it appears on your case, so we can prepare the Certificate of Service and the mailing label.
- The **court's mailing address** and the **plaintiff's attorney mailing address** for your case, as confirmed by you in the wizard. These are addresses of third parties (court clerks and law firms) and are generally available in public records.
- The **text of your generated Answer document** at the moment of purchase, so we have a stable record of what was printed and mailed.
- Your **four consent acknowledgments** (not a law firm, responsible for content, delivery not guaranteed, deadline buffer) with the timestamps you tapped each.
- USPS **tracking numbers** assigned when the packet is mailed.
- Payment confirmation from RevenueCat tied to your anonymous account.

## What we do not collect

- Your email or phone number (unless you email us for support)
- Your Social Security number, date of birth, or government IDs
- Your location
- Your contacts, photos outside of what you upload, calendar, or other device data
- Your browsing or usage data outside the app

**Note on names and mailing addresses:** If you use the free features of the app, we do not collect your name or physical address. If you purchase the Mail Filing Service, we collect your name (as it appears on the Answer) and the mailing addresses needed to fulfill the service. See the Mail Filing Service section above.

## How we store and protect your data

Your documents and case data are stored on two systems:

1. **On your device**, cached locally so the app is fast and works when you're offline.
2. **On our servers**, hosted by [Supabase](https://supabase.com/privacy), which provides our database and file storage. Supabase stores data on infrastructure provided by Amazon Web Services in the United States. Files are encrypted at rest by the storage provider, and data in transit is encrypted using industry-standard TLS.

Access is restricted by row-level security: the app's database is configured so that documents and case data tied to your anonymous account are only accessible when a request comes from your authenticated session. For free users of the app, we -- the operator -- do not routinely view individual user data.

**Exception for the Mail Filing Service.** If you purchase the Mail Filing Service, the operator accesses your Answer document, your signature, and the mailing addresses you confirmed, in order to print and mail the packet on your behalf. This access is limited to the information needed to fulfill the service and is logged internally.

Signatures are stored in a private storage bucket and retrieved only via short-lived signed URLs for the purpose of producing the printed packet.

## How we use AI on your documents

Answered uses Anthropic's Claude models, accessed through Anthropic's API, to read the text in your uploaded documents and to help draft your Answer. When the app sends your document text to Anthropic for processing:

- Anthropic processes the text only to return the result the app needs (extracted facts, identified defenses, draft language).
- **Anthropic does not use API inputs or outputs to train its models.** This is a contractual commitment documented in [Anthropic's API Privacy Policy](https://www.anthropic.com/legal/privacy).
- Anthropic retains API inputs and outputs only for a limited operational period as described in their policy, then deletes them.

We do not use your documents to train our own AI models. We do not send your documents to any AI provider other than Anthropic for the processing described above.

## How we share your data

**We do not sell your data.** We do not share your documents or case data with any third party for advertising, marketing, or any similar purpose.

We share data with the following categories of third parties:

**Service providers we rely on to run the app:**

- **Supabase** -- database and file storage
- **Anthropic** -- AI processing as described above
- **Apple** -- handles in-app purchases and crash reporting where you opt in
- **RevenueCat** -- manages subscription status and entitlements tied to your anonymous account

**Courts and plaintiff's attorneys -- only if you purchase the Mail Filing Service.** When you purchase the Mail Filing Service, you instruct us to physically mail your Answer, your hand-drawn signature, your Certificate of Service, and your name to (a) the court clerk and (b) the plaintiff's attorney of record in your case. This disclosure is the entire purpose of the service. We do not make this disclosure for any user who has not purchased the service, and we mail only to the addresses you confirm in the wizard.

**Legal process.** If we are required to disclose data in response to a lawful court order, subpoena, or other legal process, we will do so, and we will attempt to notify you before disclosure where lawful and practical.

## How long we keep your data

**Case data and documents** that you upload are retained while your account exists. If you delete the app and do not request account deletion, the data remains on our servers until you make that request. Deletion requests are processed within 30 days.

**Mail Filing Service records** -- including the order record, your signature, the text of the mailed Answer, the tracking numbers, and the acknowledgment timestamps -- are retained for **seven (7) years** from the date of mailing. This retention period exists because a Certificate of Service is a legal record that may be relevant to malpractice claims, statute-of-limitations challenges, and court-records inquiries for years after the underlying case closes. You may request earlier deletion, but we may decline or partially limit deletion of Mail Filing Service records in order to preserve our own legal records of the service we performed.

**Technical and crash logs** are retained for 90 days.

## Your choices and rights

**Delete the app.** Uninstalling the app from your device removes the local cache. Data associated with your account on our servers persists unless you request deletion.

**Request deletion.** To request deletion of all data associated with your account, email [support@ellasid.com](mailto:support@ellasid.com) from any address and describe the request. We will process deletion within 30 days and confirm when complete.

**Request a copy of your data.** Email [support@ellasid.com](mailto:support@ellasid.com) to request a copy of the data we have about you. We will provide it in a readable format within 30 days.

## Children

Answered is intended for adults (18+) who have been sued. We do not knowingly collect data from children under 18. If you believe a minor has used the app, email [support@ellasid.com](mailto:support@ellasid.com) and we will delete the data.

## Changes to this policy

If we materially change how we collect or use your data, we will update this policy and the "Last updated" date above. For significant changes, we will also notify you through the app.

## Contact

For privacy questions, email [support@ellasid.com](mailto:support@ellasid.com).

---

John DiSalle, doing business as Answered
Eau Claire, Wisconsin
