---
layout: post
title: Unauthenticated users (Unauth users)
---

### Definition

Unauthenticated users refer to unique visitors without an account or credentials when they use an application or product. Once a user signs up for an account applications will typically assign an authentication token to that user making them an authenticated user. This typically exists on the user's client (browser, phone, etc). Without this a user is considered unauth.  

**Examples of an unauthenticated users:**
- A customer goes to a website for the first time
- An authenticated user logs out or deletes an application and comes back to the application later
- A user on a website which doesn't support account creation

### Practical use

Unauthenticated users are typically the newest or lowest intent users on a platform. Many product teams consider this the top of their funnel or the beginning of their user's journey to activation and retention. New traffic will typically result in unauth users visiting the application which gives an opportunity to convert them into a retained user.

Many companies attempt to do everything in their power to convert unauthenticated users into authenticated users (a.k.a get them to sign up). This typically owes itself to powerful retention tactics that are only available for authenticated users (e.g without an email address an application can not send updates). With this said optimizing the conversion rate of unauth to auth users has been shown to be an effective way to grow a user base.

Some applications attempt to get around this problem by fingerprinting users in different ways to create a record of the user. These shadow account allow a product to potentially personalize their application to further increase conversion back into an authenticated user. This information typically lives in a users metadata (cookies, local storage, etc) and can map back to a persistent store on an application's server.

### Formulas

    # Raw volume metrics
    Unauthenticated DAUs = Unique sessions with no authentication token detected over the course of a day

    # Relative metrics
    Relative metrics are difficult to calculate for unauthenticated users given there is no way to guarantee the visitor is unique.
