# E-book Store Setup

This website is ready to sell your e-book. There is one crucial step you need to take to connect your Stripe payment link to the download page.

## How to Configure Stripe for Automatic Redirects

After a customer successfully pays for your e-book, they need to be automatically sent to the download page. Here's how to set that up in your Stripe account:

1.  **Log in to your Stripe Dashboard.**
2.  Go to the **Products** section and find the payment link you're using for this e-book.
3.  **Edit the payment link.**
4.  Look for a section called **"Confirmation page"** or **"After payment"**.
5.  Select the option to **"Redirect customers to a custom URL"**.
6.  In the URL field, you need to enter the link to your download page. Your website will be hosted on GitHub Pages, so the URL will look like this:

    `https://<your-github-username>.github.io/<your-repository-name>/download.html`

    Replace `<your-github-username>` with your actual GitHub username and `<your-repository-name>` with the name of the repository this website is in.

7.  **Save your changes.**

That's it! Now, when someone buys your e-book, they will be taken directly to the download page.
