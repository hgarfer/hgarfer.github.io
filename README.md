# Holger Garcia - Personal Website

This is the source code for my personal website hosted on GitHub Pages at [hgarfer.github.io](https://hgarfer.github.io).

## Design

The site features a clean, minimalist design inspired by modern portfolio websites with:

- Centered layout with the main title
- Four main sections: "To Work", "To Do", "To Try", "To Play"
- Social media integration (GitHub, LinkedIn, Steam)
- Responsive design that works on all devices
- Clean typography using the Inter font family

## Technology Stack

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting platform
- **SCSS** - CSS preprocessing
- **GitHub Actions** - Automated deployment

## Development

### Local Development

1. Install Ruby and Bundler
2. Clone the repository
3. Install dependencies:
   ```bash
   bundle install
   ```
4. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```
5. Visit `http://localhost:4000`

### Deployment

The site is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` branch.

## Customization

To customize the site for your own use:

1. Update `_config.yml` with your personal information
2. Modify the social links in `_layouts/home.html`
3. Customize the styling in `_sass/main.scss`
4. Add your own content sections as needed

## License

This project is open source and available under the [MIT License](LICENSE).