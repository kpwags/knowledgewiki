# :IS() Selector

**Source:** [Tuts+](https://webdesign.tutsplus.com/articles/new-css-is-for-easy-element-targeting--cms-34223)

## Examples

```css
article h1,
section h1,
aside h1 {
    font-weight: 900;
}
```

Becomes

```css
:is(article, section, aside) h1 {
    font-weight: 900;
}
```

---

```css
article h1, article h2, article h3, article h4, article h5, article h6,
section h1, section h2, section h3, section h4, section h5, section h6,
aside h1, aside h2, aside h3, aside h4, aside h5, aside h6, {
    font-weight: 900;
}
```
Becomes
```css
:is(article, section, aside) :is(h1, h2, h3, h4, h5, h6) {
    font-weight: 900;
}
```