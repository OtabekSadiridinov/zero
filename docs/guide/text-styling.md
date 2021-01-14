# Text styling

## Headings

Any heading tags of HTML are styled by Zero UI. But, if you want to change style of other tags and if you want them looks like as headings. For instance, you may want the ``<div>`` or ``<p>`` tag looks like to the ``<h1>`` tag. You can add one of the classes below to the element you want.

::: warning
Avoid using two the same heading classes in one HTML element.!!!
:::

With just simple HTML heading tags without any heading classes.
```html
<h1>This is an h1.</h1>
<h2>This is an h2.</h2>
<h3>This is an h3.</h3>
<h4>This is an h4.</h4>
<h5>This is an h5.</h5>
<h6>This is an h6.</h6>
```

With heading classes. When we just want to change styles of other HTML element to heading styles.
```html
<div class="h1">This is an h1.</div>
<div class="h2">This is an h2.</div>
<div class="h3">This is an h3.</div>
<div class="h4">This is an h4.</div>
<div class="h5">This is an h5.</div>
<div class="h6">This is an h6.</div>
```

## Paragraphs

We just have the default paragraphs. But if you want to edit style of some HTML elements to make it looks like as paragraph, you can do this by a class named ``<p>``.

```html
<p>I am a paragraph</p>
<div>I am also a pragraph</div> <!--but in real it's a div with p class-->
```

## Small style text

The ``<small>`` tag defines smaller text (like copyright and other side-comments). You can also achive small text style with ``small`` class in other HTML elements.

```html
<small>I am a text, copyright, side-comment or just a small paragraph</small>
```

## Font weights
You can make texts bold or give boldness degree to them. 1 to 9 numbers after class of ``fw-`` can be equal to CSS ``font-weight``. And also CSS font-weight accepts``normal``, ``lighter``, ``bold``, ``bolder``,  ``initial`` and ``inherit`` properties. So, Zero UI, too. You can give that style to any HTML element by placing them after ``fw-``. Below see examples:

```html
<div class="fw-700">Hello I am in bold</div>
<div class="fw-bold">Hello I am in bold</div>
```

## Font styles
You can make text style italic with ``fs-[property]`` class. In the place of [property] you place one of the below roperties.


| Property | Definition                                 |
| -------- | :----------------------------------------- |
| normal   | Text will become right in its normal state |
| italic   | Text will look like more emphasized        |
| oblique  | Text will become like above italic style   |
| unset    | Just unsets the style of the text          |
| initial  | Returns text state to  its initial state   |
| inherit  | Inherits the font-style from its parent    |

```html
<p class="fs-italic">I am right curved text.</p>
```

## Text decoration

You may notice there is an underline below the html links created with ``<a>`` tag. If you want to remove/change that or make an HTML element look like it. This part may be helpful for you. And, also you can change the style of that underline. You do this by giving the `fw-` and any of below options added class to HTML element.

| Property | Definition                                    |
| -------- | :-------------------------------------------- |
| none     | Removes any text-decoration from HTML element |
| dashed   | Adds dashed line below the text               |
| dotted   | Adds dotted line below the text               |
| double   | Adds double line below the text               |
| lh       | Adds solid line through the text              |
| overline | Adds solid line above the text                |
| solid    | Adds solid line below the text                |
| ul       | Adds line under the text                      |
| wavy     | Adds wavy line below the text                 |
| inherit  | Inherits the text-decoration from its parent  |
| initial  | Returns text-decoration to  its initial state |

## Aligning text

Align any text element in HTML. ``text-`` and one of the below options.

| Property | Definition             |
| -------- | :--------------------- |
| left     | Aligns text to left    |
| right    | Aligns text to right   |
| center   | Aligns text to center  |
| end      | Aligns text to end     |
| justify  | Aligns text to justify |
| start    | Aligns text to start   |