## Next.js Dashboard Course

This is the [Dashboard tutorial of the Next.js](https://nextjs.org/learn/dashboard-app).
This tutorial was made at 15.0.0-canary.56 next version.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Setup

After you have cloned this repo, install the dependencies with:

npm install

Then you can then start the application running:

npm run dev

That's it. Just Access http://localhost:3000/dashboard in your browser.

To login you can use:

- email: user@nextmail.com
- password: 123456

### Chapter 1

Getting Started - setup instructions

### Chapter 2

CSS Styling (Implemented in styles folder and individual components)

### Chapter 3

Optimizing Fonts and Images (Addressed through optimization techniques and potentially next/image component)

- How to add custom fonts with next/font.
- How to add images with next/image.
- How fonts and images are optimized in Next.js.

[Image Optimization Docs](https://nextjs.org/docs/app/building-your-application/optimizing/images)
[Font Optimization Docs](https://nextjs.org/docs/app/building-your-application/optimizing/fonts)
[Improving Web Performance with Images (MDN)](https://developer.mozilla.org/en-US/docs/Learn/Performance/Multimedia)
[Improving Web Performance with Images (MDN)](https://developer.mozilla.org/en-US/docs/Learn/Performance/Multimedia)

### Chapter 4

Creating Routes, Layouts and Pages (Structure defined in pages folder with layout components)

### Chapter 5

Navigating Between Pages (Implemented using next/link component or custom routing)

[How Routing and Navigation Works](https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#how-routing-and-navigation-works)

### Chapter 6

Setting Up Your Database (Depends on your backend choice; code to connect and fetch data will reside in API routes or helper functions)

### Chapter 7

Fetching Data (Handled within API routes or data fetching components, depending on the data source)

### Chapter 8

Static and Dynamic Rendering (Demonstrated through Next.js's automatic rendering and data fetching capabilities)

- Static rendering: data fetching and rendering happens on the server at build time (when you deploy) or when revalidating data.
- Ddynamic rendering: content is rendered on the server for each user at request time (when the user visits the page).

### Chapter 9

Streaming is a data transfer technique that allows you to break down a route into smaller "chunks" and progressively stream them from the server to the client as they become ready.

### Chapter 10

Partial Prerendering (Can be used to improve performance; code implementation will vary). It is a rendering model that allows you to combine the benefits of static and dynamic rendering in the same route.

### Chapter 11

Adding Search with debounce and pagination

### Chapter 12

Mutating Data (Data manipulation logic will be placed in API routes or within components using state management solutions)

- creates page and logic to add a new invoice
- revalidatePath: allows to purge cached data on-demand for a specific path
- redirect
- creates page and logic to edit an invoice and pass the id to this page
- creates logic to delete an invoice

### Chapter 13

Handling Errors

- implements try catch
- handling all errors with error.tsx
- handling more specific errors with notFound()

### Chapter 14

Improving Accessibility

- installs lint
- fixes lint errors
- implements adding aria labels (form errors)

### Chapter 15

Adding Authentication

- sets up NextAuth.js
- updates login form to handle auth
- adds logout functionality
