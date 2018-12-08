<template lang="pug">
  div
    div.fixed.wid100.top0.bgWhite
      scrollactive(:offset="-10").nav.cols
        a.scrollactive-item(href="#section0") Logo
        .navRight.hide
          a.scrollactive-item(href="#section1") What we do
          a.scrollactive-item(href="#section2") Why we're different
          a.scrollactive-item(href="#section3") Who we are
          a.scrollactive-item(href="#section4") Get in touch
          a.button Client Login
    nuxt
</template>
