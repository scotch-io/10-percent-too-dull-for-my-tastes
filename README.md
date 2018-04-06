# Announcing "10% Too Dull for My Tastes" Sublime Text Color Scheme

Article: https://scotch.io/bar-talk/announcing-10-too-dull-for-my-tastes-sublime-text-color-scheme

![](https://cdn.scotch.io/2/MtfjT0UuRQe6zKIC9Bgc_cover-image.gif)


I was recently bored and messing around with [Sublime Text 3](https://www.sublimetext.com) to see if there were any **new cool things**, **major updates**, **themes and color schemes**, or **plugin packages** that I haven't heard about lately to compete with all the [Visual Studio](https://scotch.io/courses/make-visual-studio-code-your-editor) awesome hype these days.

I came across some really neat new (and old) themes / color schemes out there. I found one I never heard of that I **absolutely loved**:

* [Behave](https://github.com/fnky/behave-theme): *A theme that makes you happy like cats on the internet, and Morgan Freeman's sexy voice*.

I can't believe I've never heard of that before - I absolutely love it. Ended up modifying everything based on this. Just making it more dull and boring (personal preference).

This isn't supposed to be some big thing. Just a **quick and fun little project** to release. Thanks for checking it out.


## Features

I ended up modifying the Behave theme a bit for my own tastes. It's now:

* **90% Perfection!**
* **10% Dull!**
* **100% Awesome!**

So in all seriousness:

* **Light, attractive colors for the eye**
* **Simplicity**
* **Cursive font**

This won't be for everyone, but so far I've been using it and and really enjoy it. Might as well share it to the world.

### Thought Process

This *just* isn't my own personal preference thing. I tried to be methodical about how the colors are selected. Everything is supposed to have a "light" tone to it and related items are all shades of each other. For example, brackets are bright, variables are less bright, and then their strings are least bright. In a somewhat cascading fashion.



## What does it looks like?

Here's some examples of it in action!

**JavaScript**
![](https://cdn.scotch.io/2/xwxZZIowT5q6jVLUAwCc_javascript.gif)
![](https://cdn.scotch.io/2/SJEbY8LPRxq2YSU4HNFc_javascript.jpg)

**HTML with Brackets (Vue.js)**
![](https://cdn.scotch.io/2/6s5lAn77RhGRWokqnMO8_vue.png)

**PHP (Laravel)**
![](https://cdn.scotch.io/2/cXB21BorRR2uCtHa8STO_php.png)


**HTML / PHP (WordPress)**
![](https://cdn.scotch.io/2/pighOud6RWzxRw9qaLM5_html.png)

**CSS / LESS / SASS**
![](https://cdn.scotch.io/2/7dck9E1pRQCiGUB19Wuk_css-sass-less.png)

**JSON**
![](https://cdn.scotch.io/2/sSEAK3toSVSxpKpoz5uQ_Screen%20Shot%202018-02-28%20at%2011.55.10%20PM.png)









## What's up with the name?

This was made pretty quickly, but I'm happy with how it turned out.

It's named after the first feedback I received for it. Which is honestly only **90% fair...**

Seriously though, I hope someone out there enjoys it as much as I do. And, definitely, please feel free to send **Pull Requests** to improve.



## How to Download

1. Install [Sublime Text 3](https://www.sublimetext.com/)

### Package Control

Open the `Command Palette` (cmd + shift + p) and search:

* 10% Too Dull for My Tastes Color Scheme


Then add to your user settings:

```
"color_scheme": "Packages/10% Too Dull for My Tastes Color Scheme/scotchy.tmTheme",
```


### Manual

Download (or clone) to your Sublime Text's package folder. On Mac located here:

```bash
# Replace bigmac with whatever your user name is
/Users/bigmac/Library/Application Support/Sublime Text 3/Packages
```

## Cursive Monospace Fonts

You need a cursive font library installed on your machine. Your options are:

The font used for the code is "[Operator Mono](https://www.typography.com/blog/introducing-operator)" and requires a license.

Super solid alternatives are: The official Material Design monospace font "[Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono)" or "[Fira Code](https://github.com/tonsky/FiraCode)".

Whatever you choose, you can add this to your user settings.

```json
"font_face": "Operator Mono",
"font_options":
[
    "gray_antialias",
    "subpixel_antialias"
],
"font_size": 17,
```


## Improved Settings

To each its own here, but here are my current Sublime Text settings. Mainly check out the `theme`, `color_scheme`, `font_options`, and `indent_guide_options`.

```json
{
    "theme": "ayu-mirage.sublime-theme",
    "color_scheme": "Packages/spocky-scotch/scotchy.tmTheme",

    "always_show_minimap_viewport": true,
    "bold_folder_labels": false,
    "detect_indentation": false,
    "dictionary": "Packages/Language - English/en_US.dic",

    "file_exclude_patterns":
    [
        ".DS_Store"
    ],
    "folder_exclude_patterns":
    [
    ],
    "font_face": "Operator Mono",
    "font_options":
    [
        "gray_antialias",
        "subpixel_antialias"
    ],
    "font_size": 17,
    "highlight_line": true,
    "ignored_packages":
    [
        "Markdown",
        "Vintage"
    ],
    "indent_guide_options":
    [
        "draw_normal",
        "draw_active"
    ],
    "overlay_scroll_bars": "enabled",
    "scroll_past_end": true,
    "show_definitions": false,
    "spell_check": true,
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": false
}
```


## Pull Requests Updates

Please send.



## Conclusion

Again, all the hardwork was done by the [Behave](https://github.com/fnky/behave-theme) creator. This is a simple lazy fork of it where I:

* * Picked new colors
* Modified a few things
* Added italic support

Give him all credit for the original theme work. Hope you guys like this one! It's free for all. Thanks!
