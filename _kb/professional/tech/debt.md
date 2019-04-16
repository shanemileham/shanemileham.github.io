---
title: Tech Debt
---

## Definitions
- Debt = something that needs to be paid off before making forward progress (or costs interest if you keep it)
- Internal tech debt = debt created in the building of tech
- External tech debt = debt that tech has to pay for created by the decisions of other teams

### Example of internal tech debt
Engineering cuts corners to deliver something, so for the next feature, they need to go back and fix before they can move forward.


### Example of external tech debt
Non tech team makes decision to get something quickly. Tech then has to pay that debt before being able to move at full speed.

Specific example: A team decides to use a google sheet for data instead of a DB. Pros here is that the result is very quick and easy to use. Debt here is that it adds 30-60% cost to the tech team because in addition to building, now tech needs to migrate not only the data but update every connection from that sheet (much more difficult). This migration tax will continually need to be paid as long as tech is not centralized.


### Tradeoffs
Debt is fine, as long as it's done responsibly. It's tradeoffs at the end of the day.

It's crucial to bring in tech to be aware of any data/tech created so that teams can minimize the migration/etc debt when it needs to be centralized.


## So what?
Paying interest on debt is never fun for anyone (not to mention it can be financially irresponsible). If you have too much of it, you end up only paying debt. Luckily we've hit escape velocity and we're now making forward progress while paying debt. So going forward we're going to take on debt responsibly.

## What can I do to help?
Glad you asked! Let us know any tech or data that you currently have, and definitely notify us for any future tech you want to add (whether bought or built) as this will give us a chance to configure a setup in a way that minimizes debt!

Actions you take can create external tech debt even if you didn't intend it, so if in doubt, just reach out and we'll figure out a solution that optimizes speed for you while accumulating minimal debt. And that will get you faster products in the future! #team
