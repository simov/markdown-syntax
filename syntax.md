
# h1

h1
===

## h2

h2
---

### h3

#### h4

##### h5

###### h6

#h1

##h2

###h3

####h4

#####h5

######h6

# 测试一
## 测试二
### 测试三

# a/b c-d

# toc - [link](https://github.com/simov/markdown-viewer) hey [link](https://github.com/simov/markdown-viewer) a

# toc - header :alien: emoji

# toc - header `code` _italic_ **bold**

# 1

# verylongheaderverylongheaderverylongheaderverylongheaderverylongheader

# Horizontal Line

---

***

___

- - -

* * *

_ _ _

# List

- ul
  - ul
    - ul


* ul
  * ul
    * ul


+ ul
  + ul
    + ul


+ ul
  - ul
    * ul


- ul
    - ul
        - ul


1. ol
  1. ol
    1. ol

-

1. ol
1. ol
1. ol
    1. ol
    1. ol
    1. ol
        1. ol
        1. ol
        1. ol

---

# Text Formatting

**bold**

__bold__

*italic*

_italic_

`inline code`

> blockquote

## Combinations

> first
>> second
> > > third
> blockquote

*`something`*

**`something`**

_`something`_

__`something`__

***`something`***

___`something`___

__*`something`*__

*__`something`__*

**_`something`_**

_**`something`**_

> `blockquote`

> **`blockquote`**

> ***`blockquote`***

---

# Link

