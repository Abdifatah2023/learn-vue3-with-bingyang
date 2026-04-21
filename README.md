# learn-vue3-with-bingyang

A Vue 3 project built while following the "Learn Vue 3 with Bingyang" course. This repo focuses on **Vue Router** concepts, developed progressively across multiple branches.

## Branches

| Branch | Topic |
| ------ | ----- |
| `vue-router-basic-routing` | Setting up Vue Router and defining basic routes |
| `vue-router-nested-routes-dynamic-route-matching` | Nested routes and dynamic route matching with params |
| `vue-router-named-views` | Rendering multiple components with named router views |
| `vue-router-programmatic-navigation` | Navigating routes via `router.push()` and `router.replace()` |
| `vue-router-navigation-guards` | Protecting routes with `beforeEach` and per-route guards |
| `vue-router-transitions` | Animating route changes with Vue transitions |
| `vue-router-scroll-behavior` | Controlling scroll position on route change |
| `vue-router-lazy-loading-routes` | Code splitting with lazy-loaded route components |
| `vue-router-dynamic-routing` | Adding and removing routes at runtime |

## Tech Stack

- [Vue 3](https://vuejs.org/)
- [Vue Router 4](https://router.vuejs.org/)
- [Vite](https://vite.dev/)
- [JSON Server](https://github.com/typicode/json-server) — mock REST API for blog post data

## Project Setup

```sh
npm install
```

### Run the App

The app fetches blog post data from a local JSON Server instance. You need to run both in separate terminals:

```sh
# Terminal 1 — start the mock API (http://localhost:3000)
npm run server

# Terminal 2 — start the dev server (http://localhost:5173)
npm run dev
```

### Build for Production

```sh
npm run build
```

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Vue (Official)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Recommended Browser Setup

- Chrome/Edge/Brave: [Vue.js devtools](https://chromewebstore.google.com/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
- Firefox: [Vue.js devtools](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/)
