# My Website Documentation

## Open Graph Meta Tags

To specify the canonical URL and type of content for your webpage, you can use Open Graph meta tags in the `<head>` section of your HTML document.

<meta property="og:url" content="https://souravwalke.com" />
<meta property="og:type" content="website" />

## Google Fonts Icon Stylesheet

To import the Google Fonts stylesheet for Material Icons, use the following <link> tag in the <head> section of your HTML document:

<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />

## Preconnect Link Tag

To establish a preconnect connection to a domain, such as Google Fonts.These tags can help improve the performance and appearance of your website when shared on social media or when using Google Fonts.

<link rel="preconnect" href="https://fonts.googleapis.com">

## Importing Multiple Font Families from Google Fonts

To import multiple font families from Google Fonts, use a single `<link>` tag with the `rel="stylesheet"` attribute. For example, to import the Fira Code, McLaren, and Poppins font families with specific weights and display settings, use the following `<link>` tag in the `<head>` section of your HTML document:

```html
<link
  href="https://fonts.googleapis.com/css2?family=Fira+Code&amp;family=McLaren&amp;family=Poppins:wght@400;700&amp;display=swap"
  rel="stylesheet"
/>
```
