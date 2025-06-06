WanderStay — Elegant Hotel Booking Platform

WanderStay is a beautifully designed, fully responsive hotel booking website built with the modern web stack. Whether you're booking a luxury retreat or exploring top-rated hotels worldwide, WanderStay delivers a seamless and elegant user experience.

FEATURES
- Responsive Design – Mobile, tablet, and desktop friendly
- Modern UI – Smooth transitions and hover effects
- Hotel Listings – Searchable and filterable hotel data
- Image Gallery – Unsplash-powered image slider
- User Authentication – NextAuth.js-based secure login
- Contact Form – Reach out directly from the site
- Real-Time Images – Integrated with the Unsplash API

TECH STACK
- Next.js 14, React 18, Tailwind CSS, TypeScript
- Lucide React, shadcn/ui, NextAuth.js, Unsplash API

GETTING STARTED
1. Clone the repo: git clone https://github.com/krishnamarora/wanderstay.git
2. Install dependencies: npm install
3. Create .env.local and add:
   - NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=your_key
   - NEXTAUTH_SECRET=your_secret
   - DATABASE_URL=your_db_url
4. Run the dev server: npm run dev

DEPLOYMENT
- Recommended: Vercel
- Connect your GitHub repo and set environment variables in dashboard

PROJECT STRUCTURE
wanderstay/
├── app/
├── components/
├── lib/
├── public/
├── styles/
├── types/
├── .env.local
├── tailwind.config.ts
├── next.config.js
└── readme.me

AUTHENTICATION
NextAuth.js with providers (Google, GitHub, email-password)

FUTURE FEATURES
- i18n support
- Stripe integration
- Email notifications
- Live chat
- Google Maps support

LICENSE
MIT © 2025 Krishnam Arora
