# `gh-pages`

- Install gh-pages
- Any static website can be hosted on the github.
- In the `package.json` add `2` commands

```json
     "homepage": "https://snrakshith.github.io/<project-name>",
     "npm run deploy": "gh-pages -d build"

```

- You can also do :

```json

     "npm run deploy": "npm run build && gh-pages -d build"

```
