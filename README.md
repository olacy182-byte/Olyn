# Olayinka. L portfolio (homepage)

A one-page portfolio website. It uses plain HTML, CSS and a little JavaScript, so it needs no build step and no installs.

## What is in this folder

```
index.html            The homepage. Text, layout, colours and scripts are all in this one file.
assets/
  images/
    logo.png                  Your logo (header and footer)
    portrait.jpg              Your photo (About section)
    hero-animation.gif        The phone animation in the top section
    hero-animation-still.jpg  Still picture shown if a visitor has reduced motion turned on
    one-person-monitor.jpg    Picture in "One person for the whole job"
    services/                 The eight pictures on the "My services" cards
    projects/                 The pictures on the "Selected work" cards
README.md             This file
```

## How to change things

- **Text:** open index.html in any text editor (VS Code, Notepad) and search for the words you want to change.
- **Pictures:** save your new picture into the same folder with the same file name to replace one. To use a different name, change the `src="..."` in index.html.
- **Colours:** at the top of index.html, inside `<style>`, the `:root { ... }` block holds every colour. Change them there once and the whole page updates.
- **Email address:** search for `Olacy182@gmail.com` and change it in each place it appears.

## Put it online with Vercel

1. Create a free account at vercel.com.
2. Upload this whole folder (index.html and the assets folder) to a new GitHub repository.
3. In Vercel choose Add New, then Project, import that repository, leave the settings as they are and press Deploy.
4. When you change a file on GitHub, Vercel updates the live site by itself.

## Notes

- The sample project and service pictures are placeholders. Replace them with your own work before sharing the site widely.
- The fonts load from Google Fonts, so they need an internet connection.
- The "Write the email" button in the quote form opens the visitor's email app. It does not send messages by itself.
