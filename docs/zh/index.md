---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "VueDefer"
  text: "基于视口的懒挂载、懒更新组件"
  tagline: 进入视口才挂载，离开自动冻结
  image:
    src: /logo.svg
  actions:
    - theme: brand
      text: 快速开始
      link: /zh/guide/getting-started

features:
  - title: 🚀 懒加载挂载
    details: 组件仅在进入视口时才会挂载渲染，减少首屏渲染压力
  - title: ❄️ 更新冻结
    details: 组件离开视口后自动冻结更新，避免不必要的重渲染
  - title: 📦 轻量零依赖
    details: 体积小巧，无任何第三方依赖，开箱即用
---
