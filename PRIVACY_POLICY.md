# KanriDO privacy policy

Last updated: October 14, 2026.

This is a courtesy translation of the Spanish original,
[Política de privacidad de KanriDO](POLITICA_DE_PRIVACIDAD.md). If the two versions differ, the
Spanish version prevails.

## 1. Data controller

- **Controller**: César Calabuig Llamas.
- **Contact**: kanrido.contact@gmail.com.

This policy covers **the KanriDO download page** (github.com/pinnacle1010/kanrido) and contact by
email. The application is covered separately, in section 2, because its situation is different.

## 2. What the application sends

KanriDO is a **local desktop application**. The data the user imports or enters —projects,
invoicing, hours, expenses, KPIs— is stored **encrypted on the user's own computer** and never leaves it.

There is no account, registration, license check, usage reporting or automatic error reporting. It
works without an internet connection.

It does only two things on the internet:

- **A one-time notice after it is installed.** The first time a new installation starts, it sends a
  request with no content to a service of César Calabuig Llamas hosted on Cloudflare. The service
  works out from the IP address the country it comes from, records that country and the day, and
  does not keep the IP. It is used to know how many installations there are, in which countries
  and at what pace. Updates do not send it again.
- **Check, when it starts, whether there is a new version**: it asks GitHub, where the versions are
  published, for the file that says which one is the latest. That request carries no business data
  and no identifier of the user; GitHub sees the IP address it comes from, as with any visit, and
  handles it under its own policy. The new version is only downloaded if the user asks for it.

Consequently, with regard to the data the user processes with the application, César Calabuig Llamas
**is neither the controller nor the processor**, and never receives, hosts or has access to that
data. The controller of that data is the user, who exercises their rights over it directly from the
application, without anyone else's involvement.

Backups are saved in the folder the user chooses, on their computer or in the storage service they
have set up. César Calabuig Llamas plays no part in this.

## 3. What César Calabuig Llamas processes

There is no website of its own: the download page is a GitHub repository (section 4). César Calabuig
Llamas processes only the following, and no other data:

| Data | Purpose | Legal basis (GDPR art. 6) |
|---|---|---|
| IP address of the installation notice, only to work out the country; the country and the day are kept, not the IP | Counting installations by country and by day | Legitimate interest |
| Email address and message content, if the user writes | Answering the question or the bug report | Legitimate interest / consent |

No analytics tool is used and no cookies are set. If there is ever a website of its own, this
policy will state here what data it processes before it starts processing it.

## 4. Downloads

The download is hosted on GitHub, which records downloads under its own privacy policy, over which
César Calabuig Llamas has no control:
https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement. The check
for new versions in section 2 also reaches GitHub.

## 5. Recipients

Data is not sold or transferred to third parties for commercial purposes.

The providers involved are GitHub, which hosts the download and processes the metadata of each
request under its own policy; Cloudflare, which hosts the service that counts installations and
receives the IP address of the notice in section 2; and Google (Gmail), which serves the contact
email.

## 6. International transfers

If any provider processes data outside the European Economic Area, the transfer relies on the
European Commission's **Standard Contractual Clauses** or another appropriate safeguard (GDPR,
chapter V).

## 7. Retention

Contact messages are kept for as long as the query lasts and, afterwards, for the applicable legal
periods.

The record of installations, with their country and day, is kept for as long as the application
is published. It contains no personal data.

## 8. Rights

The user may exercise the rights of **access, rectification, erasure, objection, restriction and
portability** by writing to kanrido.contact@gmail.com. They may also lodge a complaint with the
**Spanish Data Protection Agency** (AEPD, www.aepd.es).

> These rights over the business data the user keeps in the application are not exercised before
> César Calabuig Llamas, who does not have that data: they are exercised from the application
> itself, which lets the user view, export and delete it.

## 9. Security

In the application: the local database is encrypted with **SQLCipher (AES-256)**, the key is kept in
the operating system's secure store and, optionally, in a keychain protected by the user's password
that travels with the backups.

The download page, the installation notice and the check for new versions use **HTTPS**.

## 10. Changes to this policy

The current version is published at
https://github.com/pinnacle1010/kanrido/blob/main/PRIVACY_POLICY.md, with the date of its last
update.

---
