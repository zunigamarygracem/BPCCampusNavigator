# BPC Campus Navigator

A mobile app that helps students, visitors, and staff find buildings, offices, and facilities at Bulacan Polytechnic College (BPC).

**Version:** 1.0 (October 2026)

## Features
- Interactive campus map with search bar and category filters
- Route guide to selected destinations
- Announcements, office directory, and campus resources
- Class schedule for signed-in users
- Sign In, Sign Up, Edit Profile, and Sign Out
- Admin Dashboard to add, edit, and delete map locations, announcements, offices, schedules, and resources

## User Roles
| Role | Access |
|------|--------|
| Guest | View announcements, directory, resources, and map; get routes |
| Registered User | Guest access plus class schedule and profile editing (view-only content) |
| Administrator | Full access, including the Admin Dashboard |

## Screenshots
| Home | Campus Map | Announcements |
|------|------------|---------------|
| <img src="screenshots/01_home.png" width="220"> | <img src="screenshots/02_campus_map.png" width="220"> | <img src="screenshots/03_announcements.png" width="220"> |

| Sign In | Schedule (guest) | Profile (admin) |
|---------|------------------|-----------------|
| <img src="screenshots/04_sign_in.png" width="220"> | <img src="screenshots/05_schedule_guest.png" width="220"> | <img src="screenshots/06_profile_admin.png" width="220"> |

| Admin Dashboard | Edit Location | Edit Profile |
|-----------------|---------------|--------------|
| <img src="screenshots/07_admin_dashboard.png" width="220"> | <img src="screenshots/08_edit_location.png" width="220"> | <img src="screenshots/09_edit_profile.png" width="220"> |

## Built With
- Kotlin and Java
- Android Studio
- Canva (UI design)
- Git and GitHub

## Installation and Setup
**Install the app (APK)**
1. Open the [Releases](../../releases) page and download the latest `.apk`.
2. On your Android phone, allow installation from unknown sources if asked.
3. Open the downloaded file and tap Install.

**Run the source code**
1. Download or clone this repository.
2. Open the project in Android Studio and let Gradle sync.
3. Run the app on an Android device or emulator.

## Known Issues
- Sign In accepts invalid credentials (TC-04)
- Registered accounts are not saved after the app is closed and reopened (TC-12)

## Limitations
- Covers the BPC campus only
- No real-time GPS; uses a custom campus map with pins and a route feature
- No database; data is handled inside the app

## Developers
- Millet Cabrera
- Mary Grace Zuniga
- Charlotte Galuyo
- Marvin Garcia
- Jenylyn Banag

Bulacan Polytechnic College
