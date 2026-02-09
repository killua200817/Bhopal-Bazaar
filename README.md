# Bhopal Bazaar - Grocery Delivery App

A full-stack grocery delivery platform for Bhopal city, built with Next.js, Firebase, Stripe, and Google Maps API.

Based on the [Sarva Bazaar template](https://github.com/Shahir-47/Sarva-template).

---

## Tech Stack

- **Frontend:** Next.js 13+ (App Router), React, TypeScript, Tailwind CSS
- **Backend:** Firebase (Authentication, Firestore, Storage)
- **Payments:** Stripe
- **Mapping/Location:** Google Maps API (address autocomplete, distance calculation, route planning, delivery time estimation)
- **Styling:** TailwindCSS with custom color schemes

---

## Role-based Architecture

Bhopal Bazaar supports three distinct user roles:

1. **Customers:** Browse products, place orders, track deliveries
2. **Vendors:** List/manage products, process orders, manage business profile
3. **Drivers:** Accept and deliver orders, manage earnings and profile

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- Firebase account
- Stripe account
- Google Maps API key

### Environment Setup

Create a `.env.local` file in the root with:

```env
# Firebase
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project_id.firebasestorage.app
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
STRIPE_SECRET_KEY=your_stripe_secret_key

# App URL
NEXT_PUBLIC_APP_URL=http://localhost:3000/

# Location Services
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

### Installation

```bash
# Clone the repo
git clone https://github.com/killua200817/Bhopal-Bazaar.git
cd Bhopal-Bazaar

# Install dependencies
npm install

# Start the development server
npm run dev
```

Visit `http://localhost:3000` to view the app.

---

## Deployment

Deploy to Vercel (free tier):

```bash
# Build for production
npm run build

# Start production server
npm start
```

Or connect the GitHub repo directly to [Vercel](https://vercel.com) for automatic deployments.

---

## License

MIT License - see [LICENSE](LICENSE) for details.
