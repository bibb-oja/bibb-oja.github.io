# OJA Research Team Website

Jekyll-based GitHub Pages site for the Job Advertisement Analysis research team.

## Quick Start

### Prerequisites
- Ruby 3.0 or higher
- Bundler

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000` in your browser

### Deployment

Push to GitHub and GitHub Pages will automatically build and deploy:
```bash
git push origin main
```

Your site will be available at: `https://bibb-oja.github.io`

## Editing Content

### Publications
Edit `_data/publications.yml` to add/update publications.

### Student Topics
Edit `_data/topics.yml` to add/modify research topics by category.

### Team Members
Edit `_data/team.yml` to update team information.

### Pages
- `index.md` - Home page
- `publications.md` - Publications section
- `topics.md` - Student topics section
- `team.md` - Team section

## Structure

```
.
├── _config.yml              # Jekyll configuration
├── _data/
│   ├── publications.yml     # Publications data
│   ├── topics.yml          # Research topics data
│   └── team.yml            # Team members data
├── index.md                # Home page
├── publications.md         # Publications page
├── topics.md               # Student topics page
├── team.md                 # Team page
└── Gemfile                 # Ruby dependencies
```

## Theme

Uses Jekyll's default **minima** theme with clean, academic styling. To customize styling, create `_sass/custom.scss`.

## Notes

- The site maintains minimal connection to BIBB while being supported by them
- All content is easily editable through YAML files
- GitHub Pages builds automatically on each push
