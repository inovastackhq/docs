### Create a new project

```sh
npm create nuxt@latest my-project-name
```

OR

```sh
npx nuxi@latest init my-project-name
```

### Move into the project and install dependencies

```sh
cd my-project-name
npm install
```

### Install common packages

Install only what your project needs.

```sh
npm i --save-dev @types/node
npx nuxi@latest module add security
npx nuxi@latest module add pinia
npm i pinia
npm i vue-i18n
npm i -D @iconify-json/mdi @iconify-json/tabler
```

### Optional

```sh
npm i @lottiefiles/dotlottie-vue
npm i dayjs
npx nuxi@latest module add @nuxtjs/leaflet
npm i leaflet
npm i -D @types/leaflet
npm i -D @nuxtjs/leaflet
```
