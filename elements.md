
# h1

## h2

### h3

#### h4

##### h5

###### h6

---

# List

- ul
  - ul
    - ul

1. ol
2. ol
3. ol

# Text Formatting

regular

**bold**

*italic*

`inline code`

> blockquote

# Blockquotes

> regular

> _italic_

> **bold**

> `code`

> **`code bold`**

> ***`code bold italic`***

> nested
>> block
> > > quotes

# Link

- https://github.com
- [regular][url]
- [*italic*][url]
- [**bold**][url]
- [***bold italic***][url]
- [`regular`][url]
- *[`italic`][url]*
- **[`bold`][url]**
- ***[`bold italic`][url]***

  [url]: https://github.com/simov/markdown-viewer

# Inline Code

- `regular`

- *`italic`*

- **`bold`**

- **_`bold italic`_**

# Code Block

```
fenced code block using backticks
```

```js
var prism = 'syntax highlighting'
```

```mmd
sequenceDiagram
  Alice->>+John: Hello John, how are you?
  Alice->>+John: John, can you hear me?
  John-->>-Alice: Hi Alice, I can hear you!
  John-->>-Alice: I feel great!
```

# Image

![](http://i.imgur.com/rKYxW.jpg "Inline Alt Text")

# Emoji

:smile:

# MathJax

$$
J(\theta) = - \frac{1}{m} \sum_{i=1}^m [ y^{(i)}\ \log (h_\theta (x^{(i)})) + (1 - y^{(i)})\ \log (1 - h_\theta(x^{(i)}))] + \frac{\lambda}{2m}\sum_{j=1}^n \theta_j^2
$$

---

# GFM

## Table

table        | col             | col                | col
---          | :---            | :---:              | ---:
default      | align left      | centered           | align right
default left | align left left | centered centered  | align right right
default      | align left      | centered           | align right

## Strikethrough

~~regular~~

~~_italic_~~

~~**bold**~~

~~**_bold italic_**~~

~~`regular`~~

~~_`italic`_~~

~~***`bold italic`***~~

> ~~**_`code bold italic`_**~~

## Task List

- [x] task
- [ ] task

## Footnotes

Something something[^named]

And something else[^1], and a link[^2]


[^1]: This reference footnote contains a paragraph...

    * ...and a list

[^2]: https://github.com/simov/markdown-viewer
[^named]: https://github.com/simov/markdown-viewer

## Line Breaks

> Line 1
> Line 2
> Line 3

---

# HTML

## CSS - inline styles

<p style="text-decoration: underline;">Underline css style</p>

## `abbr` - abbreviation

An abbreviation of the word attribute is <abbr title="foobar">attr</abbr>.

## `details`, `summary` - details disclosure, details summary

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

</details>

## `dl`, `dt`, `dd` - definition list

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

## `kbd` - keyboard input

<kbd>the kbd tag</kbd>

## `sub`, `sup` - subscript, superscript

- H<sub>2</sub>O
- 19<sup>th</sup>

---

## Example Text

Nullam quis risus eget [urna mollis ornare]() vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur `ridiculus` mus. Nullam id dolor id nibh ~~ultricies vehicula~~.

The following is **rendered as bold text**.

The following is *rendered as italicized text*.

```
fenced code block using backticks
```

> This is a blockquote Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.

- Nullam congue mollis metus
- Donec massa sapien
- Tristique ac metus sit amet

1. Nullam congue mollis metus
2. Donec massa sapien
3. Tristique ac metus sit amet

| Name | Score | Time
| :-   | :-:   | -:
| John | 24    | 55s
| Doe  | 1135  | 2m:15s
| Duh  | 1     | 5s

---
