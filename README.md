# AKADEV Todo App

A Todo list app built using NextJS & Supabase.

## Clone and run locally

1. Clone repo.

2. Rename `.env.local.example` to `.env.local` and update the following:

   ```
   NEXT_PUBLIC_SUPABASE_URL=[INSERT SUPABASE PROJECT URL]
   NEXT_PUBLIC_SUPABASE_ANON_KEY=[INSERT SUPABASE PROJECT API ANON KEY]
   ```

   Both `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_ANON_KEY` can be found in [your Supabase project's API settings](https://app.supabase.com/project/_/settings/api)

3. You can now run the app locally:

   ```bash
   npm run dev
   ```

   The app should now be running on [localhost:3000](http://localhost:3000/).
