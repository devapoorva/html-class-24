# html-class-24

# DOM (Document Object Model)
    The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree. With them, you can change the document's structure, style, or content.

## Nodes
    Every element, attribute or piece of text within the document is a node in the DOM tree.

    1. Element Nodes: HTML tags 
        <div> , <p>, <section> etc.
    
    2. Text Nodes: Represent the actual content inside elements (the text between opening and closing tag <p> </p> tags)

    3. Attribute Nodes: Represent HTML attributes 
        class, id etc.

## Hirerachy: 
    DOM's structure is hirerachial
    1. Parent Node: An element that contain other elements 
        body tag
    2. Child Node: An element that is contained within another element
        p tag, h tag
    3. Sibling Nodes: Elements that share the same parent
        div tag


##### Dom Dynamic Nature
    Dom is not static. Javascript can interact with it to add, remove or modify elements, contents and attributes on the fly. This enables the creation of dynamic, interaction web pages.