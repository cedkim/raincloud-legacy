# 🌧️ `raincloud`
Serve fresh Droppy Blocks for your SDK or library, and flatten the learning curve.
## About Raincloud
### What is Droppy?
Droppy is what happens when you put together block-based and text-based programming. Droppy is suitable for all sorts of applications, and is designed to help make programming easier.
### What does Raincloud do?
Raincloud is a content management system for Droppy Blocks, powered by [Vapid](https://www.vapid.com/). It doesn't include any blocks, it just provides a way for you to manage your blocks.
### Who is Raincloud for?
Raincloud is for SDK and library developers who want to flatten the learning curve for their SDK/library.
## Using Raincloud
### Hosting
#### Method 1: Normal deploy
Raincloud can run on any server with Node.js. Simply deploy this repository to such a server, and use `npm start` to start Raincloud.
#### Method 2: Static deploy
Run Raincloud on your own computer by running `npm start`. Then, go to the dashboard (find out how in **Management**) and make your blocks. Once you're done, run `npm run staticbuild` to export static files.
### Management
#### Accessing the dashboard
To access the dashboard, visit your instance's URL, and add `/dashboard` to the end. You'll be able to secure your dashboard, and you'll also be able to manage your instance.
