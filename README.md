![](https://raw.githubusercontent.com/sohalsdr/hexo-theme-one-paper-en/main/source/img/one-paper.png)



### Fork Notes

I forked this theme so that I would be able to use this theme for my own personal blog, translate Chinese elements in the code into English ones for my use case, and potentially make modifications for my particular use case. **I do not read or write Chinese**, so this translated README has been assembled based on Google Translate and my best guesses as to what it's supposed to mean.



### Translation of the original author's description

> This is a [Hexo](https://hexo.io/) theme designed and developed in February 2022.
>
> This is a "small and beautiful" theme. To be honest, it should be called a skin instead of a theme, but what does that matter :-)
>
> I don't want to make this theme big and comprehensive. It's simply intended for writing, and you can also understand it as a blog in the traditional sense. This theme focuses on being simple, clean, and lightweight. It's first visual effect is a blank page, aiming to simulate the feeling of reading on real paper.
>
> I'm trying to keep up with the official functionality, without adding any extra unless necessary.


 ### Live Demo

 [https://zheli.design/one-paper](https://zheli.design/one-paper) *(Note: This demo is hosted by the original theme author, and is in Chinese. Google Translate doesn't seem to be able to translate the entire page either.)*



 ### Theme Features

 -   Responsive design, compatible with phones, tablets, and PCs
 -   Supports all modern browsers
 -   Common Markdown format support
 -   Code highlighting and line number display
 -   Template pages: Home Page, Article, Detailed Page, Archive Page, and Single Page
 -   No comment space



### Install

 1. [Install Hexo](https://hexo.io/docs/), and [initialize a site](https://hexo.io/docs/setup).
 2. Navigate to the `<your-hexo-site>/themes` directory and add this repository as a submodule with `git submodule add https://github.com/sohalsdr/hexo-theme-one-paper-en`.
 3. Open `<your-hexo-site>/_config.yml` in your favorite text editor, and change the `theme` line to read `theme: hexo-theme-one-paper-en`.
 4. Run `hexo generate` and then `hexo s` to preview the site and make sure everything's working!


### Built-In Font

This theme includes the [Google Montserrat](https://fonts.google.com/specimen/Montserrat) font. If you don't want to use this font, do the following：

1.   Delete all files in `source/fonts`
2.   Delete `source/css/fonts.css`
3.   Open `source/css/style.css` in a text editor, and in the first line of the `body` selector, delete `"Montserrat"` so it looks something like below:

```css
body
{
    font-family: SF UI Text", "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "Segoe UI", "Helvetica Neue", Helvetica, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", sans-serif;
}
```



### Fix Code Highlighting

This theme has the [highlightjs](https://highlightjs.org/) and [highlightjs-line-numbers.js](https://github.com/wcoder/highlightjs-line-numbers.js) plugins built in. These are on by default, and don't need to be manually enabled. However, if code highlighting isn't working, change the following values in `<your-hexo-site>/_config.yml>` from `true` to `false`. It should look like the below:

```yml
highlight:
  enable: false
prismjs:
  enable: false
```



### Replacing the Favicon

Replace `source/img/favicon.png` with your favicon. 



### Credits

Original Theme Author: [zheli design](https://zheli.design/)



### Copyright

This theme is governed by the [MIT License](https://mit-license.org/).
