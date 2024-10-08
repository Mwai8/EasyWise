## EASYWISE

My project, EasyWise, helps users easily browse, order, and track food deliveries from nearby restaurants.

# Target Audience

EasyWise is created for users who want a seamless and efficient way to order food online. It also provides restaurant owners with a simple dashboard to manage orders and update menus.

# Personal Focus
My focus has been on two key areas: ensuring a mobile-friendly, responsive user experience and implementing a reliable and scalable API for restaurant data and orders.

# Technologies Used and Choices
Frontend (Next.js): Next.js was chosen for its flexibility with server-side rendering (SSR) and static generation, both essential for ensuring fast page loads and SEO-friendly content. The decision to use Next.js also came from its built-in API routes, which reduced development time for server communication.
Backend (Node.js & Express): The backend is built with Node.js and Express because of their efficiency in handling asynchronous requests. Express provided a lightweight, scalable solution for building RESTful APIs to manage orders, user data, and restaurant menus.
Database (MongoDB): MongoDB was chosen for its flexibility in managing dynamic data structures. With varying restaurant menus and order details, a NoSQL database allowed for rapid prototyping and adjustments without requiring schema changes.
CSS Framework (Tailwind CSS): Tailwind CSS was used to ensure a mobile-responsive and streamlined design. Its utility-first approach simplified styling and improved design consistency across different views without needing additional frameworks.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
