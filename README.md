# Vite + React + Typescript + TailwindCSS + Eslint + Prettier ⚡️

### Prerequisites

✅ **Node.js**: ^4.8.0 || ^5.7.0 || ^6.2.2 || >=8.0.0
✅ **Yarn**: v1.22.19

### Getting Started

```
git clone https://github.com/mhrdini/vite-react-ts-template.git example
cd example
yarn
yarn dev
```

### Setup from Scratch

1. Install node and npm (I used [nvm](https://github.com/nvm-sh/nvm))
2. Remove all modern Yarn installations and install [classic Yarn](https://classic.yarnpkg.com)
3. Create a Vite project with the React and Typescript template using Yarn
   ```
   yarn create vite <name of repo> --template react-ts
   ```
4. Go to root directory of project
   ```
   cd <name of repo>
   ```
5. Install and configure Prettier
   - Install:
     ```
     yarn add -D prettier
     ```
   - Create [.prettierrc](https://github.com/mhrdini/vite-reactts-starter/blob/main/.prettierrc) and
     [.prettierignore](https://github.com/mhrdini/vite-reactts-starter/blob/main/.prettierignore) in root directory
6. Install and configure Eslint and its plugins
   - Install:
     ```
     yarn add -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks
     ```
   - Create [.eslintrc](https://github.com/mhrdini/vite-reactts-starter/blob/main/.eslintrc) and
     [.eslintignore](https://github.com/mhrdini/vite-reactts-starter/blob/main/.eslintignore) in
     root directory
7. Install and configure TailwindCSS
   - Install:
   ```
   yarn add -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```
   - Setup [tailwind.config.js](https://github.com/mhrdini/vite-reactts-starter/blob/main/.tailwind.config.js)
   - Initialise [src/index.css](https://github.com/mhrdini/vite-reactts-starter/blob/main/src/index.css) with TailwindCSS directives
