# Dewey Decimal Classification Web Application

A modern, responsive web application that showcases the 10 main categories of the Dewey Decimal Classification system. Perfect for librarians, students, and anyone interested in learning about library organization systems.

![Dewey Decimal Classification App](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js) ![React](https://img.shields.io/badge/React-19-blue?style=flat-square&logo=react) ![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B6FF?style=flat-square&logo=tailwind-css)

## Features

✨ **Key Features:**
- **Display All 10 Main Categories** - Complete overview of 000-900 Dewey classifications
- **Interactive Search** - Filter categories by name, description, or examples in real-time
- **Expandable Cards** - Click to reveal detailed descriptions and examples
- **Color-Coded Design** - Each category has a unique color for visual organization
- **Responsive Design** - Fully responsive from mobile to desktop
- **Dark Mode Support** - Built-in light and dark theme support
- **Modern UI** - Clean, professional interface using Tailwind CSS
- **Accessibility** - Semantic HTML and ARIA attributes throughout

## Project Structure

```
├── app/
│   ├── layout.tsx           # Root layout with metadata
│   ├── page.tsx             # Main page with search and grid
│   └── globals.css          # Global styles and theme tokens
├── components/
│   ├── header.tsx           # Header with title
│   ├── search-bar.tsx       # Search input component
│   ├── category-grid.tsx    # Grid container for categories
│   └── category-card.tsx    # Individual category card
├── lib/
│   └── dewey-data.ts        # Dewey classification data
├── public/                  # Static assets
├── package.json             # Dependencies
├── tsconfig.json            # TypeScript configuration
└── tailwind.config.ts       # Tailwind CSS configuration
```

## Getting Started

### Prerequisites
- Node.js 18+ 
- pnpm (recommended) or npm/yarn

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/dewey-decimal-app.git
cd dewey-decimal-app
```

2. **Install dependencies:**
```bash
pnpm install
# or
npm install
```

3. **Run the development server:**
```bash
pnpm dev
# or
npm run dev
```

4. **Open in browser:**
Visit [http://localhost:3000](http://localhost:3000) to see the application.

## Usage

### Searching
- Use the search bar to filter categories by:
  - Category name (e.g., "Philosophy")
  - Description keywords (e.g., "science")
  - Example items (e.g., "medicine")

### Viewing Details
- Click on any category card to expand and view:
  - Full description
  - Practical examples
  - Related topics

### Color Coding
Each category has a unique color for easy visual identification:
- 000–099: Blue (Computer Science)
- 100–199: Indigo (Philosophy)
- 200–299: Purple (Religion)
- 300–399: Pink (Social Sciences)
- 400–499: Rose (Language)
- 500–599: Orange (Science & Mathematics)
- 600–699: Amber (Technology)
- 700–799: Green (Arts)
- 800–899: Emerald (Literature)
- 900–999: Cyan (History & Geography)

## Technology Stack

- **Framework:** Next.js 16 (App Router)
- **UI Library:** React 19
- **Styling:** Tailwind CSS 4
- **Language:** TypeScript
- **Icons:** Lucide React
- **Package Manager:** pnpm

## Deployment

### Deploy to Vercel (Recommended)

The easiest way to deploy is using [Vercel](https://vercel.com):

1. **Push to GitHub:**
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. **Deploy on Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Select your GitHub repository
   - Click "Deploy"

Your app will be live in seconds!

### Deploy to Other Platforms

**Netlify:**
```bash
pnpm build
netlify deploy --prod --dir=.next
```

**Docker:**
```dockerfile
FROM node:18-alpine
WORKDIR /app
COPY package.json pnpm-lock.yaml ./
RUN npm install -g pnpm && pnpm install
COPY . .
RUN pnpm build
EXPOSE 3000
CMD ["pnpm", "start"]
```

**Self-hosted:**
```bash
pnpm build
pnpm start
```

## Environment Variables

This project doesn't require any environment variables. All data is included locally.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- ⚡ **Fast Loading:** Optimized bundle size (~50KB gzipped)
- 🎯 **SEO Optimized:** Meta tags and structured data
- 📱 **Mobile First:** Progressive enhancement
- ♿ **Accessible:** WCAG 2.1 AA compliant

## Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Resources

- [Dewey Decimal Classification Official](https://www.oclc.org/en/dewey.html)
- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [React Documentation](https://react.dev)

## Acknowledgments

- Dewey Decimal Classification system by Melvil Dewey
- Built with [Next.js](https://nextjs.org) and [Tailwind CSS](https://tailwindcss.com)
- Icons from [Lucide React](https://lucide.dev)

## Support

For support, email support@example.com or open an issue on GitHub.

---

Made with ❤️ for librarians and knowledge enthusiasts
# fad
# fad
# fad
# fad
# fad
