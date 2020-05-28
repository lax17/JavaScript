# Some insights While Builiding this project:

# HTML
  
<u>HTML data-* Attribute </u>
<ul>
<li>The data-* attribute is used to store custom data private to the page or application.</li>
<li>The data-* attribute gives us the ability to embed custom data attributes on all HTML elements.</li>
<li>The stored (custom) data can then be used in the page's JavaScript to create a more engaging user experience (without any Ajax calls or server-side database queries)</li>
</ul>
<i>The data-* attribute consist of two parts:</i>
<ul>
<li>The attribute name should not contain any uppercase letters, and must be at least one character long after the prefix "data-"</li>
<li>The attribute value can be any string.</li>
</ul>

# CSS

<b> CSS :nth-child() Selector </b>
The :nth-child(n) selector matches every element that is the nth child, regardless of type, of its parent. in other words,
The :nth-child selector allows you to select one or more elements based on their source order
:nth-child(number) {
  css declarations;
}

<b> z-index </b>
The z-index property specifies the stack order of an element.
An element with greater stack order is always in front of an element with a lower stack order.
Note: z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky)

# JAVASCRIPT
<ul>
<li>The <b>querySelector()</b> method returns the first child element that matches a specified CSS selector(s) of an element.
Note: The querySelector() method only returns the first element that matches the specified selectors. To return all the matches, use the <b>querySelectorAll()</b> method instead.</li>

<li><b>addEventListener()</b> works by adding a function or an object that implements EventListener to the list of event listeners for the specified event type on the EventTarget on which it's called.</li>
<li><b>The getAttribute()</b> method returns the value of the attribute with the specified name, of an element.</li>
<li>An <b>arrow function</b> expression is a syntactically compact alternative to a regular function expression, although without its own bindings to the this, arguments, super, or new.target keywords. Arrow function expressions are ill suited as methods, and they cannot be used as constructors.</li>
</ul>

<b> Final MEDITATION APP LOOKS LIKE:</b><br>
<img src="https://user-images.githubusercontent.com/41922928/83127200-7e9ff580-a0f7-11ea-9cbd-8331ea632174.JPG" width="150%">
