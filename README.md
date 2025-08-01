# 🛍️ StyleHub - Fashion E-Commerce Platform

A modern, responsive fashion e-commerce web application built with Next.js, TypeScript, and Tailwind CSS. Browse and buy everything from watches, shoes, pants, jeans, t-shirts, shirts, belts, and more — all in one place.

![StyleHub Preview](https://via.placeholder.com/800x400/ed751a/ffffff?text=StyleHub+Fashion+E-Commerce)

## ✨ Features

### 🛒 Shopping Experience
- **Full Product Catalog** - Browse products across all fashion categories
- **Advanced Search & Filtering** - Find products by category, price, and more
- **Product Details** - Comprehensive product information with images, ratings, and reviews
- **Shopping Cart** - Add, remove, and manage items with quantity controls
- **Wishlist** - Save favorite items for later

### 🎨 Modern UI/UX
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Clean Product Grids** - Beautiful product cards with hover effects
- **Smooth Animations** - Framer Motion powered interactions
- **Modern Color Scheme** - Professional orange and gray color palette
- **Loading States** - Smooth loading experiences throughout the app

### 🔧 Technical Features
- **TypeScript** - Full type safety and better development experience
- **State Management** - Zustand for cart and global state
- **Toast Notifications** - User feedback with react-hot-toast
- **Image Optimization** - Next.js Image component for performance
- **SEO Optimized** - Meta tags and structured data

### 📱 Mobile-First Design
- **Touch-Friendly** - Optimized for mobile interactions
- **Responsive Navigation** - Collapsible mobile menu
- **Mobile Cart** - Easy cart management on mobile devices
- **Fast Loading** - Optimized for mobile networks

## 🚀 Tech Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Lucide React** - Beautiful icons

### State Management
- **Zustand** - Lightweight state management
- **React Hooks** - Modern React patterns

### Development Tools
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## 📦 Installation & Setup

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Quick Start

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd fashion-ecommerce
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

## 🏗️ Project Structure

```
fashion-ecommerce/
├── app/                    # Next.js App Router
│   ├── cart/              # Cart page
│   ├── products/          # Products listing page
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Homepage
├── components/            # Reusable components
│   ├── Header.tsx         # Navigation header
│   ├── Hero.tsx           # Hero section
│   ├── ProductCard.tsx    # Product display card
│   └── CategoryCard.tsx   # Category display card
├── data/                  # Static data
│   └── products.ts        # Product data
├── lib/                   # Utility functions
│   └── utils.ts           # Common utilities
├── store/                 # State management
│   └── cart.ts            # Cart store (Zustand)
├── types/                 # TypeScript types
│   └── index.ts           # Type definitions
└── public/                # Static assets
```

## 🎯 Key Components

### Product Management
- **Product Data** - Comprehensive product information with images, prices, and variants
- **Category System** - Organized product categories with icons
- **Search & Filter** - Advanced filtering by category, price, and search terms
- **Product Cards** - Beautiful product display with hover effects

### Shopping Cart
- **Cart Store** - Persistent cart state with Zustand
- **Quantity Controls** - Add, remove, and update item quantities
- **Price Calculations** - Automatic subtotal, tax, and shipping calculations
- **Cart Persistence** - Cart data saved to localStorage

### User Interface
- **Responsive Header** - Navigation with search and cart
- **Hero Section** - Compelling homepage introduction
- **Product Grid** - Responsive product layout
- **Mobile Menu** - Collapsible navigation for mobile

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file for environment-specific configuration:

```env
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_key
NEXT_PUBLIC_API_URL=your_api_url
```

### Tailwind Configuration
The project uses a custom Tailwind configuration with:
- Custom color palette (primary orange theme)
- Custom animations and transitions
- Responsive breakpoints
- Component utilities

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically

### Other Platforms
The app can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- DigitalOcean App Platform
- Railway

## 🔮 Future Enhancements

### Planned Features
- **User Authentication** - Login/signup functionality
- **Payment Integration** - Stripe payment processing
- **Order Management** - Order history and tracking
- **Product Reviews** - User review system
- **Inventory Management** - Stock tracking
- **Admin Dashboard** - Product management interface

### Technical Improvements
- **Database Integration** - Replace static data with real database
- **API Routes** - Backend API endpoints
- **Image Upload** - Product image management
- **Search API** - Advanced search functionality
- **Performance Optimization** - Code splitting and lazy loading

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Unsplash** - Product images
- **Lucide** - Beautiful icons
- **Tailwind CSS** - Utility-first CSS framework
- **Next.js Team** - Amazing React framework

---

**Built with ❤️ using Next.js, TypeScript, and Tailwind CSS** 