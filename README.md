# Werkstatt

Release channel for my personal Android training app. `latest.json` points to the newest app file in `apk/`;
the app checks it twice a day and updates itself.

No training data or source code lives here.

## Changelog

### 0.11
- Today: one day per page, swipe through the week (past Sunday you land on Plan). Each day shows the session and the fields to fill in (reps × kg per exercise, + row; or time, km, effort). Two buttons: Skip and Change. "I did something else" logs any other activity instead.
- Plan: three weeks at a glance, tap a session for details and changes; Going away / Not feeling well / Arrange under "More".
- Progress: condition in plain words with one line; fatigue and form under "Details".

### 0.10
- Condition chart (Progress): fitness (6-week load), fatigue (1-week load) and form with intervals.icu-style zones; building / holding steady / declining; the plan's sessions continue the curve to your goal date. Cardio only, or cardio + strength.

### 0.9
- Away mode: enter the dates of a trip (Today or Plan → Going away). No sessions while away, or a few optional 30-minute easy/bodyweight sessions if you can train a little. Key sessions stay on your days at home; afterwards you're eased back in (easier first cardio session; easier weeks after 1, 2 or 3+ weeks away). Days away never count as missed.

### 0.8.1
- Illness and a low readiness score always take precedence over a session you made heavier; the app tells you when it does.

### 0.8
- Subtitle: "Workouts follow you".
- Arrange your week yourself (per day: off, any, gym, run, ride); the plan fills in each session. Also per single week from the Plan tab.
- Move a session to another day (swaps with what's there), make it lighter or heavier, type any duration or distance.
- Measure cardio in minutes or kilometres (pace learned from your logged sessions).
- Set your own heart-rate zones per sport.
- Today: tap any day of this or next week to preview it; log missed days afterwards with a start time.

### 0.7
- Renamed to Werkstatt, with a geometric Bauhaus wordmark and a new icon.
- Strength logging starts from what you did: change any exercise by typing its name, add your own, remove what you skipped. Weight, reps and how hard the last set felt.
- A new exercise is remembered: as an option for that movement, and as the default next time. Exercises you add on top of a session come back in that session next time.
- Quieter screens: no boxes, clearer button labels (Record, Log afterwards, Log what you did), words under the week strip.

### 0.6
- The app is light by default, even when the phone uses dark mode. Settings → Appearance: Light, Dark or Like phone.

### 0.5
- New look: quiet Bauhaus style (Jost type, paper and ink, red/blue/yellow used sparingly).
- Simpler navigation: Today, Plan, Progress. Settings sit behind the gear icon.
- Adjust plan: change goal and date, sports, training days and time, or your details at any point; the plan rebuilds from today and keeps your logs.
- Strength sessions show a front/back body map of the muscles trained.
- Every exercise has a hand-drawn pencil illustration with numbered points to look out for, in the exercise guide and while logging.

### 0.4 (versionCode 4)
- Updates are now read from `latest.json` in this repository.

### 0.3 (versionCode 3)
- Mix running and cycling in one plan (e.g. strength + running in winter, cycling in spring).
- Set the time per weekday and change the time of any single session.
- Strength sessions show the muscle groups trained; new page with exercise alternatives and weekly sets per muscle.
- Self-updates from this repository.

### 0.2
- Automatic Strava uploads; GPS recording for outdoor sessions.

### 0.1
- First version: adaptive strength + cardio plans, illness return, heart-rate strap, morning readiness check.
