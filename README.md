# GeorgeSeverson.com

Personal website showcasing bio, book reports, and wine reviews. Built with Astro and powered by Notion API.

## 🚀 Project Status

**Phase 1: Complete ✅**
- GitHub repository created
- Astro project scaffolded with Tailwind CSS
- Homepage with placeholder bio
- Books and Wine placeholder pages
- Notion databases created with sample data

**Phase 2: Next Steps**
- Integrate Notion API to pull book reports
- Integrate Notion API to pull wine reviews
- Deploy to Netlify
- Connect custom domain

## 🛠️ Tech Stack

- **Frontend:** Astro (Static Site Generator)
- **Styling:** Tailwind CSS
- **CMS:** Notion API
- **Hosting:** Netlify (coming soon)
- **Version Control:** GitHub

## 📁 Project Structure

```
george-severson-website/
├── src/
│   ├── layouts/
│   │   └── Layout.astro        # Main layout template
│   ├── pages/
│   │   ├── index.astro         # Homepage
│   │   ├── books.astro         # Book reports page
│   │   └── wine.astro          # Wine reviews page
│   └── styles/
│       └── global.css          # Tailwind styles
├── public/                      # Static assets
├── .env                         # Environment variables (not in git)
└── astro.config.mjs            # Astro configuration
```

## 🗄️ Notion Databases

### Book Reports
- **Title** (text)
- **Author** (text)
- **Date Read** (date)
- **Rating** (select: 1-5 stars)
- **Review** (text)

🔗 [View Database](https://www.notion.so/3f7c9fe965c24711ab04f266e180971d)

### Wine Reviews
- **Wine Name** (text)
- **Vintage** (number)
- **Price** (number)
- **Rating** (select: 1-5 stars)
- **Tasting Notes** (text)
- **Date** (date)

🔗 [View Database](https://www.notion.so/cb0b6b08c3f748e6ba2fda8f0ac8c953)

## 💻 Local Development

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run development server:**
   ```bash
   npm run dev
   ```

3. **Open in browser:**
   ```
   http://localhost:4321
   ```

## 🌐 Deployment (Coming Soon)

We'll deploy to Netlify with:
- Automatic deploys from GitHub
- Custom domain (GeorgeSeverson.com)
- Free HTTPS
- Environment variables for Notion API

## 📝 Adding Content

**To add a book:**
1. Go to your [Book Reports database](https://www.notion.so/3f7c9fe965c24711ab04f266e180971d)
2. Click "+ New" to add a new entry
3. Fill in Title, Author, Date, Rating, and Review
4. The website will automatically update on next build

**To add wine:**
1. Go to your [Wine Reviews database](https://www.notion.so/cb0b6b08c3f748e6ba2fda8f0ac8c953)
2. Click "+ New" to add a new entry
3. Fill in Wine Name, Vintage, Price, Rating, Notes, and Date
4. The website will automatically update on next build

## 🔑 Environment Variables

Create a `.env` file (already created) with:
```
NOTION_API_KEY=your_key_here
NOTION_BOOKS_DATABASE_ID=your_books_db_id
NOTION_WINE_DATABASE_ID=your_wine_db_id
```

## 🎯 Cost Breakdown

- Domain: ~$12/year (GeorgeSeverson.com)
- Hosting: $0 (Netlify free tier)
- Notion API: $0 (free)
- **Total: ~$12/year**

## 📚 Learning Resources

- [Astro Docs](https://docs.astro.build)
- [Notion API](https://developers.notion.com)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [Netlify Deploy](https://docs.netlify.com)

---

Built with ❤️ and AI assistance
