## How is the datat stored and structured in Docsify?
Docsify uses markdown files to process most of the coding. The way these markdown files are used is from docsify loading and parsing yourmarkdown files, andf then uses these files to display and function as a website. This is very to the point and makes the strcutre very easy to read. 

## Markdown Data in Action
One of the examples of the markdown files being used in action is by looking at the structure of the sidebar. To implement the side bar, I had to create a markdown file that told my website which markdown files correspond to which tab on the sidebar. This is an example of how markdown files are normally structured, including mine

└── docs/
    ├── _sidebar.md
    ├── index.md
    ├── getting-started.md
    └── running-services.md

This structure is easy to read and shows the order order the markdown files. 
