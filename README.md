# Card Hover Content Effect

This CSS-based project adds a smooth hover effect for cards. When you hover over each card, it reveals hidden information. This effect is great for galleries, portfolios, or product cards.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [CSS Properties](#css-properties)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

This project uses HTML and CSS to create a hover effect for cards, where an initial image or title hides and reveals additional information when hovered over.

---

## Technologies Used

| Technology | Description                                 |
|------------|---------------------------------------------|
| HTML       | Provides the structure of the webpage.      |
| CSS        | Adds style, transitions, and animations.    |

---

## CSS Properties

| Property             | Description                                                                                                                                  |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| `margin`             | Creates space around elements. Here, it removes default space around the `body`.                                                            |
| `padding`            | Creates space inside elements, between the content and the border. Here, it removes padding from `body`.                                     |
| `min-height`         | Sets the minimum height of an element. `100vh` means it will cover the full height of the viewport (visible screen area).                    |
| `background`         | Sets the background color or image. Here, `#333` makes a dark gray background.                                                              |
| `display: flex`      | Enables flexbox layout, which helps align and position items inside a container.                                                            |
| `justify-content`    | Aligns items horizontally within a flex container. `center` places items in the middle of the container.                                    |
| `align-items`        | Aligns items vertically within a flex container. `center` places items in the middle vertically.                                            |
| `font-family`        | Sets the font for the text. Here, it uses `consolas` or `sans-serif` if `consolas` is unavailable.                                          |
| `width`              | Defines the width of an element. For example, `300px` sets a fixed width of 300 pixels for the card.                                        |
| `height`             | Defines the height of an element. Here, `200px` makes each card 200 pixels tall.                                                            |
| `position`           | Controls the placement of elements. `relative` positions elements relative to where they would normally be.                                 |
| `cursor`             | Changes the mouse pointer style when hovering. `pointer` shows a hand icon, indicating the element is clickable.                            |
| `overflow`           | Controls what happens when content overflows an element's box. `hidden` cuts off extra content.                                             |
| `transition`         | Creates smooth animations when changing CSS properties. Here, `0.5s` means the animation lasts half a second.                               |
| `opacity`            | Sets the transparency level of an element. `0` makes it invisible; `1` makes it fully visible.                                              |
| `transform`          | Moves or scales elements. For example, `translateY(-100%)` moves an element up 100% of its own height.                                      |
| `text-align`         | Aligns text within an element. `center` places the text in the middle horizontally.                                                         |
| `object-fit`         | Defines how an image fits in its container. `cover` scales the image to fully fill the area without distortion.                             |
| `box-sizing`         | Controls how total element width and height are calculated. `border-box` includes padding and borders within the set width and height.      |
| `color`              | Sets the color of text. Here, `#333` is a dark gray.                                                                                        |
| `padding`            | Adds space inside elements. For example, `20px` padding creates space around the content inside the element.                                |
| `font-size`          | Sets the size of the text. `14px` makes text 14 pixels tall.                                                                                |
| `line-height`        | Sets the space between lines of text. `1.5em` provides a taller line space, making text more readable.                                      |
| `text-decoration`    | Adds or removes underlines from text. `none` removes the underline from links.                                                              |
| `font-weight`        | Defines the thickness of the text. `bold` makes the text thicker.                                                                           |
| `border-radius`      | Rounds the corners of an element. Here, `4px` makes the button edges slightly rounded.                                                      |

---

## Contributing

1. Fork the repository.
2. Create a branch for your feature (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License.

