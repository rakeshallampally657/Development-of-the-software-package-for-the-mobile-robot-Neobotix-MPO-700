# Development-of-the-software-package-for-the-mobile-robot-Neobotix-MPO-700

## Internship at Neobotix GMBH
![1563532836045](https://user-images.githubusercontent.com/79206625/125455239-8e366068-f406-41d6-a92f-fb4cbf94a1fc.jpg)


## Objectives of the Code structure:

The main objective of the structure is to make the program more efficient. All the CAN communication should be done in the separate Class, i.e. ElmoMotorCtrl Class and there should not be any CAN communication involved in any other Class and the main function as well. By this, the program will be easier to visualize and much more clear to understand.
The second objective is dealing with Error handling. In whichever function/Class error may occur, but the error should be reported in the main function.

The third objective was to use the object declaration of the Class efficiently and make the program easier to visualize and understand. 


![struct](https://user-images.githubusercontent.com/79206625/125451306-4bd4081c-1886-4f53-932d-cf742ad3742d.PNG)
