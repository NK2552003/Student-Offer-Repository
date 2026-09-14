# Billing Safety for Free Trials and Credits

“Free for students” does not always mean “no billing risk.” Use this checklist before activating anything.

## Risk levels

| Risk | Pattern | What to do |
| --- | --- | --- |
| Low | No card; automatically downgrades or stops | Still export data and note the expiry date |
| Medium | Card required; fixed subscription trial | Cancel auto-renew immediately if the provider preserves trial access after cancellation |
| High | Usage-based cloud/API account with a card | Add budgets and alerts, cap usage, and delete resources before credit expiry |

## Before clicking “Start trial”

- Read the renewal price and billing interval.
- Check whether cancelling ends access immediately or at the end of the free period.
- Check tax and currency conversion, especially for India-issued cards.
- Confirm whether unused credits expire.
- Check whether usage above the included credit is blocked or billed.
- Screenshot the final checkout and cancellation instructions.

## Cloud-specific checklist

1. Create a zero- or low-value budget alert on day one.
2. Disable paid features you do not need.
3. Stop and delete compute instances, databases, disks, snapshots, static IPs, and load balancers after use.
4. Check the billing dashboard after deletion; stopped resources can still retain billable storage.
5. Remove the payment method only if the provider permits it and doing so will not break needed resources.

## Reminder schedule

- At activation: record trial end and credit expiry.
- 30 days before: decide whether to keep, export, or migrate.
- 7 days before: cancel renewal or downgrade.
- 1 day before: verify the account shows the expected next plan and price.
- 2 days after: check the billing page and card statement.

## Known examples from this catalog

- Google AI student plans require a valid payment method and automatically charge the standard price after 12 months unless cancelled.
- Apple Music and YouTube Premium are subscriptions that continue after their introductory trial.
- Cloudflare Students requires a card. The base plan reverts to Free after the waiver, but usage above included allowances can still cost money.
- Azure for Students does not require a card, which substantially reduces accidental-billing risk until the user explicitly upgrades.
