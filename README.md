# 🌟 Perfume Shops Comparison

![pic](/public/duhi.png)
A web application for comparing various perfume shops and decant services in Russia. Built with Astro to ensure fast performance and excellent SEO optimization.

## ✨ Features

- 🏪 Detailed shop cards with ratings and reviews
- 📱 Responsive design for all devices
- 🎨 Modern interface with glass effect
- 📝 Blog with useful articles about perfumery
- 📊 Yandex.Metrika analytics integration
- 🔍 SEO optimization for better search visibility

## 🛠 Technologies

- [Astro](https://astro.build) - modern framework for building fast websites
- CSS with modern features (gradients, backdrop-filter)
- Google Fonts (Montserrat)
- Yandex.Metrika for analytics

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navigation.astro   # Navigation menu
│   │   ├── Footer.astro       # Site footer
│   │   └── PerfumeGrid.astro  # Shop cards grid
│   ├── data/
│   │   └── sellers/           # JSON files with shop data
│   ├── layouts/
│   │   └── Layout.astro       # Base page template
│   └── pages/
│       ├── index.astro        # Home page
│       ├── blog/              # Blog section
│       └── seller/            # Shop pages
```

## 🚀 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/temaprint/perfume.git
cd perfume
```

2. **Install dependencies**

```bash
npm install
```

3. **Run development server**

```bash
npm run dev
```

4. **Build for production**

```bash
npm run build
```

## 💻 Development

### Adding a New Shop

1. Create a new JSON file in `src/data/sellers/`
2. Follow this structure:

```json
{
  "name": "Shop Name",
  "emoji": "🏪",
  "website": "https://example.com",
  "chat": "https://t.me/example",
  "description": "Shop description",
  "authenticity": "✅ Original",
  "price": "💲💲 Average prices",
  "fragrances": "🌸 Assortment description",
  "reviews": "⭐ 4.8 (150 reviews)",
  "rating": 4.8,
  "pros": ["Advantage 1", "Advantage 2"],
  "cons": ["Disadvantage 1", "Disadvantage 2"],
  "customer_reviews": [
    {
      "author": "Name",
      "text": "Review text"
    }
  ]
}
```

### Adding a New Article

1. Create a new `.astro` file in `src/pages/blog/`
2. Add the article to the list on `src/pages/blog/index.astro`

## 📱 Responsiveness

The site is adapted for various devices:

- 📱 Mobile: < 768px
- 📱 Tablets: < 1200px
- 🖥 Desktop: ≥ 1200px

## 🔍 SEO

- Semantic HTML markup
- Optimized meta tags
- Fast page loading
- Responsive design
- Structured data

## 📈 Analytics

The site uses Yandex.Metrika to track:

- 👥 Traffic
- 🔄 User behavior
- 📊 Conversions
- 📱 Visitor devices

## 🤝 Contributing

1. Fork the repository
2. Create a branch for your changes
3. Make your changes
4. Create a Pull Request

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 👥 Authors

- [t3ma](https://temaprint.com)

## 🙏 Acknowledgments

- [Astro](https://astro.build) for the excellent framework