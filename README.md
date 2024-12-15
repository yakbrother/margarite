# 🚀 Margarite

## Yet Another Astro + Tailwind + DaisyUI Boilerplate

A modern, lightweight boilerplate combining the power of Astro with the utility of Tailwind CSS and the beautiful components of DaisyUI.

You can find many other boilerplates for Astro, but this is set up for my personal base for other templates. Feel free to make any suggestions/comments/complaints!

Tim Eaton
[timeaton.dev](https://www.timeaton.dev)

## ✨ Features

- [Astro](https://astro.build) - The web framework for content-driven websites
- [Tailwind CSS](https://tailwindcss.com) - A utility-first CSS framework
- [DaisyUI](https://daisyui.com) - The most popular Tailwind CSS component library
- Responsive layout out of the box
- Dark mode support
- Multiple theme options
- Type-safe configurations

## 📦 Prerequisites

- Node.js (version 14.18.0 or higher)
- npm or yarn or pnpm

## 🚀 Getting Started

1. Clone this repository:

```bash
git clone https://github.com/yakbrother/margarite.git
cd margarite
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and visit `http://localhost:4321`

## 📁 Project Structure

```
/
├── public/
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tailwind.config.cjs
```

## 🎨 Customization

### Themes

This boilerplate comes with multiple DaisyUI themes. You can modify the available themes in `tailwind.config.cjs`:

```js
daisyui: {
  themes: ["light", "dark", "synthwave"], // Add or remove themes
}
```

To switch themes, update the `data-theme` attribute in your HTML:

```html
<html lang="en" data-theme="dark"></html>
```

### Styles

Global styles can be added in `src/styles/global.css`. Tailwind utilities can be extended in `tailwind.config.cjs`.

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run astro` - Run Astro CLI commands

## 🔧 Configuration

### Astro Config

The `astro.config.mjs` file contains Astro-specific configurations. Modify this file to:

- Add new integrations
- Configure build settings
- Set up server options

### Tailwind Config

The `tailwind.config.cjs` file allows you to:

- Customize your theme
- Add new plugins
- Configure DaisyUI options
- Modify content sources

## 🎯 Best Practices

1. **Component Organization**

   - Keep components in `src/components`
   - Use `.astro` files for static components
   - Create reusable UI components

2. **Styling**

   - Use Tailwind utilities when possible
   - Create custom utilities in `tailwind.config.cjs`
   - Leverage DaisyUI components for common UI elements

3. **Performance**
   - Use Astro's built-in image optimization
   - Implement lazy loading for images
   - Minimize client-side JavaScript

## 📚 Resources

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [DaisyUI Documentation](https://daisyui.com/docs)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
