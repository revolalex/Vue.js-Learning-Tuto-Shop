![](https://img.shields.io/badge/made%20with-javaScript-yellow?logo=javaScript).
![](https://img.shields.io/badge/made%20with-vue.js-green?logo=vue.js).

<img src="https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fgithub.com%2Frevolalex%2FVue.js-Learning-Tuto-Shop" alt="Hits">.

# Vue.js-Learning-Tuto-Shop

<img width="300" src="https://user-images.githubusercontent.com/56839789/79344382-0ce95f00-7f30-11ea-9ed2-b81fa9315821.gif">

# Vue Instance:
What I learned.
- How to begin writing a Vue application with a Vue instance, and how to load basic data onto the webpage.
- The Vue instance is the root of every Vue application
- The Vue instance plugs into an element in the DOM
- The Vue instance’s data can be displayed using the mustache-like syntax {{ }} called an expression.
- Vue is reactive

# Attribute Binding:
What I learned.
- Data can be bound to HTML attributes.
- Syntax is v-bind: or : for short.
- The attribute name that comes after the : specifies the attribute we’re binding data to.
- Inside the attribute’s quotes, we reference the data we’re binding to.

# Conditional Rendering:
What I learned.
- There are Vue directives to conditionally render elements:
- v-if
- v-else-if
- v-else
- v-show
- If whatever is inside the directive’s quotes is truthy, the element will display.
- You can use expressions inside the directive’s quotes.
- V-show only toggles visibility, it does not insert or remove the element from the DOM.

# List Rendering:
What I learned.
- The v-for directive allows us to iterate over an array to display data.
- We use an alias for the element in the array being iterated on, and specify the name of the array we are looping through. Ex: v-for="item in items"
- We can loop over an array of objects and use dot notation to display values from the objects.
- When using v-for it is recommended to give each rendered element its own unique key.

# Event Handling:
What I Learned.
- The v-on directive is used to allow elements to listen for events.
- The shorthand for v-on is @.
- You can specify the type of event to listen for: click, mouseover, any other DOM event.
- The v-on directive can trigger a method.
- Triggered methods can take in arguments.
- this refers to the current Vue instance’s data as well as other methods declared inside the instance.

# Class & Style Binding:
What I learned.
- Data can be bound to an element’s style attribute.
- Data can be bound to an element’s class.
- We can use expressions inside an element’s class binding to evaluate whether a class should appear or not.

# Computed Properties:
What I learned.
- Computed properties calculate a value rather than store a value.
- Computed properties can use data from your app to calculate its values.

# Components:
What I learned
- Components are blocks of code, grouped together within a custom element.
- Components make applications more manageable by breaking up the whole into reusuable parts that have their own structure and - behavior.
- Data on a component must be a function.
- Props are used to pass data from parent to child.
- We can specify requirements for the props a component is receiving.
- Props are fed into a component through a custom attribute.
- Props can be dynamically bound to the parent’s data.
- Vue dev tools provide helpful insight about your components.

# Communicating Event:
What I learned
- A component can let its parent know that an event has happened with $emit.
- A component can use an event handler with the v-on directive ( @ for short) to listen for an event emission, which can trigger a method on the parent.
- A component can $emit data along with the announcement that an event has occurred.
- A parent can use data emitted from its child.

# Form:
What I learned
- We can use the v-model directive to create two-way binding on form elements.
- We can use the .number modifier to tell Vue to cast that value as a number, but there is a bug with it.
- We can use the .prevent event modifier to stop the page from reloading when the form is submitted.
- We can use Vue to do fairly simple custom form validation.

## Contact	
- [![LinkedIn][linkedin-shield]][linkedin-url] 	
- revolalex@gmail.com






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alexandre-rodrigueza/









