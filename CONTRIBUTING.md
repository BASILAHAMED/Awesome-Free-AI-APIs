# Contributing to Awesome Free AI APIs

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing.

## 📝 How to Contribute

### Adding a New API

1. **Check if the API qualifies**:
   - Must have a **free tier** (no credit card required OR free credits)
   - Must be AI/ML related (NLP, CV, Speech, etc.)
   - Must be publicly available (not private beta)

2. **Add the API to the appropriate category** in `README.md`:

```markdown
| API Name | Description | Free Tier | Credits/Auth | Docs |
|----------|-------------|-----------|--------------|------|
| New API | What it does | ✅ Yes/No | Details | [docs](URL) |
```

3. **Fields explanation**:
   - **API Name**: Official name (link to docs if possible)
   - **Description**: One-line summary of capabilities
   - **Free Tier**: ✅ Yes if free tier exists, ❌ No if only trial
   - **Credits/Auth**: Free credits amount, or "Free" for no-credit-card required
   - **Docs**: Link to official documentation

4. **Ensure alphabetical order** within each category

### Updating Existing APIs

- **Free tier changed?** Update the "Free Tier" and "Credits/Auth" columns
- **Documentation link broken?** Fix it
- **Better description?** Improve it
- **API discontinued?** Remove it with a note in PR

### Adding Categories

If you know of a new AI category not listed:
1. Create a new section with appropriate heading
2. Add a brief description
3. Add APIs in alphabetical order

## 🔍 Quality Standards

### Must-Have Requirements
- ✅ Free tier available (or free credits to start)
- ✅ Publicly accessible API (not invite-only)
- ✅ Official documentation exists
- ✅ AI/ML related (not just general APIs)

### Nice-to-Have
- 🎯 Clear free tier limits (requests/month, tokens, etc.)
- 📚 Good documentation with examples
- 🔧 SDKs in popular languages
- ⚡ Low latency (< 1s typical)
- 🏢 Active maintenance

### Avoid
- ❌ APIs requiring paid subscription only
- ❌ Self-hosted only (unless packaged as service)
- ❌ Beta APIs with no clear free tier
- ❌ APIs that are clearly deprecated

## 📋 Pull Request Checklist

- [ ] API has genuine free tier (tested/verified)
- [ ] Added to correct category
- [ ] Alphabetical order maintained
- [ ] Documentation link works
- [ ] No markdown formatting errors
- [ ] Description is clear and concise
- [ ] Free tier details are accurate
- [ ] No duplicate entries

## 🐛 Reporting Issues

Found an issue? Please create an issue with:
- API name
- Problem description
- Steps to reproduce (if applicable)
- Suggested fix

## 📊 Data Sources

We primarily source APIs from:
- [public-apis/public-apis](https://github.com/public-apis/public-apis) (Machine Learning, Text Analysis sections)
- Direct company announcements
- Community submissions

## 🎯 Goal

Our mission: **Help developers find and use FREE AI APIs for learning and building.**

We want to:
- Lower barriers to entry for AI/ML
- Promote APIs with generous free tiers
- Help developers avoid "bait-and-switch" services
- Build a trusted resource for the community

## 📞 Contact

- Create an issue for questions
- Follow the repository for updates

---

**Happy contributing! 🚀**