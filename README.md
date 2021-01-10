# login_app

## Project setup

```
vue create login_app

? Please pick a preset: Manually select features
? Check the features needed for your project: Choose Vue version, Babel, Router, Vuex, Linter
? Choose a version of Vue.js that you want to start the project with 2.x
? Use history mode for router? (Requires proper server setup for index fallback in production) Yes
? Pick a linter / formatter config: Prettier
? Pick additional lint features: Lint on save
? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files
? Save this as a preset for future projects? No

cd login_app

vue add vuetify

npm install material-design-icons-iconfont -D

npm install @fortawesome/fontawesome-free -D

npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### vuetify.js

```
import 'material-design-icons-iconfont/dist/material-design-icons.css'
import '@fortawesome/fontawesome-free/css/all.css'

export default new Vuetify({
  icons: {
    iconfont: 'md',
  },
})
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
