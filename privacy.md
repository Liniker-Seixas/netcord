---
layout: default
title: Privacy Policy
description: What Netcord processes, where, and what never leaves your devices.
permalink: /privacy/
---

# Netcord Privacy Policy

**Effective date: 3 October 2026**

## The short version

Netcord has no servers and no accounts. What the app records (your shots,
heart rate, workouts, court positions, match scores and where you played)
is kept on your iPhone and Apple Watch. Court Cam never records video.
Nothing is collected by us, sent to us, shared with third parties, sold, or
used for advertising. We could not read your data even if we wanted to.

Three things do leave your devices, and none of them reaches us:

- If you are signed in to iCloud, your settings, most of your profile and a
  small copy of your photo sync through your own iCloud account. This is on
  by default and you can turn it off.
- When a session starts on your Apple Watch, Apple's location service turns
  its location into a venue name.
- Files you choose to save or share, such as a backup.

## What the app processes, and why

**Health and fitness data (HealthKit).** With your permission, Netcord on
your Apple Watch reads your heart rate, active energy and distance during
the tennis workouts you start, and saves each one to Apple Health as a
tennis workout. If Auto-detect is on (it is on by default), the watch also
checks your recent heart rate and step count in the background every so
often, so it can offer to start tracking when you seem to be playing; those
readings are used on the watch at that moment and not stored. Netcord on
your iPhone reads Apple Health only if you turn on Import from Apple Health
(below). Health data is used only to show you your own statistics. It is
never used for advertising or marketing, never disclosed to third parties,
never uploaded by Netcord to any server, and never part of Netcord's iCloud
sync, in line with Apple's HealthKit guidelines.

**Apple Health import.** Only if you turn on "Import from Apple Health"
(Settings → Garmin & other watches), Netcord on your iPhone reads the
tennis workouts from the last year that other apps saved to Apple Health
(for example Garmin Connect), with their heart rate, active energy and
distance, and keeps them with your sessions on your iPhone. It reads
nothing else, and the same HealthKit rules apply.

**Garmin.** Only if you link a Garmin (Settings → Garmin & other watches →
Connect your Garmin), Netcord uses Garmin's Connect IQ library to talk to
Netcord's app on your Garmin over Bluetooth. The Garmin Connect app on your
iPhone is used to choose your watches. Netcord sends your Garmin its match
settings (scoring rules, hitting hand, singles or doubles, shot sensitivity
and haptics), and receives live updates during play and the matches it
records: shot times and types, heart rate, calories, steps, distance and
the score. Matches arrive while Netcord is open on your iPhone and stay
there like every other session. Netcord sends nothing to Garmin's servers.
Netcord on your Garmin also saves a tennis activity, which your watch syncs
to Garmin Connect; that activity is covered by Garmin's own privacy policy.
Netcord is made by Liniker Seixas, not by Garmin. What Netcord on your
Garmin records goes only to your own iPhone, never to Netcord's developer or
to Garmin, and Garmin has no responsibility for it.

**Motion data.** During a session, and while the watch app is open with
Auto-detect on, wrist motion is processed in real time on your Apple Watch
to detect and classify shots. Raw motion samples are processed in memory
and discarded. Only the results (shot type, time, intensity, direction) are
stored. During a session the watch also counts your steps and keeps the
count in the session; steps are not saved to Apple Health. To sense which
wrist you wear the watch on, Netcord asks watchOS to keep its standard
on-watch accelerometer history (the system keeps it for up to three days);
Netcord summarises it on the watch into a single wearing verdict and never
stores or sends the raw history. The one exception is Debug mode (below):
there, each Wear Check saves a short report with the motion readings it
took, on your watch and your iPhone.

**Camera (Court Cam).** Only when you open Court Cam and allow camera
access, Netcord uses the back camera to follow the players on court. Each
video frame is analysed on your iPhone as it is captured (Apple's on-device
body-pose detection), reduced to positions on the court, and immediately
discarded. No video, photo, or image of anyone is ever saved, uploaded, or
shared. What is kept is the court map: the paths of up to four players as
court coordinates, the moments they swung and which stroke each swing
looked like, and the four court landmarks you marked. Those positions are
anonymous (no faces, names or images) and stay on your iPhone with the
session. Netcord links one path to you by matching swing times to your
watch's shots, because you tapped it, or (in singles with no watch)
because it is the player on the camera's side of the net.

**Court IQ.** Court Cam's analysis features run on your iPhone and can each
be switched off in Settings → Court IQ. Stroke vision names each swing
(serve, forehand, backhand, volley, smash) from the body pose in the frame;
only the stroke name is kept, never the frame. Kit memory reads the average
colour of each player's shirt from the frame, so players who cross paths
keep their own identity; the colours are held in memory while filming and
never saved. Bump guard reads the iPhone's motion sensors while filming to
notice if the phone is knocked; the readings are not stored. Coach callouts
speak through the iPhone's speaker and record no audio. The match analysis
(rallies, how each pair moved, speeds) is computed from the court positions
above and stored with them.

