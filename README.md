# image-slider-component-for issue-report

## Problem:
```
First of all, thanks for creating a great slider component! :) 

Got Swiper JS working in/with Vite (https://vitejs.dev/), so it seems like a specific Vue Cli-problem?

Got a problem using Vue Cli (in both Vue 3 and Vue 2, https://cli.vuejs.org/). Probably because the CLI system looks for index.js in node_modules/swiper/vue and other dependencies-folders, and the folder structure is currently not set up like that. 

Would be great if someone could look at this issue :)


Error message in Vue Cli:
 ERROR  Failed to compile with 2 errors  

These dependencies were not found:
                                                                                                                                                                                                                ts/ImageSwiper.vue?vue&type=script&l
* swiper/css in ./node_modules/cache-loader/dist/cjs.js??ref--12-0!./node_modules/babel-loader/lib!./node_modules/cache-loader/dist/cjs.js??ref--0-0!./node_modules/vue-loader-v16/dist??ref--0-1!./src/components/ImageSwiper.vue?vue&type=script&lang=js                                                                                                                                                                      ts/ImageSwiper.vue?vue&type=script&l
* swiper/vue in ./node_modules/cache-loader/dist/cjs.js??ref--12-0!./node_modules/babel-loader/lib!./node_modules/cache-loader/dist/cjs.js??ref--0-0!./node_modules/vue-loader-v16/dist??ref--0-1!./src/components/ImageSwiper.vue?vue&type=script&lang=js


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
