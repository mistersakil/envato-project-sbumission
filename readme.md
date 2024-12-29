## How to Deploy a Laravel project on the *'Envato Marketplace'*

> First of all read envato 'Code Item Preparation & Technical Requirements' guideline below
>
>> [Read the doc](https://help.author.envato.com/hc/en-us/articles/360000471583-Code-Item-Preparation-Technical-Requirements)

##### <ins>Summary for organizing files & documentation</ins>

>To ensure your project is well-structured, easily editable, and adheres to industry best practices, follow these guidelines:

1. File Organization:

    *   Group related elements into clearly labeled folders (e.g., scripts, images, styles, docs).
    *   Avoid placing all files at the root of your directory.

2.  Code Style:

    *  Validate all code to ensure it is error-free.
    *   Use modern coding practices to maintain compatibility and functionality.

3.  Documentation:

    *   Provide clear and detailed documentation to guide buyers on how to edit and use the files.
    *   Include step-by-step instructions where necessary.

4.  Editability:

    *   Write clean and modular code to make customization straightforward.
    *   Use comments and meaningful names for variables, functions, and files to enhance clarity.

>   By maintaining a clear and user-focused structure, your file becomes more *valuable* and *attractive* to **buyers**.


##### <ins>The reviewer highlighted the following issues that need to be fixed</ins>
**1.  Use "strict mode":** Ensure your code starts with "use strict" on **Javascript** for better syntax compliance. Example:
    
><code>(function ($) {
        "use strict";
})(jQuery);</code>

Or top (first line) of the js file 
><code>"use strict";</code>

**2.  Proper Event Binding:** Use javascript `.on()` instead of outdated methods like `.click()`, `.bind()`, `.hover()`, `.load()`, or `.ready()`. Example:

><code>$('#exampleId').on("click", function(event) {
    // Your code here
});</code>

**3.  Unminified Files:** Provide unminified versions of your code for easier editing.

**4.    Data Validation:** Always validate data before outputting, echoing, or rendering it.

Make these updates to meet the standards and ensure approval.