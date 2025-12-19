# DevFolio - Next.js Developer Portfolio

A modern, responsive developer portfolio template built with Next.js, TypeScript, Tailwind CSS, and Framer Motion.

## 🚀 Features

- ⚡ **Next.js 15** with App Router
- 🎨 **Tailwind CSS** for styling
- 🎭 **Framer Motion** for smooth animations
- 📱 **Fully Responsive** design
- 🎯 **TypeScript** for type safety
- ⚙️ **Smooth Scrolling** navigation
- 🖼️ **Image Optimization** with Next.js Image component
- 🎪 **Interactive Components** with React hooks
- ✨ **Typed.js** integration for dynamic text animation
- 📊 **Intersection Observer** for scroll-triggered animations

## 📦 Sections

- **Hero** - Eye-catching introduction with typed text animation
- **About** - Personal information with animated skill bars
- **Services** - Showcase your services with hover effects
- **Experience** - Timeline of your work experience
- **Portfolio** - Filterable project gallery
- **Pricing** - Display your pricing plans
- **Testimonials** - Client reviews with carousel
- **Team** - Showcase your team members
- **Contact** - Contact form
- **Blog** - Latest articles and posts
- **Footer** - Social links and contact information

## 🛠️ Installation

### Prerequisites

- Node.js 18.17 or later
- npm, yarn, or pnpm

### Setup

1. **Clone or navigate to the project directory**

```bash
cd your-project-directory
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

Navigate to [http://localhost:3000](http://localhost:3000) to see your portfolio.

## 🎨 Customization

### Update Personal Information

Edit the components to personalize your portfolio:

- **Hero Section**: `components/Hero.tsx` - Update name, titles, and typed text strings
- **About Section**: `components/About.tsx` - Update bio, skills, and experience
- **Footer**: `components/Footer.tsx` - Update name, address, and contact details

### Change Colors

The main theme color is defined in `tailwind.config.ts`:

```typescript
colors: {
  primary: '#EF233C', // Change this to your preferred color
  dark: '#414141',
  light: '#797979',
}
```

### Add/Remove Sections

In `app/page.tsx`, you can easily add or remove sections by commenting out or adding component imports.

### Update Images

Replace images in the `public/img/` directory with your own:

- `hero.png` - Your hero image
- `hero-bg.jpg` - Hero background
- `about.jpg` - About section image
- `portfolio-1.jpg` to `portfolio-6.jpg` - Your projects
- `team-1.jpg` to `team-4.jpg` - Team member photos
- `testimonial-1.jpg` to `testimonial-3.jpg` - Client photos
- `blog-1.jpg` and `blog-2.jpg` - Blog post images
- `contact.jpg` - Contact section background

## 📁 Project Structure

```
.
├── app/
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Main page
├── components/
│   ├── About.tsx            # About section
│   ├── BackToTop.tsx        # Back to top button
│   ├── Banner.tsx           # Promotional banner
│   ├── Blog.tsx             # Blog section
│   ├── Contact.tsx          # Contact form
│   ├── Experience.tsx       # Experience timeline
│   ├── Footer.tsx           # Footer
│   ├── Hero.tsx             # Hero section
│   ├── Navbar.tsx           # Navigation bar
│   ├── Portfolio.tsx        # Portfolio gallery
│   ├── Price.tsx            # Pricing section
│   ├── Service.tsx          # Services section
│   ├── Team.tsx             # Team section
│   └── Testimonial.tsx      # Testimonials carousel
├── public/
│   └── img/                 # Images
├── next.config.js           # Next.js configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
└── package.json             # Dependencies

```

## 🚢 Deployment

### Deploy on Vercel (Recommended)

The easiest way to deploy your Next.js app is to use [Vercel](https://vercel.com):

1. Push your code to GitHub/GitLab/Bitbucket
2. Import your repository on Vercel
3. Vercel will automatically detect Next.js and configure the build settings
4. Click "Deploy"

### Other Platforms

You can also deploy to:
- **Netlify**: Use the Next.js plugin
- **AWS Amplify**: Configure build settings for Next.js
- **Docker**: Use the included Dockerfile (create one if needed)

### Build for Production

```bash
npm run build
npm run start
```

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This template is based on the DevFolio HTML template from [HTML Codex](https://htmlcodex.com).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

## 💡 Tips

1. **Optimize Images**: Use WebP format for better performance
2. **SEO**: Update metadata in `app/layout.tsx`
3. **Analytics**: Add Google Analytics or other tracking tools
4. **Performance**: Run Lighthouse audits to optimize performance
5. **Accessibility**: Test with screen readers and keyboard navigation

## 📞 Support

If you have any questions or need help, feel free to open an issue or reach out!

---

**Built with ❤️ using Next.js**

