# lightbox-social

This script adds social sharing functionallity to [Lightbox](https://github.com/lokesh/lightbox2). The idea arose from Lightbox2 [issue #111](https://github.com/lokesh/lightbox2/issues/111). I'm hoping to expand the scope of the original idea a little, providing sharing for Twitter, Facebook, and Google+. 

## First Phase Goals
For the first iteration, the script should automatically insert a link to the [Facebook sharer utility](https://developers.facebook.com/docs/plugins/share-button/#faqdialog). This feature will provide very little control over how the resulting post is displayed on Facebook, but will not require registering the site as a Facebook app before use. The link that gets shared will contain a hashed reference to the specific image being shared and will launch that image on page load. No fuss, no muss, just a simple addition of functionallity to share each image on a page.

## Future expansion
Initial improvement will focus on deeper integration with Facebook. Hopefully, simply adding a Facebook API token will activate the [Facebook sharing dialog](https://developers.facebook.com/docs/reference/dialogs/feed/) and add additional info (like a specific thumbnail image, title, and caption) to the resulting post. Once Facebook functionallity is sufficently developed, the plan is to turn attention towards similar functionality (in as far as is possible) for Google+ and Twitter.
