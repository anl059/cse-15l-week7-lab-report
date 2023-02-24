**1) Delete any existing forks of the repository you have on your account**
* go to your lab7 repository on github and click on settings
<img width="698" alt="image" src="https://user-images.githubusercontent.com/122491210/221077726-e120fb68-08a4-4118-a993-257d01e0b08b.png">

* scroll to the bottom to where you should see:
<img width="605" alt="image" src="https://user-images.githubusercontent.com/122491210/221076749-fb8a430b-6800-4cd6-b055-0d2fe3ecb84c.png">

* click on delete repository and type what is required:
<img width="342" alt="image" src="https://user-images.githubusercontent.com/122491210/221077124-62e0cdf2-5320-43b9-b7ec-5a912e00a831.png">

**2) Fork the repository**
* go to the lab7 repository on github through this link: [lab7](https://github.com/ucsd-cse15l-w23/lab7)
* click the fork button which looks like this:
<img width="336" alt="image" src="https://user-images.githubusercontent.com/122491210/221077562-e9e90e12-9448-481b-82a5-dd3a212ae991.png">

* create a new fork of the lab7 repository
<img width="600" alt="image" src="https://user-images.githubusercontent.com/122491210/221077642-6bfa1dff-9501-469c-b32b-6921a3c4b33a.png">

**3) Start the timer!**
* start a timer on your phone so you can easily check your time once you are done with all the tasks

**4) Log into ieng6**
* open the terminal through VS Code with ```<ctrl><shift><`>``` and type `ssh cs15lwi23aby@ieng6.ucsd.edu`
<img width="405" alt="image" src="https://user-images.githubusercontent.com/122491210/221079403-ff359530-b5ed-4e64-9af4-e72ce2d881a5.png">

* no password is required due to ssh keys set up during lab

**5) Clone your fork of the repository from your Github account**
* go to your lab7 repository on github and click on code
<img width="343" alt="image" src="https://user-images.githubusercontent.com/122491210/221079098-48f6c8c5-319b-4cb2-8197-13cc3cba8b81.png">

* make sure to copy the link from the ssh tab with `<ctrl><c>`
* in the terminal type `git clone` and then paste the github link by right clicking
<img width="421" alt="image" src="https://user-images.githubusercontent.com/122491210/221079668-901ea69a-b73d-451d-b5f5-2522f5a9ac39.png">

**6) Run the tests, demonstrating that they fail**
* make sure you are in lab7 by typing `cd lab7`
<img width="237" alt="image" src="https://user-images.githubusercontent.com/122491210/221080380-0fa697be-f727-4b93-bd6b-d77aad792d51.png">

* compile the test files by typing `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`
<img width="572" alt="image" src="https://user-images.githubusercontent.com/122491210/221080736-b97ba26d-a7e0-4316-a109-348acbb5c507.png">

* run the test files by typing `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`
<img width="762" alt="image" src="https://user-images.githubusercontent.com/122491210/221080642-2684a122-36cc-4531-93f7-a0dec8d9ddac.png">

**7) Edit the code file to fix the failing test**
* enter the ListExamples file by typing `nano ListExamples.java` to use the nano editor
<img width="828" alt="image" src="https://user-images.githubusercontent.com/122491210/221080965-3b59e96a-5c46-44c9-9923-05076d2c842b.png">

* use `<ctrl><w>` to use the find function and then type `0,` and then press `<enter>`
* press the right arrow twice `<right><right>` then press the delete arrow twice `<delete><delete>`
<img width="147" alt="image" src="https://user-images.githubusercontent.com/122491210/221081521-726b204c-d3ce-4c9e-a008-1f979600677c.png">


* hold the down arrow until you reach the bottom of the file `<down>` and then press the up arrow 7 times `<up><up><up><up><up><up><up>`
* then press the left arrow 6 times `<left><left><left><left><left><left>` and then press `<delete>`then press `<2>`
<img width="189" alt="image" src="https://user-images.githubusercontent.com/122491210/221082690-a30f9022-5532-4d2f-a11c-666acc445e35.png">

* after that, press <ctrl><o> then <enter> then <ctrl><x> to save and exit the nano editor

**8) Run the tests, demonstrating that they now succeed**
* recompile the file by typing `javac ListExamples.java`
<img width="328" alt="image" src="https://user-images.githubusercontent.com/122491210/221083109-0bb65ec6-b679-48ff-972b-11b66253a216.png">

* press the up key 3 times to go back to the command used to run the test files `<up><up><up>`
<img width="766" alt="image" src="https://user-images.githubusercontent.com/122491210/221083341-a57a3d23-0ff4-4dc4-8467-b6cd94d3bca7.png">

**9) Commit and push the resulting change to your Github account**
* type `git add ListExamples.java` then `git commit -m "debugged"` then `git push origin main` to update your lab7 repository
<img width="587" alt="image" src="https://user-images.githubusercontent.com/122491210/221083638-582e1eeb-adf7-4d9d-acbc-6f5fb58e8d3a.png">


