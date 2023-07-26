# INTRODUCTION TO MARKDOWN 

<!--HEADING-->
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

##### Heading 6

---

<!--Italics-->
_This is going to be a paragraph that is using italic styling_

*This is going to be a paragraph that is using italic styling*

---

<!--Strong-->

This is an example of **strong text**, anything between two opening asterisks and two closing asterisks will be displayed as **strong text**

This is another example of a way to have __strong text__ in our document. Anything between two opening underscores and closing underscores will be displayed as __strong text__.

<!--Strike Through-->

This is an example of a ~~strikethrough~~ text. Anything between the opening double tilde and closing double tilde characters will be displayed as ~~strikethrough~~ text.

---
<!--Horizontal Rule-->

We can add triple hyphens to create a horizontal rule for separating content. 

Another way to add _Horizontal Rules_ in our document markdown is by using three underscores.
___

<!--Escape Character Rule using Backslash-->

This is an example of a *text with an asterisk*. When we don't want it to be italicized, we want to use the backslash \ to escape the rule of using an opening \*asterisk* and closing \*asterisk* to enclose the text content.
---

<!--Blockquote-->

> We use the greater than symbol to display a block of text as a quote with a background and line on the left side.

> *“The first time you're careful. You learn what you need to know to kill and take care of the details.”* __Ted Bundy__

---
<!--Link Rule-->

**NOTE**:
We wuold want to put the link description inside square brackets and the link to the resource inside of two open and close parentheses.

[Sena Farahgibli Pexels Collection](https://www.pexels.com/@sena-124841843/)

__NOTE__:
We can add a balloon tip title to our link by using double quotes after the link to the resource.

[Sena Farahgibli Pexels Collection](https://www.pexels.com/@sena-124841843/ "This is Sena's Pexel Photo Collection")

<!--LIST ITEM RULES-->
<!--UNORDERED LIST ITEMS-->

* Item 1 - this is going to be our list item 1
  * This is our list item 1 child item 1
  * This is our list item 1 child item 2
* Item 2 - this is going to be our list item 2
  * This is our list item 2 child item 1
  * This is our list item 2 child item 2
* Item 3 - this is going to be our list item 3
  * This is our list item 3 child item 1
  * This is our list item 3 child item 2
* Item 4 - this is going to be our list item 4
  * This is our list item 4 child item 1
  * This is our list item 4 child item 2
* Item 5 - this is going to be our list item 5
  * This is our list item 5 child item 1
  * This is our list item 5 child item 2

<!--ORDERED LIST-->

1. Item 1 - this is going to be our list item 1
   
   1.1 This is our list item 1 child item 1
  
   1.2 This is our list item 1 child item 2
  
2. Item 2 - this is going to be our list item 2
   
   2.1 This is our list item 2 child item 1
   
   2.2 This is our list item 2 child item 2
   
3. Item 3 - this is going to be our list item 3
   
   3.1 This is our list item 3 child item 1

   3.2 This is our list item 3 child item 2
   
4. Item 4 - this is going to be our list item 4

   4.1 This is our list item 4 child item 1

   4.2 This is our list item 4 child item 2
   
5. Item 5 - this is going to be our list item 5
   
   5.1 This is our list item 5 child item 1

   5.2 This is our list item 5 child item 2

---

<!--CODE BLOCK INLINE EXAMPLE RULE-->

**NOTE**: *__Backticks__ will allow us to show the code block or paragraph tags in this example. It is located below the tilde character and on tab of the tab key*

`<p> This is a paragraph taw with an inline code block example and closing tags </p>`

---


<!--IMAGE RULE-->

![This is an image](https://images.pexels.com/photos/54379/pexels-photo-54379.jpeg?auto=compress&cs=tinysrgb&w=600)

---
<!--GITHUB FLAVOR SET OF CODE BLOCK-->

<!-- CODE BLOCKS FOR GITHUB DOCUMENTATION-->

```install npm
npm install

npm start
```

---

**NOTE**:
You can specify some syntax code blocks for different languages

```javascript
function testAdd(num1,num2){
return num1 + num2;
}
```

```python
def pythonAdd(num1,num2);
return num 1 + num2;
```

```C#
Public static int Sum(int num1, int num2)
{
int total;
total = num1 + num2;
return total;
}
```

---

<!--table rules-->

| Name   | Nickname | Email |
|--------|----------|-------|
|Kathleen| Kat      | kkmborja@kodego.com |
|Mark    | Mumbles  | mark@mumbles.com|  

---

<!--TASKS LIST-->

* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [ ] Task 4
