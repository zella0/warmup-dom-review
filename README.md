
# DOM assessment

## 1. What does DOM stand for?

> Your answer here
Document Object Model
---

## 2. In your own words, describe the DOM and how it is used.

> Your answer here
DOM is used to manipulates elements in HTML with javascript // giving verbs to our nouns
---

## 3. Where should a `<script>` tag that links to a js file that manipulates the DOM go? Why?

> Your answer here
Above the end of the body line, because we want to make sure all of our HTML are rendered
---

## 4. How does one select an element in the DOM that has an ID of `foo`?
document.getElementById('foo')
```js
//Your answer here
```

---

## 5. How does one select all elements in the DOM that have a class of `bar`?
document.getElementsByClassname('.bar')   ??
```js
//Your answer here
```

---

## 6. How does one select all elements in the DOM that are `<section>` tags?
document.getElementsByTagName('section')
```js
//Your answer here
```

---

## 7. How does one change the style color to red for all elements with the class `change-me`?

```js
document.getElementsByClassname('.change-me').style.color = "red";
//Your answer here
```

---

## 8. How does one create a new `<div>` element and append it to the body?

```js
let div = document.createElement('div')
document.body.appendChid(div)
```

---

## 9. How does one create an `<li>` element and append it to the `<ul>` with the id `todo-list`?

```js
let toDoList = document.getElementById('todo-list');
let li = document.createElement('li');
toDoList.appendChild(li);
//Your answer here
```

---
