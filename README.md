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
## 7. Edit the content of the file new.xml - write information about yourself (full name, age, number of pets, future desired salary). Write everything in XML format
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`nano new.xml`   
```
<?xml version="1.0" encoding="UTF-8"?>   
<VSenakosau>   
  <fullName>Vadzim Senakosau</fullName>   
  <age>36</age>   
  <numberOfPets>1</numberOfPets>   
  <desiredSalary>4900</desiredSalary>   
</VSenakosau>   
```
## 8. Send the changes to a remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`git add new.xml`
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`git commit -m "add information about myself in new.xml"`   
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`git push`   
## 9. Create a preferences.xml file
vvsen@Vadim MINGW64 /c/vadim/qa/github/XML (main)   
`touch preferences.xml`
## 10. In the preferences.xml file, add information about your preferences (favorite movie, favorite series, favorite food, favorite season, country you would like to visit) in XML format
vvsen@Vadim MINGW64 /c/vadim/qa/github/xml (main)   
`nano preferences.xml` 
```
<?xml version="1.0" encoding="UTF-8"?>   
<VSenakosau>   
  <favorite_movie>1+1</favorite_movie>   
  <favorite_tv_series>Breaking Bad</favorite_tv_series>   
  <favorite_food>Shaverma</favorite_food>   
  <favorite_time_of_year>Summer</favorite_time_of_year>   
  <party_i_would_like_to_visit>Party in bali</party_i_would_like_to_visit>   
</VSenakosau>   
```
## 11. Create a skills.xml file, add information about skills that are going to be learned at the course in XML format.
vvsen@Vadim MINGW64 /c/vadim/qa/github/xml (main)      
`touch skills.xml`   
vvsen@Vadim MINGW64 /c/vadim/qa/github/xml (main)      
`nano skills.xml`   
```
<?xml version="1.0" encoding="UTF-8"?>
<Skills>
  <skill1>Basic theory</skill1>
  <skill2>Client-server architecture</skill2>
  <skill3>HTTP methods</skill3>
  <skill4>JSON, XML</skill4>
  <skill5>API testing via Postman</skill5>
  <skill6>Charles and Fiddler</skill6>
  <skill7>Dev Tools</skill7>
  <skill8>VPN</skill8>
  <skill19>Mobile testing</skill9>
  <skill110>Feature of iOS, Android</skill10>
  <skill8>Build iOS apps on XCode</skill8>
  <skill19>Android Studio</skill9>
  <skill110>ADB</skill10>
  </Skills>
```
## 12. Send two files at once to the remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/xml (main)      
`git add . && git commit -m "add preferences.xml and skills.xml" && git push`   
[main aaebda4] add preferences.xml and skills.xml   
 2 files changed, 24 insertions(+)   
 create mode 100644 preferences.xml   
 create mode 100644 skills.xml   
Enumerating objects: 5, done.   
Counting objects: 100% (5/5), done.   
Delta compression using up to 12 threads   
Compressing objects: 100% (4/4), done.   
Writing objects: 100% (4/4), 819 bytes | 819.00 KiB/s, done.   
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0   
To https://github.com/VSenakosau/XML.git   
   8af1063..aaebda4  main -> main   
## 13. Create bug_report.xml file in the web interface 
`Click "Add file", select "Create new file" -> Enter bug_report.xml`
## 14. Save the changes at the web interface
Click the "Commit changes" button ->     
if necessary, enter the data in the Commit message and Extended description fields description ->   
Click the "Commit changes" button   
# 15. At the web interface, modify the bug_report.xml file and add the bug report in XML format
Click on the file name ->   
Click on the "Edit this file" icon ->   
Enter data   
```
<?xml version="1.0" encoding="UTF-8"?>
<bugReport_xml>
  <id>128</id>
  <severity>trivial</severity>
  <priority>low</priority>
  <title>The message in the tooltip begins with a lowercase letter when hovering over the image of the link [Argentine peso forecast: ARS seeking new bottom amid longstanding and persistent economic woes on the https://capital.com/argentine-peso-forecast-ars] page</title>
  <environment>Windows 11 Pro, Chrome 112</environment>
  <stepsToReproduce>
    <step1>1. Navigate to capita.com</step1>
    <step2>2. Scroll down to the [Financial News] block</step2>
    <step3>3. Click tab [Forex]</step3>
    <step4>4. Select section [USD latest: GBP/USD, EUR/USD, USD/JPY trading setups]</step4>
    <step5>5. Hover the cursor over the image of the links in the [USD latest: GBP/USD, EUR/USD, USD/JPY trading setups] section</step5>
  <expectedResult>The text of the tooltips on each image starts with a capital letter</expectedResult>
  <actualResult>The text of the tooltips for the link image [Argentine peso forecast: ARS seeking new bottom amid longstanding and persistent economic woes] begins with a lowercase letter</actualResult>
  <attachment>URL to the video</attachment>
  <License>All</License>
  <author>SVadim</author>
</bugReport_xml>
```
# 16. Save the changes at the web interface
Click the "Commit changes" button ->        
if necessary, enter the data in the Commit message and Extended description fields description ->      
Click the "Commit changes" button   
# 17. Synchronize remote and local XML repository   
vvsen@Vadim MINGW64 /c/vadim/qa/github/xml (main)   
We use the `git pull` command in the terminal    
`git pull origin main`   
```
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.82 KiB | 93.00 KiB/s, done.
From https://github.com/VSenakosau/XML
 * branch            main       -> FETCH_HEAD
   aaebda4..e48cf78  main       -> origin/main
Updating aaebda4..e48cf78
Fast-forward
 bug_report.xml | 19 +++++++++++++++++++
 1 file changed, 19 insertions(+)
 create mode 100644 bug_report.xml
``` 



