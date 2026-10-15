# Steadhand site

One-page website for missed-call answering for trade businesses in Dallas-Fort Worth, in English and Spanish.

Plain HTML and CSS with a little JavaScript. No build step: open `index.html` in a browser, or host the folder on GitHub Pages or Netlify.

## Change the name, email or WhatsApp

At the bottom of `index.html`, edit the `CONFIG` block:

```js
var CONFIG = {
  brand: "Steadhand",
  email: "raiyanislam058@gmail.com",
  whatsapp: "8801531992476"
};
```

Also change the brand name in the `<title>` and `og:title` tags at the top of `index.html`, since link previews read those before any script runs.

## Files to add

- `audio/demo-en.mp3`, `audio/demo-es.mp3`: recorded demo calls
- `img/raiyan.jpg`: your photo, 4:5
- `img/before-1.jpg`, `img/after-1.jpg`, `img/before-2.jpg`, `img/after-2.jpg`: concept screenshots, 3:4
- `img/og.jpg`: link-preview image, 1200×630

## Spanish link

Send Spanish-speaking owners to `yoursite/?lang=es` to open the page in Spanish.
