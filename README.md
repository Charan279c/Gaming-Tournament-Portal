# ArenaX Gaming Tournament Portal

ArenaX is a gaming tournament management website created for the Full Stack Web Development course review.

The project helps players join gaming tournaments and helps administrators manage tournaments.

## Problem Statement

Gaming tournaments are often managed using WhatsApp groups, Google Forms, and spreadsheets. This makes registration, team details, schedules, results, and leaderboard management difficult.

ArenaX provides one portal where players can view tournaments, register, and track tournament activity.

## Modules

### User Module

A player can:

- Sign up
- Log in
- Browse tournaments
- Filter tournaments by game
- Register for tournaments
- View registered tournaments
- View leaderboard
- View Local Storage data
- Log out

### Admin Module

An admin can:

- Log in
- Open Admin Dashboard
- Create tournaments
- View all tournaments
- Delete tournaments
- View registration count
- View user count
- View Local Storage data
- Log out

## Technologies Used

- HTML
- CSS
- JavaScript
- CSS Flexbox
- CSS Grid
- Browser Local Storage
- JSON

## Local Storage Keys

| Key | Purpose |
|---|---|
| `users` | Stores signup user accounts |
| `currentUser` | Stores current logged-in user |
| `tournaments` | Stores tournament details |
| `registrations` | Stores player tournament registrations |

## Default Admin Login

```text
Email: admin@arenax.com
Password: admin123
