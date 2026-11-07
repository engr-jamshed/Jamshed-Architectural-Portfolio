# J. Ahmed — Architectural Visualization Portfolio

A responsive, dark-luxury portfolio website. It is a static website and can be edited in a browser through GitHub, then published with Netlify.

## Quickest way to publish (no coding software required)

1. Create or sign in to a GitHub account: https://github.com/
2. Create a new repository, for example `jamshed-archviz-portfolio`.
3. Choose **Add file → Upload files** and upload `index.html` from this package. Commit the upload.
4. Create/sign in to Netlify: https://app.netlify.com/
5. Choose **Add new site → Import an existing project** and connect GitHub.
6. Select your new repository. Leave the build command and publish directory blank (or set publish directory to `.`), then deploy.
7. Netlify gives you a public website address. You can change the site name in Netlify's site settings.

## How to edit online

1. Open your GitHub repository in your browser.
2. Click `index.html`, then click the pencil **Edit this file** button.
3. Use Ctrl+F to find the text you want to change.
4. Edit the text or image URL, then click **Commit changes**.
5. Netlify automatically republishes the site after the GitHub change.

## Change your contact email

In `index.html`, search for `your.email@example.com` and replace every occurrence with your real email address. The contact form uses the visitor's email app (mailto); it is not a server-backed form.

## Change project images and details

Each project is an `<article class="project"...>` inside the section with `id="work"`.

- Replace the `src="https://..."` URL in its `<img>` tag with your image's public HTTPS URL.
- Change `data-title`, `data-type`, `data-year`, and `data-description`.
- Change the visible project heading and small category/year labels too.
- To add a project, duplicate one complete `<article>` block and edit its details.
- `data-category` must be one of: `exterior`, `interior`, `floorplan`, or `commercial` for the filters to work.

For reliable image hosting, use public image URLs or add your images to a folder in the GitHub repository (for example `images/villa-front.jpg`) and use `src="images/villa-front.jpg"`.

## Change your name, biography and links

Search for `J. AHMED`, `Jamshed Ahmed`, `Bangladesh`, and the social URLs, then replace them with your own details.

## Important notes

- The project photos included are illustrative sample photos, not your actual renders. Replace them before presenting the portfolio to clients.
- Skill bars are sample values. Adjust their widths in the `style="width:90%"` values.
- The website is static. The contact form opens the visitor's email program; it does not store submissions online.
- This package contains `index.html` and this guide. No build tools or paid software are required.
