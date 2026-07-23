---
title: Gospel AI Privacy Policy
---

# Gospel AI privacy policy

Last updated: July 22, 2026

Gospel AI is operated by Faba Development / Luke Fairbanks ("we," "us"). It provides scripture and religious-content search and AI-assisted answers. Because prompts can reveal religious or philosophical beliefs, please choose carefully what you submit.

## Information handled

Depending on how you use the app, Gospel AI handles:

- account information, including Firebase user ID, email address, and a name or profile image supplied by Google sign-in;
- prompts, search queries, conversation history, AI answers, citations, settings, and optional feedback;
- subscription status and store product information (not payment-card details);
- local app state and cached conversations; and
- operational request information produced by hosting infrastructure, such as timestamps, response status, a one-way pseudonymous network identifier used for daily abuse limits, and diagnostic logs.

The app does not need precise location, contacts, photos, audio, financial information, health data, or payment-card information for its current features.

## How information is used

We use the information to authenticate accounts, provide search and AI answers, save and synchronize signed-in conversations, verify subscription access, operate and secure the service, troubleshoot failures, prevent abuse, and respond to privacy requests.

## AI data-sharing permission

Before the first AI question or search, the mobile app asks for permission to send the question and relevant recent conversation context to our AI providers. If you choose **Not now**, the request is not sent and AI search or answer generation does not begin. You can review or turn off this permission under **Settings > Privacy > AI data sharing**. If you turn it off, the app asks again before another AI request.

Questions about religion can reveal religious or philosophical beliefs. Please avoid including names, contact information, or other sensitive personal details that are not needed for your question.

## Where information goes

- **Google Firebase** provides authentication and stores signed-in conversations and account-linked app data.
- **Apple and Google** may provide sign-in services, depending on the method you choose.
- **OpenAI** receives prompts and conversation context used for intent parsing or answer generation.
- **Hugging Face inference providers** may receive search queries or query/passage pairs for embedding or reranking.
- **RevenueCat** receives an app-specific user identifier, product, entitlement, and subscription-event information used to provide and restore Pro access.
- **Apple App Store or Google Play** processes purchases and manages subscriptions. Gospel AI does not receive your full payment-card details.
- **Vercel** hosts the web client.
- **DigitalOcean and related infrastructure providers** host backend/search services and their operational logs.

Third parties handle data under their own terms and configured retention controls. OpenAI's API data controls are described at <https://developers.openai.com/api/docs/guides/your-data>. Hugging Face describes Inference Provider security at <https://huggingface.co/docs/inference-providers/security>. Firebase privacy information is at <https://firebase.google.com/support/privacy>.

## Storage and retention

Signed-in conversations are stored in Firestore under the account's Firebase ID and may also be cached on the device. Guest conversations are stored locally. Daily usage counters are retained for quota and abuse prevention. Backend and provider logs may contain request or query-derived information and are retained according to operational and provider security needs.

No single fixed retention period currently applies to every stored conversation or operational record. Information can remain until you delete available content, clear local app data, request account/data deletion, or the service removes it under its operational retention process. Providers may retain limited security or abuse-monitoring records under their own policies.

## Your choices and deletion

You can use guest mode for local conversations, avoid submitting identifying details, turn off AI data sharing, delete individual conversations, clear local app storage, and sign out.

Signed-in users can choose **Settings > Privacy > Delete account**. The in-app flow deletes saved Firestore conversations and nested messages, local conversation caches, backend account-linked usage and entitlement records, the RevenueCat customer profile, and the Firebase authentication account. For Sign in with Apple accounts, the flow also requests fresh Apple authorization and revokes the app's Apple token. Information already processed by an AI provider may remain for the limited retention or security periods described in that provider's policy.

Deleting an account does not cancel an App Store or Play Store subscription. Manage or cancel the subscription through the store's native subscription-management screen before or after deleting the Gospel AI account.

For access questions or deletion help, email us with "Gospel AI privacy request" and the account email address. Do not include your password, authentication codes, payment details, or prompts in the request.

## Security

We use platform authentication, access rules, encrypted network transport, and provider controls. No system can guarantee absolute security, and we review these controls periodically.

## Children

Gospel AI is not designed for children under 13 to create accounts or submit personal information without appropriate parent or guardian involvement. The current app does not implement age verification. A parent or guardian can contact us to request deletion.

## Changes and contact

Material changes will be posted here with a new update date. Questions and privacy requests can be sent to [luke_fairbanks@icloud.com](mailto:luke_fairbanks@icloud.com).

[Back to all policies](../)
