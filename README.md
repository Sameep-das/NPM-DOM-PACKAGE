
# DOM-HELPER NPM PACKAGE

This package provides various helper functions to manipulate the DOM tree with ease. It is safe and easy to use

Functions Included 
-
    1. Fetch an element by its class name.
    2. Class toggling using a selector class or an id.
    3. Add and Remove CSS styles.
    4. Manipulate text content.
    5. Create and append a child to any parent container.


All Functions Parameters -
-
    1. getElementByClass(selectorClassName)
    2. removeClassByClass(selectorClass, targetClass)
    3. addClassByClass(selectorClass, targetClass)
    4. removeClassByID(selectorID, targetClass)
    5. addClassByID(selectorID, targetClass)
    6. setPropByClass(selectorClass, property, value)
    7. removePropByClass(selectorClass, property)
    8. changeText(selectorClass, text)
    9. createAndAppendChild(element, attribute, attValue, contentOfChild, parentClassName)

## Demo

1. Create a package.json file in your project folder. Use -


```npm init``` or ```npm init -y```

2. Inside your project folder in the terminal type -

  ```npm install @sameep21/dom-helper```
  or
  ```npm i @sameep21/dom-helper```

3. Inside your script file you can use - 

```import * as dommer from 'https://esm.sh/@sameep21/dom-helper'```
or ```import * as dommer from '@sameep21/dom-helper';```

//change dommer to whatever you want

4. Or, create a minimal declaration file (optional, for better editor support):
- Create a file named dom-helper.d.ts in your project (e.g., in the root or in a types folder) with:
    ```declare module '@sameep21/dom-helper';```

5. To use any function -
```dommer.createAndAppendChild('a', 'href', 'index.html', 'Links to parent', 'parent');```

