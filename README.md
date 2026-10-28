# Faith Course Platform

A React + Vite **prototype** for a course and event registration website inspired by the public structure of Faith & Future Summit. Includes public pages and a basic admin interface; there is **no student dashboard**.

## Run locally

```bash
npm install
npm run dev
```

## Features

- Homepage, About, Courses, Events, Speakers, Past Programs, Media, Get Involved, Contact, Blog and FAQ.
- Free/paid program cards and visitor registration form.
- Admin overview, course creation/removal, registration review and CSV export.
- Contact form and responsive layout.

## Prototype only — important

The current GitHub source is a **simplified React implementation**, not an exact copy of the newer downloadable local-demo ZIP and not a pixel-perfect clone of the reference site. Demo registrations, messages, and program edits now use temporary React memory state and reset when the page refreshes. Admin login is demonstration-only (`demo@admin.local` / `Demo123!`) and is **not secure**. Do not use this prototype to collect real participant details or payments on a public server.

For production use, implement Supabase authentication with Row Level Security, server-side authorization, secure payment verification, file storage, email notifications, and privacy controls. Environment variable placeholders are provided in `.env.example`.

The original downloadable ZIP from the conversation remains separate from the code pushed to this repo.

## Local demo testing

Run `npm install` and `npm run dev`, open `/admin`, and use the provided development demo credentials from the login screen. All data changes reset upon refresh. No production database is connected.
