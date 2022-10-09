## Installation for existing projects

First, run the following command:

```bash
yarn add -D @commitlint/cli @commitlint/config-conventional eslint eslint-config-next  eslint-config-prettier eslint-plugin-jsx-a11y eslint-plugin-prefer-arrow-functions eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-react-prefer-function-component prettier husky prettier-plugin-tailwindcss
```

Add the following files to the existing project:

```
.eslintignore
.eslintrc.js
.prettierignore
.prettierrc
commitlint.config.js
jsconfig.json
```

Add the following folders to the existing project:

```
.husky
```

Add the following commands to your package.json scripts:

```json
...
"scripts": {
    "prepare": "husky install",
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
...
```
