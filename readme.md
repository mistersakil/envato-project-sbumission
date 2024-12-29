## How to Deploy a Laravel project on the *'Envato Marketplace'*

> First of all read envato 'Code Item Preparation & Technical Requirements' guideline below
>
>> [Read the doc](https://help.author.envato.com/hc/en-us/articles/360000471583-Code-Item-Preparation-Technical-Requirements)

### <ins>Summary for organizing files & documentation</ins>

>To ensure your project is well-structured, easily editable, and adheres to industry best practices, follow these guidelines:

1. **File Organization:**

    *   Group related elements into clearly labeled folders (e.g., scripts, images, styles, docs).
    *   Avoid placing all files at the root of your directory.

2.  **Code Style:**

    *  Validate all code to ensure it is error-free.
    *   Use modern coding practices to maintain compatibility and functionality.

3.  **Documentation:**

    *   Provide clear and detailed documentation to guide buyers on how to edit and use the files.
    *   Include step-by-step instructions where necessary.

4.  **Editability:**

    *   Write clean and modular code to make customization straightforward.
    *   Use comments and meaningful names for variables, functions, and files to enhance clarity.

>   By maintaining a clear and user-focused structure, your file becomes more *valuable* and *attractive* to **buyers**.


### <ins>The reviewer highlighted the following issues that need to be fixed</ins>
1.  **Use "strict mode":** Ensure your code starts with "use strict" on **Javascript** for better syntax compliance. Example:
    
><code>(function ($) {
        "use strict";
})(jQuery);</code>

Or top (first line) of the js file 
><code>"use strict";</code>

2.  **Proper Event Binding:** Use javascript `.on()` instead of outdated methods like `.click()`, `.bind()`, `.hover()`, `.load()`, or `.ready()`. Example:

><code>$('#exampleId').on("click", function(event) {
    // Your code here
});</code>

3.  **Unminified Files:** Provide unminified versions of your code for easier editing.

4.    **Data Validation:** Always validate data before outputting, echoing, or rendering it.

Make these updates to meet the standards and ensure approval. <a href="https://forums.envato.com/t/laravel-projects-requirements-for-approval/381284" target="_blank">See Forum Discussion</a>

### <ins>In which category a laravel template should upload?</ins>

>If you are uploading a Laravel-based website template, it should be submitted under the PHP Scripts category. However, keep these points in mind

1.  **CMS Approval Challenges:** Building a CMS with Laravel may still face rejection due to high standards for CMS items.

2.  **Category Fit:** Laravel templates/themes don’t have a specific subcategory under PHP Scripts. If your item is an add-on, tool, module, or component, it can fit within one of the subcategories.

3.  **Framework Considerations:**

    *   Laravel has stricter server requirements and may not perform well on cheap hosting without tools like opcache.
    *   Installation in subdirectories might be more complex compared to simpler frameworks.

Ensure your item aligns with the subcategory’s purpose and is optimized for flexibility and performance. <a href="https://forums.envato.com/t/uploading-a-laravel-website-template-which-category/411674/4" target="_blank">See Forum Discussion</a>






