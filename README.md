# fulljs
## Setting up React project from scratch

Following Pluralsight course and this: https://jscomplete.com/learn/1rd-reactful

- those instructions are meant to be up to date, but babel-eslint has changed to @babel/eslint-parser, installed like this:  
  `npm i -D @babel/eslint-parser`

## Also added Prettier as it was recommended:
- `npm install --save-dev --save-exact prettier`
- `echo {}> .prettierrc.json`
- `npx prettier --write` 
- `npx prettier --check` 
- `npm install --save-dev eslint-config-prettier`  
   
And added it to my IDE, Atom:
- `apm install prettier-atom`

## From https://github.com/prettier/prettier-atom :  
"How to use.  
There are two ways to format your code:  

Automatically format on save (requires enabling in Packages → Prettier → Toggle Format on Save)  
Run the command Prettier: Format to invoke Prettier manually  
Windows/Linux: ctrl + alt + f  
Mac: control + option + f  
Prettier will search up the file tree looking for a prettier config to use. If none is found, Prettier will use its default settings.  

Prettier will also respect your .prettierignore file."  

--------------------------

## To run development server:

- run two terminals with one of these commands each:  
`npm run dev:server`  
`npm run dev:bundler`  
And the page will be served on http://localhost:4242/   

---------------------------
