# GITHUB - homework (XML)
## 1. Create a remote repository called XML
In the header on the main page on the right, click "+" ->   
In the dropdown, select "New repository"->   
In the required "Repository name" field, enter "XML" ->   
Click the "Create repository" button at the bottom of the page   
## 2. Clone the XML repository to the local computer
vvsen@Vadim MINGW64 /c/vadim/qa/github   
`git clone https://github.com/VSenakosau/XML.git`   
Cloning into 'XML'...   
remote: Enumerating objects: 3, done.   
remote: Counting objects: 100% (3/3), done.   
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0   
Receiving objects: 100% (3/3), done.   
## 3. Create a new.xml file inside the local XML
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)
`touch new.xml`
## 4. Add the file to Git
vvsen@Vadim MINGW64 /c/Vadim/QA/github/JSON (main)   
`git add new.xml` or `git add .`
## 5. Commit the file
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`git commit -m "add new.xml"`   
[main 16155fd] add new.xml   
 1 file changed, 0 insertions(+), 0 deletions(-)   
 create mode 100644 new.xml   
 ## 6. Send the file to a remote GitHub repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`git push`
Enumerating objects: 4, done.   
Counting objects: 100% (4/4), done.   
Delta compression using up to 12 threads   
Compressing objects: 100% (2/2), done.   
Writing objects: 100% (3/3), 279 bytes | 279.00 KiB/s, done.   
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0   
To https://github.com/VSenakosau/XML.git   
   7a929a1..16155fd  main -> main
## 7. 
