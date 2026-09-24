# DeAr Client Follow-Up — Shared Team App

This version uses a server database and login system.

## Main changes
- Admin can create team member accounts.
- All members log into the same app URL.
- Everyone sees the same Clients and Projects/Properties.
- When a Client is assigned to a member, that member gets an instant in-app notification and, if browser notifications are allowed, a browser notification.
- Reassignment also sends a notification.
- Shared follow-up history and notes.
- Shared property/project database.
- Call and WhatsApp buttons.
- Client status and next follow-up tracking.

## Deploy
Node.js 20+ is required.
1. Upload this folder to a Node hosting service.
2. Build/install: `npm install`
3. Start: `npm start`
4. Set ADMIN_USERNAME and ADMIN_PASSWORD environment variables.
5. For persistent SQLite storage, set DB_FILE to a persistent disk path.
6. Open the HTTPS app URL on every phone. Everyone uses the same URL but different login.
7. Admin creates team accounts from Team.

For production with a larger team, replace SQLite with PostgreSQL/Supabase and add password reset, role permissions and scheduled push reminders.
