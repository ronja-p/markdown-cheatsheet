# Markdown Cheatsheet

This cheatsheet was created by following Traversy Media's [Markdown Crash Course](https://youtu.be/HUBNt18RFbo "Markdown Crash Course - Traversy Media")

---

## Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
---

## Emphasis

```
*This text is italic*

_This text is italic_
```
*This text is italic*

```
**This text is strong**

__This text is strong__
```
**This text is strong**

```
~~This text is strikethrough~~
```
~~This text is strikethrough~~

---

## Horizontal Rule

```
---
___
```

## Blockquote

```
> This is a blockquote
```
> This is a blockquote

## Links

```
[Example Link](https://www.google.com "Link title")
```
[Example Link](https://www.google.com "Link title")

## Images

```
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```
![Markdown Logo](https://markdown-here.com/img/icon256.png)

---

## Lists

### Unordered List:

```
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
```
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2

### Ordered List:

```
1. Item 1
1. Item 2
1. Item 3
    1. Nested Item 1
    1. Nested Item 2
```
1. Item 1
1. Item 2
1. Item 3
    1. Nested Item 1
    1. Nested Item 2
---

## Inline Code Block

```
`const helloWorld = () => console.log("Hello World");`
```
`const helloWorld = () => console.log("Hello World");`

---

## Code Blocks

```
    ```bash
    npm install
    ```
```
turns into
```bash
npm install
```
---

```
    ```javascript
    const addNums = (num1, num2) => {
        const sum = num1 + num2 
        return sum
    }
    ```
```
turns into
```javascript
    const addNums = (num1, num2) => {
        const sum = num1 + num2 
        return sum
    }
```
---

## Tables

```
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| Jane Doe | jane@gmail.com |
```
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| Jane Doe | jane@gmail.com |

---
## Task Lists

```
* [x] Task 1
* [x] Task 2
* [ ] Task 3
```
* [x] Task 1
* [x] Task 2
* [ ] Task 3