# Personal Academic Website Template

This template combines the best elements from Alex Zhang's and Ben Eysenbach's academic websites:

- **Ben's Clean Navigation**: Simplified, professional navigation bar
- **Alex's Front Page Layout**: Beautiful spacing and structure
- **Alex's Blue Tag System**: Colored tags for research areas (NLP, ML, CV, RL, etc.)

## 🚀 Quick Setup Steps

### 1. Basic Information (_config.yml)
Replace the placeholder information:
```yaml
first_name: [YOUR_FIRST_NAME]     → first_name: John
middle_name: [YOUR_MIDDLE_NAME]   → middle_name: A. (optional)
last_name: [YOUR_LAST_NAME]       → last_name: Smith
email: [YOUR_EMAIL@DOMAIN.COM]    → email: john.smith@university.edu
```

### 2. About Page (_pages/about.md)
- Replace `[YOUR NAME]` with your name
- Replace `[YOUR RESEARCH AREAS]` with your research focus
- Update your subtitle/position
- Add your photo to `assets/img/your_photo.jpg`
- Update the research highlights section

### 3. Publications (_bibliography/papers.bib)
Replace template papers with your own:
```bibtex
@article{your_paper_id,
title={Your Paper Title},
author={Your Name and Coauthors},
year={2024},
abbr = {NLP},              # This creates the blue tag!
selected = {true},          # Shows on main page
preview = {preview.png},    # Image in assets/img/
code = {https://github.com/your-repo},
website = {https://your-project.com},
}
```

### 4. Profile Photo
- Add your photo to `assets/img/your_photo.jpg`
- Update the filename in `_pages/about.md`:
  ```yaml
  profile:
    image: your_photo.jpg
  ```

### 5. News Items (_news/)
Create news markdown files for updates:
```markdown
---
layout: post
date: 2024-01-15 12:00:00
title: Paper Accepted!
inline: true
---
Brief description of your news.
```

## 🎨 Design Features Preserved

### Blue Tag System (from Alex's site)
Available tags that will show as colored badges:
- `abbr = {NLP}` - Natural Language Processing (blue)
- `abbr = {ML}` - Machine Learning  
- `abbr = {CV}` - Computer Vision
- `abbr = {RL}` - Reinforcement Learning
- `abbr = {Dataset}` - Dataset papers
- `abbr = {Survey}` - Survey papers
- `abbr2 = {RL}` - Secondary tag (can combine with abbr)

### Clean Navigation (from Ben's site)
- Professional, minimal design
- Responsive mobile navigation
- Clean hover effects
- Social media integration ready

### Front Page Layout (from Alex's site)
- Perfect spacing and typography
- Research highlights section
- News and selected papers integration
- Professional academic styling

## 📁 Important Directories

- `_pages/about.md` - Main homepage content
- `_bibliography/papers.bib` - Your publications
- `_news/` - News items and updates  
- `assets/img/` - Images and photos
- `_config.yml` - Site configuration

## 🛠️ Local Development

1. Install Jekyll: `gem install bundler jekyll`
2. Install dependencies: `bundle install`
3. Run locally: `bundle exec jekyll serve`
4. View at: `http://localhost:4000`

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Push to a GitHub repository
2. Go to Settings → Pages
3. Set source to "GitHub Actions"
4. The site will build automatically

### Custom Domain (Optional)
1. Add CNAME file with your domain
2. Configure DNS settings
3. Enable HTTPS in GitHub Pages settings

## 📝 Content Tips

### Writing Good Research Highlights
- Keep descriptions concise but informative
- Group related papers together
- Use consistent formatting
- Include links to projects and code

### News Items
- Keep them short and scannable
- Include dates
- Link to relevant papers/projects
- Regular updates keep the site fresh

## 🎯 What's Included

✅ **From Alex's Site:**
- Beautiful front page layout and spacing
- Research highlights section structure
- Blue NLP/ML/CV tag system
- Professional typography and styling

✅ **From Ben's Site:**
- Clean, minimal navigation bar
- Professional header design
- Simplified social media integration

✅ **Template Additions:**
- Placeholder content for easy customization
- Clear setup instructions
- Example papers and news items
- Detailed commenting and documentation

## 🔧 Customization

The template is designed to be easily customizable. Most styling comes from the original al-folio theme, with specific enhancements from both researchers' sites preserved.

Feel free to modify colors, fonts, and layouts by editing the SCSS files in `_sass/`.

---

**Ready to launch your academic website!** 🎉

Replace the template content with your information and you'll have a professional academic website with the best design elements from both reference sites.