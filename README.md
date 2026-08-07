# Sodi Support

**Sodi — Log Your Salt.** A sodium and blood pressure awareness app for iPhone
and Apple Watch, built around Siri.

This is the support page. If something is broken or confusing,
[open an issue](https://github.com/ohwhybe/sodi-support/issues) and it will be
read.

- 📄 [Privacy Policy](privacy-policy.md)

---

## Getting help

**[→ Open an issue](https://github.com/ohwhybe/sodi-support/issues/new)**

Helpful things to include:

- What you did, and what you expected instead
- Your iOS version and device (e.g. iPhone 15 Pro, iOS 26.2)
- A screenshot, if it is something you can see
- If it is a food that logged wrongly: the exact words you said or typed

Please **do not include personal health information** in a public issue — no
blood pressure readings, no medical history. A description of the bug is enough.

---

## Frequently asked

### Does my data leave my phone?

No. There is no Sodi server. Your entries stay on your device and, if you use
iCloud, sync through your own private iCloud account that only you can read.
Nothing is sent to the developer. See the [Privacy Policy](privacy-policy.md).

### Where do the sodium numbers come from?

Two places, and Sodi labels which is which on every food:

- **Packaged and Western foods** — the USDA FoodData Central database, a public
  reference dataset.
- **Singapore hawker and kopitiam dishes** — the developer's own researched
  estimates.

Both are **estimates**, which is why Sodi shows a range rather than one exact
number. A plate of char kway teow from two different stalls genuinely differs by
hundreds of milligrams, and the amount of soup or gravy you actually finish
changes the total a lot. A single confident number would be misleading, so Sodi
does not show one.

### A food I eat is missing, or matched to the wrong thing

This is the most useful thing you can report. Sodi keeps a private, on-device
note of phrases it could not match, but it cannot send them anywhere — so
telling us directly is the only way a food gets added.

Open an issue with the name you use for the dish (including how you would say
it out loud) and roughly what is in it.

### Siri did not understand me

Try the built-in phrases first — "Hey Siri, log a meal in Sodi", then say what
you ate when it asks. If Siri opens the wrong app, renaming things in the
Shortcuts app usually fixes it.

Sodi works fully without Siri. Every voice action has a tap equivalent.

### Do I need Apple Intelligence?

No. Sodi uses on-device Apple Intelligence to interpret what you say when your
iPhone supports it, and falls back to a built-in parser when it does not. Both
paths look up the same food database, so the numbers are identical either way.

### Nothing shows up in the Health app

Check that the Apple Health toggle is on in Sodi's Settings, then check Health →
Sharing → Apps → Sodi and confirm the categories are enabled. iOS asks for read
and write permission separately, and it is easy to grant one and not the other.

### How do I delete everything?

Settings → Delete All Data. That clears your entries, totals, favourites,
settings, and the samples Sodi wrote into Apple Health. It cannot be undone.

### How do I export my data?

Settings → Your Data → Export as JSON or CSV. The file goes through the normal
iOS share sheet, so you can send it wherever you like.

### Sodi Pro / restoring a purchase

Settings → Sodi Pro → Restore Purchases. Purchases are tied to your Apple
Account, so a restore works on any device signed in to the same account.
Billing, refunds, and cancellations are handled by Apple, not by Sodi —
[Apple's guide is here](https://support.apple.com/en-us/HT202039).

---

## Please read

Sodi is a tracking and awareness tool. It is **not a medical device** and does
not provide medical advice. It shows you what you logged and what patterns
appear in it — nothing more. Talk to a qualified health professional about your
own health, and never change anything about your treatment based on what an app
shows you.

