# Snipcart with Angular & Firebase integration

You can use this Angular example project to follow these blog posts:
- [DevAces post original en español](https://devaces.com.mx/blog/post/tgg7TnbIHW8GEUl4ofa5)
- [Medium blog post](https://medium.com/@alantheace/how-to-set-up-an-online-store-with-snipcart-angular-firebase-75a403b973f6)

The example includes a `products.json` file in the assets folder that you can use as a template for your own products and import it to Firebase Realtime Database.

## Testing

To test this example you have to:
1. Run `npm install`
2. Add your Snipcart test API key in the `index.html` file
3. Create a Firebase project and enable the Realtime Database
4. *Optionally*, edit the `products.json` file to include your own products
5. Import the `products.json` file in the Realtime Database
6. Change the `productsUrl` property inside the `app.component.ts` file to your own RTDB products path
7. Add your website domain and your RTDB products path to the trusted domains in the Snipcart Dashboard
8. Run the Angular project

For a more detailed explanation please check out one of the blog posts mentioned above.
