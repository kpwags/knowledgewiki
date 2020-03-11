# Numeric Input

When it comes to number inputs we should probably follow the lead of Hanna Laakso, who wrote about their [accessibility problems](https://technology.blog.gov.uk/2020/02/24/why-the-gov-uk-design-system-team-changed-the-input-type-for-numbers/) and argued that we should stick to a regular input with a type of text like this instead:

```html
<input type="text" inputmode="numeric" pattern="[0-9]*">
```