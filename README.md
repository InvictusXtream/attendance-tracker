# INVICTUS — Smart Attendance & Academic Tracker

**Version:** `V27.3.13`  
**Target Cohort:** BCA Sec-B  

INVICTUS is a student-focused academic companion designed to streamline daily college attendance, dynamic lecture tracking, timetable exceptions, and assessment results across a 6-semester architecture.

---

## ✨ Key Features

### 📅 Smart Day-Level Attendance
- **Multi-Status Logging:** Record days as **Present** (Regular College Day, Exam Day, Custom), **Absent**, **Holiday**, or **Blank** (excluded from calculations).
- **Submission Windows & Gates:** Tracks regular submission windows (`08:30 AM – 09:30 AM`) with automatic **Late Submission** flags, alongside a two-gate cross-semester and current-semester missed-date resolution flow.
- **Bulk & Historical Management:** Mark date ranges at once, filter Attendance History by status/month, and view a 3-year interactive calendar (`August 2026 – July 2029`) with protected college holiday markers.

### 📚 Dynamic Timetable & Lecture Tracking
- **Lecture-Level Outcomes:** Track individual slots as **Attended**, **Absent**, **Teacher Absent**, **No Classes**, **Class Test**, or **Surprise Test**.
- **Schedule Exceptions:**
  - **Set Replacement:** Swap out which lecture occupies a scheduled slot.
  - **Set Adjustment:** Redirect attendance credit when attending a different subject during a scheduled period while preserving the original slot's analytics.
  - **Set to Default:** Selectively revert adjustments, replacements, or both for any date.
- **Unmarked Lecture Scanner:** Automatically detects unfinished past lectures on eligible days.

### 🎓 Isolated 6-Semester Architecture
- **Separated Data Stores:** Maintains independent working periods, timetables, subjects, attendance logs, and assessment records for **Semesters 1–6**.
- **Unified Views:** Combines semester stores into read-only unified history and date-driven Dashboard reports while keeping edits safely scoped.

### 📝 Assessment & Result Management
- **Categorized Logs:** Track **Subject** performance, **Surprise Tests**, **Class Tests**, and **Exam Results** (Sessional, Internal, University).
- **Pending Queue & Reordering:** Manage incomplete assessments via the pending results bell, and drag-and-drop exam cards to customize display order per semester and exam type.

### 📈 Analytics & Dashboard
- **Progress Reports:** Read-only **Monthly** and **Semester** breakdowns for both day-level attendance and lecture-wise percentages.
- **Temporary Semester Filters:** Filter monthly dashboard cards by specific semesters (`Semesters 1–6`) without altering global session settings.

### 💾 Offline-Ready Data & Customization
- **Backup & Restore:** Full JSON/data **Export** and **Import** functionality to safeguard academic records.
- **Profile Persistence:** Toggleable **Profile Saving** to retain profile photos, names, Gmail, and College Joining Dates even across logouts or full app data resets.
- **UI & Security Controls:** Light/Dark appearance modes, adjustable font/display scaling, in-app notification reminders, and Student ID/Password management.

---

## 🧭 App Structure

| Tab | Core Responsibilities |
| :--- | :--- |
| **Attendance** | Submit daily attendance, resolve missed-date gates, filter history, and inspect the multi-year calendar. |
| **Semester** | Manage the Daily Timetable, apply Schedule Exceptions, view Lecture Breakdowns, and log Submitted Results. |
| **Dashboard** | Review date-driven Weekly, Monthly, and Semester attendance and lecture percentage reports. |
| **Settings** | Configure Account details, active Semester, Notifications, Backups/Resets, Display scaling, and Security. |

---

## 🚀 Daily Workflow

1. **Log Day Status:** Open **Attendance** and submit today's status (resolving or bypassing any prior unmarked-date gates).
2. **Mark Lectures:** Navigate to **Semester → Daily Timetable** and record each lecture status once its scheduled start time is reached.
3. **Handle Exceptions:** Tap the clock icon on a Regular College Day to apply a **Replacement** or **Adjustment** if the schedule changes.
4. **Track Assessments:** Log class/surprise tests inline or complete pending exam entries via the **Results Bell**.
5. **Monitor Progress:** Check **Lecture Wise Percentage** and **Dashboard** reports to stay on top of attendance thresholds.

---

## 👨‍💻 Credits & License

- **Developer:** Ritik Yadav  
- **Design:** Crafted under AI Assistance  
- **Copyright:** © 2026 INVICTUS — Attendance Tracker
