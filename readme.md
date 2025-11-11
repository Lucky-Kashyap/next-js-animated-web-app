# Cam Shot Website

A modern, high-performance web application built with Next.js for managing and showcasing photography content. Revolutionize how you manage event photos and delight your clients with cutting-edge AI technology.

## 🚀 Features

- **AI-Powered Photo Filtering** - Guests can instantly find their photos by taking a selfie
- **Secure Sharing Options** - Flexible access via QR codes, links, or PINs
- **Event Photo Collections** - Organize photos into curated collections for easy access
- **Multi-Event Management** - Easily manage multiple clients and events simultaneously
- **White-Labeled Experience** - Custom-branded experience for photographers and studios
- **Advanced Analytics** - Track event performance and client engagement
- Modern, responsive design with smooth animations
- Optimized image and video handling for fast loading
- User-friendly interface with intuitive navigation
- SEO optimized with Next.js server-side rendering

## 🛠️ Tech Stack

- **Next.js 14+** - React framework with App Router
- **React 18+** - UI library
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - High-quality React components
- **Bits UI** - Accessible component primitives
- **Framer Motion** - Animation library for smooth transitions
- **Next/Image** - Optimized image handling
- **Next/Video** - Optimized video handling

## 📋 Prerequisites

- Node.js 18+ (LTS version recommended)
- npm, yarn, or pnpm package manager

## 🔧 Installation

1. Clone the repository:

```bash
git clone [your-repository-url]
cd cam-shot-website
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Set up environment variables:

```bash
cp .env.example .env.local
```

Edit `.env.local` with your configuration values.

## 🚀 Development

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Navigate to `http://localhost:3000/`. The application will automatically reload if you change any of the source files.

## 🏗️ Build

Build the project for production:

```bash
npm run build
# or
yarn build
# or
pnpm build
```

Start the production server:

```bash
npm start
# or
yarn start
# or
pnpm start
```

The build artifacts will be stored in the `.next/` directory.

## 🧪 Testing

Run unit tests:

```bash
npm test
# or
yarn test
# or
pnpm test
```

Run linting:

```bash
npm run lint
# or
yarn lint
# or
pnpm lint
```

## 📁 Project Structure

```
cam-shot-website/
├── src/
│   ├── app/                 # Next.js App Router pages
│   │   ├── layout.tsx       # Root layout
│   │   ├── page.tsx         # Home page
│   │   └── ...
│   ├── components/          # React components
│   │   ├── ui/              # shadcn/ui components
│   │   └── ...
│   ├── lib/                 # Utility functions
│   ├── hooks/               # Custom React hooks
│   ├── styles/              # Global styles
│   └── ...
├── public/                  # Static assets (images, videos)
├── components.json          # shadcn/ui configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── next.config.js           # Next.js configuration
├── tsconfig.json            # TypeScript configuration
├── package.json             # Project dependencies
└── README.md               # Project documentation
```

## 🎨 Styling & Components

This project uses:

- **Tailwind CSS** for utility-first styling
- **shadcn/ui** for pre-built, customizable components
- **Bits UI** for accessible component primitives
- **Framer Motion** for smooth animations and transitions

## 🖼️ Image & Video Optimization

- Use Next.js `Image` component for optimized images
- Use Next.js `Video` component for optimized videos
- Images are automatically optimized and lazy-loaded
- Support for responsive images with multiple sizes

## 🔐 Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_API_URL=your_api_url
NEXT_PUBLIC_APP_URL=your_app_url
# Add other environment variables as needed
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- shadcn for the beautiful UI components
- Bits UI for accessible primitives
- Framer Motion for smooth animations
- Tailwind CSS for the utility-first approach

## 📞 Contact

- Email: contact-us@cam-shot.com
- Phone: +91 90019 51346
- Address: A-36, Gokul Vatika, JLN Road, Jaipur, Rajasthan, India - 302018

---

© 2025 Cambiante Technologies. All rights reserved.
