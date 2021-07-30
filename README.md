# Stats Preview Card Component

<p align="left">
  <img src="https://img.shields.io/badge/Difficulty-Newbie-14C2C8?style=for-the-badge&logo=frontendmentor" alt="Difficulty">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/vanzasetia/stats-preview-card-component?style=for-the-badge&logo=github">
  <a href="https://twitter.com/vanzasetia" target="_blank"><img src="https://img.shields.io/twitter/follow/vanzasetia?logo=twitter&style=for-the-badge" alt="Twitter followers." /></a>
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vanzasetia/stats-preview-card-component?style=for-the-badge&logo=git">
  <img alt="Netlify" src="https://img.shields.io/netlify/2d2496d3-5e67-4d25-9c98-e8f1f4909066?style=for-the-badge&logo=netlify">
</p>
<p>
  <a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>

## Feedback and Live Review

- [🌍 Live Review](https://vanzastatscardcomponent.netlify.app/)
- [👉 Give feedback on Frontend Mentor platform](https://www.frontendmentor.io/solutions/stats-card-components-html5-css3-sass-4CzuajXQF)
- [🐦 Give Feedback on Twitter](https://twitter.com/vanzasetia/status/1420692932152094733?s=19)

## Table of contents

- [Story](#the-story-when-doing-this-challenge)
- [What I Learned](#what-i-learned)
- [Technology that I used](#built-with)
- [Useful Resources](#useful-resources)
- [Continued Development](#continued-development)

## The Story When Doing This Challenge

I will start with the `style-guide.md` file. This time it is showing me clearly on what color that I have to use. But, there are two font families which are [Inter](https://fonts.google.com/specimen/Inter) and [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca). It doesn't tell me when I need to use Lexend Deca or Inter.

So, I tried a couple times and then I found out that **COMPANIES**, **TEMPLATES**, and **QUERIES**, that needed `Lexend Deca`. The others text were `Inter`.

The hardest thing on this challenge was the purple overlay. You can use pseudo element, `background-blend-mode`, and `mix-blend-mode`. I used `mix-blend-mode`, because in my opinion it's using the `image` height. So, I didn't need to add `height` manually and it's simple.

Just write `mix-blend-mode: multiply` on img style and write `background-color` on it's parent element.

For the responsiveness, I used flexbox, but you could use grid if you wanted. There's no specific reason for that, it's just my personal preference.

## What I Learned
* Using `mix-blend-mode` property.
* I learned on how to use `picture` tag.

## Built With

This project is created using **HTML5**, **CSS3**, and **Sass**.

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="" width="auto" height="70px">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="" width="auto" height="70px">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="" width="auto" height="70px">
</p>

## Useful Resources
* [mix-blend-mode - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode)
* [picture: The Picture element - HTML: HyperText Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)

## Continued development

Even though it's been a while since I did this challenge, if you have
any feedback or other comments feel free to write it down in
**community feedback** on
[Frontend Mentor](https://www.frontendmentor.io/solutions/stats-card-components-html5-css3-sass-4CzuajXQF).
I will try my best to reply your comments and fixing issues that you
have found.
