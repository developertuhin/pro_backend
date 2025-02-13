# Project setup for professional industiral development

-[Model Link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj?origin=share)

## Startar setup for every development :

==> Create a git repositories to push all code updation
==> Create a blank Project folder
=> npm init (To initialze package.json )
=> create a reamde.md file

## Folder and File Structue::::

==> it means root folder
=> sub folder
--> file

==> Public =>temp -->.gitkeep
==>src=>(controllers,db,routes,middlewares,utils)
==>src -->(constants.js,app.js,index.js)

--> .gitignore (search in google for node all gitignore codes)
-->.env
-->.prettierignore
-->.prettierrc
Packages :

---

- Nodemon = npm i -D nodemon ( Reload server every single update inside the code)
- Prettier = npm i -D prettier (Make professional code extra like ,, tab gap, colon rules,)

## Prettier Package [file setup]

## .prettierrc

{
"singleQuoete":false,
"bracketSpacing":true,
"tabWidth":2,
"trailingComma":"es5",
"semi":true
}

## .prettierignore

_.env
.env
.env._
/.vscode
/node_modules
./dist
