---
layout: default
title: Privacy Policy
description: What Netcord processes, where, and what never leaves your devices.
permalink: /privacy/
---

# Privacy Policy

<p class="updated">Last updated 3 October 2026</p>

## The short version

Netcord has no servers. Everything the app records (your shots, heart
rate, workouts, locations, court positions and match scores) stays on
your iPhone and Apple Watch. Court Cam never records video. Nothing is collected by us, transmitted to us, shared with
third parties, sold, or used for advertising. We could not read your data
even if we wanted to.

## What the app processes, and why

**Health and fitness data (HealthKit).** With your permission, Netcord
reads your heart rate, active energy, and distance during workout sessions
you start, and saves your tennis sessions as workouts in Apple Health.
This data is used solely to show you your own statistics. It is never used
for advertising or marketing, never disclosed to third parties, and never
uploaded by Netcord to any cloud service, in line with Apple's HealthKit
guidelines.

**Apple Health import.** Only if you turn on "Import from Apple Health"
(Settings → Garmin & other watches), Netcord reads the tennis workouts
other apps saved to Apple Health (for example Garmin Connect), with their
heart rate, active energy and distance, and keeps them with your sessions
on your iPhone. It reads nothing else, and the same HealthKit rules apply.

**Garmin.** Only if you link a Garmin (Settings → Garmin & other watches),
Netcord uses Bluetooth through Garmin's Connect IQ library to receive the
matches Netcord on your Garmin sends: shot times and types, heart rate,
calories, steps, distance and the score. Garmin Connect is used once to
choose your watches. Netcord sends nothing to Garmin, and the matches stay
on your iPhone like every other session. Activities your Garmin saves to
Garmin Connect are governed by Garmin's own privacy policy.

**Motion data.** During a session (and, if enabled, while the watch app is
open for auto-detection), wrist motion is processed in real time on your
Apple Watch to detect and classify shots. Raw motion samples are processed
in memory and discarded. Only the derived results (shot type, time,
intensity, direction) are stored. To sense which wrist you wear the watch
on, Netcord also asks watchOS to keep its standard on-watch accelerometer
history (the system keeps it for up to three days); Netcord summarizes it on
the watch into a single wearing verdict and never stores or sends the raw
data.

**Camera (Court Cam).** Only when you open Court Cam and allow camera
access, Netcord uses the back camera to follow the players on court. Each
video frame is analysed on your iPhone as it is captured (Apple's on-device
body-pose detection), reduced to positions on the court, and immediately
discarded. No video, photo, or image of anyone is ever saved, uploaded, or
shared. What is kept is the court map: the paths of up to four players as
court coordinates, the moments they swung and which stroke each swing
looked like, and the four court landmarks
you marked. Those positions are anonymous (no faces, names or images)
and stay on your iPhone with the session. Netcord links one path to you by
matching swing times to your watch's shots, because you tapped it, or (in
singles with no watch) because it is the player on the camera's side of the
net.

**Court IQ.** Court Cam's analysis features run on your iPhone and can each
be switched off in Settings → Court IQ. Stroke vision names each swing
(serve, forehand, backhand, volley, smash) from the body pose in the frame;
only the stroke name is kept, never the frame. Kit memory reads the average colour
of each player's shirt from the frame, so players who cross paths keep
their own identity; the colours are held in memory while filming and never
saved. Bump guard reads the iPhone's motion sensors while filming to notice
if the phone is knocked; the readings are not stored. Coach callouts speak
through the iPhone's speaker and record no audio. The match analysis
(rallies, how each pair moved, speeds) is computed from the court
positions above and stored with them.

**Your profile.** Anything you add to your profile (name, photo, gender,
birth year, height, level, club, racket, goal) is optional, stays on your
iPhone, and is used only to show you your own profile. You pick the photo
with the system photo picker; Netcord sees only the picture you choose (no
library access) and keeps a cropped copy on the device.

**iCloud.** When iCloud sync is on (App Store version), your profile, a
small copy of your photo, and your settings are kept in your own iCloud
account using Apple's iCloud key-value storage, so a new iPhone signed in to
your Apple ID picks them up. That data is stored by Apple under your
account; Netcord's developer has no access to it. You can turn sync off in
Settings → iCloud & backup.

**Backups.** "Back up everything" creates one file with your sessions,
profile, photo and settings. It goes only where you save or send it (for
example your iCloud Drive), and "Restore from a backup" reads it back.

**Debug logs.** Only if you turn on Debug mode (Settings → Debugging),
Netcord writes a log of app events (shots, points, syncs, Court Cam steps,
errors) to a file on your iPhone and watch. It can include heart rate and
shot data. Logs never leave your devices unless you share them, and you
can clear them at any time.

**Location.** With your permission, Netcord captures one coarse location
fix when a session starts, so the session can be tagged with the venue.
The coordinates and venue name are stored only inside the session record
on your devices. You can decline location access and everything else
still works.

**Match scores and settings.** Scores you log and preferences you set are
stored on-device.

## Where your data lives

- On your iPhone and Apple Watch, in the app's private storage, protected
  by iOS device encryption.
- Data moves between your watch and phone exclusively through Apple's
  encrypted Watch Connectivity channel.
- Your device backups (iCloud or computer backups, managed by Apple under
  Apple's terms) may include the app's data like any other app.

## Not a medical device

Netcord is a sports tracker, not a medical device. Heart rate, calories and the other readings it shows are for training insight only, not for diagnosing, treating or monitoring any medical condition.

## What Netcord never does

- No accounts, no sign-in, no Netcord servers.
- No analytics SDKs, no crash-reporting SDKs, no third-party code that
  phones home.
- No advertising, no tracking, no sale or sharing of data of any kind.

## Your controls

- **Permissions:** HealthKit, Motion, Camera, and Location access can each be
  declined at the prompt or revoked any time in iOS Settings and the
  Health app. The app degrades gracefully.
- **Export:** Settings → Data → Export all sessions gives you everything
  as a JSON file you own.
- **Profile:** every profile field can be cleared, and the photo removed
  (touch and hold it).
- **Delete:** Settings → Data lets you delete demo data or every session
  (with its Court Cam recording); a recording still waiting for its match
  can be discarded from Home → Court Cam.
  Deleting the app removes all app data; workouts previously saved to
  Apple Health remain under your control in the Health app.

## Retention

Data is kept on your devices until you delete it or uninstall the app.
We retain nothing, because we receive nothing.

## Children

Netcord is not directed at children under 13 and collects no data from
anyone.

## Changes

If a future version ever changes how data is handled (for example, opt-in
cloud sync), this policy will be updated first and the change will be
clearly announced in the release notes, with new behavior off by default.

## Contact

Questions or requests: open an issue at https://github.com/Liniker-Seixas/netcord/issues. Issues are public,
so describe the problem without posting health data. Help with the app:
https://liniker-seixas.github.io/netcord/support/.
