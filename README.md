
# 👋 Introduction to Thuan's App 👋
This application was created for the purpose of practicing my programming skills using C/C++ language combined with Qt framework and some other applications. Based on my programming skills using the above resources, I created my own application for my personal purpose.  
This application has some features like below:
#### Layout:
 - This app has 2 layouts: vertical and horizontal

| Vertical layout | Horizontal layout |
| :--------: | :-------: |
| ![image](https://github.com/user-attachments/assets/1582309d-0126-4da2-be3e-b832c28a77dd) |![image](https://github.com/user-attachments/assets/40f07fff-b453-4efe-9692-09c2b47b8aa9)|
|Mothod|Set each group as a block, set new position for each block when click to Change Layout button.|
|Button Change Layout|![image](https://github.com/user-attachments/assets/e85f882d-23d4-431c-9adb-1cb8deb71cd2) and ![image](https://github.com/user-attachments/assets/f3593d37-4416-47bf-8772-97e00d989374) |

** Video result:

https://github.com/user-attachments/assets/e7a1bc68-1b5b-419d-a849-b7b77b389e97

#### ✨ Clock:
 - It displays current time such as day, month, hour with background that can change according to the time of day (morning,night)
   
| Morning version | Night version |
| :--------: | :-------: |
|![image](https://github.com/user-attachments/assets/be8feff5-a390-49a5-8d36-979d4a599f5b)|![image](https://github.com/user-attachments/assets/ee1e214d-e0d8-49cf-ac33-766265b11f6a)|
|Format|Day, Date, Time: Minutes|
|Class using| QTime, QDate|

#### ✨ Picture showing:
 - It shows my pictures follow scroll method.
   
| Showing picture UI | ![image](https://github.com/user-attachments/assets/57167f71-fb22-436d-8656-850100d1997f) |
| :--------: | :-------: |
|Method|Modify name of picture follow form "number".png and using setStyleSheet to show the picture base on name of picture. When scrolling, number will be increased or descreased to show corresponding picture with name of it. It can be scrolled automatically or using button. |
|Class/Method|setStyleSheet, QPropertyAnimation, setDuration|
|Button Next/Back Image|![image](https://github.com/user-attachments/assets/902483d2-3400-4add-9ba8-f10fdc919d18) and ![image](https://github.com/user-attachments/assets/80b0baf8-da34-4371-82e0-3c22650551dc)|

** Video result:

https://github.com/user-attachments/assets/4985c7aa-f9ff-42ec-86e5-666398cf5aca

#### ✨ Taskbar: 
 - I can access to some websites (Google Search, Facebook, Youtube, Github) and applications (Zalo, Visual Studio Code) in my computer through this application.
   
| Usage App/Website | Coding App/Website |
| :--------: | :-------: |
|![image](https://github.com/user-attachments/assets/979a285d-08f8-45d6-8481-5e7c209aee94)| ![image](https://github.com/user-attachments/assets/3d9cb242-3d77-4c62-bf6c-c7952f0bf7b7)|
|Method|Create each App/website is each button, when click these buttons, It will open a url or a .exe file|
|Class/Method|QDesktopServices::openUrl() for website, QProcess::startDetached() for app|

** Video result:

https://github.com/user-attachments/assets/5cf8d9b1-5ca7-4cc2-b47d-e5d1276f1233


#### ✨ Manage some personal activities are: 
  -⚡Earning/Spending management.

|  | Description |
| :--------: | :-------: |
|Earning Informations| Date earning, earning type, amount earning, descriptions|
|Spending informations| Data spending, spending type, amount spending, desciptions|
|Method|Creat a Dialog to get Earning/Spending informations from User, save these informations to a small database (using excel file) and show these informations to a tag in main Window|
|Library/Class/Method|QXlsx, QDialog,... |
|Note|With vertical layout: only show date and amount, horizontal layout: show date, amount, desciptions|
||User can hide/unhide the Earning/Spending amount or accumulated amount by hide/unhide button|
*** Video result Earning:

https://github.com/user-attachments/assets/ccf9f869-f0af-4ad3-a66d-a374fee7eb5c

*** Video result Spending:

https://github.com/user-attachments/assets/4086acf0-8470-4933-b9cc-509f469bea7e

  - ⚡Planning management.

|  | Description |
| :--------: | :-------: |
|Planning Informations| Time planning, Date planning, descriptions of planning|
|Method|Creat a Dialog to get Planning informations from User, save these informations to a small database (using excel file) and show these informations to a tag in main Window|
|Library/Class/Method|QXlsx, QDialog,... |
|Note|User can check to the status box to mark it as completed or not. If it is completed, It will be disappeared|

*** Video result Planning:

https://github.com/user-attachments/assets/586e7bdf-0e40-4158-851b-1ad903bfdac9

  - ⚡Passwords management.

|  | Description |
| :--------: | :-------: |
|Password Features| Password management, Add new password, Modify excisting password|
|Add new password informations| name of password, ID of password, Password|
|Method|Creat a Dialog to get password informations from User, save these informations to a small database (using excel file) and show these informations to main Window by some nescessary informations|
|Library/Class/Method|QXlsx, QDialog,... |

*** Video result Password management:

https://github.com/user-attachments/assets/c0881c09-55da-4440-a2fd-c2df79a2c854


#### ✨ Device control:
  - I can control (Turn On/Off) devices (Fan, Light) in my room.

|  | Description |
| :--------: | :-------: |
|Features| Control Fan and Light (simulate in Proteus) via this app by button, update status of of Fan and Light to this app to monitor|
|Application/IDE/Framwork using|Qt framework, Keil C, Proteus, Virtual Serial Port Driver|
|Qt|Implement code for setting Uart/ send data to control Fan/Light, Recevie data to show status of Fan/Light|
|Keil C|Implement code for module control Fan/Light by C languages using STM32F103C8|
|Proteus|Simulate Fan/Light, Uart, MCU STM32|
|Virtual Serial Port Driver| Create 2 virtual COM and pair it each other to simulate Uart communication|
|Method| Connect this app with module Fan/Light control by UART communication, send data from this app to module control to turn On/Off Fan/Light and recevied data from module control to show status of Fan/Light on this app|
|Library/Class/Method|QSerialPort,QMovie,... |

*** Video result:

https://github.com/user-attachments/assets/1b34ee86-800a-4b11-9436-68feeec88998



