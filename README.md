# Polite Chaos Portfolio

> A modern, animated portfolio website built with Next.js, featuring smooth animations and a unique design aesthetic.

## 🚀 Live Demo

**[https://politechaos.netlify.app/](https://politechaos.netlify.app/)**

## ✨ Features

- **Modern Design**: Clean, minimalist interface with bold typography
- **Smooth Animations**: Powered by GSAP and Framer Motion for fluid transitions
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Components**: Dynamic menu, preloader, and scroll-triggered animations
- **Performance Optimized**: Built with Next.js 15 for optimal performance
- **SEO Friendly**: Meta tags and semantic HTML for better search visibility

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) - React framework with App Router
- **Styling**: CSS Modules with custom animations
- **Animations**: [GSAP](https://greensock.com/gsap/) + React GSAP
- **Smooth Scrolling**: [Lenis](https://github.com/studio-freight/lenis)
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **Typography**: Custom fonts (Neue Montreal, Pangram Sans, Big Shoulders Display)

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router pages
│   ├── page.jsx           # Home page
│   ├── contact/           # Contact page
│   ├── work/              # Portfolio work
│   ├── studio/            # Studio information
│   ├── stories/           # Client stories
│   └── sample-project/    # Project showcase
├── components/            # Reusable React components
│   ├── Button/            # Custom button component
│   ├── Menu/              # Navigation menu
│   ├── Footer/            # Site footer
│   ├── Preloader/         # Loading animation
│   └── ...               # Other UI components
└── hooks/                 # Custom React hooks
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anishpuj/polite-chaos.git
   cd polite-chaos
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📦 Build & Deployment

### Local Build

```bash
npm run build
npm start
```

### Deploy to Netlify

1. **Static Export** (already configured)
   ```bash
   npm run build
   ```
   
2. **Deploy**: Upload the `out/` folder to Netlify or connect your GitHub repository

### Deploy to Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel will auto-detect Next.js and deploy automatically

## 🎨 Customization

### Branding

- Update site metadata in `src/app/layout.js`
- Modify contact information in `src/app/contact/page.jsx`
- Update footer credits in `src/components/Footer/Footer.jsx`

### Styling

- Global styles: `src/app/globals.css`
- Component styles: Individual CSS files in each component folder
- Typography: Custom fonts in `public/fonts/`

### Animations

- GSAP animations are configured in individual components
- Smooth scrolling handled by Lenis
- View transitions powered by `next-view-transitions`

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile Safari/Chrome

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Anishpuj/polite-chaos/issues).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Anish Pujari**

- Portfolio: [https://politechaos.netlify.app/](https://politechaos.netlify.app/)
- GitHub: [@Anishpuj](https://github.com/Anishpuj)

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Animations by [GSAP](https://greensock.com/gsap/)
- Icons from [React Icons](https://react-icons.github.io/react-icons/)
- Smooth scrolling by [Studio Freight Lenis](https://github.com/studio-freight/lenis)

---

**⭐ If you like this project, please give it a star!**
