This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

## 🛠️ Essential Git Aliases

Boost your daily Git workflow with these powerful aliases. Run these commands in your terminal to configure them globally:

### 🌟 1. Beautiful Git Log (`git lg`)
Get a clean, colorful, and organized view of your commit history.
```bash
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
```

### 📋 2. Concise Status (`git s`)
View your working tree status in a short format.
```bash
git config --global alias.s status --short
```
*💡 **Alternative:** For a more detailed short status (including branch tracking):*
```bash
git config --global alias.s "status -sb"
```

### 🌿 3. Quick Branch (`git b`)
List, create, or delete branches faster.
```bash
git config --global alias.b branch
```

### 💾 4. Fast Commit (`git co`)
Commit your changes with a message quickly.
```bash
git config --global alias.co "commit -m"
```

### ➕ 5. Add All Changes (`git a`)
Stage all modified and new files in one go.
```bash
git config --global alias.a "add ."
```

### 🚀 6. Quick Checkout (`git c`)
Switch branches or restore working tree files.
```bash
git config --global alias.c "checkout"
```

### 🔀 7. Fast Merge (`git m`)
Merge branches with ease.
```bash
git config --global alias.m merge
```
