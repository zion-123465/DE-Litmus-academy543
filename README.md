# DE-Litmus-academy543

A Next.js project with Vercel Web Analytics integration.

## Features

- **Next.js 15** with App Router
- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **Vercel Web Analytics** for tracking visitor data

## Vercel Web Analytics

This project includes Vercel Web Analytics, which automatically tracks page views and user interactions. The Analytics component is integrated in the root layout (`app/layout.tsx`).

### Enabling Analytics on Vercel

1. Deploy this project to Vercel
2. Go to your Vercel dashboard
3. Select your project
4. Navigate to the **Analytics** tab in the sidebar
5. Click **Enable** to activate Web Analytics
6. After the next deployment, analytics data will start being collected

## Getting Started

First, install dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint to check code quality

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel Web Analytics Documentation](https://vercel.com/docs/analytics)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
