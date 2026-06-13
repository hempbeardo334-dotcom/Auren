# AUREN - AI Fashion Commerce Platform

A modern, AI-powered fashion ecommerce platform built with Next.js 16, TypeScript, and Tailwind CSS.

## 🚀 Features

- **AI-Powered Recommendations**: Intelligent fashion suggestions based on user preferences
- **Modern UI/UX**: Clean, responsive design with glassmorphism effects
- **Full Ecommerce Flow**: Browse, search, add to cart, and checkout
- **Product Management**: Dynamic product pages with size/color selection
- **User Dashboard**: Account management and order history
- **Admin Panel**: Store management and analytics
- **Search Functionality**: Real-time product search and filtering
- **Shopping Cart**: Persistent cart with quantity management
- **Responsive Design**: Mobile-first approach with desktop optimization

## 🛠️ Tech Stack

- **Framework**: Next.js 16 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Icons**: Lucide React
- **Notifications**: Sonner
- **Deployment**: Ready for Vercel/Netlify

## 📁 Project Structure

```
auren/
├── app/                    # Next.js app directory
│   ├── admin/             # Admin dashboard
│   ├── dashboard/         # User dashboard
│   ├── product/[slug]/    # Dynamic product pages
│   ├── shop/              # Shop page with search
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   ├── page.tsx           # Homepage
│   ├── loading.tsx        # Loading component
│   ├── error.tsx          # Error boundary
│   └── not-found.tsx      # 404 page
├── components/            # Reusable components
│   ├── navbar.tsx         # Navigation with search & profile
│   ├── cart-drawer.tsx    # Shopping cart sidebar
│   ├── product-card.tsx   # Product display card
│   └── footer.tsx         # Site footer
├── lib/                   # Utility functions
│   └── products.ts        # Product data & functions
├── store/                 # State management
│   └── cart-store.ts      # Shopping cart state
└── types/                 # TypeScript definitions
    └── index.ts           # Type definitions
```

## 🏃‍♂️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/auren.git
   cd auren
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   ```
   http://localhost:3000
   ```

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run typecheck` - Run TypeScript type checking

## 🎨 Design System

- **Colors**: Black (#080808), White, Gray variants
- **Typography**: Custom serif font for headings, system fonts for body
- **Spacing**: Consistent 4px grid system
- **Effects**: Glassmorphism, subtle shadows, smooth transitions

## 🔧 Configuration

### Tailwind CSS
Custom utilities and components are defined in `globals.css`.

### TypeScript
Strict type checking enabled with custom path aliases:
- `@/*` maps to `./*`

### Next.js
Configured for optimal performance with:
- Image optimization
- Static generation where possible
- Dynamic routes for products

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository
2. Deploy automatically on push
3. Environment variables configured in dashboard

### Netlify
1. Build command: `npm run build`
2. Publish directory: `.next`
3. Set environment variables

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Design inspiration from modern fashion ecommerce platforms
- Icons from Lucide React
- Images from Unsplash
- Built with love for fashion and technology enthusiasts

---

**AUREN** - Where AI meets fashion. 🛍️✨