# Hotel Management System

A beginner full-stack web project for managing hotel operations — my first project
combining PHP, MySQL, HTML, CSS, and JavaScript, all in a single monolithic app
(no framework, no separation into services/modules).

> **Status:**  Completed *

## Overview

A basic hotel management system covering *( e.g. room bookings, guest
records, admin login)*. Built as an early practice project to get comfortable
with a full PHP + MySQL stack end-to-end before working with more structured
architectures.

## Tech Stack

- Backend: PHP
- Database: MySQL
- Frontend: HTML, CSS, JavaScript (mixed directly into the PHP files)

## Features

- [ ] Room booking / availability
- [ ] Guest records
- [ ] Admin login/dashboard
- [ ] Account creation
- [ ] Publishing Hotels
- [ ] Registering a Hotel

## How to Run

Standard local PHP + MySQL setup (XAMPP/WAMP/MAMP):

1. Place the project folder (code_new) inside your server's web root (e.g. `htdocs/`)
2. Start Apache and MySQL
3. Import the provided `.sql` file into phpMyAdmin to create the database
4. Update the database connection details (host/username/password/db name) in
   the config/connection file if needed
5. Visit `http://localhost/<project-folder-name>` in your browser

## Notes

This was a self-directed first project rather than a course assignment, so it's
not cleanly separated into modules — most logic lives directly in the PHP pages
alongside HTML/CSS/JS. It's a good honest snapshot of an early full-stack
attempt; later projects (like the UCSC Student Help Desk System) reflect more
structured practice built on what this one taught.
