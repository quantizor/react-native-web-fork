---
title: Installation
date: Last Modified
permalink: /docs/installation/index.html
eleventyNavigation:
  key: Installation
  parent: Start
  order: 1
---

:::lead
An overview of how to install and use {{ site.name }}.
:::

React Native for Web can be used for multi-platform and web-only applications. It can be incrementally adopted by existing React Web apps and integrated with existing React Native apps. Preact is also supported.

```shell
npm install react-dom react-native-web@npm:{{ site.packageName }}
```

The Babel plugin is recommended for build-time optimizations.

```shell
npm install --save-dev babel-plugin-react-native-web
```

---

## Quickstart

### Expo

[Expo](https://expo.dev) is a framework and a platform for universal React applications. [Expo for Web](https://docs.expo.dev/workflow/web/) uses React Native for Web, provides dozens of additional cross-platform APIs, includes web build optimizations, and is compatible with the broader React Native ecosystem. See the Expo docs for more information.

### Create React App

[Create React App](https://github.com/facebook/create-react-app) is a basic way to setup a simple, web-only React app with built-in support for aliasing `react-native-web` to `react-native`. However, it's generally recommended that you use Expo.

```shell
npx create-react-app my-app
cd my-app
npm install react-native-web@npm:{{ site.packageName }}
npm start
```
