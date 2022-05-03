## Amazona Readme Log

4. Publish to github
   1. create githb account
   2. push to github from vs code
5. Create Website Layout
   1. Add header
   2. Add main
   3. Add footer
6. Connect to Sanity.io
   1. install sanity
   2. init sanity
   3. create product model
   4. insert sample data
7. List Products
   1. add localhost:3000 to the CORS origins in sanity
   2. fetch products from sanity
   3. render products on screen
8. Create Product Details Screen
   1. add `[slug].js` to product folder
   2. create component
   3. get slug from the URL
   4. fetch product from sanity client
   5. render product image, info
   6. show add to cart button
9. Create Dark and Light Mode
   1. define Context, Store and reducer
   2. set darkMode flag
   3. use it on layout

Current Lesson: 9

## NPM Error

Sanity command wasn't being found. Use npx prefix instead when running sanity commands.

To start sanity server, `cd` into directory and start the content server with command: `npx sanity start`

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
