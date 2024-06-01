# Link preview tool
### HTML template for a page thumbnail image, shown for shared links

<img src="https://indieaisle.com/images/thumbnail-template-preview.png" alt="Screenshot of the thumbnail template" width="300">

Preview image for a page on your site that gets shown when sharing a link to it, usually on social media, messaging, and chat apps. Use the [Blocks Edit visual editor](https://blocksedit.com/) for free to change the avatar image and text. Click Capture to save the screenshot image to upload to your site.

Getting set up:
1. [Sign up](https://app.blocksedit.com/signup/) for a free Blocks Edit account.
2. From the dashboard, at the top, click **New Theme** to upload the HTML template.
3. That's it, you're ready to start!
 
Using Blocks Edit:
1. On dashboard, click **New Page**.
2. Name your page and click on it.
3. Click **Edit** button at the top.
4. Click on placeholder content on the right to change it.
5. Click **Save** button at the top.
6. Click **Capture** button to download.

#### How do I add my image to my site?
To setup your image to be used for links, you'll need to add a snippet of code to the `head` area of the page you want to add your image to:

    <meta property="og:image" content="[IMAGE_URL]">

Change `[IMAGE_URL]` to the URL for where you uploaded your image.

Additionally, add text info for the link card with these properties:

    <meta property="og:title" content="The title of your page goes here">
    <meta property="og:description" content="A short description that is also included.">
