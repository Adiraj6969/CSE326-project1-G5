# EduTrack — Student Dashboard

## Project Overview

EduTrack is a front-end student dashboard for an Assignment Submission Tracker. It helps students see their assignments, deadlines, and submission statuses in one place.

This is a prototype made with **HTML, CSS, and JavaScript**. It uses sample assignment data and does not require a backend or database.

## Features

- **Sidebar navigation** for Dashboard, Assignments, Deadlines, Profile, and Logout.
- **Summary cards** showing total, pending, submitted, and overdue assignments.
- **Assignment table** showing each course, assignment title, deadline, status, and action.
- **Search** to find assignments by course or title.
- **Status filters** for All, Pending, Submitted, and Overdue.
- **Demo submission action** that changes an assignment's status and updates the summary cards.
- **Responsive layout** for smaller screens.
- **Lucide icons** for navigation, cards, courses, and actions.

## Technologies Used

- **HTML** — page structure and content.
- **CSS** — colours, layout, cards, table, status labels, and responsive design.
- **JavaScript** — search, filters, count updates, and demonstration interactions.
- **Lucide static icon font** — interface icons loaded through a CDN.

## Colour Palette

| Colour | Hex |
|---|---|
| Humming Bird | `#CAF4F4` |
| China Ivory | `#FCFFE9` |
| Flicker | `#FFF2CC` |
| Cinderella | `#FDE0D9` |
| Restful | `#CAEFD1` |
| Dark red | `#830000` |
| Red accent | `#BC0202` |

## How to Run

1. Save the dashboard code as `students.html`.
2. Open the file in a browser, or run it with VS Code Live Server.
3. Keep an internet connection available so the Lucide icon font can load.

## Important Limitations

- Assignment details are sample data written into the HTML.
- Marking an assignment as submitted only changes the current page; it is not saved permanently.
- There is no real login authentication, file upload, database, or teacher-to-student data connection.
- The Logout link should be updated to match the actual filename of the login page.

## Possible Future Improvements

- Connect a backend and database to store assignments.
- Add real login and role-based access for students and teachers.
- Allow students to upload assignment files.
- Allow teachers to create assignments and review submissions.
- Save status changes between visits.

## Project Goal

The goal of EduTrack is to demonstrate how a student-friendly assignment tracking interface can be designed using front-end web technologies. It provides a clear overview of coursework and demonstrates basic interactive features without requiring backend concepts.
