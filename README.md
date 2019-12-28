# Boilerplate

https://github.com/serhii-havrylenko/monorepo-babel-ts-lerna-starter#the-goal

## Concerns
1. Why Babel instead of native tsc?
  - Pros:
    - Babel is very mature
    - Do not miss cool feature from Babel community
    - Plays well with ESLint
  - Cons
    - Do not have all TypeScript features (e.g. `const enum`)
    - Do not have type check (this can be solved by configuring `tsconfig.json` file with `emit` option turn off.)
