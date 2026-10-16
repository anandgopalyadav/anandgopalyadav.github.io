# Anand Gopal Yadav — Portfolio

Static website: one index.html + images folder. No build step.

## Option A: Render (free)
1. Create a GitHub repo named `portfolio` and upload everything in this folder.
2. render.com -> New -> Static Site -> connect the repo.
3. Build command: (leave empty)   Publish directory: `.`
4. Deploy. You get https://<name>.onrender.com

## Option B: GitHub Pages (free, fastest)
1. Create a repo named `anandgopalyadav.github.io` and upload these files.
2. Repo -> Settings -> Pages -> Source: main branch, root.
3. Live at https://anandgopalyadav.github.io

## Option C: Netlify Drop
Drag this whole folder onto https://app.netlify.com/drop

## Edit content
Projects, services, skills and certificates are lists at the bottom of index.html
(search for `const P=`, `const SVCS=`, `const SKILLS=`, `const CERTS=`).
To add a project, copy one line in `const P=[...]` and change the text.
s: 'done' = Completed, 'next' = Upcoming.  u: GitHub link (optional).
