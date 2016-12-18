# vue-parallaxy
[![npm](https://img.shields.io/npm/v/npm.svg)](https://www.npmjs.com/package/vue-parallaxy)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/apertureless/vue-parallax/blob/master/LICENSE.txt)
![npm dependencies](https://david-dm.org/apertureless/vue-parallax.svg)

Is a compontent for fast 60fps parallax scroll effects in vue 2.

## Demo

[Demo here](https://apertureless.github.io/vue-parallax/)

## Install

`npm install vue-parallaxy` or `yarn add vue-parallaxy`

## Usage
*vue-parallax* works with slots. So you can pass an image or even srcsets for better mobile experiences.

```javascript
// Image.vue

<template>
  <parallax>
    <img src="path/cool-background-image.jpg" alt="very cool bg">
  </parallax>
</template>

<script>
  import Parallax from 'vue-parallaxy'
  export default {
    components: {
      Parallax
    }
  }
</script>
```


## Props

| Prop   |      Type      |  Default Value | Description
|----------|:-------------:|------|------|
| parallax |  Boolean | true | Activates parallax effect |
| speedFactor |  Number   | 0.15 | factor on how strong the effect is|
| fixed | Boolean | false | Other parallax effect. Image is fixed in position |
| sectionHeight | Number | 70 | section height for mobile |
| breakpoint | String | '(min-width: 968px)' | Media query for mobile deactivation |


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## Contributing

1. Fork it ( https://github.com/apertureless/vue-parallax/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

This software is distributed under [MIT license](LICENSE.txt).
