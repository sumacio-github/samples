This is a cheat sheet for markdown.

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
*This text* is italic

_This text_ is italic

<!-- Strong -->
**This text** is strong

__This text__ is strong

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal Rule -->
___
---

<!-- Escape Characters -->
\*This text\* is not italic

\_\_This text\_\_ is not strong

<!-- Blockquote -->
> This is a quote

<!-- Links -->
[Sumac.io](https://github.com/sumacio-github)

[Sumac.io](https://github.com/sumacio-github "Hover over title")

<!-- Images -->
![Sumac logo](https://avatars0.githubusercontent.com/u/54295791?s=200&v=4)

<!-- Unordered List -->
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
- Item 1
- Item 2
- Item 3
    - Nested Item 1
    - Nested Item 2

<!-- Ordered List -->
1. Item 1
1. Item 2
1. ITem 3
    1. Nested Item 1
    1. Nested Item 2

<!-- Task List -->
* [x] Task 1
* [ ] Task 2
- [x] Task 1
- [ ] Task 2

<!-- Inline Code -->
This is an `<span>inline code</span>` block

<!-- Code Block -->
```
<html>
    <body>
        <h1>Hello World</h1>
        <p>This is a formatted block of code.</p>
    </body>
</html>
```
```html
<html>
    <body>
        <h1>Hello World</h1>
        <p>This is a sample web page.</p>
    </body>
</html>
```
```css
#tower-of-pisa {
    font-style: italic;
}
```
```bash
sudo apt-get update
sudo apt-get install git -y
git clone https://github.com/sumacio-github/samples.git
```
```java
var coffee = new Coffee();
while (working) {
    if (coffee.isEmpty()) {
        coffee.brew();
        coffee.refill();
    }
    coffee.drink();
    work.execute();
}
```
```javascript
function drink(cup1, cup2) {
    return cup1 + cup2;
}
```
```python
def drink(cup1, cup2):
    return cup1 + cup2
```

<!-- Tables -->
| Name | Department | Price |
| -----|:----:| -----:|
| Left Justified | Centered | Right Justified |
| Lamp | Office | 14.99 |
| Blender | Kitchen Appliance | 199.99 |
| Dog Food Storage Container | Pet Supplies | 9.99 |