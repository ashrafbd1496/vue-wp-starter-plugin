# Vue.js WordPress Starter

A WordPress [Vue.js](https://vuejs.org/) starter plugin with required toolbelts 😎

## 📦 What it ships with?

- Pre-configured webpack config
  - Babel loader, Vue loader, CSS and LESS loader
  - Separate `vendor.js` with all vendor scripts
  - Uglify JS for production
  - Separate `frontend.js` and `admin.js`
  - Extracted CSS/LESS to separate `frontend.css` and `admin.css` files.
  - Auto reloading with Browser with **Browsersync** _([config](config.json))_
- [Vue](https://vuejs.org/) and [Vue Router](https://router.vuejs.org/en/)
- Frontend (shortcode) and Backend starter app
- Modern PHP codebase with [namespace](http://php.net/manual/en/language.namespaces.php) support

## 🚚 Running

1. Clone this repository in your plugins folder
2. Activate the plugin
3. Use node version 16 (command : nvm install 16 and nvm use 16, check node version : node -v)

## 👨‍💻 Post Installation

1. The name of the plugin class is `Base_Plugin`, change the class name with your desired class name.
1. Replace the PHP namespace `App` with your desired name.
1. Replace `baseplugin` or `BASEPLUGIN` reference in files.
1. Run `npm install`
1. To start developing, run `npm run dev` 🤘
1. For production build, run `npm run build` 👍

## 🎁 Preview

![screenshot](http://tareq.in/owiyZI+)

## ⛑ Extra Goodies

## About

Made by [Tareq Hasan](https://github.com/tareq1988) from [weDevs](https://wedevs.com).

_Found anything that can be improved? You are welcome to contribute._
