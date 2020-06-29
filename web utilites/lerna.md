# Lerna

## Used by popular opensource JavaScript projects

---

### Tool for managing JS Projects with `monorepo` workflow.

```js
 Steps:
    - Install @ Root Level
        yarn add -D -W lerna

    - Initialise Lerna
        npx lerna init
        (It creates lerna.json a config file for lerna)

    - Add these config to lerna.json
        "npmClient":"yarn",
        "useWorkspace":"true",
        "lerna":"2.11.0"
    - Scripts
        "scripts":{
            "test":"lerna run test",
            "diff":"lerna diff",
            "new-version":"lerna version - conventional-commit=yes",
            "test:specific":"lerna run test --scope={@walnut/common,@walnut/server}",
            ---
            "test:specific":"lerna run test --scope = @walnut/common"
        }
```

## !! Use `Commitizen` for conventional commits
