# Steps to use the file:
1. Download the repository
2. Set up the project with npm and install the required dependencies.
  - Change your project directory:
    cd /d "e:\Projects\vGHC-Slot-Checker-main\vGHC-Slot-Checker-main"
  - Initialize the project with npm:
    npm init -y
  - Install the required dependency:
    npm install puppeteer
  - Then you can run your script:
    node checkRequestMeeting.js
2. run node checkRequestMeeting.js
  - Open your terminal/command prompt
  - Change your project directory:
    cd /d "e:\Projects\vGHC-Slot-Checker-main\vGHC-Slot-Checker-main"
  - Run your script:
    node checkRequestMeeting.js
3. It will open the browser and navigate to the Grace Hopper Celebration exhibitor catalog. In the browser window that opened, you need to log in to your Grace Hopper Celebration account. Then go back to your command prompt/terminal. Press the Enter key to continue the script. 
4. The script runs continuously until you stop it with Ctrl+C. It checks every 5 minutes (you can change checkInterval). It alerts you immediately when spots are found. 

<img width="1152" height="2048" alt="image" src="https://github.com/user-attachments/assets/300f94a4-7ebf-4808-9a1b-8ae6f46904b1" />

The enabled word shows if the request meeting button for that company is open for booking or not.

-> Open: true

-> Closed: false

#Note: 
Enable cookies so you do not need to repeatedly log in :)

## All the best!
