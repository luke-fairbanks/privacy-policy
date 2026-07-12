---
title: Gospel AI Privacy Policy
---

# Gospel AI privacy policy

Last updated: July 12, 2026

Gospel AI is operated by Faba Development / Luke Fairbanks ("we," "us"). It provides scripture and religious-content search and AI-assisted answers. Because prompts can reveal religious or philosophical beliefs, please choose carefully what you submit.

## Information handled

Depending on how you use the app, Gospel AI handles:

- account information, including Firebase user ID, email address, and a name or profile image supplied by Google sign-in;
- prompts, search queries, conversation history, AI answers, citations, settings, and optional feedback;
- local app state and cached conversations; and
- operational request information produced by hosting infrastructure, such as timestamps, response status, network information, and diagnostic logs.

The app does not need precise location, contacts, photos, audio, financial information, health data, or payment-card information for its current features.

## How information is used

We use the information to authenticate accounts, provide search and AI answers, save and synchronize signed-in conversations, operate and secure the service, troubleshoot failures, prevent abuse, and respond to privacy requests.

## Where information goes

- **Google Firebase** provides authentication and stores signed-in conversations and account-linked app data.
- **OpenAI** receives prompts and conversation context used for intent parsing or answer generation.
- **Hugging Face inference providers** may receive search queries or query/passage pairs for embedding or reranking.
- **Vercel** hosts the web client.
- **DigitalOcean and related infrastructure providers** host backend/search services and their operational logs.

Third parties handle data under their own terms and configured retention controls. OpenAI's API data controls are described at <https://developers.openai.com/api/docs/guides/your-data>. Hugging Face describes Inference Provider security at <https://huggingface.co/docs/inference-providers/security>. Firebase privacy information is at <https://firebase.google.com/support/privacy>.

## Storage and retention

Signed-in conversations are stored in Firestore under the account's Firebase ID and may also be cached on the device. Guest conversations are stored locally. Backend and provider logs can contain query-derived information; we are reducing that logging and intend to use short, security-focused retention.

No single fixed retention period currently applies to every stored conversation or operational record. Information can remain until you delete available content, clear local app data, request account/data deletion, or the service removes it under its operational retention process. Providers may retain limited security or abuse-monitoring records under their own policies.

## Your choices and deletion

You can use guest mode for local conversations, avoid submitting identifying details, delete conversations where the current app offers that control, clear local app storage, and sign out. The currently released app does not yet provide a complete in-app account-deletion workflow, and deleting a conversation parent may not remove every nested message record. To request access or complete deletion, email us with "Gospel AI privacy request" and the account email address. Do not include your password or prompts in the request.

## Security

We use platform authentication, access rules, encrypted network transport, and provider controls. No system can guarantee absolute security, and we review these controls periodically.

## Children

Gospel AI is not designed for children under 13 to create accounts or submit personal information without appropriate parent or guardian involvement. The current app does not implement age verification. A parent or guardian can contact us to request deletion.

## Changes and contact

Material changes will be posted here with a new update date. Questions and privacy requests can be sent to [luke_fairbanks@icloud.com](mailto:luke_fairbanks@icloud.com).

[Back to all policies](../)
