---
marp: true
theme: gaia
color: black
---

![VueJS logo bg width:80%](./logo.png)

---

## Introduction

- JS framework for building user interfaces.
- Created by Evan You.
- Unlike other big frameworks (React, Angular), Vue isn't maintained by a large corporation such as Meta or Google.
- Like React, it builds on top of HTML, CSS and JS.
- Used to develop single-page applications.

---

## Why Vue (not exclusive)

- Creates dynamic frontend apps
- Component-based architecture promotes reusability
- Easy to integrate with other projects
- Integrates well with backend systems to make full stack.
- Virtual DOM, fast
- Good community

---

## Why Vue? (exclusive)

- Vue is simple and intuitive to learn.
- Inspired from Angular as best parts of Angular extracted, leaving behind the limitations.
- Doesn't contain the complexities of other frameworks. Syntax etc.
- Can be used on server-side when used with SSR framework (Nuxt).
- Extremely lightweight

---

## Layout

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    ...
  </head>
  <body>
    <div id="app"></div>
  </body>
</html>
```

---

```javascript
const app = Vue.createApp({
    template: '<h1>Hello World</h1>',
})

app.mount(#app);
```

---

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    ...
  </head>
  <body>
    <div id="app">{{message}}</div>
  </body>
</html>
```

---

```javascript
const app = Vue.createApp({
    data() {
        message: "Hello World",
    }
})

app.mount(#app);
```

---

## Advantages

- Short learning curve
- Good community support
- Shortest startup time

## Disadvantages

- Doesn't render in older operating systems
- Not as trustworthy overall as not backed by large organisation
- Developed in China, so most documentations in Chinese

---

## Companies that use it

- Adobe
- Grammarly
