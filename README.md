// Installation

-   Node install
-   Create 2 folders :
    dist: for final output / production , src: for the code files
-   Create index.html inside the 'dist' folder
-   Create input.css file inside the 'src' folder
-   run command - 'npx tailwindcss init' : node package executor to initialize tailwindcss utility
-   Add content location inside tailwind.config file for watch .html, .js etc
-   Run tailwind build process for input and output file. (ref: tailwind docs)
    npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch
-   Link the css file into HTML
