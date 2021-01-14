# Introduction

## What is ZeroUI.

Zero UI - is a CSS framework created by Otabek Sadiridinov for using easily in any project. Zero is lightweight and class-based CSS framework. This helps you not to write much CSS and solve most common CSS problems. Then, this framework helps you to create the most wanted components.

Why Zero UI? Because you don't need to create anything from zero. Zero UI helps you...

## Installation

To use Zero UI in your projects, you need to include its CSS and Javascript files in your project. You can get the files in your project with this with 3 ways. And, we recommend all of the by looking the situation of your project. If you want to use Zero UI with CLI project, you should use the 3<sup>rd</sup> [Install via NPM/Yarn](#_3-install-via-npm-yarn) way. If you just want to use Zero UI with HTML, CSS, JS included project, you should use the 1<sup>st</sup> [Directly with tags](#_1-directly-with-tags) way. And if you don't want to download the static files but use via internet you should use the 2<sup>nd</sup> [Using CDN](#_2-using-cdn) way.

### 1.Directly with tags

You need include the files like below in order to call local files. Put the link tag in the head part of HTML document. Also, you need to include the script tag before the end of body part.

```html
<link href="./aseets/zero/base.css"></link>
<script href="./aseets/zero/base.js"></script>
```

### 2.Using CDN

This is the same with the [Directly with tags](#_1-directly-with-tags) part. But, this time you just replace relative urls with absolute ones, instead. So, you don't need to download Zero UI's static files. They will be loaded from the <abbr title="Content Delivery Network">CDN</abbr> .

```html
<link href="https://cdnjs.com/zero/base.css"></link>
<script href="https://cdnjs.com/zero/base.js"></script>
```

### 3.Install via NPM/Yarn

Let's say you've a CLI project. Maybe Vue.JS, React, or Angular and etc... You should install Zero UI using a package manager into your CLI project. These package managers are commonly NPM or Yarn. We recommend using Yarn. Because, it's great!

```bash
yarn add zero # with yarn
npm install zero # with npm
```

Then, include below registering part in your entry file. This file maybe named as app/main/entry.js or another file.

```js
# VueJS
import Vue from "vue"
Vue.register(ZeroUI, "node_modules/zeroui/base")
```

## And more

Lorem ipsum dolor sit amet consentequer....
