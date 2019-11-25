# Finance-Expense-Tracking-App
This application helps with tracking for personal or business expenses on an individual basis. It could be used to track travel or business expenses and deliver information in an easy to read format. Users can track enter charges and expenditures daily and create a pool of data for them to have a holistic understanding of the expenditures the user has.
## Testing this application
1.	Download and unzip the code files required for the application
2.	Make sure Visual Studio Code is installed your machine (if you have not already done so)
3.	Go to https://nodejs.org/en/ and download Node.js (if you have not already done so)
4.	Go to https://git-scm.com/downloads and download Git (if you have not already done so)
    - Open Powershell and create a new alias (if you have not already done so)
        - New-Alias -Name git -Value "$Env:ProgramFiles\Git\bin\git.exe"
5.	In Visual Studio Code, open the unzipped folder containing the application and Install all the required packages:
    - npm install
6.	In Visual Studio Code with the test app open and in the terminal and run ng serve
    - ng serve
7.	Next add a new terminal with ng serve still running in the other terminal and run nodemon ./webserver.js
    - nodemon ./webserver.js
8.	Open a web browser and navigate to the localhost URL to view the app.
    - http://localhost:4200/

