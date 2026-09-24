# DeAr FollowUp CRM

A mobile-friendly PWA MVP for DeAr Realty Solutions. It works on iPhone and Android browsers and can be installed to the home screen.

## Current MVP
- Lead entry/edit/delete
- Lead search
- Status and next follow-up date
- Call shortcut
- Assigned team member field
- Follow-up dashboard with today/overdue
- Property inventory
- Offline local storage

## Important
This first build stores data in the browser/device. It is NOT yet a shared multi-user cloud CRM. For team use, the next step is to connect the same interface to Supabase (authentication + PostgreSQL + row-level security), then deploy the frontend on Netlify/Vercel.

## Run
Serve this folder from any static web host. Opening `index.html` directly may disable service-worker installation; use a static host for PWA behavior.
