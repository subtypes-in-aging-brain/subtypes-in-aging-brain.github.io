# Web application for identifying the subtypes in aging brain

This repo intends to host the webapplication, hosted at subtypes-in-aging-brain.github.io.

Note for administrators :
### Build the website once you have added the notebooks

To check you materials and how they integrate within the website, run :  
```
jupyter-book build ./
```
You can they see the results by opening the `_build/html/index.html` file in your browser.
You should be able to navigate and see the website with your modifications.

### Add to the website online

Once you are satisfied with your changes, you can open a merge request so that administrators review your code and add it to the website


Github tracks the `_build` folder of the `gh-pages` branch. To push the static files to this branch, we use the `ghp-import` package.
To use it, you just have to run the following code :
```
ghp-import -n -p -f _build/html
```
