-----What is Impact Score? 

It is a concept invented by RMDS Lab aiming to measure the real-world impact of data scientists. It is very often that people would ask how you recommend data scientists to me or how you measure the quality of them. So impact score is right to the point to answer such questions. It utilizes not only the activities you make on RMDS ecosystem platform but also the external platforms to validate and qualify your contribution or, impact in data field. The credit goes to RMDS, who operates a comprehensive ecosystem platform that captures the data science peer-review projects, tools, courses, knowledge to facilitate talent growth for data scientists like you guys.

-----What is the use case of Impact Score?

There are multiple use cases of impact score in our imagination. For example, the technical recruiters may view your impact score board to sort the candidates. As a reference for first screening. Academic institutions may also make use of the impact score to evaluate professors, instructors and spot the right person to lecture courses in relevant field. And university students of course. They may include it in resume or CV to showcase their ability or previous achievements. Surely, they are not the only cases. We are glad to see more and more users are managing their impact scores. In the future, we believe impact score would be more useful and powerful.

-----How do we measure it? 

There are five dimensions. The first three  dimensions are project based, which measures the quality, popularity, and outcome of the project you uploaded. The latter two are person based: it would take your background and the activities on platform into account, such as your education level, how popular you are in our community, how many people follow you etc.

-----How do you use the source code?

The code is written in python3, saved in .ipynb file. To open .ipynb file you need to set up Jupyter Lab environment. Here is the link to set up jupyter lab environment: https://jupyter.org/install.
Then you may check if you have all the dependencies required for running this code in the requirements.txt

The inputs for generating impact score are 11 csv files in the company_data folder, you need to put the folder and input_files.conf file in the same directory with the source code file. The input_files.conf records all the input file path to be read by read_all_inputs() function. The output will be stored in daily_user_score_report_{today}.csv in the same directory.








