---
title: NextStop Privacy Policy
---

# NextStop privacy policy

Last updated: July 12, 2026

NextStop is a route-planning, navigation, trip-sharing, and subscription app operated by Faba Development / Luke Fairbanks ("we," "us").

## Information handled

Depending on the features you use, NextStop handles:

- account identifiers, email address, display name, authentication provider, optional profile image, account timestamps, and subscription status;
- trip titles and descriptions, stop names and addresses, place IDs, notes, route order, distance, duration, route geometry, status, and arrival/departure timestamps;
- precise foreground location while you use active navigation, including route progress and current stop;
- friend requests, friendship records, sharing recipients, viewer activity, and shared route/location progress;
- an Expo push token and notification content such as names, trip titles, route identifiers, and friend activity;
- purchase and entitlement information, including subscription product, renewal/expiration status, and purchase history; and
- local app settings, guest trips, authentication state, map caches, and related device storage.

The app does not access your device address book. Current code requests foreground location for navigation; it does not intentionally run continuous background-location tracking.

## How information is used

We use this information to create accounts, build and optimize routes, provide navigation, save and synchronize trips, share routes with recipients you choose, show live route progress, manage friends and notifications, process subscriptions, prevent abuse, troubleshoot failures, and respond to privacy requests.

## Sharing and service providers

When you enable route sharing, selected friends or people with a share link can see trip stops, addresses, route progress, and current location. Do not share a link with someone who should not have that access.

NextStop uses service providers including:

- **Google Firebase** for authentication, database, and file storage;
- **Apple Maps/Core Location** and **Google Maps, Places, Directions, and Geocoding** for location search, geocoding, maps, routes, and navigation;
- **Mapbox** for route optimization;
- **Expo Push Service, Apple Push Notification service, and Firebase Cloud Messaging** for notifications;
- **RevenueCat and the applicable app store** for purchases, entitlements, and subscription history; and
- **Apple and Google** for social sign-in and platform services.

The currently released build also contains Meta/Facebook SDK components even though Facebook sign-in is unfinished. Those components are being removed; until an updated build is installed, Meta's SDK may process automatic app events according to its configuration and policies.

## Location and route sharing

During active navigation, the app can update precise location approximately as movement or time thresholds are met. Current code can upload active-route location even when a separate sharing toggle is not enabled so that route progress works. If sharing is enabled, recipients can view that progress. Shared routes are displayed as expiring after 24 hours, but the current service does not guarantee automatic deletion of the underlying route or viewer records after that period.

## Notifications and purchases

If notifications are enabled, an installation-specific push token and notification payload are processed through Expo and Apple or Google. Notification text may appear on a lock screen. RevenueCat receives an account-linked user identifier and purchase/entitlement history to provide subscriptions. Deleting an account does not itself cancel an app-store subscription; subscriptions must be managed through the applicable store.

## Retention and deletion

Account, profile, signed-in trip, friendship, sharing, active-route, notification, and related records remain until deleted through an available control, removed in response to a verified request, or removed under an operational retention process. Guest trips and local settings remain on the device until cleared or the app is uninstalled. Mapping caches generally expire between about 30 minutes and 24 hours. Providers and app stores retain records under their own requirements.

The current in-app Delete Account flow attempts to delete major account records but may not remove every nested viewer record, friend request, notification, profile image, local cache, or RevenueCat record, and it can fail when recent reauthentication is required. A hardened deletion flow is being prepared. Until it is released, email us for a complete deletion request. We may need to verify account ownership. Do not send passwords, location history, or payment details by email.

## Security and choices

You can decline location or notification permission, use guest mode for local trips, limit sharing recipients, revoke a shared link by stopping sharing where available, sign out, clear local data, and manage subscriptions in the app store. Some features will not work without the relevant permission or account data.

We use platform authentication, Firebase rules, encrypted network transport, and provider controls. No system can guarantee absolute security. Public mobile-client identifiers do not provide authorization; server-side rules and provider restrictions are required and are under continuing review.

## Children

NextStop's current store age rating allows a general audience, but the service handles accounts, precise location, and social sharing and does not currently implement age verification or parental consent. Children should use the service only with a parent or guardian's involvement where required. A parent or guardian can contact us to request access or deletion.

## Changes and contact

Material changes will be posted here with a new update date. Questions and privacy requests can be sent to [luke_fairbanks@icloud.com](mailto:luke_fairbanks@icloud.com).

[Back to all policies](../)
