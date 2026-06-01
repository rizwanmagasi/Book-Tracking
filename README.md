# BookTracker

> A Minimalist, Professional Library Management Ecosystem — Seamlessly tracking borrowed books, deadlines, reading history, and local library logs on-the-go.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Android_Studio-blue?style=for-the-badge&logo=android-studio)](https://github.com/sohiaking/BookTracker)

> **Deployment Architecture:**
> - **Platform:** Native Android Client Client (Material Design 3 Layouts)
> - **Storage Environment:** 100% Offline-First Local Storage Engine

---

## About the App
BookTracker is a sleek personal assistant built to solve the frustration of forgotten return deadlines, lost paper receipts, and unorganized reading logs. Whether you are a university student managing academic loans or a passionate reader keeping tabs on neighborhood libraries, BookTracker offers a beautiful dashboard workspace to log your active books, track dynamic countdown timers, preserve detailed notes, and maintain a historical ledger of completed reads without requiring complex cloud accounts.

---

## App Screenshots

| Dashboard (Empty) | Active Tracker | Borrowed Books |
|:---:|:---:|:---:|
| ![Dashboard Empty](screenshots/dashboard_empty.jpg) | ![Active Tracker](screenshots/dashboard_active.jpg) | ![Borrowed Books](screenshots/borrowed_list.jpg) |

| Add Book Screen | Book Details | Return Confirmation |
|:---:|:---:|:---:|
| ![Add Book Screen](screenshots/add_book.jpg) | ![Book Details](screenshots/book_details.jpg) | ![Return Confirmation](screenshots/return_dialog.jpg) |

| Reading History | Unified Search Engine | Empty States View |
|:---:|:---:|:---:|
| ![Reading History](screenshots/reading_history.jpg) | ![Search Engine](screenshots/search_screen.jpg) | ![Empty States](screenshots/empty_books.jpg) |

---

## Download APK

[![Download APK](https://img.shields.io/badge/Download_APK-BookTracker-gold?style=for-the-badge&logo=android)](apk/BookTracker.apk)

> **Installation Quick Guide:** Download APK → Open file → Allow unknown sources → Install → Run
> *(Note: If your compiled file exceeds the 25MB browser upload limit, paste your Google Drive share link inside the parenthesis above!)*

---

## What Makes BookTracker Premium?

> **Designed with a warm palette and focused entirely on data minimalism. No login walls, zero background ads, and instant layout loading.**

### Feature Architecture Comparison

| Capability | Standard Notes App | BookTracker Workspace |
|---|---|---|
| **Due Date Awareness** | Static Text Notes | Dynamic "Days Left" Countdown Badges |
| **Status Classification** | Manual lists | Automated Matrix (Active / Due Soon / Overdue) |
| **History Retention** | Overwritten upon deletion | Permanent "Reading History" Archive Logs |
| **Search Indexing** | Scans titles only | Unified searching by Title, Author, or Library location |

---

## Features

- **Dynamic Status Dashboard** — Quick-view metric cards instantly mapping `Total Books`, `Active`, `Due Soon`, and `Overdue` status aggregates.
- **Visual Deadline Trackers** — High-visibility contextual status banners calculating precise countdown increments (e.g., "14 days remaining").
- **Library Form Architecture** — Simple book adding fields with input validation parameters covering Book Title, Author Name, Library Source, and customizable Notes.
- **Archived History Engine** — Keeps a record of returned assets, letting you review your lifecycle statistics and early notes over time.
- **Instant Search Utility** — A comprehensive, real-time filtered indexing page scanning across nested library targets instantly.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Mobile Application** | Native Android Client Architecture |
| **Development IDE** | Android Studio |
| **User Interface Engine** | Android XML Layouts + Material 3 Design Rules |
| **Database Architecture** | Local Structured SQLite Database Client |
| **Build Automation** | Gradle Build Automation System |

---

## How to Install the APK

1. Click the **Download APK** badge button above.
2. Transfer or download the `.apk` file onto your targeted Android hardware.
3. Open your mobile system file directory, tap the file, and select **Install**.
4. If prompted by system firewalls, toggle **"Allow installation from unknown sources"**.
5. Launch **BookTracker** from your mobile app drawer.

---

## How to Run the Project Code

1. Clone or download this project repository onto your desktop computer.
2. Launch **Android Studio** and choose *Open Project*, selecting this specific directory.
3. Allow the IDE to completely sync and resolve the configuration files through **Gradle**.
4. Set up an Android Virtual Device (AVD Emulator) or connect a physical phone via USB Debugging.
5. Press the green **Run** button to compile and execute the app build.

---

## Android Permissions

| Permission String | Operational Purpose |
|---|---|
| `android.permission.INTERNET` | Retains application environment sandbox stability and library check updates. |
| `android.permission.POST_NOTIFICATIONS` | Required to pop timely local system reminder alerts before book due dates expire. |

---

## Documentation
- [Privacy Policy](docs/privacy_policy.pdf)
- [User Manual Portfolio](docs/user_manual.pdf)

---

## Future Enhancements
- [ ] Implement integrated barcode scanning via device camera to auto-fetch book details.
- [ ] Add native system calendar sync hooks for push deadline alerts.
- [ ] Introduce dark mode UI layout switching rules.
- [ ] Add data CSV export/import options for seamless local migrations.

---

## Developed By

- **Student Name:** rizwan haidar
- **Class / Semester:** 6th
- **Department Name:** Department of Computer Science
- **GitHub Workspace:** [@rizwanmagasi](https://github.com/sohiaking)

---

<div align="center">
  <b>BookTracker AI — Your Personalized Local Library Companion</b>
</div># Book-Tracking
