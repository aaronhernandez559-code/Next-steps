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

## Put it on an iPhone home screen

1. Host this folder anywhere that serves static files (for example GitHub Pages: repo Settings → Pages → deploy from the main branch, root folder).
2. Open the site in Safari, tap Share, then **Add to Home Screen**.

Note: the chime won't sound if the iPhone's silent switch is on, or if the screen is locked when the timer ends.
