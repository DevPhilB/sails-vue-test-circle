# sails-vue-test-circle
Sails.js & Vue.js with CircleCI

#### Install modules

```bash
$ cd sails-test && npm install
$ cd ../vue-test && npm install
```

### Development

```bash
$ cd sails-test && sails lift
$ cd ../vue-test && npm run serve
```
http://localhost:1337 (Sails) or http://localhost:8080 (Vue)

### Build & run

```bash
$ cd vue-test && npm run build
$ cd ../sails-test && sails lift
```