---
title: pydeck
css: ['abs-layout','bg-nord', 'bg-open-color', 'border-layout', 'card', 'devices', 'filters', 'font-nord', 'font-open-color', 'lines',  'nord-dark', 'nord-light', 'nord', 'open-color', 'pure', 'spaces', 'text-circle', 'text-rect', 'default-fonts','typo', 'default', 'style','ek']
self_contained: True
mathjax: True
remarkjs: "https://remarkjs.com/downloads/remark-latest.min.js"
remark_config:
    ratio: "16:9"
    navigation:
        scroll: True
        touch: True
        click: false
    countIncrementalSlides: True
    highlighting:
        highlightLanguage: "-"
---

class: middle, center, inverse
# Title of My pydeck Presentation
<br>

### With a Subtitle to Match
<br>

by @someone

---
# A First Slide  
With three bullet points:  
+ Here is point 1
+ Here is point 2
+ Here is point 3

---
class: nord-light
# A Second Slide  
With three incremental bullet points:  

+ Here is point 1  

--

+ Here is point 2  

--

+ Here is point 3

---

class: nord-dark, center, middle

# Dark Theme

with centered text

<small>.letter-spacing-20[As a chapter page feel cool]</small>

---
class: nord-dark, center, middle font-xxl

# Gestalt theory suggests that 

$$x > \sum_{i=1}^{n}{x_i}$$

---
class: typo font-xl
# border layout for columns

.west.width-50.gutter-12[

### .nord11[a column title]

- a lefthand bullet
- another lefty
]

.east.width-50.gutter-12[

### .nord15[another col title]

- a righthand bullet
- a second righty
]

---
class: typo nord font-xl
# Automatic Col layout

This way you can ignore the formatting and just have the list lay itself out as necessary

.column-2.column-norule.b-center[

- row 1
- row 2
- row 3
- row 4
]

---

class: nord-light
# A look at parks in Colorado

.west.width-70.gutter-8[
![Parks](https://www.colorado.com/sites/default/files/blackcanyon_NPS_Lisa-Lynch.jpg)
]

.east.width-30.font-xl.gutter-8.left[
- with images, it's useful to use manual columns
- so that the columns can differ in size
- allowing for a larger image
]

---
class: nord-dark 
# A look at parks in Colorado using autocols
<br>

.column-2.column-norule.font-xxl[
![Parks](https://www.colorado.com/sites/default/files/blackcanyon_NPS_Lisa-Lynch.jpg)
- with auto cols
- the image is smaller
- and the third bullet is just an example
]

---

class: center middle font-xxl

# For More Info On Built-In Styling

See the [remark-it example page](https://remark-it.vercel.app/index-en_US.html)