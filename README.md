[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fleerob%2Fleerob.io&env=NEXT_PUBLIC_SANITY_PROJECT_ID,NEXT_PUBLIC_SANITY_DATASET,SANITY_API_TOKEN,SANITY_PREVIEW_SECRET,SANITY_STUDIO_REVALIDATE_SECRET&envDescription=These%20values%20are%20needed%20to%20connect%20to%20Sanity%20and%20fetch%20content%20for%20blog%20posts.)

# yarp.cloud devsite

- **Framework**: [Next.js](https://nextjs.org/)
- **Database**: [PlanetScale](https://planetscale.com)
- **ORM**: [Prisma](https://prisma.io/)
- **Authentication**: [NextAuth.js](https://next-auth.js.org/)
- **Deployment**: [Vercel](https://vercel.com)
- **CMS**: [Sanity](https://www.sanity.io/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)

## Learn More
- [yarp.cloud](yarp.cloud) 
## Overview

- `layouts/*` - The different page layouts each MDX category (blog, snippets) uses.
- `lib/*` - Short for "library", a collection of helpful utilities or code for external services.
- `pages/api/*` - [API Routes](https://nextjs.org/docs/api-routes/introduction) powering [`/dashboard`](https://leerob.io/dashboard), newsletter subscription, guestbook, and post views.
- `pages/blog/*` - Static pre-rendered blog pages using MDX.
- `pages/dashboard` - [Personal dashboard](https://yarp.cloud/dashboard) tracking metrics.
- `pages/sitemap.xml.tsx` - Automatically generated sitemap.
- `pages/feed.xml.tsx` - Automatically generated RSS feed.
- `pages/*` - All other static pages.
- `prisma/*` - My Prisma schema, which uses a PlanetScale MySQL database.
- `public/*` - Static assets including fonts and images.
- `styles/*` - A small amount of global styles. I'm mostly using vanilla Tailwind CSS.

## Running Locally

This application requires Node.js v16.13+.

```bash
git clone https://github.com/Jibbscript/yarp.yarp.git
cd yarp.yarp
yarn
yarn dev
```

Create a `.env` file similar to [`.env.example`](https://github.com/Jibbscript/yarp.yarp/blob/main/.env.example).


