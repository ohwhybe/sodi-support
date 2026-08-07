# Sodi — Privacy Policy

**Last updated: 7 August 2026**

Sodi is a sodium and blood pressure awareness app for iPhone and Apple Watch.

The short version: **Sodi does not collect your data.** There is no Sodi server.
Everything you log stays on your device and, if you have iCloud turned on, in
your own private iCloud account — which only you can read. The developer cannot
see it.

This policy explains that in detail.

---

## Who we are

Sodi is developed by an independent developer. Contact details are at the bottom
of this page.

## What Sodi stores, and where

Everything below is stored **on your device**. If iCloud is enabled on your
iPhone, it also syncs through **your own private iCloud account** (Apple's
CloudKit private database), which is encrypted and tied to your Apple Account.
The developer has no access to it, and no ability to grant anyone else access.

| What | Why | Where it goes |
|---|---|---|
| Food entries (item, portion, meal, time) | To show your daily total and history | Your device + your private iCloud |
| Daily totals | To draw the ring, widgets, and trends | Your device only |
| Your daily sodium target and app settings | To personalise the app | Your device + your private iCloud |
| Favourites and recent foods | Quick logging | Your device + your private iCloud |
| Unrecognised food phrases | So the food list can be improved over time | Your device + your private iCloud |

**Sodi does not transmit any of this to the developer or to any third party.**

## Apple Health

If you turn on the Apple Health toggle, Sodi will:

- **Write** the sodium, sugar, and calories from foods you log, plus any blood
  pressure reading you enter in Sodi, into Apple Health.
- **Read** blood pressure and heart rate from Apple Health, so it can show them
  next to the sodium you have logged.

Apple Health data is governed by your iOS privacy settings. You choose what Sodi
may read and write, and you can change or revoke that at any time in the Health
app under Sharing → Apps. Sodi never sends Health data anywhere. Blood pressure
in particular is **never stored in Sodi's own database** — Apple Health is the
only place it lives.

If you turn the toggle off, Sodi stops writing new samples. Samples already
written stay in Apple Health until you delete them there, or use Sodi's "Delete
All Data", which removes the samples Sodi created.

## Camera and photos

Sodi can scan a nutrition label or photograph a dish to help you log faster.

- Images are processed **entirely on your device** using Apple's on-device
  Vision framework.
- Photos are **not saved by Sodi**, not uploaded, and not sent to any server.
- Only the resulting text or suggestion is used, and only to prefill fields you
  then review.

Camera access is requested only when you use those features, and you can decline
or revoke it in iOS Settings without losing any other functionality.

## Siri and voice

If you log meals by voice, the request is handled by Apple's Siri and App
Intents system, and the meal is interpreted **on your device**. Apple's own
privacy policy governs Siri itself.

Sodi keeps the raw text of what you said only briefly, to help you correct a
mistaken entry — it is **automatically deleted after 30 days**.

## What Sodi does *not* do

- **No analytics.** No Firebase, no Google Analytics, no crash-reporting SDK, no
  usage tracking of any kind.
- **No advertising**, no ad identifiers, no ad networks.
- **No tracking**, as Apple defines it. Sodi does not track you across apps or
  websites, and shares nothing with data brokers.
- **No account.** There is no sign-up, no login, no email address collected.
- **No selling or sharing of personal information**, ever, to anyone.
- **No third-party servers.** Sodi makes no network calls that carry your health
  information.

## Purchases

Sodi Pro is sold through Apple's In-App Purchase. **Apple** processes the
payment — Sodi never sees, receives, or stores your payment details. Sodi only
receives Apple's confirmation of whether a subscription or purchase is active.
Apple's privacy policy governs that transaction.

## Your control over your data

- **Export** everything as JSON or CSV at any time (Settings → Your Data).
- **Delete** everything at any time (Settings → Delete All Data). This clears
  your entries, totals, favourites, settings, and the Health samples Sodi wrote.
- **Delete individual entries** at any time.
- **Turn off iCloud sync** for Sodi in iOS Settings → your name → iCloud.
- Deleting the app removes the on-device copy. Data in your private iCloud is
  removed via iOS Settings → your name → iCloud → Manage Storage.

Because the developer holds none of your data, requests to access, correct, or
delete it are handled entirely by you, using the controls above. If you need
help doing that, contact us.

## Children

Sodi is not directed at children under 13, and does not knowingly collect
information from them. Since Sodi collects no personal information at all, there
is nothing for us to hold or delete.

## Legal bases and your rights

Depending on where you live, you may have rights under the EU/UK GDPR,
Singapore's PDPA, or laws such as the CCPA — for example the right to access,
correct, delete, or port your personal data, and the right not to be
discriminated against for exercising those rights.

Sodi is designed so those rights are satisfied by design: the developer is not a
controller or processor of your health information, because it never leaves your
possession. The export and delete controls above give you direct, immediate
access and erasure. Sodi does not sell or share personal information, so there
is nothing to opt out of.

## A note on the numbers

Sodium values in Sodi are estimates. Values for packaged and generic Western
foods come from the **USDA FoodData Central** database (public domain). Values
for Singapore hawker and kopitiam dishes are the developer's own curated
estimates, shown as ranges because real portions vary a great deal between
stalls and servings. They are labelled in the app as estimates.

Sodi is a tracking and awareness tool. It is not a medical device and does not
provide medical advice. Talk to a qualified health professional about your own
health.

## Changes to this policy

If the way Sodi handles data ever changes, this page will be updated and the
"Last updated" date above will change. Meaningful changes will also be noted in
the app's release notes. If Sodi ever begins collecting anything, that will be
stated here plainly and in Apple's privacy label before it happens.

## Contact

Questions about this policy or about your data:

- Open an issue: <https://github.com/ohwhybe/sodi-support/issues>
- Email: `<!-- TODO: add the contact address you want published here -->`

<!--
  Deliberately left blank rather than filled with a personal address: this page
  is public and permanently indexable, so the address belongs to whoever
  maintains Sodi's support, not necessarily a personal inbox. App Store Connect
  requires a support URL (this repo) and separately asks for a contact email
  that is NOT shown publicly — so a personal address can go there instead of
  here if you would rather not publish one.
-->

 
