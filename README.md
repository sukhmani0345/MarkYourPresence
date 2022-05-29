![image](https://user-images.githubusercontent.com/84336698/170666222-51473996-e7e6-4b0c-b5e3-2e907ddbd4f2.png)
![image](https://user-images.githubusercontent.com/84336698/170666159-c8babf06-dc87-4248-bc88-492017f3b2a2.png)
# MarkYourPresence By Sukhmani Kaur
This year the Microsoft Engage Mentees were given with 3 challenges to choose from and build a functional prototype under the guidance of mentors.
The 3 challenges were-
1. Face Recognition
2. Data Analysis
3. Algorithms

The challenge chosen by me is **Face Recognition**.

**Mark Your Presence** is an Automatic Attendance Marker in which you just need to register only once and then just within seconds you can get your attendance marked.<br/>
Video Demo - https://www.youtube.com/watch?v=YGwqUlyT2h4
# Mark Your Presence Features
1. Register
2. Train the model
3. Take attendance
4. Student Details

**Register**<br />
After clicking on the button Register, you will be redirected to the Registration page where you will have to enter your name and roll number and click the submit button. After submitting, the webcam will automatically capture your face and store the information into the TrainingImages folder within the Sub folder created automatically with your name and your detailed will be stored into the StudentDetails.csv.

**Train the model**<br />
Here, the images Stored will be used to train the model to check its accuracy that will be printed on the console.

**Take Attendance**<br />
After clicking on the button Take Attendance, the webcan will automatically capture your face and will show your name over the rectangle indicating that your attendance has been marked.You can check so after going into the Attendance.csv where you will find that your name roll number along with the time has been updated in the sheet.

**Student Details**<br />
Here, you can check the details of the students entered till now which will ppear in the form of a table.

# Installation Guide
To use this project, follow the following steps:-

Initialize the git on your terminal:<br />
```
git init
```
Clone this repository:<br />
```
git clone https://github.com/sukhmani0345/MarkYourPresence
```
Change the directory<br />
```
cd MarkYourPresence
```
Open your code editor( VS Code preferred) and go to its terminal and run the following command to install all required packages:<br />
```
pip install -r requirements.txt
```

# Hosting the Web App
1. In VS Code using the Code Runner Extension, run the ```app.py```
2. Now use the ```localhost``` 
3. You will find the following link in your terminal.<br />
![image](https://user-images.githubusercontent.com/84336698/170706857-f70bef66-2f11-42f6-9609-8de961c5522f.png)
4. Click on it and in chrome you will find the web app running.<br />
5. Now you can access all of its features.<br />
![image](https://user-images.githubusercontent.com/84336698/170863221-e44e81e3-eae8-464e-99f3-b670fafa66de.png)

# Development Cycle
I used Trello as my primary application for designing the board for the development process of Mark Your Presence. I divided my entire development process into 3 sprints as shown in the images below.<br />
![image](https://user-images.githubusercontent.com/84336698/170844675-68fcc7c5-3757-4834-84df-68a796c21356.png)

