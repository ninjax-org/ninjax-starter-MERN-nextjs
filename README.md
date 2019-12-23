# NinjaX Starter MERN stack with nextjs

This is a NinjaX starter pack running Mongo, Express, React, Node, and Next.js. The best way to download this starter is with `ninja install starter MERN-nextjs` after you have installed the command line tool.[NPM link]. If this is your first time using NinjaX, it is also recommended you read `getting started` on the main NinjaX repository. After that, install this repo and head to the Demo section.

This starter includes the following:

- Essential boilerplate which will run locally with `ninja run`
- Hot reloading and bundling/compiling out of the box
- Routing 
- LESS styles
- Mongo integrations with examples of both reads, and writes
- Essential email/password authentication
- Testing setup with continuous integration
- 1 Script deployment onto Zeit Now
- Auto deployment onto dev and staging environment
- Material UI theme

# Demo Walkthrough

### Configuration
1. Install NinjaX cli with `npm i -g ninjaxcli` 
2. Run in your terminal: `ninja install starter MERN-nextjs`
3. `cd ninjax-starter-mern-nextjs`
4. `npm install && npm run`
5. Navigate to `http://localhost:3000/` to observe your NinjaX homescreen

### Demo

6. Routing: 
Click on the 'About' link in the top navbar. Notice the url change to a clean '/about' route as it navigates you to the about page. This was done through the "Link" component which was imported in the `components/NavBar.js` file. In order to add a new route, you simply add a new file to the `pages` directory, and it will automatically generate the route with that filename. Currently our starter comes with three routes: `/`, `/About`, `/Profile`, and also `*` which it uses as a fallback and displays a 404 page. This directory must be named `pages`. The only other protected directory name is `public` which we will cover later. 

Now go ahead and click on the `/Profile` page and observe the url. It includes custom query params in the url. Here is more on the [Link component and routing](https://nextjs.org/docs#with-link) in Next.js.

# Boosters

- Official Approved Boosters
- All Boosters

Boosters are add-ons to your starter packs. The code fully injects directly into  your codebase so you can both better understand it, and fully customize. You can add them with 'ninja add-booster [name of booster]` To read more about boosters, head over to our documentation on boosters in our main NinjaX repo. 
