# vue-cordova-demo

## 1. Create Vue project
```
vue create vue-cordova-demo
```
## 2. Create Cordova project
```
cordova create cordova_app net.z9p.app "Z9P Blog"
```
## 3. Add i18n supports
```
vue add i18n
```
## 4. Add android supports
```
cd cordova_app
cordova platform add android
```

## 5. Run now
```
npm install
npm run build
cd cordova_app
cordova run
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
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
