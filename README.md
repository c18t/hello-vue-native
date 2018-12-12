# hello-vue-native
ExpoなしのVue Nativeお試しです(失敗)

- [Installation — Vue Native](https://vue-native.io/docs/installation.html#Setup-with-React-Native)

## Usage
```sh
$ react-native run-ios
```

## Project Making
```sh
$ ghq get git@github.com:c18t/hello-vue-native.git
$ mv hello-vue-native/ HelloVueNative
$ react-native init HelloVueNative --version 0.55.0
prompt: Directory HelloVueNative already exists. Continue?:  (no) yes
:
:
:
$ mv HelloVueNative hello-vue-native
$ cd hello-vue-native
$ touch README.md
$ touch LICENSE
$ yarn add vue-native-core vue-native-helper
$ yarn add -D vue-native-scripts
$ touch vueTransformerPlugin.js
$ touch rn-cli.config.js
$ mv App.js App.vue
$ open ios/HelloVueNative.xcodeproj
```

## cf.
- http://masaru-tech.hateblo.jp/?page=1488889556
- https://github.com/GeekyAnts/vue-native-core/issues/84

## License
[WTFPL](./LICENSE)
