# Vue JS 3 + Firebase recipe

## Setting up a Firebase Project

## VueFire
[VueFire](https://vuefire.vuejs.org/) Realtime bindings between Vue/Vuex and Firebase   
___Note: This version currently supports Vue 2 and Firebase 7. Support for Vue 3 / Composition API and Firebase 8 is on the way.___   
Install VueFire
```bash
npm install vuefire firebase
```

## Vue CLI
Install Vue CLI globally (Requirers Node)   
```bash
npm install -g @vue/cli

vue --version
```
Create a project   
```
vue create <project-name>
  > Manually select features
    > Choose Vue version
    > Babel
    > TypeScript
    > Linter / Formatter
      > 3.x
  ? Use class-style component syntax? N
  ? Use Babel alongside TypeScript (required for modern mode, auto-detect polyfills, transpiling JSX)? Y
  > ESLint + Prettier
  > Lint on save
  ? Where to you prrefer placing config for Babel, ESLint, etc?
  > In dedicated config files
  ? Save this as preset for future projects? N
```
Run the application   
```
npm run serve
```
