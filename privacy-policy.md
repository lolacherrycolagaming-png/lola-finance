# Privacy Policy — Lola Finance

_Last updated: 2026-10-30 (budget suggestions added)_

Lola Finance is a private, self-hosted personal finance application operated by David De Santis for
their own household. It is not offered to the public, and no one else can sign up for or use it.

## What we collect

When the operator connects their own financial accounts through **Plaid**, Lola Finance receives:

- account names, types, masked account numbers (last 4 digits) and balances;
- bank and credit card transactions (date, amount, merchant, category);
- brokerage investment transactions and holdings.

Plaid's handling of data is described in the
[Plaid End User Privacy Policy](https://plaid.com/legal/#end-user-privacy-policy).

## How it is used

Only to show the operator their own net worth, spending and investments, to track tax lots and
wash sales, and to suggest where the household could budget and save. Budget suggestions are computed
on the same server; a small AI model that also runs on that server writes their wording. No data is sent
to any outside AI service. The data is **not sold, shared, rented or used for advertising**, and is not disclosed to
anyone except as required by law.

## Where it is stored and how it is protected

On a single server in the operator's home, not in a public cloud. Access requires the operator's
private network (Tailscale) plus a login with multi-factor authentication; all access is over HTTPS.
Backups are encrypted.

## Retention and deletion

Bank data is kept while an account is connected and deleted when it is disconnected; disconnecting
also revokes access at Plaid. Investment records are kept for up to 7 years for tax purposes.
Backups age out within about 6 months. Details: the data retention and deletion policy.

## Contact

Questions about this policy: lolacherrycolagaming@gmail.com.
