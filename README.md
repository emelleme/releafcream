# The WHEAT Stack

Welcome to the shortest stack out there. This stack combines Functions,  Eleventy, Alpine.js and Tailwind CSS to make static site authoring easy and minimal!

The workers and HTMX was added to the E. A. T. components  to make this a complete serverless deployment that is designed to operate on edge systems with minimal compute power.

There are some other goodies in here, but they change so often that it's probably not worth including here, just check the `package.json` file!

## Getting Started with TEA part of the stack

Just run the usual commands and peep the `package.json` file to see the available scripts and packages.

For the lazy:

- `npm i` to build that big ol' `node_modules` folder
- `npm run dev` to boot up that dev server and start building
- `npm run build` when you're ready to build a production bundle

**Bonus**
`npm run build && npx serve dist` will boot up a local server of your production site!

## Getting Started with Functions

Functions can be run in a number of different ways, including localhost or on a cloud server. For most of our applications we will utilize Cloudflare Workers, as it is the most minimal for operations on edge systems. 

Integration docs coming soon. 

Read more about cloudflare pages functions at https://developers.cloudflare.com/pages/platform/functions
