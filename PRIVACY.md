# Aeroloop Privacy Policy

**Last updated:** 2026-05-23
**Version:** 1.2.0

## TL;DR

**Your data stays on your watch.** Aeroloop does not collect, transmit, or sell any personal data. We have no servers, no analytics service, no third-party trackers.

## What Aeroloop reads

To provide its features, Aeroloop reads from your Garmin watch's local sensors and history:

- **Heart Rate** (current and during sessions)
- **Heart Rate Variability (HRV)** — from your watch's existing history
- **Stress Score** — from your watch's existing history
- **Body Battery** — from your watch's existing history
- **Time of day** — for Diagnose's circadian-aware recommendations

None of this data leaves your watch.

## What Aeroloop stores

Locally on your watch via `Application.Storage`:

| Key | Purpose | Size |
|---|---|---|
| `history` | Last 20 breathing sessions (duration, protocol, biometric deltas) | ~3 KB |
| `streak` | Days of consecutive practice | < 100 bytes |
| `totalSessions` | All-time session count | < 100 bytes |
| `prefVibration`, `prefBacklight`, `prefAccentColor`, `prefEndMode`, `prefEndValue` | User preferences | < 200 bytes |
| `lastPattern` | Last protocol used (for Repeat shortcut) | < 100 bytes |
| `analytics` | Anonymous usage counters (opt-out in Settings) | ~1.5 KB |
| `lastBoltSec`, `lastButeykoSec` | Most recent breath-hold test results | < 100 bytes |
| `onboardingComplete`, `disclaimerAck` | First-launch flags | < 100 bytes |

Total: well under Garmin's 50 KB app storage limit.

## FIT activity recording

When you complete a breathing session ≥ 30 seconds, Aeroloop creates a standard Garmin FIT activity (sub-sport: Yoga) so the session appears in **Garmin Connect** as a workout. This is the same mechanism used by every Garmin recording app.

Garmin Connect is governed by Garmin's own privacy policy. Aeroloop does not access or transmit Garmin Connect data.

## Analytics

Aeroloop's "Stats" feature (toggle in Settings) tracks anonymous usage counters **on your watch only**:

- App opens, active days, install date
- Which menu items, intentions, protocols you use
- Diagnose runs and acceptance rate
- Session completions vs abandonments
- Time-of-day buckets

This data **never leaves your watch**. It powers the "Your Aeroloop" view that shows you your own practice patterns. You can disable analytics or wipe all counters from **Settings → Stats**.

## What Aeroloop does NOT collect

- ❌ Name, email, location, age, gender, weight, or any identity
- ❌ Network traffic, IP address, device serial
- ❌ Audio, video, photos, or messages
- ❌ Contacts or calendar
- ❌ Any data sent to third parties

## Medical disclaimer

Aeroloop is for **general wellness only**. It is not a medical device, does not diagnose, treat, or prevent any condition. Consult your doctor before use if you have heart, lung, or anxiety conditions. Stop if dizzy.

## Children

Aeroloop is not intended for users under 13. Connect IQ Store requires you to comply with Garmin's age policies.

## Changes

This policy may be updated when new features change data handling. Material changes will be noted in the in-app About screen.

## Contact

Questions about privacy? Contact via the Connect IQ Store developer page.
