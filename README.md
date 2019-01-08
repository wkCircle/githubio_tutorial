There are three methods that you can embed pdf viewer into HTML. Overview of these three methods is given below.</br>
Method1: pdf won't appear in index.html. Instead, it shows strings with link to the target pdf file (use pdf.js to open).</br>
Method2: directly use pdf.js to view a pdf file.</br>
Method3: directly use google pdf viewer to view a pdf file.


Tutorial Step by Step

0. Open a browser and sign in your github account.
1. Create a new repository <username>.github.io and set this repo as private. (README can be initialized or not, up to you.)</br>
   Note: E.g., my github ID is "wkCircle", so I should create a repo with name: "wkCircle.github.io"</br>
   (Ofiicial Tutorial: https://help.github.com/articles/create-a-repo/)
2. Download the index.html that I've sent to you. 
   Modify the index.html by uncommenting one of the 3 methods.

3. A. If you're using Method 1 or 2: Upload your pdf file onto this repo.</br>
   (Official tutorial: https://help.github.com/articles/adding-a-file-to-a-repository/)
   
   B. If you're using Method 3: Upload your pdf file onto google drive. --> Double click that file</br>
   --> More Actions --> Open in new window --> More Actions --> Embed item</br>
   --> copy & paste the html code given into index.html file to replace codes in Method3.</br>
   
4. Upload your index.html (the file name cannot be changed.) onto the same github repo.
5. Go to Settings tab --> Find the GitHub Pages Section</br>
   --> Double check that you can see the message "Your site is published at https://\<username\>.github.io/"
6. Copy the web address and use incognito mode/window to test the availability of the web. 
7. Done!

`PS`
Before uploading index.html, you can firstly inspect its appearance on your local machine: just
double click the file and your browser will show how it looks like. Notice that your pdf file and index.html should be placed at the same dir.
`Relevant tutorial`
Ref: https://gitbook.tw/chapters/github/using-github-pages.html
