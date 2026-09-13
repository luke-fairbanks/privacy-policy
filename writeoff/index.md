---
title: WriteOff Privacy Policy
---

# WriteOff privacy policy

Last updated: September 13, 2026

WriteOff: Deduction Scanner ("WriteOff") is operated by Faba Development LLC
("we," "us"). This notice describes what the app actually does with your
information. The short version: your records stay on your phone; the photos,
receipt text and questions you submit are sent to our server and to an AI
provider only to be identified or read, are not stored by us, and are not used
to train models; and the app sends no analytics.

## What WriteOff does

WriteOff helps self-employed people in the United States work out whether an
expense may be a federal income-tax deduction, and keep the records for it. It
provides educational guidance and record organization. It is not tax advice,
not a tax preparer and not a substitute for a CPA, enrolled agent or tax
attorney. See the Terms of Use for the full statement.

## Information you provide

- **Business profile.** Your occupation, how your business is set up (for
  example sole proprietor or single-member LLC), your state, an optional
  description and start year. We never ask for a Social Security number,
  Employer Identification Number, bank or card details, or a copy of a tax
  return.
- **Expense checks.** Photos you take or choose, text recognized from
  receipts, questions you type, and the answers you give to follow-up
  questions (amounts, dates, percentages, choices).
- **Saved records.** The expenses you choose to save, with any photo,
  receipt image, business-purpose note and notes you add.

## What leaves your phone, and where it goes

**To identify a photo,** the photo is sent over an encrypted connection to
our server and from there to Google's Gemini API, together with your
occupation and the tax year. Before upload the app re-encodes the image at a
reduced size, which removes camera metadata such as location. The provider
returns a description and category; our server discards the photo once the
request completes. We do not keep photos on our server.

**To read a typed question,** the text is sent the same way. **To read a
receipt,** the app recognizes the text on your phone using Apple's on-device
text recognition; only the recognized lines are sent, not the image.

**To assess an expense,** the item, category, tax year, your answers and your
business profile are sent to our server, where a rules engine produces the
assessment from published IRS guidance. No AI model is involved in that
decision and nothing is stored.

**For optional AI explanations and wording suggestions** ("Ask Follow-Up"
and "Suggest wording"), the assessment and your question are sent to the AI
provider; the response is labeled as AI-generated in the app.

**Who receives it.** Two parties: our server, which relays the request, and
Google, which processes it under the
[Gemini API Terms of Service](https://ai.google.dev/gemini-api/terms). We use
Google's paid API. Under its terms Google does not use content sent through
the paid API to train its models, and may retain it for a limited period for
abuse detection and legal compliance. We do not send your name or any
identifier that would let Google link requests to you. The provider is named
in the app before your first check and on the "Your data" screen; if it ever
changes, this policy and those screens change first.

**Your consent.** The app asks for your explicit agreement before anything is
sent, and explains it again in Settings. You can decline, and you can still
save records by entering them yourself.

Our server is hosted on Cloudflare. Our logs record request counts, timings
and error codes; they never record photos, receipt text, questions, amounts,
merchants or assessment contents.

## Usage counts

To apply the free allowance and prevent abuse, our server keeps counters: how
many checks an anonymous, app-generated identifier has used, and, for free
checks, how many came from a network address that day. These are numbers,
not content. They are not linked to your name or Apple Account.

## What stays on your phone

Saved records, photos, receipt images, business purposes, notes and your
business profile are stored in the app's private storage on your device,
protected with your device passcode (iOS data protection) and included in
your device backups if you have backups enabled. WriteOff has no user
accounts and no cloud storage of records. If you delete a record, or the
app, it is gone; we hold no copy.

## Purchases

Subscriptions are processed by Apple. We use RevenueCat to validate purchases
and manage access. RevenueCat receives the receipt Apple issues and a random
app-specific identifier; it does not receive your name, email or any content
from the app. The same random identifier is what our server uses to count
free checks.

## Analytics

This version of WriteOff sends no usage analytics and does not track you
across other companies' apps or websites. If analytics are added in a future
version, this policy will say so before that version ships, and events will
never include photos, receipt contents, amounts, merchants, business names,
questions or notes.

## Crash reports

If you have opted into sharing analytics with app developers in iOS
Settings, Apple provides us with crash logs. These do not include your
records.

## Permissions

- **Camera** is requested only when you choose to scan an item or receipt.
- **Photos** are provided through the system photo picker; WriteOff only
  receives the photos you select and never has access to your library.

WriteOff does not request location, contacts, the microphone or
notifications.

## Children

WriteOff is not directed at children under 13 and does not knowingly collect
information from them.

## Your choices and deleting your data

- Delete any record from within the app; its photo and receipt are removed
  with it.
- Settings › "Delete all records and profile" removes everything the app
  stored on your phone.
- Deleting the app removes all of its data.
- Because we keep no copy of your records, photos or questions on our
  servers, there is nothing further for us to delete. The free-check
  counters are anonymous; you may nonetheless ask us to clear them at the
  address below.

## Changes

If this policy changes, the new version will be posted at this address with a
new date, and material changes will be shown in the app.

## Contact

Faba Development LLC —
[luke_fairbanks@icloud.com](mailto:luke_fairbanks@icloud.com). Include
"WriteOff" in the subject. Do not send passwords, payment details or tax
identification numbers.
