---
layout: page
title: SCSS
---

#SCSS lint
https://github.com/brigade/scss-lint/blob/master/config/default.yml

#FLexbox
https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

http://breakpoint-sass.com

# Referencing selectors

On Sass 3.4:

```scss
.semantic {
  @at-root {
    ul#{&} {
      padding: 0;
      margin: 0;
    }
    p#{&} {
      margin: 0;
    }
  }
}
```

Generates:

```scss
ul.semantic {
  padding: 0;
  margin: 0;
}

p.semantic {
  margin: 0;
}
```
