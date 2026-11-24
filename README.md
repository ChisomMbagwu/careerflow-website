# Career Flow website

One page: `index.html`, plus the logo files in `assets/`.

## Preview it
Unzip, then double-click `index.html`. It opens in your browser. You need internet for the photos and font.

## Put it online (free)
- **Netlify:** go to app.netlify.com/drop and drag this whole folder in. You get a live link in about a minute. You can add a custom domain later.
- **GitHub Pages:** upload the folder to a repository, then turn on Pages under Settings.

## Change a photo
Photos load from the Career Flow Google Drive. In `index.html`, find `const PHOTOS` and `const GALLERY` near the bottom.
1. Open the photo in Drive and copy the ID from its link: `drive.google.com/file/d/THIS_PART/view`
2. Paste it in place of the old ID.

The photos must stay shared as "Anyone with the link".

**Before launch (recommended):** download the photos you use, shrink them to about 1600px wide (squoosh.app works well), put them in `assets/photos/`, and replace each ID with the path, for example `"assets/photos/hero.jpg"`. The page loads faster and stops depending on Drive.

## Edit text
All text is plain HTML in `index.html`. Search for the words you want to change.
Team members are in `const TEAM` near the bottom.

## Before going live
- Add sources for the three statistics in "The guidance gap" (marked TODO), or remove them.
- Add the Facebook and LinkedIn page links in the footer (marked TODO).
- The contact form opens the visitor's email app. To collect entries instead, connect it to Formspree or Google Forms.
