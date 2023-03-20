# Yuriy Ulanov

---

## Junior Frontend Developer

---

## Contact Info:

#### Phone: +7(921)871-89-18

#### E-mail: 1859697@gmail.com

#### Telegram: @yuriyula

---

## Summary:

I've been doing front-end development for about a year. Previously engaged in SEO promotion of Internet resources and contextual advertising. I am currently developing online games in html 5 using canvas and pixi.js

---

## Key skills:

- HTML, CSS - advanced
- JavaScript - intermediate
- Git, Github
- Webpack, Gulp
- Sass, Pug
- PHP - basics
- React - intermediate

## Code example:

function digitalRoot(n) {
let arr = String(n).split('');
let res = arr.reduce((a, b) => +a + +b, 0);

if (String(res).length == 1) {
return res;
} else {
return digitalRoot(res)
}
}
