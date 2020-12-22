# Learning DOM
1. ## **`document`** object
    - main source for now <https://www.w3schools.com/jsref/><br>
    #### **getting HMTL elements --->>>**
    - `document.getElementById(id)` - <https://www.w3schools.com/jsref/met_document_getelementbyid.asp>
    - `document.getElementsByTagName(tag)` - <https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp>
    - `document.getElementsByClassName(element class)` -
    <https://www.w3schools.com/jsref/met_document_getelementsbyclassname.asp>
    - `document.querySelector(CSS selectors)` - <https://www.w3schools.com/jsref/met_document_queryselector.asp>  
    - `document.querySelectorAll(CSS selectors)` - <https://www.w3schools.com/jsref/met_document_queryselectorall.asp>
    #### **create new HTML element (node) --->>>**
    - `document.createElement(nodename)` - https://www.w3schools.com/jsref/met_document_createelement.asp
    - `document.createTextNode(data)` - <https://developer.mozilla.org/en-US/docs/Web/API/Document/createTextNode>  
    - `ParentNode.append(...nodesOrDOMStrings)` - <https://developer.mozilla.org/en-US/docs/Web/API/ParentNode/append>
2. ## **`element`** object
    #### **events --->>>**
    - `element.addEventListener(event, function, useCapture)` -
    <https://www.w3schools.com/jsref/met_element_addeventlistener.asp>
    #### **attributes --->>>**
    - `element."attributeName, not class attribute".[attribute property]? = "property[value of the property]?"`
    - `element.setAttribute(attributename, attributevalue)` -
    <https://www.w3schools.com/jsref/met_element_setattribute.asp>    
    - `element.removeAttribute(attributename)` - <https://www.w3schools.com/jsref/met_element_removeattribute.asp>
    #### **insert element relative to some element --->>>**
    - `element.insertAdjacentHTML(position, text)` - <https://developer.mozilla.org/en-US/docs/Web/API/Element/insertAdjacentHTML>
3. ## **`window`** object
    #### **timing events --->>>**
    - `setInterval(function, milliseconds, param1, param2, ...)` -<https://www.w3schools.com/jsref/met_win_setinterval.asp>
    - `setTimeout(function, milliseconds, param1, param2, ...)` - <https://www.w3schools.com/jsref/met_win_settimeout.asp>