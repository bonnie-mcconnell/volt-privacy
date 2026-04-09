# Volt  -  Privacy Policy

**Last updated:** April 2026

## What Volt collects

Volt stores the following data **locally on your device only**:

| Data | Purpose | Where stored |
|------|---------|--------------| 
| Battery level readings (0–100%) | Power usage graph and time estimates | Local file (`battery_history.json`) |
| Charging state (true/false) | Distinguish charge/discharge sessions | Local file |
| Timestamps of readings | Graph x-axis, age calculations | Local file |
| Timestamp of last full charge | "Last full charge" statistic | Local SharedPreferences |
| Cached drain rate (one float) | Subtitle after service restart | Local SharedPreferences |

## What Volt does NOT collect

- No personal information (name, email, phone number, location)
- No device identifiers (IMEI, Advertising ID, Android ID)
- No crash reports or analytics
- No data is ever transmitted to any server
- No data is ever shared with any third party

## Local storage only

All data remains on your device. Volt has no servers, no cloud sync, no account system, and no network requests of any kind. The app works entirely offline.

## CSV export

The "Export history as CSV" feature writes a file to your Downloads folder containing your battery readings. This file is yours. Volt does not transmit it anywhere. You choose whether to share it.

## Permissions explained

| Permission | Why needed |
|-----------|-----------|
| `FOREGROUND_SERVICE` | Keep the battery monitoring service running |
| `FOREGROUND_SERVICE_DATA_SYNC` | Android 14+ foreground service type declaration |
| `RECEIVE_BOOT_COMPLETED` | Restart monitoring after device reboot |
| `POST_NOTIFICATIONS` | Show battery level in notification bar |
| `USE_EXACT_ALARM` | Keep-alive timer fires on schedule |

Volt does not request location, contacts, camera, microphone, or any other sensitive permission.

## Data retention

Battery history is stored for up to 24 hours (288 readings at 5-minute intervals). Older readings are automatically discarded. You can clear all data by uninstalling the app.

## Children

Volt does not collect any data from anyone, including children under 13.

## Contact

Questions about this privacy policy? Contact: bonniep.mcconnell@gmail.com
