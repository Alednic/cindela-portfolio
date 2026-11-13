
# Cindela Portfolio

This static portfolio uses a single HTML file with CSS and a small amount of JavaScript. It needs no server or build step and can be hosted with GitHub Pages.

## Updating the content

- **Name, bio, and contact details:** edit the sections with `id="home"`, `id="about"`, and `id="contact"` in `index.html`.
- **Add a project:** copy one `<article class="card" ...>` block inside `.project-grid`, then update its title, description, tags, category, and links.
- **Categories:** use `data-category="web"`, `game`, `data`, `mobile`, or `design`. The filter buttons are in `.filters`.
- **Colors and typography:** edit the values in `:root` near the beginning of the `<style>` block.

## Adding images

Create an `images` folder next to `index.html`, then add image files using the names shown in comments on each project card. The four projects with screenshots each have a three-image collage. Files are named `starlight.jpeg` through `starlight3.jpeg`, `gamedev.jpeg` through `gamedev3.jpeg`, `GPdI.jpeg` through `GPdI3.jpeg`, and `where2go.jpeg` through `where2go3.jpeg`. If a project has no images, its colored cover remains as a placeholder. The hero currently uses a monogram that you can replace with a photo or illustration.

## GitHub Pages

Upload `index.html` to the root of your GitHub repository, then commit and push. In the repository, open **Settings → Pages**, choose deployment from your branch and the `/ (root)` folder, then save. GitHub Pages will publish the site after its deployment finishes.

The initial project details and profile links came from the `index.html` you provided. Update any GitHub links that should point to a specific project repository.
