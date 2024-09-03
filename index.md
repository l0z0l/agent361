---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Hello,Agent!"
  text: "记录构建历程，从想法到实现。"
  tagline: -----------------------------------
  image:
    src: /logo.svg
    alt: Agent361
  actions:
    - theme: brand
      text: 阿里云百炼
      link:  https://bailian.aliyun.com/
    - theme: alt
      text: 开始阅读
      link: /agent000

features:
  - icon: 💰
    title: BillowFlow
    details: myinv.cn - 投资助手，为您的投资决策提供数据驱动的洞察。无论是股票、债券还是加密货币，我们都能帮助您做出明智的选择。
  - icon: 🌍
    title: 网站导航
    details: soul.icu —— 我的个性化互联网导航，开启智能网站搜索之旅。
  - icon: 🔑
    title: InsightWebx
    details: blockbase.cn —— 探索区块链技术与业务的深度学习平台。
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #ba34fe 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>