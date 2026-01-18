# 3D Skateboard Customizer 🛼

[![Next.js](https://img.shields.io/badge/Next.js-15.0.7-black)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2.3-blue)](https://reactjs.org/)
[![Three.js](https://img.shields.io/badge/Three.js-0.171.0-green)](https://threejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC)](https://tailwindcss.com/)
[![Prismic](https://img.shields.io/badge/Prismic-CMS-orange)](https://prismic.io/)

An interactive 3D skateboard customization web application built with Next.js, React Three Fiber, and modern web technologies. Customize your skateboard with real-time 3D visualization, physics simulation, and smooth animations.

## 🌐 Live Demo

Check out the live application: [3D Skateboard Customizer](https://3d-skateboard-two.vercel.app/)

## ✨ Features

- **Interactive 3D Customization**: Real-time skateboard customization with Three.js
- **Physics Simulation**: Realistic physics using Matter.js for dynamic interactions
- **Smooth Animations**: GSAP-powered animations for enhanced user experience
- **Responsive Design**: Mobile-friendly interface with Tailwind CSS
- **CMS Integration**: Content management with Prismic
- **Component-Based Architecture**: Modular React components with TypeScript
- **Slice Machine**: Visual development with Prismic's Slice Machine

## 🛠️ Tech Stack

- **Frontend Framework**: Next.js 15 with App Router
- **3D Graphics**: React Three Fiber (@react-three/fiber) and Drei (@react-three/drei)
- **Physics Engine**: Matter.js
- **Animations**: GSAP (@gsap/react)
- **Styling**: Tailwind CSS with PostCSS
- **CMS**: Prismic (@prismicio/client, @prismicio/next, @prismicio/react)
- **Language**: TypeScript
- **Development Tools**: ESLint, Slice Machine

## 🚀 Installation & Setup

### Prerequisites

- Node.js (version 18 or higher)
- npm, yarn, pnpm, or bun package manager
- Git

### Clone the Repository

```bash
git clone <repository-url>
cd 3dapp-by-tabarak
```

### Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### Environment Setup

1. Create a `.env.local` file in the root directory
2. Add your Prismic repository URL and access token if needed:

```env
NEXT_PUBLIC_PRISMIC_ENDPOINT=your-prismic-endpoint
PRISMIC_ACCESS_TOKEN=your-access-token
```

### Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### Build for Production

```bash
npm run build
npm start
```

## 📁 Project Structure

```
3dapp-by-tabarak/
├── src/
│   ├── app/                 # Next.js App Router pages
│   │   ├── api/            # API routes
│   │   ├── build/          # 3D skateboard builder page
│   │   └── fonts/          # Font optimization
│   ├── components/         # Reusable React components
│   │   ├── Skateboard.tsx  # Main skateboard component
│   │   └── ...
│   ├── lib/                # Utility functions
│   └── slices/             # Prismic slices
│       ├── Hero/           # Hero section with interactive skateboard
│       ├── ProductGrid/    # Product display grid
│       └── ...
├── public/                 # Static assets
│   ├── skateboard/         # Skateboard textures
│   └── hdr/               # HDRI environment maps
├── customtypes/            # Prismic custom types
└── ...
```

## 🎮 Usage

1. **Navigate to the Builder**: Go to the `/build` page
2. **Customize Your Skateboard**: Use the interactive controls to modify colors, materials, and design
3. **Real-time Preview**: See changes instantly in the 3D viewport
4. **Physics Interaction**: Experience realistic physics simulation
5. **Responsive Experience**: Works seamlessly on desktop and mobile devices

## 🛠️ Development

### Slice Machine

This project uses Prismic's Slice Machine for visual development:

```bash
npm run slicemachine
```

### Linting

```bash
npm run lint
```

### TypeScript

The project is fully typed with TypeScript. Type definitions are automatically generated for Prismic content.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is private and proprietary.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- 3D graphics powered by [Three.js](https://threejs.org/)
- Content managed by [Prismic](https://prismic.io/)
- Physics simulation by [Matter.js](https://brm.io/matter-js/)
- Animations by [GSAP](https://greensock.com/gsap/)
