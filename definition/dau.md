---
layout: post
title: DAU (Daily active user)
---

### Definition

DAU is an abbreviation for "Daily Active User". This metric is typically used for understanding how often users return to a service. When a user comes to a service everyday they would be considered a DAU. If the same user comes only once in a week they are a DAU just the day they visited. They would also be considered a [WAU](/definition/wau/) or weekly active user for that week.

### Practical use
DAU is fundamental metric that is used by small and large teams. It is tracked to understand how many unique users are coming daily. If DAUs suddenly decrease/increase this could severely affect a company's bottomline. **Monitoring this metric is crucial** to understanding business health and growth. Although don't be fooled by a sequence of low volume days. DAUs are typically effected by cyclical events like holidays, natural disasters or even a particular night of the week. One way to account for such events is to look at historical data. Year over year data is particularly helpful since holidays or seasonal events can be matched up.

How is it measured? Depending on what a practitioner is looking for they might attribute each unique session as a DAU. Another major decision in DAU accounting is whether or not to exclude [unauthenticated users](/definition/unauthenticated-users/). Some services only focus on users who have signed up and have an authenticated session token. This typically occurs when a company is only monetizing authenticated users. For example a service like Facebook only shows ads to active authenticated users. They mostly likely focus on measuring authenticated DAUs. Some companies like Reddit show advertisements to all users. So unauthenticated users are probably an important piece of DAUs for their team.

### Formulas

    # Raw volume metrics
    Authenticated DAUs = Unique sessions with an authenticated token on a specific day
    Unauthenticated DAUs = Unique sessions with no authentication token detected on a specific day

    # Relative metrics
    Authenticated DAUs / Total registered users = % of users who use the site daily
