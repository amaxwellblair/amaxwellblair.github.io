---
layout: post
title: WAU (Weekly active user)
---

### Definition

WAU is an abbreviation for "Weekly Active User". This metric is typically used for understanding how often users return to a service. If a user comes to a service one day a week, they would be considered a WAU. If a user comes several times during a week, their status as a WAU remains unchanged. When looking for a more frequent measure of user activity [DAUs](/definition/dau) can be monitored.

### Practical use
*This definition won't go through the basics of what an active user count is check out [DAU](/definition/dau) (Daily Active Users) for more information on this*

WAU is typically measured to understand a user's activity but with less bias then the [DAU](/definition/dau) calculation. For example an app that is used only on weekends will have an abnormally low [DAU](/definition/dau) count during the week. So monitoring WAUs is a normalized view of user count in this case.

A WAU is a common unit that many products goal metrics on. [DAUs](/definition/dau) have a fast feedback loop but they have too much variance to rely on. MAUs on the other hand are extremely stable but the feedback cycle is too long and can slow down a team. WAU being somewhere in the middle of the two has given the metric favorable mixture of both attributes (feedback speed and lower variance).

### Formulas

    # Raw volume metrics
    Authenticated WAUs = Unique sessions with an authenticated token over the course of a week
    Unauthenticated WAUs = Unique sessions with no authentication token detected over the course of a week

    # Relative metrics
    Authenticated WAUs / Total registered users = % of users who use the site weekly
