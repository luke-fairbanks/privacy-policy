---
title: Mane Privacy Policy
---

# Mane privacy notice

Last updated: September 9, 2026


Mane is a hairstyle try-on app made by Faba Development LLC. This notice explains what happens to your photos and the little other data the app handles. It is written to match what the app actually does; if the app changes, this page changes with it.

## Your photos

**What is sent.** To create a preview, the app sends the photo you chose (and, if you add one, a reference photo of a haircut) to our server, which forwards it to Google's Gemini image model. The model edits the hair and returns a new image. Before the photo leaves your device, the app crops it to the frame you see on screen and reduces it to at most 1024 pixels on its longest side.

**Who receives it.** Two parties: our server, which relays the request, and Google, which processes the image under the [Gemini API Terms of Service](https://ai.google.dev/gemini-api/terms). We use Google's paid API. Under its terms Google does not use content sent through the paid API to train its models, and may retain it for a limited period for abuse detection and legal compliance.

**What we keep.** Nothing. Our server does not store your photos or the generated images; it holds them in memory only for the duration of the request. Your photos and every look you create are saved on your device alone, in the app's private storage.

**Your consent.** The app asks for your explicit agreement before the first preview, and explains this again in Settings. You can decline, in which case no photo is sent.

**Deleting.** Delete any look from History, or everything from Settings → Delete all looks. Deleting the app removes all of it. Because we hold no copy, there is nothing further to request from us.

## Purchases

Mane Pro is sold through Apple's In-App Purchase. We use RevenueCat to check whether a subscription is active. RevenueCat receives your purchase history and an anonymous, app-generated identifier; it does not receive your name, email or Apple ID. Our server asks RevenueCat about that identifier before creating a preview, so that free allowances and Pro access are applied correctly. See [RevenueCat's privacy policy](https://www.revenuecat.com/privacy).

## Usage counts

To enforce the free allowance and protect against abuse, our server keeps counters keyed by the anonymous purchase identifier and, for free previews, by network address for the current day. These are numbers, not images or personal details.

## Analytics

If a build includes analytics, the app records product events such as "preview started", "style selected" and "purchase completed" under a random identifier, using PostHog. Events never include your photos, your descriptions, or anything that identifies you. Builds that ship without an analytics key send nothing. *(Update this paragraph when a build ships with analytics enabled.)*

## Permissions

- **Camera** — only when you tap "Take a selfie".
- **Photos** — choosing a photo uses the system picker, which shares only the image you select. Saving a look asks for add-only access to your library; the app never reads it.

No location, contacts, microphone or tracking permissions are requested. Mane does not use the advertising identifier and does not track you across apps or websites.

## Children

Mane is not directed at children under 13, and we do not knowingly collect information from them.

## Changes and contact

Changes to this notice are posted here with a new effective date. Questions: lukedfairbanks@gmail.com.
