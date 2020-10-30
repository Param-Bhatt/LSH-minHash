# LSH-minHash
Assignment 2 done as a part for the course IS F469 Information Retrieval.


### Guidelines for using :
* <i>df</i> is a global variable which contains all the data that our model will use.<br> We have generated this from <u>human_data.txt</u> , so you can change this and run the file to generate a custom csv and update the df accordingly. <br>
* <i>query</i> is the variable that stores your query and searches for it. Please update that for every run . <br> 
<i>Note that the dataset variable should be an array of strings.</i>
* Now , to run the program , run :<br>
    * If you are on windows<br>
                ```
                python3 ir.py
                ```
    * If you are on linux <br>
                ```
                py ir.py
                ```
    * If you are using Google Colab <br> 
                ```
                Press Ctrl+F9 after uploading the IR.ipynb file along with the contents of the repository
                ```
                
                        
 ### Dependencies :
 We install these libraries each time when the program is run, and it is recommended to enable GPU on your google colab as well, to speed up the pre-processing.
 * numpy
 * pandas
 * random
 * pdoc3 ( for documentation )
  
### Contribution Guidelines:

##### Creating a PR:
* Fork the repository to your own account
* Clone the repository to your local system , make any changes you wish to
```
git clone https://github.com/<your_username>/LSH-minHash
```
* For each new feature, create a new branch of the name <i>feature_name<i>
  ```
  git checkout -b <feature_name>
  ```
* Comment the code properly with all necessary comments wherever needed
* While coding , follow the iflake coding guidelines for a cleaner and better code quality.
    * You can install iflake8 on your system as :
      ```
      pip install flake8
      ```
    * You can run it as :
      ```
      flake8 path/to/your/code
      ```
* Push the changes to your fork
* Create a pull request
* Resolve conflicts as required

##### To install dependencies
* numpy
```
pip install numpy
```
* pandas
```
pip install pandas
```
* random
```
pip install random
```
