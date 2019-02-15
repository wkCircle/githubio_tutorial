## Basic Tutorial- Build your own website by free Github Pages
You can build your own personal website by using github pages. In the following, I provide 3 methods to build your own website. One of the simplest way is to put your already-on-hand Reseme or CV here and show it to the public. This way, you don't need to learn HTML language since github pages reruies `index.html` to be the home page. Our task now becomes: how to show your pdf within HTML to the public?

## Let's Begin.
To show your home page to the public, please refer to the step 2.
There are three methods that you can embed pdf viewer into HTML. Overview of these three methods is given below.</br>
- Method1: pdf won't appear in `index.html`. Instead, it shows strings with link to the target pdf file (use pdf.js to open).</br>
- Method2: directly use pdf.js to view a pdf file.</br>
- Method3: directly use google pdf viewer to view a pdf file.


## Tutorial Step by Step

0. Open a browser and sign in your github account.

1. Create a new repository \<username\>.github.io and set this repo as private/public depbeding on whether you want to show your files in this repo to the public or not. (README can be initialized or not, up to you.)</br>
   Note: E.g., my github ID is "wkCircle", so I should create a repo with name: "wkCircle.github.io"</br>
   (Ofiicial Tutorial: https://help.github.com/articles/create-a-repo/)

2. Under your repository name, click **Settings** &rarr; Find the **GitHub Pages** &rarr; Under the Source tab, select **master branch** in the drop-down menu &rarr; click **Save**

3. Download my repo and open the file `index.html`. 
   Modify the `index.html` by uncommenting one of the 3 methods.

4. <!----!>
	1. If you're using Method 1 or 2: Upload your pdf file onto your own repo, namely `<usename>.github.io` </br> (Official tutorial: https://help.github.com/articles/adding-a-file-to-a-repository/)
	2. If you're using Method 3: 
		Upload your pdf file onto google drive. &rarr; Double click that file</br>
		&rarr; More Actions &rarr; Open in new window &rarr; More Actions &rarr; Embed item</br>
		&rarr; copy & paste the html code given into index.html file to replace codes in Method3.</br>
   
5. Upload your index.html (the file name cannot be changed.) onto the same github repo.

6. Go to Settings tab &rarr; Find the GitHub Pages Section</br>
   &rarr; Double check that you can see the message "Your site is published at https://\<username\>.github.io/"

7. Copy the web address and use incognito mode/window to test the availability of the web. 

8. Done!

PS</br>
Before uploading index.html, you can firstly inspect its appearance on your local machine: just
double click the file and your browser will show how it looks like. Notice that your pdf file and index.html should be placed at the same dir.</br>

Relevant tutorial</br>
Ref: https://gitbook.tw/chapters/github/using-github-pages.html
