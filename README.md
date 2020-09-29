# CodeAndData
## Crawler
### Crawler/APK
A crawler to get apk files from APK Download.
### Crawler/review
  A crawler to get reviews from google play.
<br>
## AnalyzeAPK
Analyze apk files to get mappings between features and used APIs.
    
### Usage
* The steps to use the program are as follows:<br>
    Firstly, analyze apks by using *AnalyzeApkByApktool.py*, the output is the source smali file and resource folder.<br>
    Secondly, taking the apk file and the corresponding resource folder as input of *GetMappings.py*, you can get two XLSX files: one of the files shows the features extracted from the apk, and the other file shows the APIs used by these features.<br>
  
  
## Example
Several APK files and the results gained after processing them with the code in AnalyzeAPK.
