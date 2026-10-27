# WAC Daily Schedule

**https://laddiemawery.github.io/wac-schedule/**

A day-by-day view of who's playing whom across the WAC (Section 2) schools, combined from each
school's Schedule Galaxy calendar. Filters can go in the link, for example
`?school=MAY&view=week` or `?sport=girls-volleyball&level=varsity`.

The schedule itself runs as a Google Apps Script web app. This page only loads it: fetching the page
without a Google sign-in lets it open in browsers signed in to several Google accounts, which Apps
Script web apps don't support. If the web app's address changes, update the `APP` line in
`index.html`.
