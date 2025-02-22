# React Router Unhandled Paths Bug
This repository demonstrates a common issue in React Router v6 where unmatched paths unexpectedly redirect to the home page instead of displaying a 404 Not Found page.  The solution shows how to correctly handle these situations by adding a catch-all route.

## Bug
The original `App.js` lacks a route to handle paths not explicitly defined. This leads to the application defaulting to the first defined route when a user tries to navigate to an invalid URL.