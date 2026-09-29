# SkillSync Vercel-ready website

This is a Vite + React website connected to the existing Google Apps Script backend.

## Deploy on Vercel
1. Extract this ZIP.
2. Upload the folder to a GitHub repository.
3. In Vercel, import that GitHub repository.
4. Framework preset: Vite.
5. Build command: `npm run build`
6. Output directory: `dist`
7. Deploy.

The Apps Script API URL is already configured in `src/main.jsx`.

## Important
The website uses the existing Apps Script endpoint as its backend and does not create Supabase/Firebase or another database.
