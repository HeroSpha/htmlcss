# Html and Css Tutorial

In this tutorial we will use google fonts and css variables

## Resources used

### Css Variables

CSS variables, also known as custom properties, allow you to declare a variable in CSS and then use it throughout your stylesheet. This can help make your code more maintainable and reduce repetition.

Here's an example of how to use CSS variables:

```
  :root {
    --main-color: #006699;
  }
```

and to use the color in any of your css, use it like code below.

```
  p {
    color: var(--main-color)
  }
```

### Google Fonts

Google Fonts is a popular library of free and open source fonts that you can use in your web projects. Here's how to use Google Fonts in your CSS:

- Go to the Google Fonts website (https://fonts.google.com/) and browse the available fonts. You can search for a specific font or browse by category or popularity.
- Once you've found a font you like, click on the "+" icon next to it. This will add the font to your collection.
- Click on the "Use" tab to see the code you need to add to your CSS to use the font. You can choose to import the font into your stylesheet, or you can use a link element in your HTML to load the font from Google's servers.
- Copy the CSS code for your chosen font, and paste it into your stylesheet. Here's an example:

```
/* Import the font into your stylesheet */
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');

/* Use the font in your CSS */
body {
  font-family: 'Open Sans', sans-serif;
}

```

In this example, we're importing the "Open Sans" font from Google Fonts, and then using it as the font family for the body element.

- Save your stylesheet and refresh your webpage to see the new font in action.
  That's it! With just a few lines of code, you can add a beautiful and unique font to your website using Google Fonts.
