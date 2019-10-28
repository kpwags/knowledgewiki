# Typography

## Improving Readability

- The main paragraph font-size should be between 16pxand 18px (1em and 1.25em) depending on the font you choose.
- Manually set line-height (the vertical space between two lines of text) to make your text less cramped and easier to read. Start with line-height: 1.25 (that is 1.25 times the font-size) for headings and at least 1.5 for paragraphs (but no more than 1.9) and adjust from there. The longer the line of text, the larger the line-height should be. To keep your text flexible, avoid adding a unit to your line-height. Without a unit the line-height you set will be proportional to your font-size. For example, line-height: 1.5 and font-size: 18px would give you a line height of 27 pixels. If you changed your font size to font-size: 16px on smaller screens, the computed line height would then change to 24 pixels automatically.
- Pay attention to how many characters are in a line of text and aim for 45 and 75 characters long (including punctuation and spaces). Doing so reduces reading fatigue for your users by limiting the eye and head movement needed to follow a line of text. With the variable nature of the web, it’s impossible to completely control line length, but you can use max-width values and breakpoints to prevent lines of text from getting too long. Generally speaking, the shorter the line of text, the faster it will be to scan for quick reading. And don’t worry too much about counting the characters in every line. Once you do it a few times, you’ll develop a sense for what looks right.

Source: [CSS Tricks](https://css-tricks.com/design-principles-for-developers-processes-and-css-tips-for-better-web-design/)
