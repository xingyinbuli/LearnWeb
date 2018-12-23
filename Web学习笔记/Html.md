# Html basic

[MDN HTML](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

`HTML (Hypertext Markup Language)`

![img](https://mdn.mozillademos.org/files/9347/grumpy-cat-small.png)

![img](https://mdn.mozillademos.org/files/9345/grumpy-cat-attribute-small.png)

典型案例：

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image">
  </body>
</html>
```

## image

图片案例：`alt`指的是图片资源不加载的时候 

```
<img src="images/firefox-icon.png" alt="My test image">
```

## heading

标题HTML contains 6 heading levels, `<h1>–<h6>`

## list

1. **<u>Unordered lists</u>** are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in element.
2. **<u>Ordered lists</u>** are for lists where the order of the items does matter, such as a recipe. These are wrapped in an  element.

Each item inside the lists is put inside an ***Li*** (list item) element.

```
<p>At Mozilla, we’re a global community of</p>
    
<ul> 
  <li>technologists</li>
  <li>thinkers</li>
  <li>builders</li>
</ul>

<p>working together ... </p>
```

## Links

```
<a>link</a>
<a href="">link</a>
<a href="baidu.com>link</a>
```

## link

```
<link href="main.css" rel="stylesheet">
```

`rel` means relationship

# CSS basic

`CSS (Cascading Style Sheets)` ![CSS p declaration color red](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)

> **Selector**

The HTML element name at the start of the rule set. It selects the element(s) to be styled (in this case, [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) elements). To style a different element, just change the selector.

> Declaration

A single rule like `color: red;` specifying which of the element's **properties** you want to style.

> Properties

Ways in which you can style a given HTML element. (In this case, `color` is a property of the [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) elements.) In CSS, you choose which properties you want to affect in your rule.

> Property value

To the right of the property after the colon, we have the **property value**, which chooses one out of many possible appearances for a given property (there are many `color` values besides `red`).