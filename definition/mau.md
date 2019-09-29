---
layout: post
title: MAU (Monthly active user)
---

### Definition

MAU is an abbreviation for "Monthly Active User". This metric is used to describe the population of users on a service. If a user comes to a service one day a month, they would be considered a MAU. If a user comes several times during a month or even every day of a month, their status as a MAU remains unchanged. When looking for a more frequent measure of user activity [DAUs](/definition/dau) or [WAUs](/definition/wau) can be monitored.

### Practical use
*This definition won't go through the basics of what an active user count is check out [DAU](/definition/dau) (Daily Active Users) for more information on this*

MAU is usually the largest measurement of a user's activity. For less seldom used apps MAU could make sense to monitor but many companies also use it as a public reporting metric. For example Facebook often reports on their total MAU count to give investors a view into how they are growing. This metric is often favored for this purpose since it won't show as large of swings as [DAUs](/definition/dau) or [WAUs](/definition/wau). For example if one time event occurred towards the end of a financial reporting period it could significantly drop a shorter term metric. On the other hand because MAU is an accumulation of all users who came for one month it will be more insulated from such one off changes.

### Formulas

    # Raw volume metrics
    Authenticated MAUs = Unique sessions with an authenticated token over the course of a month
    Unauthenticated MAUs = Unique sessions with no authentication token detected over the course of a month

    # Relative metrics
    Authenticated MAUs / Total registered users = % of users who use the site monthly
