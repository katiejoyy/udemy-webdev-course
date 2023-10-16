# CSS Selectors
## Selectors
- * universal selector
- element selector, which could be all images or buttons change 
- selector list, select all h1s and all h2s

### ID selector
- ID can be used on anything for css to hook onto
- It should be only used once to be unique.


### Class selector
- Class can be applied to multiply elements 

### Descendant selector
- select all <a>'s that are nested inside an <li>
- li a {
    colour: teal;
}
### Adjacent Selector
- select only the paragraphs that are immediately preceded by an <h1>
 - h1 + p

 ### Direct child
 - select only the <li>'s that are direct children of a <div> element
 - div > li

 ### Attribute selector
 - Select all input elements where the type attrubute is set to "text
 - input[type="text"]

 ### Pseudo classes
 - keyword added to a selector that specifies a special state of the selected element(s)
 - :active
 - :checked 
 etc

 ### Pseudo elements
 - keyword added to a selctor that lets you style a particular part of selected elements

 - :: after
 - :: before
 etc

 ### Specificity
 - Specificity is how the brower decides which rules to apply when multiple rules could apply to the same elemts. 

 - It is a measure of how specific a given selector is. The more specific selector "wins"

