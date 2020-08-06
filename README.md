This repo is created for the Youtube course CSS tutorial

## CSS Tutorial and related files

1. CSS crash course series:

   - Tutorial: https://www.youtube.com/watch?v=RnMusR_1NEc&list=PLtPNAX49WUFN-MDcKvoIMSIOUBFg0n74C
   - File: all repo

2. CSS Course 2020 | CSS Selectors, Properties and Values | Absolute Beginners | Part #1

   - Tutorial: https://youtu.be/05Zv_9wHKe8
   - Files: `index.html`, `style/style.css`

3. CSS Flexbox Tutorial | Flexbox Layout - CSS Course 2020 For Beginners | Part #2
   Tutorial: https://youtu.be/otGdMjmB0ZY

   - Files: `css-basic.html`, `flex-web-page.html`, `style/flexbox-layout.css`

4. CSS Grid Tutorial | Grid Layout - CSS Course 2020 For Beginners | Part #3

   - Tutorial: https://youtu.be/9s0MjByo_nQ
   - Files: `css grid/grid-basic.html`

5. How To Create Responsive Layout With CSS Grid | Grid Tutorial - CSS Course 2020-Beginners | Part #4
   - Tutorial: https://youtu.be/-54X0m-camg
   - Files: `css grid/grid-layout.html`, `style.css`

### what is CSS

CSS is:

- Cascading Style Sheets
- describes how HTML elements should be displayed
- makes website prettier.
- can be written in HTML elements or in the
  external file with .css extension

### Foundation of CSS

1. Selector
2. Property
3. Value

- CSS works alongside with HTML to make web page beautiful.

### CSS Syntax

`Selector { Property: Value; }`

`Property: Value;` is call CSS declaration

### How to write CSS

- Inline CSS - Inside HTML Element
- Embedded CSS - In the head Element
- External CSS - Separate file with .css extension

### CSS Selector

    - CSS selector is the reference for the content that you like to apply your CSS. They are HTML elements, id, classes, attributes and their values.
    - The selector can be used alone or they can be combined to refer to the specific content or the group of the content.

The selectors are categories as per below:

#### 1. Basic Selector

I have included the most commonly used selector in the Basic selector. The most commonly used selector as below:

1. HTML elements such as `\*, <p>, <div>, <span> and more box elements
2. ID attribute, where the value of the id is referred, ie. `<p id="main-para">` where the `id` attributes and the value is `main-para`. In this case, the `#main-para` is used as the selector. `#` means that the value the id of an element. ID is used to target one specific content
3. The class attribute, where the value of the class is referred, ie. `<p class="top-para">` where the `class` attributes and the value is `top-para`. In this case, the `.top-para` is used as the selector. `.` means, it is the class of the element. ID is used to target one specific content. Class selector mainly used to refer multiple contents which needs exactly the same CSS.

#### 2. Element Selector

I already mentioned element in the Basic selector. However, I'd like to look into little more in the element selector.

Element selector can be used as a combination as follow:

1. The element inside an Element
2. Multiple Elements
3. Combination of elements
4. Relation to an element

#### 2. Attribute Selector

Similar to the Element selector, we can use attributes to target the content to apply the CSS.

Element selectore can be used as combination as follow:

1. Element inside a Element
2. Multiple Elements
3. Combinatiion of elements
4. Relation to an element

#### 3. Pseudo-elements `selector:: pseudo-element {

property: value;
}
I.e. =>
p:: first-line {
color: red;
}`

#### 4. Pseudo-class `selector: pseudo-class {

property: value;
}
I.e. =>
a: hover {
color: red;
}`
