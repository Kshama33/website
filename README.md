This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

In this Project, i have successfully completed it and made a website for a restaurant
for ordering food items.
In this website following things are being used

- NodeJs (Backend)
- ReactJs (Frontend)
- MongoDB (Database)
- JWT ( Authentication)
- Paypal (Payment Gateway)
- cloudinary

First i made the front end of the website where i have created different pages for the website like
footer,header, sliding page, product page, cart page, payment page, admin dashboard and delivery page.
After that i had to add the support for MongoDB server where the product and
order details are stored.

Payment system required to do the transaction is done using paypal api were are used in payment page.

Next.js is used for making admin dashboard which can trak the order details
and update the status which will be shown in delivery page.

Finally a buttton was added where you can add new products by just upload
the image and adding required details. For storing images cloudinary is being used.
The file path is stored in MogoDB server.
