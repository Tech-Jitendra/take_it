# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```


├── .expo/
├── app/
│   ├── auth/                # Authentication screens (Login, Signup, etc.)
│   │   ├── LoginScreen.tsx
│   │   ├── SignupScreen.tsx
│   │   └── ForgotPasswordScreen.tsx
│   ├── product/             # Product-related screens
│   │   ├── ProductListScreen.tsx
│   │   ├── ProductDetailsScreen.tsx
│   │   ├── components/      # Reusable components for product screens
│   │   └── styles.ts        # Styles specific to product screens
│   ├── cart/                # Shopping cart screens
│   │   ├── CartScreen.tsx
│   │   ├── CheckoutScreen.tsx
│   │   └── OrderSummaryScreen.tsx
│   ├── profile/             # User profile-related screens
│   │   ├── ProfileScreen.tsx
│   │   ├── OrderHistoryScreen.tsx
│   │   └── SettingsScreen.tsx
│   ├── tabs/                # Main navigation tabs
│   │   ├── _layout.tsx
│   │   ├── HomeScreen.tsx
│   │   ├── ExploreScreen.tsx
│   │   └── FavoritesScreen.tsx
│   ├── _not-found.tsx       # 404-like screen
├── assets/                  # Static files
│   ├── images/              # App images
│   └── fonts/               # Custom fonts
├── components/              # Reusable components shared across the app
│   ├── Button.tsx
│   ├── Header.tsx
│   ├── ProductCard.tsx
│   └── RatingStars.tsx
├── constants/               # App-wide constants
│   ├── api.ts               # API endpoint constants
│   └── theme.ts             # Theme-related constants
├── hooks/                   # Custom hooks
│   ├── useAuth.ts           # Hook for authentication
│   ├── useCart.ts           # Hook for cart logic
│   └── useProductQuery.ts   # Hook for fetching products
├── services/                # API services
│   ├── authService.ts       # Authentication API
│   ├── cartService.ts       # Cart API
│   └── productService.ts    # Product-related API
├── store/                   # Global state management (React Query or other state libraries)
│   ├── cartStore.ts
│   ├── userStore.ts
│   └── productStore.ts
├── scripts/                 # Automation scripts
├── .gitignore
├── app.json
├── expo-env.d.ts
├── package.json
├── tsconfig.json
└── README.md
