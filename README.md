# SkanMakery

SkanMakery is a full-stack QR platform starter built with Next.js, MongoDB and QRCode.

## Included in v1 starter

- Landing page
- User registration/login
- JWT session cookie
- User dashboard
- QR creation for URL/Text/Phone/Email/WhatsApp/Wi-Fi/Location/Contact
- Own-domain QR route
- Basic scan counter
- Admin role + admin dashboard
- MongoDB collections
- Responsive UI

## Setup

1. Install Node.js LTS.
2. Copy `.env.example` to `.env.local`.
3. Add your MongoDB Atlas connection string.
4. Set a strong `AUTH_SECRET`.
5. Run `npm install`.
6. Run `npm run dev`.
7. Create the first admin user with the seed script below.

## First admin

The project intentionally keeps admin creation server-side. Create a small seed command or manually insert an admin user with a bcrypt password hash. Do not expose an admin registration page.

For production, use a strong unique admin password and enable MFA on your infrastructure/accounts.

## Production roadmap

- R2/S3-compatible file uploads for image/PDF/video
- PNG/SVG QR downloads
- Print designer
- Dynamic QR editing
- Analytics
- Admin user management
- Subscription/billing
- Abuse controls/rate limits
- Email verification/password reset
- Audit logs
- API keys
