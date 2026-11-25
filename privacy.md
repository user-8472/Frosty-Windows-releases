---
title: Privacy policy
---

# Frosty Windows privacy policy

Effective 25 November 2026.

Frosty Windows tells you whether you'll need to scrape frost off your car in the morning. It has no
ads, no accounts and no tracking.

**Frosty Windows collects only the minimum information needed for the features it offers.** Most of
what the app knows never leaves your phone. Something leaves it only when a feature can't work
without it (a forecast needs the place it's for), or when you choose to send it. Nothing reaches
the developer unless you send it yourself.

## What's collected, and when

### Never leaves your phone

- Your alerts: their names, the places you park, the times you leave, your days and settings.
- The forecasts the app downloads, your answers to "Was it frosty?", what the Adaptive forecast
  beta learns from them, and the app's activity log.

These stay on your phone (and in your phone's own backup, if you have that switched on; see below)
until you uninstall the app, unless you put some of them in a report you choose to send.

### Sent automatically, because a feature needs it

- **Each alert's place** (coordinates, to about 10 metres), whenever the app checks its forecast:
  to Open-Meteo, or the US National Weather Service as a backup. Not sent to the developer.
- **On the version installed from GitHub only**: a request for the list of new versions, to GitHub.
  It contains nothing about you or your alerts.

### Sent only when you use a feature

- **The text you type** in place search: to Open-Meteo's place search.
- **A street address you type** (Android), **your current location** if you tap **Use my current
  location**, or **the spot under the map pin** when you zoom in to street level: to your phone's
  built-in address lookup (usually Google's on Android, Apple's on iPhone), to name the spot.
- **The part of the map you're looking at**, if you open the map: to OpenFreeMap, for the map pictures.

None of these go to the developer. Like any website, each of these services sees your phone's
internet (IP) address when the app connects to it.

### Sent to the developer only if you choose to send it

- **A crash report** (the error, phone model, and the activity log with names and places removed),
  if you email one. Kept in the developer's inbox until you ask for it to be deleted.
- **A problem report** (one morning's forecast, the place rounded to about 10 km, and your recent
  "Was it frosty?" answers for that alert, with no names), if you email one. Kept until you ask for
  it to be deleted.
- **Adaptive forecast beta results** (your answers, what the app learned, places rounded to about
  10 km, phone model, no names), only if you've turned the beta on and tap Send or email them.
  Results sent with Send are kept on the developer's results server for up to a year, or deleted
  sooner if you email the results code the app shows you; emailed ones are kept until you ask.

You see what's in each of these before it's sent, and can change it or not send it at all.

The sections below give the details.

## What stays on your phone

Your alerts, the forecasts the app has fetched, your answers to "Was it frosty?" and its activity
log are stored only on your phone. Frosty Windows has no account. Its only server is the beta
results server, which receives results only when you send them. Uninstalling the app deletes all
of it from your phone.

### Your phone's own backup

If backup is switched on in your phone's settings, Android can include the app's data (your alerts,
settings and answers) in your phone's backup to your Google account, so they come back when you
set up a new phone. That backup is made and kept by Google for you; the developer can't see it.
You can turn it off in your phone's backup settings. On a new phone, open Frosty Windows once after
the restore: that sets its alarms and notifications again and asks for any permissions Android
didn't carry over.

## What goes online, and why

The app only connects to the internet to:

- **Fetch forecasts** for the places you set alerts for, from [Open-Meteo](https://open-meteo.com/)
  and, when Open-Meteo can't be reached, the US [National Weather Service](https://www.weather.gov/)
  as a backup (it only has forecasts for the United States; for other places it answers that it
  has none). These requests contain the place's coordinates (to about 10 metres), not who you are.
- **Look up a place you search for** by name, using Open-Meteo's place search. The request contains
  the text you typed.
- **Name your current location**, only if you tap **Use my current location**: the app reads your phone's
  location once and asks your phone's built-in address lookup (on Android usually provided by Google,
  on iPhone by Apple) for the name of that spot. The location is used to set up that alert and isn't
  tracked afterwards. The app never uses your location in the background.
- **Look up a street address you type** (Android): when what you type starts with a house number,
  the app asks your phone's built-in address lookup (usually provided by Google) for matching
  addresses, once you pause typing. The address only places the pin; the app keeps the spot, not
  the address, unless you choose the address as the alert's name.
- **Show a map**, only if you tap **Pick on a map** or pick an address: the map pictures come from
  [OpenFreeMap](https://openfreemap.org/), which serves OpenStreetMap maps. Its servers see which part
  of the map you're looking at, not who you are. Zoomed in to street level, the app asks your phone's
  address lookup for the nearest address once the map stops moving, to show "Near…" under the pin;
  that address isn't saved. The spot is named from the town names drawn on the map.
- **Check for and download new versions** (Android version installed from GitHub only): the app
  asks GitHub for the list of releases and, when you update (or automatic updates are on), downloads
  the new version from GitHub. These requests contain nothing about you or your alerts. The iPhone
  and Google Play versions never contact GitHub; they're updated by the App Store and Google Play.

Like any website you visit, these services see your phone's internet (IP) address when the app
connects to them. Their own privacy policies apply to what they do with it. Frosty Windows sends them
nothing that identifies you.

## Things you choose to open

- **Buy me a hot chocolate** opens Frosty Windows' [Ko-fi](https://ko-fi.com/frostywindows) page in your
  browser. Payments happen on Ko-fi, never in the app, and Ko-fi's privacy policy applies there.
- **Email Frosty Windows** opens your email app with a message to frostywindowsapp@gmail.com. Only
  what you choose to send reaches the developer.
- **Email a crash report** appears only after the app has hit an error. It opens your email app with
  a message to frostywindowsapp@gmail.com containing the error, the app version, your phone's maker,
  model and Android version, and up to the last 25 entries of the app's activity log (forecast checks and alerts,
  with your alerts' names and places replaced by "Alert 1", "Alert 2" and so on, and times mentioned
  inside the entries, such as your commute and alert times, replaced by "[time]"; each entry still
  shows the date and time it happened). Until then the details stay on your phone, and you can read
  or change the message before sending it, or not send it at all. The app never sends crash reports
  by itself. If you send one, it reaches the developer from your own email address and is used only
  to find and fix the problem. To have a crash report you sent deleted, email
  frostywindowsapp@gmail.com.
- **Report a problem** (in Settings, and on an alert's details screen) opens your email app with a
  message to frostywindowsapp@gmail.com with room for you to say what went wrong, then the app
  version, your phone's maker, model and Android version and, for the alert you pick, the forecast
  for that morning: when you leave (date and time), the verdict and chance, the scraping estimate,
  the lowest air and estimated glass temperatures, dew point, wind and cloud, where the car is
  parked (open, carport or garage), when the forecast was downloaded, the place rounded to
  about 10 km, and your last few "Was it frosty?" answers for that alert (each morning's date, what
  the forecast said and what you found). It doesn't include your alerts' names or
  place names. As with a crash report, you can read or change the message before sending it, or
  not send it at all; it reaches the developer from your own email address, is used only to
  improve the forecasts and fix problems, and is deleted on request to frostywindowsapp@gmail.com.
- **Was it frosty?** After a commute, the home screen (and the buttons on the morning notification)
  can ask whether there was frost. Your answers stay on your phone, where they make up the "Your
  reports" record on the alert's details screen. They leave your phone only in a problem report
  or a beta results email (below) that you choose to send.
- **Adaptive forecast (Beta)** is off unless you turn it on in Settings. It works out on your phone,
  from your answers, how frosty each spot gets compared with the forecast, and shows that as a
  second chance. Nothing is sent by itself. "Send my results" opens an email in your own email app
  with your answers (date and time, what the forecast said, what you found, and the night's
  forecast numbers), what the app learned for each alert, each alert's parking type and its place
  rounded to 1 decimal (about 10 km), the app version and your phone's model. It has no alert or
  place names. You can read or change it before sending it, or not send it at all; it's used only
  to test and improve the forecast, and is deleted on request to frostywindowsapp@gmail.com.
  Instead of email, the same screen can send these results, with any note you add, straight to the
  developer's results server (run on Cloudflare), without an email address. It is sent only when
  you tap Send, after the screen shows exactly what will be sent. The server keeps the results,
  the app version and store and the date they arrived, under a random results code shown to you;
  it doesn't keep your IP address (used only to limit how often one connection can send) or
  anything else that identifies you or your phone. Results are deleted after a year, or sooner if
  you email your results code to frostywindowsapp@gmail.com.
- **Share Frosty Windows** opens your phone's share menu with a short message; you choose who gets it.

## Permissions

- **Location** (only when you tap Use my current location): to find where your car is parked.
- **Notifications**: to warn you about frost.
- **Alarms** (exact alarms and full-screen alarms on Android; alarms on iPhone): so warnings and
  alarms come at the right minute and can ring over the lock screen.
- **Unrestricted battery use** (Android, optional): so the phone doesn't stop the overnight forecast
  check.
- **Install apps** (Android version from GitHub only): to install updates you download in the app.

## What the developer doesn't do

No analytics or tracking tools, no automatic crash reporting (a crash report reaches the developer
only if you choose to email it), no advertising IDs, and no selling or sharing of data. Apart from an
email you choose to send, or beta results you choose to send, nothing the app does sends
information to the developer.

## How Google Play's Data safety section describes this

Google counts anything that leaves your phone as "collected", even when it's only used to answer a
request. So the Google Play listing says Frosty Windows collects:

- **Location** (approximate and precise): your alerts' places, sent to the forecast services as
  described above. Used for app functionality, not stored by the developer, not shared. A problem
  report you choose to email also contains one place rounded to about 10 km, kept in the
  developer's inbox until you ask for it to be deleted.
- **In-app search history**: the place names you search for, sent to Open-Meteo's place search.
  Optional; used for app functionality, not stored, not shared.
- **Crash logs and diagnostics**: only the crash reports and problem reports you choose to email. Optional; used to find
  and fix bugs, kept in the developer's inbox until you ask for them to be deleted, not shared.
- **Approximate location and diagnostics in beta results**: only if you turn on the Adaptive
  forecast beta and choose to send your results (places rounded to about 10 km, phone model).
  Optional; used to test and improve the forecast, kept for a year at most, not shared.

## Children

Frosty Windows isn't aimed at children and doesn't knowingly collect information from children.

## Changes

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions about privacy: **frostywindowsapp@gmail.com**.
