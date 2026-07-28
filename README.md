# Variedades Glenda Express — Production Starter

## What this is
The first real connected foundation: Supabase authentication, customer sign-up, profiles, offices, pricing, shipments, multiple packages, package QR payloads, and package status history.

## Do this next
1. Open your Supabase project.
2. Go to **SQL Editor**.
3. Open `supabase/schema.sql`, copy everything, and run it once.
4. Copy `.env.example` to `.env`.
5. Test locally with:
   ```
   npm install
   npm run dev
   ```

## Owner account
Do not hard-code the owner password in GitHub.

Create the owner through the app using an email and the phone number `6312296243`. Then run:

```sql
update public.profiles
set role='owner'
where phone='6312296243';
```

The starter uses email/password sign-in. Phone/password can be added after configuring an SMS provider.

## GitHub
Upload the project files to:
`luisisthecoolone-dot/Variedades-Glenda-Express`

Never upload a service-role key or database password.
