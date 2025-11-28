# SINz Peaks Website

This is the official static website for **SINz Peaks**, a game and app development studio. The site showcases our games, dev logs, and studio information, and is optimized for Google Play developer identity verification.

## Features

- Clean, modern, minimal design with a futuristic touch
- Fully responsive layout
- Mobile hamburger navigation
- SEO optimized with meta tags and Open Graph
- Contact form with JavaScript validation
- Blog-style dev logs
- Ready for GitHub Pages deployment

## Running Locally

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/sinzpeaks.git
   cd sinzpeaks
   ```

2. Open `index.html` in your web browser.

No server required; it's a static site.

## Deploying to GitHub Pages

1. Create a new repository on GitHub named `sinzpeaks` (or your preferred name).

2. Push this code to the `main` branch:
   ```
   git init
   git add .
   git commit -m "Initial commit: SINz Peaks website"
   git branch -M main
   git remote add origin https://github.com/yourusername/sinzpeaks.git
   git push -u origin main
   ```

3. Go to your repository on GitHub.

4. Navigate to **Settings** > **Pages**.

5. Under **Source**, select **GitHub Actions**.

6. The site will be available at `https://yourusername.github.io/sinzpeaks/`.

## Custom Domain (Optional)

To use a custom domain:

1. Create a `CNAME` file in the root with your domain (e.g., `www.sinzpeaks.com`).

2. Update your DNS settings to point to GitHub Pages.

3. Enable the custom domain in repository settings.

## Adding New Games

1. Add game images to `assets/images/`.

2. Edit `games.html` and add a new `<div class="game-item">` with the game details.

## Adding New Dev Logs

1. Create a new HTML file in the `blog/` folder (e.g., `new-post.html`).

2. Add the post link to `devlogs.html` in the `<div class="posts">` section.

3. Follow the structure of `blog/sample-post.html`.

## Customization

- **Colors**: Edit the CSS variables or direct colors in `assets/css/style.css`.
- **Fonts**: Change the `font-family` in the CSS.
- **Logo**: Replace `assets/images/logo.svg` with your custom logo.
- **Content**: Update text in the HTML files as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.