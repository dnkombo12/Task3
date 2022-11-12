<img width="895" alt="taoko" src="https://user-images.githubusercontent.com/84934041/201499121-8b38f9e3-02c6-4e5b-9aa5-c6756bed789a.png">


Task Overview | Installation Instructions | Link to Module 3

Introduction
Experience Technology at JP Morgan Chase
Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.

Module 3 Task Overview
Display data visually for traders. Use Perspective to create the chart for the trader’s dashboard.
Aim: Use Perspective to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. Basically, you have to modify the existing live chart to be able to (1) track and display the ratio between the two stock prices (2) show the historical upper and lower bounds of the stocks' ratio (3) and finally, show 'alerts' whenever these bounds are crossed by the ratio.

Please clone this repository to start the task
From the existing live graph, update it to track the ratio between two stocks over time and NOT the two stocks’ top_ask_price over time.
Update the graph to also track the historical upper and lower bounds of the stocks' ratio
Trigger 'alerts' (i.e. draw red lines) on the graph whenever the bounds are crossed by the calculated ratio in a specific time period
Upload a git patch file as the submission to this task
Upload a video detailing your process and work
Setup / Installation
In order to get the server and client application code working on your machine, follow the setup here

Note:This is the version of the JPM 3 exercise that uses Python 3. The Python 2.7 version is in this other repo

How to Run
Similar to Task 2, start the data feed server by running the python server

Make sure your terminal / command line is in the repository first before doing any of this.

If you are using Windows, make sure to run your terminal/command prompt as administrator.

python datafeed/server3.py

If you encounter an issue with datautil.parser, run this command:

pip install python-dateutil
If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run npm install && npm start to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have npm (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

Known Issues
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. This is the alternative unzipped version: https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz
Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

How to fix the code to meet the objectives
To make the changes necessary to complete the objectives of this task, follow this guide.

How to submit your work
A patch file is what is required from you to submit. To create a patch file, follow this guide. Then submit the patch file in the JPM Module 3 Page.