**Your profile.** Everything on your profile (name, photo, gender, birth
year, height, years playing, level, club, racket, favourite shot, goal) is
optional and is used only to show you your own profile. It is kept on your
iPhone. With iCloud sync on, your profile also syncs through your iCloud,
except your gender, birth year and height, which stay on your iPhone (and
in backups you make). You pick the photo with the system photo picker;
Netcord sees only the picture you choose (no library access) and keeps a
cropped copy on the device.

**iCloud sync.** If you are signed in to iCloud, sync is on by default.
Netcord keeps your settings (except switches that belong to one device,
such as Debug mode and Apple Health import), your profile without gender,
birth year and height, and a small copy of your photo in your own iCloud
account, using Apple's iCloud key-value storage, so another iPhone signed
in to your Apple ID picks them up. Sessions, health data and court maps are
not part of it. That data is stored by Apple under your account; Netcord's
developer has no access to it. Turning off Sync with iCloud (Settings →
iCloud & backup) stops syncing and removes Netcord's copy from iCloud; if
another iPhone of yours still has sync on, it puts the copy back, so turn
it off there too. Deleting the app alone does not remove that copy, so turn
sync off first.

**Backups.** "Back up everything" (Settings → iCloud & backup) creates one
JSON file with your sessions, your whole profile, your photo and your
settings. It goes only where you save or send it (for example your iCloud
Drive), and "Restore from a backup" reads it back.

**Debug logs.** Only if you turn on Debug mode (Settings → Debugging),
Netcord writes a log of app events (shots, points, syncs, Court Cam steps,
errors) to files on your iPhone and watch, and the watch sends its log to
your iPhone after each match. Logs can include heart rate and shot data.
They never leave your devices unless you share them. "Clear debug logs"
removes the copies on your iPhone; the watch keeps at most 20 MB of logs
and drops the oldest first. Turning Debug mode off stops new logs.

**Location.** With your permission, when you start a session on your Apple
Watch, Netcord takes one approximate location fix (to about 100 metres) and
asks Apple's location service to turn it into a venue name. That lookup
sends the coordinates to Apple, under Apple's privacy policy. The
coordinates and venue name are stored only in the session, on your devices
and in backups you make. You can decline location access and everything
else still works.

**Siri.** If you score a point by asking Siri on your Apple Watch, Siri
handles the request under Apple's privacy policy and Netcord receives only
the point. Netcord never records or listens to audio itself.

**Match scores and settings.** Scores you log and preferences you set are
stored on your devices. With iCloud sync on, your settings also sync
through your iCloud as described above.

## Where your data lives

- On your iPhone and Apple Watch, in the app's private storage, protected
  by device encryption.
- Between your Apple Watch and iPhone, data moves through Apple's encrypted
  Watch Connectivity channel. Between a linked Garmin and your iPhone, it
  moves over Bluetooth through Garmin's Connect IQ library.
- With iCloud sync on, your settings, your profile (without gender, birth
  year and height) and a small photo are kept in your own iCloud key-value
  storage.
- Your device backups (iCloud or computer backups, managed by Apple under
  Apple's terms) may include the app's data like any other app.

## Not a medical device

Netcord is a sports tracker, not a medical device. Heart rate, calories and
the other readings it shows are for training insight only, not for
diagnosing, treating or monitoring any medical condition.

## What Netcord never does

- No accounts, no sign-in, no Netcord servers.
- No analytics SDKs, no crash-reporting SDKs, no third-party code that
  phones home.
- No advertising, no tracking, no sale or sharing of data of any kind.

## Your controls

- **Permissions:** Health, Motion & Fitness, Camera, Location, Bluetooth
  and notifications can each be declined at the prompt or changed any time
  in Settings on your iPhone or watch, and in the Health app. Netcord keeps
  working without any of them; you lose only the feature that needs it.
- **Auto-detect:** turn off "Auto-detect tennis play" (Settings → Shot
  detection) to stop the watch's background check.
- **iCloud:** turn off "Sync with iCloud" (Settings → iCloud & backup) to
  stop syncing and remove Netcord's copy from iCloud.
- **Export:** Settings → iCloud & backup → Back up everything gives you
  your sessions, profile, photo and settings as one JSON file you own.
- **Profile:** every profile field can be cleared, and the photo removed
  (touch and hold it).
- **Delete:** Settings → Data → Delete all sessions removes every session,
  with its Court Cam recording, from your iPhone; "Remove demo data"
  removes only the demo sessions. A recording still waiting for its match
  can be discarded from Home → Court Cam. Deleting the app removes what it
  stored on your devices, but not Netcord's copy in your iCloud: turn off
  sync first to remove that. Workouts saved to Apple Health remain under
  your control in the Health app.

## Retention

Data is kept on your devices until you delete it or delete the app.
Netcord's copy in your iCloud is kept until you turn off iCloud sync, even
after the app is deleted. We retain nothing, because we receive nothing.

## Children

Netcord is not directed at children under 13 and collects no data from
anyone.

## Changes

If a future version changes how data is handled, this policy will be
updated first and the change will be announced in the release notes.

## Contact

Questions or requests: open an issue at
https://github.com/Liniker-Seixas/netcord/issues. Issues are public, so
please don't post health data. Help with the app:
https://liniker-seixas.github.io/netcord/support/.
