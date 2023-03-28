# Project Template Generator

Build your own custom project templates with this project template generator from anywhere on your machine.

## Why the Project Template Generator

If you have to create alot new projects with the same setup you can use this template generator to setup a single project and reuse that project for your new projects.

## Yarn

This project is using yarn berry to switch to yarn 3.x from 1.x use

```bash
yarn set version berry
```

if you want to switch back use

```bash
yarn set version classic
```

## Steps to setup the template generator

```bash
1. yarn install
2. create your project template in the src/templates directory. I have already added a sample-project in there for guidance.
3. Once you have added your "base project" run yarn build.
4. run yarn start to test if everything works.
5. choose your project to use and name your new project.
6. wait for the new template post processor to finish installing your new projects node_modules.
```

### Use Generator from anywhere

Register generate-template as a command line interface

```bash
1. run npm link
2. check if it is linked correctly by running npm list -g
3. When successful you can run "generate-project-template" from anywhere on your machine
```

## Publish it to npm

```bash
1. run yarn version to check versioning and update version
2. run yarn pack to check packaging
3. run yarn publish to publish your package
2. When successful you can run "npx generate-project-template" on any machine!
```
