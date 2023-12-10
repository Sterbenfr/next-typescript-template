# Next TypeScript Template

This is a complete Next.js project template using TypeScript, linters like
ESlint and Prettier and the app router. It allows you to skip the tedious
details for the following:

- Adding and configuring TypeScript support.
- Enabling TypeScript linting.
- Automatic linting and checks for Typescript errors on commit.

> [!TIP]  
> **Note that I am using npm for the following steps but you can do the same
> with other package manager like yarn**

## Project Creation

Clone this repo into the directory you want to use for your new project, delete
the Git history, and then reinit as a fresh Git repo:

```bash
$ git clone https://github.com/Sterbenfr/next-typescript-template.git <your project directory>
$ cd <your project directory>
$ rm -rf ./.git/
$ git init
$ npm install
$ npx husky install
```

> [!IMPORTANT]  
> You'll also need to install the
> [Prettier - code formatter ](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode),
> [Prettier ESLint](https://marketplace.visualstudio.com/items?itemName=rvest.vs-code-prettier-eslint)
> and
> [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
> extensions in your VSCode

## Initial Publish

Some additional steps need to be performed for a new project. Specifically,
you'll need to:

1. Create your project on GitHub (do not add a README, .gitignore, or license).
2. Add the initial files to the repo:

```bash
$ git add .
$ git remote add origin git@github.com:<your GitHub username>/<your project name>
$ git push -u origin master
```

## Usage

I will also recommend my keybinds to be able to lint without saving and I'll
slip in some that I find usefull :

> [!NOTE]  
> To use these keybinds you need to open the command palette (ctrl + shift + p
> by default) and search Preferences : Open Keyboard Shortcuts (JSON) and **_Do
> Not Forget_** to delete the shortcuts.json file after

[Recommended Keyboard Shortcuts](./shortcuts.json)

You can then run the server by using :

```bash
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) with your browser to
see the result.

You can start editing the page by modifying `app/page.tsx`. The page
auto-updates as you edit the file.

## Learn More

Official Next.js TypeScript documentation:
[Next.JS Typescipt Doc](https://nextjs.org/docs/basic-features/typescript)
