# JSD Dashboard

This is a static dashboard built with a single-page HTML app stored in `index.html`.

## Deploy to Vercel

1. Create a GitHub repository and commit the project files.
2. Connect the repository to Vercel:
   - Go to https://vercel.com/new
   - Select the GitHub repo
   - Set the root directory to this project folder
3. Vercel will detect the `vercel.json` config and deploy `index.html` as a static site.

## Notes

- The current app stores data in browser `localStorage`.
- This means it is a static deployment without a remote database.
- If you want a real backend/database, I can add a Vercel API + Supabase/Supabase DB integration next.
