# Studymart Dashboards

This project includes two dashboards in one page:

- **Admin dashboard**: lets admins post courses.
- **User dashboard**: shows the exact list of courses posted by admins.

## Run

Open `index.html` in a browser.

## How it works

- Courses are saved in browser `localStorage` under `studymart_courses`.
- When an admin posts a course, both dashboards re-render immediately.
