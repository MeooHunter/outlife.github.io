---
layout: home

hero:
  name: Mine304
  text: Gì đó ko bt viết gì
  tagline: 1.20.4
  actions:
    - theme: brand
      text: Về Chúng Tôi
      link: /about
    - theme: alt
      text: Discord của chúng tôi
      link: https://discord.gg/bWKtMR7jmy

features:
  - title: tính năng 1
    details: #
  - title: tính năng 2
    details: #
  - title: tính năng 3
    details: #

---

<style>
.dark .VPContent.is-home {
  background-image: url(public/img/1.jpg);
}
.VPContent.is-home {
  background-image: url(public/img/4.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
}
.VPContent::before {
  content: "";
  position: fixed;
  top: 0; left: 0; bottom: 0; right: 0;
  backdrop-filter: blur(5px);
}

:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);
}
</style>
