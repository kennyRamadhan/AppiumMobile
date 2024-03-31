A. For running this project make sure your local machine already installed :
      1. Java
      2. Eclipse for Java Developers
      3. Node JS
      4. Appium Server
      5. Android Studio (For create virtual device if you choose running using emulators) 

B. After you cloning this repo and open it with eclipse there must be an error in pom.xml (the system cannot find the path specified) its happen because different path from my local machine to yours, but you can updated the project and solved the error by doing : Right-click on the project -> Go to Maven -> Update project.

C. Change configurations settings on appiumBase.java 
      1. Line number 31 change with your local path main.js usually placed in AppData/Roaming/npm/node_modules/appium/build/lib/main.js
      2. Line number 36 change your own device name
      3. Line number 37 change to your path where you stored the apk
      
D. Before run the test make sure your mobile device already enable developers options 

D. After the errors gone you can open e2eMobile.java file and do : Right-click -> Run As -> 1. TestNG Test

E. The reports will be stored in test-output folders and you can choose index.html or emailable-report.html

F. Sometimes you might be face an errors but you can try with another mobile device 
