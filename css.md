## What is CSS?
    CSS is a stylesheet language used to define the presentation of HTML or XML documents. It controls the layout, colors, fonts, and overall style of a page.
    Key Concepts:
    Selectors, properties, and values
    How CSS is linked to HTML (inline, internal, external styles)

## Type of CSS
    1. Inline CSS
        Inline CSS is written directly within an HTML element using the style attribute. It affects only that specific element.

        Syntax: You add CSS rules directly within the HTML tag using the style attribute.

        <p style="color: red; font-size: 16px;">This is an inline styled paragraph.</p>

    2. Internal (Embedded) CSS
        Definition: Internal CSS is written within a <style> tag in the <head> section of an 
        
        HTML document. It applies to the entire document unless otherwise specified.
        
        Syntax: You define the CSS rules inside a <style> block in the HTML document's <head>

    3. External CSS
        Definition: External CSS is written in a separate .css file and linked to an HTML document via the <link> tag. This is the most common and recommended way to apply CSS to a website.

        Syntax: The CSS file is linked to the HTML file using the <link> tag, typically within the <head> section of the HTML document.

        

## 2. CSS Selectors and Specificity
    What Are CSS Selectors?
        CSS selectors are patterns used to select and style HTML elements.
    Types of Selectors:
        Type selector (e.g., p for <p>)
        Class selector (e.g., .my-class)
        ID selector (e.g., #my-id)
        Attribute selector (e.g., [type="text"])
        Pseudo-classes (e.g., :hover, :nth-child)
        Pseudo-elements (e.g., ::before, ::after)
        Specificity in CSS
        Specificity determines which CSS rule is applied when multiple rules could affect an element.
        ID selectors have the highest specificity, followed by class selectors, and then type selectors.

