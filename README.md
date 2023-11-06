# Ecommerce Project using Next JS 14.01
by Damir Toriya.

## Technology Stack
```
the latest versions were used. (06.11.2023)
Next.js: https://nextjs.org/
Sanity.io: https://www.sanity.io/
Stripe: https://stripe.com/
Shadcn/UI: https://ui.shadcn.com/
TailwindCSS: https://tailwindcss.com/
Use Shopping Cart: https://useshoppingcart.com/
```
## Getting Started
To get started with this Ecommerce project, follow these steps:
1. Clone the project repository to your local machine:
  ```
git clone https://github.com/DamirTD/EcommerceProject_NEXTJS.git
  ```
2. Change your working directory to the project folder:
```
cd nextjs-ecommerce
```
2. Install the project dependencies using your preferred package manager (npm, yarn, pnpm, bun):
```
npm install
# or
yarn install
# or
pnpm install
# or
bun install

```
4. Run the development server:
```
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
5. Open your web browser and navigate to http://localhost:3000 to view the project.

## To open sanity.io studio mode
1. Open ecommercedamir location:
```
cd ecommercedamir
```
2. You should be in the following directory:
``
{yourPath}/nextjs-commerce/ecommercedamir/
``
3. Run the development server for Sanity.io Studio:
```
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
4. Open your web browser and navigate to http://localhost:3333 to access the Sanity.io Studio for content management.


After opening the local web page, make sure to log in to your Sanity.io account with the same account you used to create the schema before.


## Important note

To enable Stripe payment for this project, you need to enable it in the project settings. You can do this by visiting the following URL:
``
https://dashboard.stripe.com/settings/checkout
``
By default, Stripe payment is disabled in this project. You can enable it as needed for your specific use case.

## Adding Products to the Ecommerce Store
To add products to your ecommerce store, follow these steps:


1. Access the Sanity.io Studio mode as described in the previous section.
2. Navigate to the product section within the Studio.
3. Click the "Add New" button to create a new product.
4. Fill in the product details, including title, description, price, and any other relevant information.
5. Upload images for the product.
6. Save the product, and it will be added to your ecommerce store.

## Customizing the UI with Shadcn/UI and TailwindCSS
To customize the user interface of your ecommerce website, you can take advantage of Shadcn/UI and TailwindCSS. Here's how you can get started:


1. Explore the Shadcn/UI documentation to understand the available components and styles.
2. Customize the UI components to match your brand and design preferences.
3. Modify the CSS and styles using TailwindCSS utility classes to achieve the desired look and feel.
4. Make changes to the project's styling files to reflect your design choices.

## .env
This file contains NEXT_PUBLIC_STRIPE_KEY, it is not desirable to show this code. Please study how to close access to view this key.

