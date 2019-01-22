---
layout: post
title: Authenticated users (Auth users)
---

### Definition

Authenticated users are visitors to an application with credentials or an account of some form. This is typically denoted with some form of token placed in client side storage (browser cookies, in-app storage, etc). This token represents the users account and is persistent for some period of time. This token is typically given to a user when they sign up for a service or they login to an existing account.

**Examples of how an authenticated user is created:**
- User signs up for the first time on an application
- User logs into their account
- User clicks on an email sent to their registered email address and is given an authentication token once they land inside the application

### Practical use

Authenticated users are typically monitored on a [daily](/definition/dau/), [weekly](/definition/wau/) or monthly basis. Excluding spam and fraudulent accounts becomes more important at scale and can quickly become a large issue; especially if account creation doesn't require unique information (phone number, credit card, etc).

Given that most public consumer tech companies report to investors in terms of authenticated users the accuracy and importance of this measurement can not be overstated. This is mainly due to most monetization being predicated on a user having an account. Without an account users typically can consume content without giving any information in return like an email address or a credit card. This does not exclude [unauthenticated users](/definition/unauthenticated-users/) from being monetized but they typically have a lower LTV than their auth counter part.

### Formulas

    # Raw volume metrics
    Authenticated DAUs = Unique sessions with an authenticated token on a specific day
