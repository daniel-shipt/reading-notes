# Structure web pages with HTML

# Wireframes 
## What is a wireframe?

* Wireframing is a practice used by UX designers that allows them to create and plan their desgin for a website, app, or product!
  Based on user research, this process focuses on how the client or designer wants the user to process information on a site.

* Wireframing is a great way of getting to know how a user interacts with your interface.

### Here are a few examples of how different designers can structure the process from design to implementation:

* Wireframe > Interactive Prototype > Visual > Design 
* Sketch > Code
* Sketch > Wireframe > Hi-Def Wireframe > Visual > Code
* Sketch > Wireframe > Visual > Code

### Three key principles on how to make a good wireframe:

1. **Clarity** - Your wireframe is an aid for you to visualize the layout of your site page and make sure the important questions and goals are achievable, without being distracted by aesthetics
2. **Confidence** - Ease of navigation throughout your site and clear visuals increase user confidence in your brand.
3. **Simplicity is key** - Too much information, copy or links can be distracting to the user and will have a negative affect on the users ability to achieve their goals.

# HTML

### What is HTML?

* HTML (Hypertext Markup Language) is the code used to structure a webpage and its content. Content can be structured using paragraphs, bullet points or even images. 
HTML consists of a series of elements. You can enclose, or wrap parts of the content to make it appear a certain way. For example, enclosing tags can make a word or image hyperlink
to somewhere else, they can italicize words or even make the font bigger or smaller.

### Anatomy of an HTML element

```<p>My dog has a lot of energy</p>```

1. **Opening tag:** This consists of the element ``<p>`` (paragraph element) which is wrapped in opening and closing **angle brackets**. This states where the element begins.
2. **Closing tag:** This is the same as the opening tag, but it includes a *forward slash* before the element name ``</p>``. This states where the element ends.
3. **The Content:** "My dog has a lot of energy" - This is the content of the element, which in this case is just text.
4. **The element:** All of the content together make up the element.

### Attributes of an element

* Attributes contain extra information about the element that you don't wat to appear the content itself.

``` <p class ="editor-note">My dog has a lot of energy</p> ```

* In this example **class** is the attribute *name* and **editor-note** is the attribute *value*. The **class** attribute allows you to provide the element a non-unique identifier 
that can be used to target it.

### An attribute should always have the following: 

1. A space between it and the element name.
2. The attribute name followed by an equal sign.
3. The atrribute value wrapped by opneing and closing quotation marks.

### Nesting elements 

* You can also place elements inside of other elements, called nesting.

``` <p>My dog has <strong>A LOT</strong> of energy.</p> ```

Note: You do need to make sure that the elements are properly nested. In this example, it is opened using the ```<p>``` element first, then the ```<strong>``` element, so we have
to make sure to close the ```<strong>``` element first, and then the ```<p>``` element.



