# About this repo
This is a nodejs-boilerplate. there is no real use case for this code but all technical discussions and challenges are welcome :blush:

# Dependencies
* NodeJS 12 (nvm is preferred, .nvmrc exists)
* Yarn 1.22 or above
* Typescript 3.9.7
* Jest
* Es-Lint with typescript support

# Setup local :computer:
## Clone repo
```bash
git clone https://github.com/mahmood-sajjadi/node-boilerplate.git
cd node-boilerplate
```

## Install dependencies
npm is not allowed. please use yarn and gain benefit of having exact same dependency versions with the help of yarn.lock
`yarn install`

## Run it :running:
This code doesn't have any UI or CLI, it is creating a library. to use it, another project required. but always you are welcome to run test.
`yarn run test`

## Linting
As it is an small project not too many custom rules added, but default rules can be executed as follow
`yarn run lint`

## Building the project :fire:
just run following command and find the build result in folder named dist
`yarn run build`

## Debugging code and test cases :bug:
there are two ways to do that. by help of VSCode or any other IDE
### VSCode
there is folder in this project with the name of `.vscode`. this folder include the required configuration for you IDE.
Just open debug tab and run `Jest All`

### Other IDEs
run following command
`yarn run test:debug`
follow the command line messages by opening chrome and attaching the debugger.

# Contributing
This is just another nodejs-boilerplate to help me on start of any new nodejs project.
But I want to use this opportunity to ask all of you to review and suggest better way or more cool features for this nodejs-boilerplate
I tried to implement everything in few hours so there are many ways to improve this code and many other cool features which is missing, you are welcome to help me on this :wink:
What do you included in your nodejs-boilerplate?
to do that please
* create an issue in github in this repo https://github.com/mahmood-sajjadi/node-boilerplate/issues
* or fork this project and do the changes.

# What I like to do later
* improving build
* adding husky hooks
* add more eslit rules or maybe prettier
* adding some example project which using this library
* adding more inline-comments and maybe typedoc to auto generate documentation
* refactoring code to use .env files or config files for hardcoded values in the code
