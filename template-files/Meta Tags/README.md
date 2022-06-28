# Meta Tags

With meta tags you can control: 
 * How users see your project link when viewed on a search engine or shared on social media 
 * Different behaviors and UI preferences on mobile devices.

 These tags should be added to the `<head>` section usually in the `index.html` file.

___ 

### Must Have

```
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1 minimum-scale=1,maximum-scale=1,user-scalable=no">
<meta name="description" content="Description">
<meta name="keywords" content="Keywords">

<link rel="shortcut icon" type="image/png" href="/assets/branding/favicon.png" />
```

| Tag      | Description |
| ----------- | ----------- |
| charset      | Specifies character encoding for the HTML document       |
| viewport   | Controls page view size and shape - [Read More](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag)       |
| description   | Short, accurate description of the page or app. Used for search engine and browser bookmark descriptions.       |
| keywords   | Comma separated, words relevant to the page's content.       |
| shortcut icon   | Path to favicon - tab icon.       |

___ 

### Other
```
<meta name="theme-color" content="#4285f4">

<link href="/manifest.json" rel="manifest">
```

| Tag      | Description |
| ----------- | ----------- |
| theme-color      | Specifies color of some mobile browser UIs - [Read More](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name/theme-color)       |
| manifest      | Create a manifest.json and link to it if you would like to take advantage of PWA features  - [Read More](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json)  |

### Social Media

```
<!-- Facebook -->
<meta property="og:title" content="">
<meta property="og:description" content="">
<meta property="og:image" content="https://project.usgs.gov/full/path/to/facebook.png">
<meta property="og:url" content="https://projectpath.usgs.gov">

<!-- Twitter -->
<meta name="twitter:title" content="">
<meta name="twitter:description" content="">
<meta name="twitter:image" content="https://project.usgs.gov/full/path/to/twitter.png">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image:alt" content="">
```

These meta tags control how the link looks when shared on Facebook or Twitter. You can control the title, description, and image that displays. Use the `facebook.png` and `twitter.png` files as templates for images. They are the correct size.