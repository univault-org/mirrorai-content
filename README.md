# MirrorAI Content

This repository contains all content for MirrorAI, including blog posts, guides, and documentation.

## 📁 Structure

```
mirrorai-content/
├── README.md
├── blog/
│   ├── _drafts/          # Work in progress
│   ├── _published/       # Published posts
│   └── assets/           # Images and media
└── .github/
    └── workflows/
        └── quality-check.yml
```

## 🚀 Contributing

### For Content Contributors:
1. **Fork** this repository
2. **Create** a new branch for your content
3. **Write** your blog post in `blog/_drafts/`
4. **Submit** a pull request
5. **Content** will be automatically published to mirrorai.me

### For Team Members:
1. **Clone** main app with submodules: `git clone --recursive`
2. **Update** content: `git submodule update --remote`
3. **Test** locally: `pnpm dev`
4. **Deploy**: `pnpm deploy`

## 📝 Blog Post Format

```markdown
---
title: "Your Blog Post Title"
description: "Brief description for SEO"
date: "2024-01-15"
author: "Your Name"
tags: ["voice-coaching", "breathing", "ai"]
---

Your content here...
```

## 🎯 Quality Guidelines

- **Clear, engaging writing**
- **SEO-optimized** titles and descriptions
- **Relevant tags** and categories
- **High-quality images** (if applicable)
- **Proper markdown formatting**

## 🔗 Links

- **Main App**: [mirror-ai-app](https://github.com/univault-org/mirror-ai-app)
- **Live Site**: [mirrorai.me](https://mirrorai.me)
- **Blog**: [mirrorai.me/blog](https://mirrorai.me/blog)

## 📊 Content Categories

- **Voice Coaching**: Techniques and tips
- **Breathing Analytics**: Breathing pattern analysis
- **AI Technology**: MirrorAI features and updates
- **Case Studies**: Real-world applications
- **Tutorials**: Step-by-step guides

---

*This content repository is automatically synced with the main MirrorAI application.* 