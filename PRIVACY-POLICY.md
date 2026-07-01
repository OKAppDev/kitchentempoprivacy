# Kitchen Tempo — Privacy Policy

**Effective date:** [July 01, 2026]

Kitchen Tempo is a dinner-planning app made by OKAppDevelopment. This policy
explains, in plain language, exactly what happens to your information when you use
the app. We've tried to write it the way we built the app: honestly, and with as
little collection of your data as possible.

The short version: your data stays on your device, there are no accounts, and the
only time anything leaves your phone is when *you* choose to import a recipe.

---

## The short version

- Your recipes, your planned meal, and your settings are stored **only on your
  device**. We keep no copy.
- There are **no accounts and no login**. We don't know who you are.
- We use **no analytics, no advertising, no crash reporting, and no tracking** of
  any kind.
- The **only** information that leaves your device is a recipe you ask the app to
  import — a link, pasted text, or a photo — which is sent to our processing
  service ("the engine") and to our AI provider, Anthropic, to read the recipe for
  you.
- We don't sell or share your information. We can't — we don't collect it in the
  first place.

---

## What's stored on your device

Everything you create in Kitchen Tempo lives in your device's local storage:

- **Saved recipes** you've added or imported.
- **Your current meal** — the dishes you've selected and your serving time.
- **Your settings** — such as whether example recipes are hidden.
- **An anonymous device key** (explained below).

None of this is sent to us or stored on our servers. We have no database of users
and no copy of your recipes. If you uninstall the app, or use **Delete all my
data** in Settings, it's gone.

---

## What leaves your device — and only when you import a recipe

Kitchen Tempo does its scheduling on your device. Information is sent off your
device **only** when you actively import a recipe, and only the specific thing
you're importing:

- **Import by link:** the web address you provide is sent to our engine, which
  fetches that public web page and passes its text to Anthropic to extract the
  recipe. (This means the recipe website sees a request from our engine, not from
  your device.)
- **Import by text:** the text you paste is sent to our engine and on to Anthropic
  to extract the recipe.
- **Import by photo:** the image is sent to our engine and to Anthropic to read
  the recipe. The photo is handled **in memory only**, for the moment it takes to
  read it — it is **never written to disk, never saved, and never logged**, on
  your device or on our engine. Only the resulting text recipe is kept, and it
  stays on your device.

In every case, what comes back and is stored is just the structured recipe
(ingredients and steps as text) — on your device.

Two other pieces of information are involved in making a request over the internet:

- **Your anonymous device key** (see below), sent with import and scheduling
  requests.
- **Your device's IP address** — as with any app that connects to the internet,
  our engine necessarily sees it. We use it only transiently to apply fair-use
  rate limits and prevent abuse. We don't store it alongside your recipes or use
  it to identify you.

---

## Our AI provider: Anthropic

To read recipes, our engine uses **Anthropic's Claude AI**. When you import a
recipe, the content being imported — the page text, your pasted text, or your
photo — is sent to Anthropic **solely** to extract the recipe into a structured
format.

- Anthropic **does not use this content to train its AI models.**
- Anthropic may **retain the content for a limited period** for safety and
  abuse-monitoring purposes. At the time this policy was written, that is up to
  approximately 30 days. For the current details, please see Anthropic's privacy
  policy at <https://www.anthropic.com/legal/privacy>.

We've deliberately limited what the AI is allowed to do: it can only ever return a
recipe, or report that the input isn't a recipe. It can't be used as a
general-purpose assistant on your data.

---

## What our engine records

Our engine keeps only **minimal operational logs** needed to run the service and
keep it secure — for example, which type of request was made, whether it
succeeded, and timing information. These logs are designed **not** to contain your
recipe text, the links you import, your photos, or the contents of what you send.
We deliberately avoid logging the content you provide.

---

## The anonymous device key

The first time you run the app, it generates a **random identifier** and stores it
on your device. This identifier is a string of characters that is **not linked to
your name, email, or any personal detail** — it's just a random value.

It is sent with import and scheduling requests so our engine can apply fair-use
limits and prevent abuse (for example, stopping one device from overwhelming the
service). It tells us nothing about who you are. You can reset it at any time with
**Delete all my data** in Settings, which generates a new one.

---

## Permissions the app uses

- **Camera** — only if you choose to import a recipe by photo. Kitchen Tempo uses
  your device's built-in camera app to take the picture, so the app itself doesn't
  access the camera hardware directly. The photo is used only for that import and
  is not saved by the app.
- **Notifications** — so the app can send you cooking-timer alerts (for example,
  "take the chicken out of the oven"). These are scheduled and delivered entirely
  on your device; no information leaves your phone to make them work.

---

## What we don't do

To be completely clear, Kitchen Tempo does **not**:

- Require an account, email, or login.
- Include any analytics, advertising, or crash-reporting services.
- Track you across apps or websites, or build a profile of you.
- Collect your location, contacts, or other device data.
- Sell, rent, or share your information with anyone for marketing.

---

## Deleting your data

Because your data lives on your device, you control deleting it:

- Use **Delete all my data** in the app's Settings to immediately erase your saved
  recipes, current meal, and settings, and to reset your anonymous device key.
- Or uninstall the app to remove everything.

We have no server-side copy to delete, because we never made one. Note that recipe
content you previously imported may still be briefly retained by Anthropic under
their policy, as described above — that retention is outside our control, but it is
not linked to your identity.

---

## Your choices and rights

Since your information stays on your device and we hold no account for you, you can
view and delete your data directly in the app at any time, and you decide what (if
anything) you import. Because we don't collect personal information about you,
there's no personal profile to request from us. For the recipe content processed
by Anthropic, please refer to Anthropic's privacy policy linked above.

---

## Security

We protect your information by holding as little of it as possible, and by:

- **Keeping your data on your device**, rather than in a central server database
  that could be breached.
- **Encrypting data in transit** — all communication with our engine uses HTTPS.
- **Hardening our engine** against common web attacks.

No system is perfectly secure, but because we collect and store so little, there is
very little that could be exposed.

---

## Children's privacy

Kitchen Tempo is a general-audience cooking tool and is not directed at children
under 13 (or the equivalent minimum age in your country). We do not knowingly
collect personal information from children — and, in fact, we don't collect
personal information from anyone.

---

## Changes to this policy

If we change this policy, we'll update the effective date at the top, and for
significant changes we'll note it in the app or its store listing. Because we don't
have your contact information, please check back here for the current version.

---

## Contact

Questions about this policy or your privacy? Email us at
**OKAppDevelopment@proton.me**.
