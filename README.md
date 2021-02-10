# Landing-page

Stack: Html, CSS, Flexbox, Grid Layout.

```
code block
``` 
```css
//css code
.title {
    grid-area: tt;
}

.name {
    grid-area: nm;
}

.email {
    grid-area: em;
}

.latter {
    grid-area: lt;
}

.send {
    grid-area: sd;
}

.wrapper {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-auto-rows: minmax(60px, auto);
    grid-gap: 20px;
    grid-template-areas: 
      "tt   tt"
      "nm   em"
      "lt   lt"
      "sd   sd";
}
```
