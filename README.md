# AI in Life Sciences Quiz Microsite

This package gives you a polished static landing page plus a post-quiz results summary page.

## Files
- `index.html` - landing page with quiz intro and Start Quiz button
- `results.html` - post-quiz summary page
- `styles.css` - shared styling
- `results.json` - editable stats for the results page

## Before you publish

### 1) Create your Microsoft Forms quiz
- Build the quiz in Microsoft Forms.
- Turn it into a quiz.
- Set the correct answers and points.
- Decide whether to collect participant names/emails.
- Copy the share link.

### 2) Add your Forms URL
Open `index.html` and replace this link:

```html
href="https://forms.office.com/"
```

with your actual Microsoft Forms quiz link.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder.
3. In GitHub, go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your branch (usually `main`) and folder `/root`.
6. Save. GitHub will publish your site and give you a URL.

## Publish on Vercel
1. Create a GitHub repository with these files.
2. Log into Vercel.
3. Click **Add New Project** and import the GitHub repo.
4. Keep default settings for a static site.
5. Deploy.
6. Vercel will generate a public URL.

## How to use the results page
After the quiz closes:
1. Export Microsoft Forms responses to Excel.
2. Calculate the summary numbers you want to show.
3. Edit `results.json` with your final values.
4. Commit/push the updated file.
5. Refresh `results.html` on your site.

## Suggested 3-day flow
- Day 1: Open quiz and share landing page URL
- Day 2: Reminder mail / Teams post
- Day 3: Close quiz and export results
- Day 4: Update `results.json` and share the summary page

## Optional improvements
- Replace placeholder participant names in `results.json`
- Add your own deadline text on the landing page
- Change colors in `styles.css` to match your team branding
