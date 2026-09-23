# DrugScan Privacy Policy

_Last updated: September 23, 2026_

DrugScan ("we", "the app") helps you look up FDA drug-label information and dietary-supplement
labels by scanning a barcode, photographing the medication name on a label, or searching by name.

## The short version

- **There are no accounts.** DrugScan does not ask you to sign in, and we never learn who you are.
- **Your saved medications and history never leave your device.**
- **Photos of labels are never uploaded or stored.** They are read on your iPhone and discarded.
- **We do not sell your data, run ads, or include any analytics or tracking SDKs.**
- The one thing that leaves your device is **the name of the medication you look up**, sent to
  retrieve its label and generate a summary.

## What stays on your device

**Saved medications, scan history, and your remaining free lookups** are stored locally in the iOS
Keychain and app storage. They are never transmitted to us and we cannot see them.

**Label photos and camera frames.** The camera reads barcodes and, in the "Scan Label" feature,
recognizes the printed medication name — including on pharmacy prescription labels that may show
your name, your prescriber, or an Rx number. **All of this image processing happens on your iPhone**
using Apple's Vision framework. The image is never uploaded and never saved. Only the medication
name extracted from it is used for the lookup, exactly as if you had typed it.

## What leaves your device

**Label lookups.** To fetch label information, the app sends the scanned code or the medication name
to public U.S. government health databases: **openFDA** and **DailyMed** (U.S. National Library of
Medicine), and the **NIH Dietary Supplement Label Database (DSLD)**. No identifier of any kind
accompanies these requests.

**Plain-language summaries.** When you open a label, the medication name and public label fields
(purpose, warnings, dosage, ingredients) are sent to our summary service, which uses **OpenAI** to
generate the summary. No account, name, device identifier, or other personal information is
included, because the app holds none. Our service does not log or store the contents of these
requests. OpenAI may retain API inputs for a limited period for abuse monitoring under its own
policies. On devices that support on-device summarization with Apple Intelligence, that processing
happens entirely on your iPhone and nothing is sent.

**Technical request data.** Our summary service is rate-limited to prevent abuse, which involves
briefly holding the requesting IP address in memory. It is not written to disk, logged, or retained.

## What we collect

Apple requires apps to declare data collection. Our single declaration is:

| Category | Purpose | Linked to you? | Used for tracking? |
|---|---|---|---|
| **Health** — the medication you look up | App functionality (retrieving the label and generating its summary) | **No** | **No** |

We consider the medication you search for to be health-related information, so we declare it even
though it reaches us without any identifier and cannot be traced back to you.

We collect **no** contact information, **no** name or email, **no** device or advertising
identifiers, **no** location, **no** usage analytics, and **no** diagnostics.

## Subscriptions

Purchases are processed by **Apple** through the App Store. Your subscription is tied to your Apple
ID, not to any account with us. We never receive or store your payment card details.

## Sharing

We do **not** sell your personal information and we do **not** share it with advertisers or data
brokers. Information is shared only with the providers needed to run the app: **Apple** (App Store
purchases), **OpenAI** (generating summaries), and the public **FDA/NIH** databases, which receive
only the code or search term needed to return label data.

## Retention & deletion

Because we hold no account and store nothing about you on our servers, there is no profile to
delete. You control all of your data directly:

- **Clear saved medications and history:** Account → Clear scan history.
- **Delete everything:** delete the app from your iPhone.

To ask a question about this policy or request information, contact us at drugscan.support@gmail.com.

## Children

DrugScan is not directed to children under 13, and we do not knowingly collect their personal data.

## Medical disclaimer

Information in DrugScan comes from public FDA (openFDA/DailyMed) and NIH (DSLD) databases; for
supplements, it is self-reported by manufacturers and may be incomplete. Label matching — especially
reading a medication name from a photo — is a best guess and can be wrong, so always confirm the
result matches the product in your hand. All content, including generated summaries, is for
informational purposes only and is **not medical advice**. Always read the product label and consult
a pharmacist or clinician.

## Changes

We may update this policy; material changes will be reflected by the "Last updated" date above.

## Contact

E & E LLC — drugscan.support@gmail.com
