# 02. Create a User Interface with Vanilla JavaScript and DOM

### [📹 Video](https://egghead.io/lessons/react-v2-01-create-a-user-interface-with-vanilla-javascript-and-dom?pl=a-beginners-guide-to-react-v2-6c4d)

### [💻 CodeSandbox](https://codesandbox.io/s/github/kentcdodds/beginners-guide-to-react/tree/codesandbox/01-document-create-element?from-embed)

## MHF Notes

Working with JS-generated DOM elements.

Get access to the root div

Append a div to it

Put text into it

## Egghead Notes

* To create a user interface with JavaScript you will need a place to append your JavaScript DOM \(Document Object Model\) elements. This will be the `root` of our application.
* Get access to that element using the document's API.
* We create our element and add properties to it.
* Finally, appended it to the DOM element.

```markup
<body>
  <div id="root"></div>
  <script type="text/javascript">
    const rootElement = document.getElementById('root');
    const element = document.createElement('div');
    element.textContent = 'Hello World';
    element.className = 'container';
    rootElement.appendChild(element);
  </script>
</body>
```

## Additional resource

* [Egghead - Select a DOM Element with document.getElementById](https://egghead.io/lessons/javascript-select-a-dom-element-with-document-getelementbyid)
* [MDN - `Element` Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Element)

