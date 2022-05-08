# Code Refactor Starter Code
URL: 
Github Repo: https://github.com/Hephaestus01/cbc-m1_challenge

The source code files have been refactored to provide better accessibility. This was accomplished in the following ways:
- Additional clarity to the HTML structure by changing div elements to more specific tags, including nav, section, and article
- Providing image alt tags. Because these images do not provide additional information beyond the text provided in the corresponding element's section, the alt tags were left as blank, so that screen readers do not call out URL tags, etc.

Additional code optimizations:
- index.html
    - Added comments to notate different content sections of the page
    - Checked and corrected any broken links

- style.css
    - Added comments to notate different content sections of the page
    - Consolidated styles in:
        - Content section images
        - Content section h2 headers
        - Class elements that were previously pointing to a single element
            - Updated to call out the parent class with element type