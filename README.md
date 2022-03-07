# Framework
Running Framework for Testing Simple Calculator application:

Framework features:
Framework will take 1 parameter json file path, 
Json file contain test data
Framework will process the json and create feature file for bdd testing and run the feature file and store he test result in html file.


Steps:

•	Download and Extract framework.zip from https://github.com/harshanaik20/Framework

•	After downloading please update details in  /venv/pyvenv.cfg file with your machine base python. Or you can create new env and make sure that all pkg listed in reqirement.txt is installed (pip install –r requirement.txt )

•	Open command prompt in framework directory and run command and activate venv using  venv\Scripts\activate command  

•	Run command  python Framework.py test_data.json
Test_data.json  file will be the json data input for testing

•	Test report will be stored in behave-report.html