[link with inline URL](https://github.com/simov/markdown-viewer)

[link with index][1]

[named link][some-url]

[some-url]

[some-url][]

[parentheses in URL](https://en.wikipedia.org/wiki/Scheme_(programming_language))

[escaped parentheses in URL](https://en.wikipedia.org/wiki/Scheme_\(programming_language\))

<someone@gmail.com>

<https://github.com/simov/markdown-viewer>

https://github.com/simov/markdown-viewer

## Combinations

- italic
  - [*named link*][some-url]
  - *[named link][some-url]*
  - [_named link_][some-url]
  - _[named link][some-url]_
- bold
  - [**named link**][some-url]
  - **[named link][some-url]**
  - [__named link__][some-url]
  - __[named link][some-url]__
- bold italic
  - [***named link***][some-url]
  - ***[named link][some-url]***
  - [___named link___][some-url]
  - ___[named link][some-url]___
  - [*__named link__*][some-url]
  - [__*named link*__][some-url]
  - __*[named link][some-url]*__
- code
  - [`named link`][some-url]
- code italic
  - *[`named link`][some-url]*
  - [*`named link`*][some-url]
  - _[`named link`][some-url]_
  - [_`named link`_][some-url]
- code bold
  - **[`named link`][some-url]**
  - [**`named link`**][some-url]
  - __[`named link`][some-url]__
  - [__`named link`__][some-url]
- code bold italic
  - [***`named link`***][some-url]
  - ***[`named link`][some-url]***
  - [___`named link`___][some-url]
  - ___[`named link`][some-url]___
  - [*__`named link`__*][some-url]
  - [__*`named link`*__][some-url]
  - __*[`named link`][some-url]*__

---

# Image

![named-image]

![2]

![2][]

![][2]

[![3]][some-url]

[![named-image]][some-url]

![](http://i.imgur.com/rKYxW.jpg "Inline Alt Text")

[![](http://i.imgur.com/rKYxW.jpg)](https://github.com/simov/markdown-viewer)

  [1]: https://github.com/simov/markdown-viewer
  [2]: http://i.imgur.com/rKYxW.jpg (Image Index)
  [3]: http://i.imgur.com/rKYxW.jpg (Image Index with Link)
  [named-image]: http://i.imgur.com/rKYxW.jpg "Named Image"
  [some-url]: https://github.com/simov/markdown-viewer

---

# Code Block

    code block using indentation

```
fenced code block using backtick
```

~~~
fenced code block using tilde
~~~

---

# GFM

## Table

table        | col             | col                | col
---          | :---            | :---:              | ---:
default      | align left      | centered           | align right
default left | align left left | something centered | something align right
default      | align left      | centered           | align right

| table        | col             | col                | col
| -            | :-              | :-:                | -:
| default      | align left      | centered           | align right
| default left | align left left | something centered | something align right
| default      | align left      | centered           | align right

## Strikethrough

~~strikethrough~~

~~`something`~~

~~**`something`**~~

~~***`something`***~~

~~__`something`__~~

~~___`something`___~~

~~__*`something`*__~~

~~*__`something`__*~~

~~**_`something`_**~~

~~_**`something`**_~~

> ~~**_`something`_**~~

## Task List

- [x] task
- [ ] task
- [x] [link](https://github.com/simov/markdown-viewer), **formatting**, and <del>tags</del> supported

## Line Breaks

> Line 1
> Line 2
> Line 3

## Footnotes

Something something[^named]

And something else[^1], and a link[^2]


[^1]: This reference footnote contains a paragraph...

    * ...and a list

[^2]: https://github.com/simov/markdown-viewer
[^named]: https://github.com/simov/markdown-viewer

---

# HTML

## CSS Style

<h2>HTML Tags</h2>
<div style="text-decoration: underline;">
  <p><strong>bold</strong> and underline</p>
</div>

## Details/Summary

<details open><summary>Open by Default</summary>

- [x] task
- [ ] task

</details>

<details><summary>Click to Expand</summary>

```js
var code = 'block'
```

### Inner Header

[link](https://github.com/simov/markdown-viewer)

:alien:

</details>

## Definition List

<dl>
  <dt>Name</dt>
  <dd>Godzilla</dd>
  <dt>Born</dt>
  <dd>1952</dd>
  <dt>Birthplace</dt>
  <dd>Japan</dd>
  <dt>Color</dt>
  <dd>Green</dd>
</dl>

## KBD

<kbd>the kbd tag</kbd>

## Supscript/subscript

- 19<sup>th</sup>
- H<sub>2</sub>O

## MathML

<p>
When
<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi>a</mi><mo>&#x2260;</mo><mn>0</mn>
</math>,
there are two solutions to
<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi>a</mi><msup><mi>x</mi><mn>2</mn></msup>
  <mo>+</mo> <mi>b</mi><mi>x</mi>
  <mo>+</mo> <mi>c</mi> <mo>=</mo> <mn>0</mn>
</math>
and they are
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>x</mi> <mo>=</mo>
  <mrow>
    <mfrac>
      <mrow>
        <mo>&#x2212;</mo>
        <mi>b</mi>
        <mo>&#x00B1;</mo>
        <msqrt>
          <msup><mi>b</mi><mn>2</mn></msup>
          <mo>&#x2212;</mo>
          <mn>4</mn><mi>a</mi><mi>c</mi>
        </msqrt>
      </mrow>
      <mrow>
        <mn>2</mn><mi>a</mi>
      </mrow>
    </mfrac>
  </mrow>
  <mtext>.</mtext>
</math>
</p>

---

# Extras

## Syntax Highlighting

- [Examples and Syntax](prism.md)

<table>
  <thead>
    <tr>
      <th>Syntax Highlighting inside HTML table</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <pre class="language-js"><code class="language-js">var hello = 'hi'</code></pre>
      </td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>amazing</td>
    </tr>
  </tfoot>
</table>

## MathJax

- [Examples and Syntax](mathjax.md)

## Mermaid

- [Examples and Syntax](mermaid.md)

<table>
  <thead>
    <tr>
      <th>Diagram inside HTML table</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <pre><code class="mermaid">
          sequenceDiagram
            Alice->>+John: Hello John, how are you?
            Alice->>+John: John, can you hear me?
            John-->>-Alice: Hi Alice, I can hear you!
            John-->>-Alice: I feel great!
        </code></pre>
      </td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>amazing</td>
    </tr>
  </tfoot>
</table>

## Emoji

- shortcode: :wave: :alien:
- unicode: 👋 👽
- ascii: :D :/

```
:wave:
```
```
something :wave:
```
- < :wave:
- &lt; :wave:
- `:wave:`
- `something :wave:`
- [link](https://something/:wave:/a)
- emoji shortnames like `:smile:` will be converted to :smile: using EmojiOne images

```
:smile:
```

```js
console.log(':smile:')
```

---

# Escapes

<em\>HTML tags</em\>

\\ \` \* \_ \{ \} \# \+ \- \. \! \[ \] \( \)

`` `\(` ``

````
```
fenced code block
```
````

---

# Quirks

## Code block inside list

1. item 1

```
code block
```

2. item 2

3. item 3

## Tables inside nested lists

case 0: a table at indentation level 0, after a paragraph (at level 0) -- this should render the table not-indented

|A|B|
|-|-|
|1|2|

* case 1: a table at indentation level 1, after a list item at level 1 -- this should render the table indented once

    |A|B|
    |-|-|
    |1|2|

    * case 2: a table at indentation level 2, after a list item at level 2 -- this should render the table indented twice

        |A|B|
        |-|-|
        |1|2|

case 3: a table at indentation level 1, after a a paragraph (at level 0) -- this should render the raw text into a code block

    |A|B|
    |-|-|
    |1|2|

## blank line code block

1.  python 3.7.9:
```shell
Some code

Here
```

## Empty table cells

|   | Test    |
|---|---------|
| 1 | Problem |

| Column 1 | Column 2 | Column 3  |
|----------|----------|-----------|
| This     | Is       | Correct   |
|          | Rendered | Incorrect |


## h2 before

# h1

## Problem with spaces as new-line after bold/italics followed by a period

https://github.com/simov/markdown-viewer/issues/124

line 1 \*\*bold follwed by period\*\*.  
line 2  
line 3 \*\*bold\*\*  
line 4  
line 5 \*italic follwed by period\*.  
line 6  
line 7 \*italic\*  
line 8  
line 9 text followed by period.  
line 10  
line 11 text  
line 12  

## Blank line in code block breaks rendering

https://github.com/simov/markdown-viewer/issues/125

* First support:
```
Bold
Underline
InvertColors
ClearAttributes
ResetAllAttributes

Red
IntenseRed
OnRed
OnIntenseRed
```

## line breaks in CJK

https://github.com/simov/markdown-viewer/issues/127

Markdown-Viewer是浏览器上最好的Markdown预览插件，能够对Md文件进行高度定制化的预
览，支持众多选项设置，易于安装，免费开源。
