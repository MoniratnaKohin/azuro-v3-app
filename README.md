This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## License
[This license](/LICENSE.md) applies to all code contained in this repository.

## Customization

### Theme
This project utilizes a [Tailwind CSS](https://tailwindcss.com/docs/theme) theme configuration, allowing you to customize theme colors, element border-radius, and typography sizes to suit your needs. Check [tailwind.config.ts](/tailwind.config.ts) file.

### Affiliate address
Change the `NEXT_PUBLIC_AFFILIATE_ADDRESS` variable in [.env](/.env) file with your address and other related to project information.

### Social login
Register at https://dashboard.privy.io/account:
- Create a project, go to "Embedded wallets" page, "Smart Wallets" tab, enable it, choose "Safe" (we support only this), configure paymasters for your app chains (https://dashboard.pimlico.io/apikeys).
- Go to "Settings" and copy `App ID`.
- Put value to `NEXT_PUBLIC_PRIVY_APP_ID` variable in [.env](/.env)

### Logo
To add your project logo change [Logo](/src/components/ui/Logo/Logo.tsx) component.

## Run project

First, install dependencies:

```bash
npm install
```

And run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
# azuro-v3-app
