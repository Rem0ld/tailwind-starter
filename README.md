# Project starter with Tailwind ready to use

To generate css and each time you modify config file, execute this command

`npx tailwindcss build main.css -o output.css`

---

Too add font or colors:

```
module.exports = {
  purge: [],
  theme: {
    fontFamily: {},
  },
  extend: {
    colors: {}
  }
}
```

Too activate purging, add this in configuration file:

```
purge: {
  enabled: true,
  content: [
    './**/*.html'
  ]
}
```
