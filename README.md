# Space Exploration Landing Page

This project is a simple landing page for a space exploration theme. It uses HTML to structure the content and CSS to create the visual design. The page includes a hero section with a background image, a logo, a headline, a call-to-action button, and a footer note.

## What the Project Does

The page is designed to look like a promotional space exploration banner. It introduces the idea of joining an exploration mission and uses styling choices that make the page feel bold, themed, and readable.

The main sections are:
- A hero area with a galaxy background image
- A logo image at the top
- A heading that highlights the word "Exploration"
- A button that invites the user to join
- A footer note with terms and conditions

## What I Learned

### Background Images with `background-size: cover`

The hero section uses a background image in CSS. The `background-size: cover` property makes the image scale so it fills the entire element without stretching.

This is useful because it keeps the background looking full and visually balanced, even if the screen size changes. The image may be cropped a little, but it will always cover the whole area.

### WebP Image Format

The background image uses the `.webp` format.

WebP is a modern image format that usually has better compression than older formats like `.jpg` or `.png`. That means it can give smaller file sizes while keeping good quality, which helps pages load faster.

### Google Fonts and Attaching External Fonts

The page uses the Oxanium font from Google Fonts. It is added in the HTML using `<link>` tags in the `<head>` section.

This is called attaching an external font. Instead of relying only on default system fonts, the page loads a custom font from Google and then applies it in CSS using `font-family`.

This improves the design because the typography matches the space theme better than a standard font would.

### The `<span>` Tag

The `<span>` tag is used inside the heading to wrap only the word "Exploration".

A `span` is an inline container with no meaning by itself. It is useful when you want to style just part of a sentence without affecting the whole line. In this project, it is used to add the underline effect only to one word.

### IDs and Utility Classes

The project uses both IDs and classes for styling.

An ID, like `#hero` or `#main-logo`, is used for one specific element. It is best when the element is unique on the page.

A utility class, like `.underline` or `.btn`, is reusable. Utility classes are helpful when you want to apply a small styling pattern to one or more elements without creating a new custom rule each time.

In this project:
- `#hero` styles the main banner section
- `#main-logo` styles the logo image
- `.btn` styles the button
- `.underline` adds the underline effect to part of the heading

### `text-shadow` for Readability

The heading uses `text-shadow` to make the text stand out against the galaxy background.

This improves readability because bright or busy backgrounds can make text harder to see. The shadow creates contrast around the letters, helping the headline remain clear and visually strong.

## Summary

This project taught me how to:
- Build a simple landing page with HTML and CSS
- Use a background image that fills its container
- Work with WebP images for better performance
- Attach and use an external Google Font
- Style part of a sentence with a `span`
- Use IDs and utility classes effectively
- Improve text readability with `text-shadow`

## Files

- `index.html` contains the structure of the page
- `style.css` contains the visual styling
