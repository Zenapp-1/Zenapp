# AppCheon Web Clone - Next.js Project

A modern web clone of AppCheon built with Next.js, React, TypeScript, and Tailwind CSS.

## Features

- 🎨 Modern dark theme design
- 📱 Responsive layout with Tailwind CSS
- 🚀 Built with Next.js and TypeScript
- 💨 Fast performance with optimized components
- ✨ Interactive product cards
- 📱 Mobile-friendly design

## Getting Started

### Prerequisites

- Node.js 16+ 
- npm or yarn

### Installation

1. Install dependencies:

```bash
npm install
# or
yarn install
```

2. Run the development server:

```bash
npm run dev
# or
yarn dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
src/
├── app/
│   ├── layout.tsx      # Root layout component
│   ├── page.tsx        # Main page
│   └── globals.css     # Global styles with Tailwind
├── components/
│   ├── Header.tsx      # Header with logo and title
│   ├── ProductGrid.tsx # Product cards grid
│   └── SocialSection.tsx # Social links and information
└── ...
```

## Technologies Used

- **Next.js 14** - React framework
- **React 18** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript** - Dynamic functionality

## Customization

### Colors

Colors are defined in `tailwind.config.ts`. Adjust the theme colors as needed:

```typescript
theme: {
  extend: {
    colors: {
      dark: '#1f1f1f',
      darker: '#0a0a0a',
    },
  },
},
```

### Content

Edit component files in `src/components/` to customize:
- Product cards in `ProductGrid.tsx`
- Header content in `Header.tsx`
- Social links in `SocialSection.tsx`

## License

This project is open source and available under the MIT License.
