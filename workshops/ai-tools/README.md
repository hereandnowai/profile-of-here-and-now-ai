# AI Tools Gallery

A comprehensive, filterable gallery of AI-powered tools for educators, professionals, and researchers.

## 🌐 Live Site
**URL:** https://hereandnowai.pages.dev/workshops/ai-tools/

## ✨ Features

### Advanced Filtering
- **By Profession**: Teachers, HR, Marketing, Sales, Customer Service, Researchers, Developers, CEOs
- **By Pricing**: Free, Freemium (Free Tier Available), Paid
- **By Search**: Real-time search across tool names, descriptions, and features

### Tool Information
Each tool card displays:
- Tool name with logo
- Pricing badge (color-coded)
- Detailed description
- Key features as tags
- Direct link to the tool

### Design
- HERE AND NOW AI branding (Yellow #FFDF00, Teal #004040)
- Responsive grid layout
- Animated stat counters
- Smooth hover effects
- Card animations on load

## 📋 Currently Listed Tools (15)

### Education-Focused Tools
1. **Khanmigo** - Free AI teaching assistant by Khan Academy
2. **Brisk Teaching** - Chrome/Edge extension for lesson planning
3. **Eduaide.Ai** - Library of AI-powered educational resources
4. **MagicSchool AI** - 60+ AI tools for educators
5. **Canva for Education** - Design platform with AI assistant
6. **Diffit** - Adapts resources to reading levels
7. **Curipod** - Interactive lesson creator
8. **Gradescope** - AI-assisted grading platform
9. **Microsoft Immersive Reader** - Accessibility tool

### General AI Assistants
10. **Google Gemini** - Multi-purpose AI assistant
11. **OpenAI ChatGPT** - Conversational AI
12. **Microsoft Copilot** - Microsoft 365 integration
13. **Anthropic Claude** - Research and curriculum AI
14. **Google NotebookLM** - AI research notebook
15. **Canva Magic Studio** - AI-powered design assistant

## 🔧 How to Add New Tools

To add a new AI tool to the gallery, edit the `aiTools` array in `index.html`:

```javascript
{
    name: "Tool Name",
    logo: "TN",  // 2-3 letter abbreviation
    description: "Detailed description of the tool and its capabilities...",
    url: "https://tool-website.com",
    pricing: "free",  // Options: "free", "freemium", "paid"
    professions: ["teachers", "developers"],  // Array of applicable professions
    features: ["Feature 1", "Feature 2", "Feature 3"]  // Key features as tags
}
```

### Profession Options
- `teachers`
- `hr`
- `marketing`
- `sales`
- `customer-service`
- `researchers`
- `developers`
- `ceos`

### Pricing Options
- `free` - Completely free
- `freemium` - Free tier available with paid upgrades
- `paid` - Paid only

## 🎨 Branding Colors

- **Primary Yellow**: `#FFDF00`
- **Secondary Teal**: `#004040`
- **Background Dark**: `#0a0a0a`
- **Background Secondary**: `#1a1a1a`

## 📱 Responsive Design

The gallery is fully responsive and works seamlessly on:
- Desktop (1400px+ max-width)
- Tablet (768px - 1399px)
- Mobile (<768px)

## 🚀 Deployment

The site is automatically deployed to Cloudflare Pages when changes are pushed to the main branch.

**Deploy command:**
```bash
wrangler pages deploy . --project-name=hereandnowai --branch=main
```

## 📊 Statistics

- **Total Tools**: 15 (and growing)
- **Professions Covered**: 8
- **Free Tools**: 4
- **Freemium Tools**: 10
- **Paid Tools**: 1

## 🔮 Future Enhancements

Potential features to add:
- User ratings and reviews
- Favorites/bookmarking
- Tool comparisons
- Category tags (beyond profession)
- Video demos/tutorials
- Integration guides
- Community contributions

## 📞 Contact

**HERE AND NOW AI**
- Website: https://hereandnowai.com
- Email: info@hereandnowai.com
- Mobile: +91 996 296 1000

---

*Last Updated: December 15, 2025*
