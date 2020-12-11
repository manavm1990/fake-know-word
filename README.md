# CRA-ChakraUI-AirBnB-Prettier-Husky

This is a CRA _with_ ChakraUI, but w/o `"web-vitals'` and tests. The ability to run 'simple tests' via [Ponicode](https://www.ponicode.com/) is included.

The ability to `eject` has been removed.

Serviceworkers are removed 🔥.

'Automated' 'pre-commit' linting (using a modified AirBnB) with VS Code integration is provided.

`npm i` then `npm start` 🦄

Check out [Chakra UI](https://chakra-ui.com/) docs 💄.

---

This README will serve as more of a changelog. This will illustrate how this template got started and what was changed so it's more clear what the finished product is. You might also `git log` for addl. info.

---

1. [`npx create-react-app` with `--template @chakra-ui`](https://chakra-ui.com/guides/integrations/with-cra)
2. [Add `"airbnb"` to 'eslint.'](https://www.npmjs.com/package/eslint-config-airbnb)
3. Adding [Prettier] with ['pre-commit 🪝'](https://prettier.io/docs/en/precommit.html). Integration with linter is also resolved, along with '.prettierignore' 🙈.
4. 🔥 Remove 'serviceworkers' stuff.
5. `"react/react-in-jsx-scope": 0` - `import React from "react"` no longer needed! 🎊
6. Adding 'jsconfig.json' for [CRA absolute imports](https://create-react-app.dev/docs/importing-a-component/#absolute-imports)
7. Adding some starter files 🌱. See comments 💡 and/or delete 🔥 them if not needed.
