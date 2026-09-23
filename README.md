# Cougar Shop mockup

A static web page that recreates the home page of the "Cougar Shop" (a university bookstore) using [Semantic UI](https://semantic-ui.com/). It was made for a web design class and there is no server or build step.

## See it

Open `Index.html` in a browser. It needs an internet connection, because Semantic UI and jQuery are loaded from a CDN (with integrity checks).

The pictures `Finished Top Menu.png` and `Finished Middle.png` are the mockups the page was built to match.

## What the page has

**Top menu bar**
- No border or shadow, a light grey background and space on both sides
- Social media icons grouped on the left; home, search, account and a **My Cart** dropdown on the right (click it to see "My cart is currently empty")

**Middle section**
- The logo centered, 200 px wide
- A centered menu with four dropdowns (Textbooks, Apparel, Gifts, Collections) and a Search item

**Footer**
- A dark background with 50 px of space above and below
- Three columns (Navigation, Main menu, Connect), each with a heading line and a list; an email box with a Join button (mockup only, it sends nothing)
- Bigger, inverted social icons because the background is dark, and the copyright line at the bottom

## Files

| File | What it is |
| --- | --- |
| `Index.html` | The page |
| `style.css` | The colours and spacing for the menus and footer |
| `coug.jpg`, `centerimage.jpg` | The logo and the banner image |
| `Finished Top Menu.png`, `Finished Middle.png` | The mockup images |

## Notes

- All links, buttons and the email box are placeholders and do not go anywhere.
- The file is called `Index.html` with a capital I. Web servers that run on Linux (including most hosting) look for `index.html` in lowercase, so rename the file before publishing the page.
- Editor and system files (`.idea/`, `.DS_Store`) were committed earlier and can be deleted from the repository.
