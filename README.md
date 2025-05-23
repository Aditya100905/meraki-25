# Next.js + Javascript + Tailwind

The official website of MERAKI 2K25, the techfest of IIIT Una .

## Features

-   [x] Next.js
-   [x] Javascript
-   [x] Tailwind CSS
-   [x] ESLint
-   [x] Prettier

## Usage

1.  Click the `Use this template` button.
2.  Create a new repository.
3.  Clone the repository.
4.  Install dependencies.

```sh
yarn
```

5.  Start development server.

```sh
yarn dev
```

## Folder Structure

``` sh
/meraki
│── public/              # Static assets (images, icons, etc.)
│── app/                 # App Router (Server Components)
│   ├── layout.tsx       # Root layout component
│   ├── page.tsx         # Home page component
│   ├── (auth)/          # Authentication-related routes (e.g., login, signup)
│   ├── (dashboard)/     # Protected dashboard pages
│   ├── api/             # API routes (server actions)
│   ├── favicon.ico      # App favicon
│   └── globals.css      # Global styles
│── components/          # Reusable UI components
│── lib/                 # Utilities, helpers, and configurations
│── styles/              # Custom styles and Tailwind configurations
│── hooks/               # Custom React hooks
│── context/             # Global state management (if used)
│── constants/           # Static data and configurations
│── types/               # TypeScript type definitions
│── .env.local           # Environment variables (not committed)
│── .gitignore           # Git ignore file
│── next.config.js       # Next.js configuration
│── package.json         # Dependencies and scripts
│── tsconfig.json        # TypeScript configuration
│── README.md            # Project documentation
```

## Scripts

```sh
# Run the app in the development mode.
yarn dev

# Run the test watcher in an interactive mode.
yarn test:watch

# Builds the app for production to the build folder.
yarn build

# Runs the built app in production mode.
yarn start

# Lints and fixes files.
yarn lint

# Formats files.
yarn format
```

## Acknowledgements

-   [Next.js](https://nextjs.org)
-   [Javascript](https://www.javascript.com/)
-   [Tailwind CSS](https://tailwindcss.com/)
-   [ESLint](https://eslint.org)
-   [Prettier](https://prettier.io)
