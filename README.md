# DSTRKT — Minimal E-commerce Frontend

A fully responsive, minimalist e-commerce frontend for DSTRKT, a brand focused on clean, type-driven grocery shopping experiences.

## 🎨 Design Philosophy

- **Minimalist**: Clean, uncluttered design with maximum whitespace
- **Type-driven**: Typography-focused design with PP Neue Montreal, Inter, and Diatype fonts
- **Responsive**: Fully responsive across all devices
- **Future-ready**: Structured for easy integration with backend APIs and CMS

## ✨ Features

### ✅ Implemented
- **Homepage** (`/`) - Hero section, category preview, newsletter signup
- **Category Pages** (`/category/[slug]`) - Dynamic routing with placeholder content
- **Product Pages** (`/product/[slug]`) - Template ready for future products
- **Categories Listing** (`/categories`) - All available categories
- **About Page** (`/about`) - Brand information
- **Cart Page** (`/cart`) - Shopping cart with placeholder state
- **Navigation** - Clean top navigation with mobile support
- **Footer** - Brand information and copyright
- **Animations** - Smooth fade-in animations using Framer Motion
- **Responsive Design** - Mobile-first approach

### 🔧 Technical Features
- **Next.js 14** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **Framer Motion** for animations
- **Dynamic Routing** for categories and products
- **Placeholder States** for future data integration

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd DSTRKT
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   ├── page.tsx           # Homepage
│   ├── categories/        # Categories listing
│   ├── category/[slug]/   # Dynamic category pages
│   ├── product/[slug]/    # Dynamic product pages
│   ├── about/             # About page
│   └── cart/              # Cart page
├── components/            # Reusable components
│   ├── Navigation.tsx     # Top navigation
│   └── Footer.tsx         # Footer component
```

## 🎯 Key Design Elements

### Color Scheme
- **Background**: Pure white (`#FFFFFF`)
- **Text**: Pure black (`#000000`)
- **Accents**: Black with opacity variations

### Typography
- **PP Neue Montreal**: Primary brand font
- **Inter**: Secondary font for body text
- **Diatype**: Monospace font for technical elements

### Layout
- **Grid System**: Responsive grid for product layouts
- **Spacing**: Generous whitespace and padding
- **Borders**: Subtle black borders with opacity

## 🔮 Future Integration Points

### Backend Integration
```typescript
// TODO: Replace placeholder functions with actual API calls
const fetchProducts = async () => {
  // Will fetch from backend API
}

const fetchCategories = async () => {
  // Will fetch from backend API
}
```

### CMS Integration
- Product data structure ready for headless CMS
- Category management system
- Content management for about page

### E-commerce Features
- Shopping cart functionality
- Checkout process
- User authentication
- Order management

## 🛠️ Development

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Adding New Pages
1. Create new directory in `src/app/`
2. Add `page.tsx` file
3. Follow existing component patterns

### Styling Guidelines
- Use Tailwind CSS classes
- Follow the established color scheme
- Maintain consistent spacing
- Use the specified font families

## 📱 Responsive Breakpoints

- **Mobile**: `< 768px`
- **Tablet**: `768px - 1024px`
- **Desktop**: `> 1024px`

## 🎨 Animation Guidelines

- **Fade-in**: 0.6-0.8s duration
- **Stagger**: 0.1s delay between items
- **Easing**: `ease-out` for natural feel

## 📄 License

This project is private and proprietary to DSTRKT.

---

**DSTRKT. — Minimal Groceries.**
© 2025 All rights reserved. 