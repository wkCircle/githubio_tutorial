## Basic Tutorial- Build your own website by free Github Pages
You can build your own personal website by using GitHub pages. In the following, I provide 3 methods to build your own website. One of the simplest way is to put your already-on-hand Reseme or CV here and show it to the public.</br>
This way, you don't need to learn HTML language since GitHub pages reruies `index.html` to be the home page. Our task now becomes: how to show your pdf within HTML to the public?

## Let's Begin.
To show your home page to the public, please refer to the step 2. </br>
There are three methods that you can embed pdf viewer into HTML. Overview of these three methods is given below.
- Method1: pdf won't appear in `index.html`. Instead, it shows strings with link to the target pdf file (use pdf.js to open).
- Method2: directly use pdf.js to view a pdf file.
- Method3: directly use google pdf viewer to view a pdf file.


## Tutorial Step by Step

0. Open a browser and sign in your github account.

1. **Create** a new repository `<username>.github.io` </br>
&rarr; Set this repo as **private/public** depending on whether you want to show your files in this repo to the public or not. </br>
&rarr; (**README** can be initialized or not, up to you.)</br>
E.g., my github ID is "wkCircle", so I should create a repo with name: "wkCircle.github.io"</br>
(Ofiicial Tutorial: https://help.github.com/articles/create-a-repo/)

2. Download my repo and open the file `index.html`. </br>
   Modify the `index.html` by uncommenting one of the 3 methods.

3. ..
	- If you're using Method 1 or 2: </br>
	Upload your pdf file onto your own repo, namely `<usename>.github.io` </br> 
	(Official tutorial: https://help.github.com/articles/adding-a-file-to-a-repository/) </br>
	
	- If you're using Method 3: </br>
	Upload your pdf file onto google drive. &rarr; Double click that file</br>
	&rarr; **More Actions** &rarr; Open in new window &rarr; **More Actions** &rarr; **Embed item**</br>
	&rarr; Copy & paste the given html code into `index.html` file to replace codes in Method 3.</br>
   
4. Upload your `index.html` (the file name cannot be changed.) onto your github repo.

5. Under your repository name, click **Settings** &rarr; Find the **GitHub Pages** section </br> 
&rarr; Select **master branch** in the drop-down menu under the **Source** tab &rarr; click **Save**. </br> 
Then you should see the message </br>
```diff
+ Your site is published at https://\<username\>.github.io/</font> 
```
under the same section. </br>
(Official Tutorial: https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/)

6. Copy the web address in 5. and use incognito mode/window to test the availability of the web. 

7. Done!

### Note
- Before uploading index.html, you can firstly inspect its appearance on your local machine: </br>
just double click the file and your browser will show how it looks like. </br>
- Your pdf file and index.html should be placed at the same dir.</br>

## Reference
https://gitbook.tw/chapters/github/using-github-pages.html (Chinese)
