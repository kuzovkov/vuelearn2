https://cli.vuejs.org/guide/
-----------------------------------

##Install

Warning regarding Previous Versions

The package name changed from vue-cli to @vue/cli. 
If you have the previous vue-cli (1.x or 2.x) package installed globally, 
you need to uninstall it first with 

```bash
npm uninstall vue-cli -g 
#or 
yarn global remove vue-cli
```

```bash
npm install -g @vue/cli
vue --version
npm install -g @vue/cli-service-global
```

##Checking
```bash
nano `App.vue`
```

```html
<template>
  <h1>Hello!</h1>
</template>
```
```bash
vue serve
vue serve MyComponent.vue

vue build MyComponent.vue
```

##Create project

```bash
vue create hello-world

vue ui
```
#Pulling 2.x Templates (Legacy)

```bash
npm install -g @vue/cli-init
# vue init now works exactly the same as vue-cli@2.x
vue init webpack my-project
```