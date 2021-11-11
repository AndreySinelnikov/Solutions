### CONTEXT: 

Documentation made with Slate contains bold+italic text nested within italic text: `*(requires proper Allure settings in ***pom.xml***)*`. 
IDEA preview displays it without any problems, but actual site with documentation fails to handle it properly.

### SOLUTION: 

Use HTML for outer tags: `<i>(requires proper Allure settings in ***pom.xml***)</i>` works.
