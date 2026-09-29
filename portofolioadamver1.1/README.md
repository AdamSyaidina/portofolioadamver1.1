# Adam Personal Portfolio - Static Version

Static version of the portfolio originally generated with Stitch.

## Changes
- Removed Flask/Python backend.
- Removed OpenRouter API calls.
- Removed server-side email handling.
- Removed `.env` and `requirements.txt`.
- Converted navigation to static `.html` pages.
- Cannt is now a local, predefined portfolio assistant. It does not call an AI API.
- Contact form opens the visitor's email client using `mailto:`.
- Original CSS and image assets are preserved.

## Deploy to Vercel
1. Put all files in this folder into a GitHub repository.
2. Import the repository into Vercel.
3. Framework Preset: Other.
4. Build Command: leave empty.
5. Output Directory: leave empty.
6. Deploy.

The root `index.html` is the entry page.
