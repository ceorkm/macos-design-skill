# Skill Submission Guide

This skill is now ready to be published to multiple skill repositories!

## ✅ Already Published

### 1. GitHub Repository
- **URL**: https://github.com/ceorkm/macos-design-skill
- **Status**: ✅ Live
- **Visibility**: Public

## 📤 Ready to Submit

### 2. Anthropic Official Skills Repository

Submit a PR to the official repository: https://github.com/anthropics/skills

**Steps:**
1. Fork the `anthropics/skills` repository
2. Clone your fork locally
3. Copy your skill folder to `skills/macos-design/`
4. Create a PR with title: "Add macOS Design Skill"
5. In PR description, include:
   ```
   # macOS Design Skill

   Build native-feeling macOS applications that look like Apple designed them.

   ## What it does
   - Provides complete design system for macOS native apps
   - Includes layout patterns, visual design, and interaction guidelines
   - Comes with production-ready SnapVault demo

   ## Why it's useful
   - Captures years of Apple design knowledge
   - Exact CSS values and code snippets
   - Works for web, Electron, Tauri, native frameworks

   ## Testing
   - Skill successfully creates native-feeling macOS apps
   - Demo app (SnapVault) showcases all principles
   - Includes light/dark mode, vibrancy, animations, keyboard shortcuts
   ```

**Quick command:**
```bash
# Clone anthropics/skills
git clone https://github.com/anthropics/skills.git
cd skills/skills

# Copy your skill
cp -r /Users/femi/Downloads/files-2 macos-design

# Create branch and commit
git checkout -b add-macos-design-skill
git add macos-design/
git commit -m "Add macOS Design Skill"
git push origin add-macos-design-skill

# Then create PR on GitHub
```

---

### 3. Awesome Claude Skills

Submit to the community-curated list: https://github.com/travisvn/awesome-claude-skills

**Steps:**
1. Fork the repository
2. Edit `README.md`
3. Add your skill under the appropriate category (Design/UI)
4. Create PR with title: "Add macOS Design Skill"

**Entry to add:**
```markdown
### [macOS Design](https://github.com/ceorkm/macos-design-skill)
Build native-feeling macOS applications with complete design system including layout patterns, visual design, and interaction guidelines. Includes production-ready demo app.
```

---

### 4. Skills.sh Directory

Visit https://www.skills.sh (or the appropriate submission portal)

**Submission info:**
- **Skill Name**: macOS Design
- **Category**: Design & UI
- **Description**: Native macOS app design system - Build apps that feel like Apple designed them
- **Repository**: https://github.com/ceorkm/macos-design-skill
- **Demo**: Included (SnapVault)
- **Tags**: macos, design, ui, native, apple, desktop, electron, tauri

---

### 5. VoltAgent Awesome Agent Skills

Submit to: https://github.com/VoltAgent/awesome-agent-skills

Similar process to Awesome Claude Skills - add entry to appropriate category.

---

## Installation Methods Users Can Use

### Method 1: Claude Code CLI (Recommended)
```bash
claude code install https://github.com/ceorkm/macos-design-skill
```

### Method 2: Manual Installation
```bash
# Clone to Claude skills directory
git clone https://github.com/ceorkm/macos-design-skill \
  ~/.claude/skills/macos-design
```

### Method 3: Direct Download
1. Download ZIP from GitHub
2. Extract to `~/.claude/skills/macos-design/`
3. Restart Claude Code

---

## Promotion Checklist

- [x] GitHub repository created and pushed
- [ ] Submit PR to anthropics/skills
- [ ] Add to awesome-claude-skills
- [ ] Register on skills.sh directory
- [ ] Add to VoltAgent awesome-agent-skills
- [ ] Share on Twitter/X with #ClaudeCode #Skills
- [ ] Share on Reddit (r/ClaudeAI)
- [ ] Post on Hacker News (Show HN)
- [ ] Write blog post/tutorial

---

## Quick Stats

- **Lines of Code**: ~2,000
- **Files**: 7
- **Documentation**: 30KB+
- **Demo App**: Fully functional
- **Dependencies**: None (pure HTML/CSS/JS)

---

## Support

If users have questions:
- GitHub Issues: https://github.com/ceorkm/macos-design-skill/issues
- Demo: Open `snapvault.html` in browser
- Docs: Read reference files in `references/` directory
