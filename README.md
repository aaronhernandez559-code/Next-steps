# Next Step

A small, phone-friendly focus app with two tools:

- **Steps**: type a big task ("clean my room") and get small steps to check off one at a time, with a quick encouraging message after each one.
  - Choose **Regular** or **Tiny** steps, or tap **Make it smaller** to split the step in front of you.
  - Each step has a color, an icon and a time estimate. A colored timeline shows how far along you are and roughly what time you'll finish.
  - **Start timer** on a step sets the countdown to fit that step.
- **Check-in**: rate energy from Empty to Full, tap what gave energy and what drained it (or add your own), and get encouragement plus a thought for the day. A "Lately" section shows the top energy boosts and drains over the past two weeks.
- **Move**: log physical activity (what, how long, how it felt) toward a 60-minute daily goal, see the last 7 days at a glance, and get a quick 1-minute move when you need a reset.
- **Trends**: charts of energy and activity over the last 14 days, whether energy is higher on active days, and the top energy boosts and drains. Each chart unlocks after 3 days of data.
- **Timer**: a visual countdown for 5, 10, 15 or 25 minutes with a soft chime at the end.

Everything is in `index.html` with no build step. Progress is saved on the device.

Live app: https://aaronhernandez559-code.github.io/Next-steps/

## DSM-5-TR Clinician Companion

A separate reference app for therapists (for example marriage and family therapists), in `dsm-companion/index.html`.

- Toggle between **Classification** (chapters, disorders and ICD-10-CM codes) and **Diagnostic Criteria** for any diagnosis.
- Cross-reference differentials and compare two diagnoses side by side.
- Write notes and save diagnoses to **Read Later**. Notes and bookmarks are saved on the device in that browser.
- The DSM-5-TR criteria text is copyrighted by the American Psychiatric Association and is not included. Each diagnosis has a field where clinicians enter criteria from their own licensed copy.

Live app: https://aaronhernandez559-code.github.io/Next-steps/dsm-companion/

## Chronicle: Learn History & Art

A bite-sized learning app in `chronicle/index.html`, in the spirit of story-based history apps.

- Four tracks on a path that unlocks one step at a time:
  - **History** (6 lessons) and **Art** (6 lessons).
  - **America** (9 lessons): a Harlem Renaissance unit (the movement, Langston Hughes, Zora Neale Hurston, Harlem's jazz stages, Harlem's artists) and an American Turning Points unit (the Lincoln Memorial in 1939 and 1963, Jackie Robinson, the Moon landing, Woodstock).
  - **Places** (8 lessons): the Grand Canyon, the Mississippi River, Yellowstone, Mount Everest, the Amazon, the Sahara, the Great Barrier Reef and Antarctica.
- Each lesson is about 5 minutes: 5 short story screens, then a 3-question quiz with an explanation after every answer.
- Earn XP, level up, keep a daily streak, and collect a **Legend** card for every lesson you finish.
- Progress is saved on the device in that browser.

Live app: https://aaronhernandez559-code.github.io/Next-steps/chronicle/

## Trust Setup Guide

A step-by-step guide for families planning a trust, in `trust-guide/index.html`.

- **Find my trust**: 9 quick questions (state, family, goals, estate size, real estate, lawsuit risk, long-term care) recommend a trust type, other trusts to consider, and clauses to include (spendthrift, staggered ages, special-needs sub-trust and more).
- **Learn**: 8 trust types (revocable living, testamentary, irrevocable gifting/SLAT, life insurance (ILIT), special needs, domestic asset protection, Medicaid, charitable remainder). Each one covers how it protects assets, what it doesn't protect, tax consequences (income, gift, estate, capital gains basis), setup steps and cost. Also includes an asset-protection comparison, 2026 tax numbers, and common questions.
- **My details**: grantors, trustees, successors, beneficiaries and shares, payout ages, and the assets going into the trust.
- **Documents**: draft trust agreement, Schedule A, certification of trust, assignment of assets, pour-over will, Crummey notice, affidavit of solvency, funding checklist, attorney meeting worksheet, and a letter to family. Print any one or all of them (or save as PDF), or download them as Word files to edit.
- **Set up & file**: a checklist for that trust type covering signing, notarizing, recording deeds, getting an IRS EIN, and Forms 709, 1041 and 5227, with links to the official sites.
- **Share**: send the app link to family. Use **Plan file** to save your answers as a file that a family member can open on their own device.

Documents are drafts for review with a licensed attorney, not legal advice. Answers are saved only on the device.

Live app: https://aaronhernandez559-code.github.io/Next-steps/trust-guide/

## Put it on an iPhone home screen

1. Host this folder anywhere that serves static files (for example GitHub Pages: repo Settings → Pages → deploy from the main branch, root folder).
2. Open the site in Safari, tap Share, then **Add to Home Screen**.

Note: the chime won't sound if the iPhone's silent switch is on, or if the screen is locked when the timer ends.
