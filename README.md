# linux-AdministrationHomework3
![image](https://github.com/user-attachments/assets/fd8816f9-f80b-4039-b5d0-e700131174d3)

•	Go to your home directory and then go to superman directory

•	Create a new file called "first4movies" using vi command

•	Write anything you know about all first 4 movies of superman.  If you never watched superman then you can enter at least 20 names of your family members.  This file should have 20 lines and each line should have 5-6 words

Solutions : To move to the directory of superman should be done with the use of cd command ie cd superman and creating a new fill will be done with the use of vi editor command ie vi first4movies and to input the info about the movie with the use of insert (i) to insert them and when done escape with the esc key and :wq to save the file 

![image](https://github.com/user-attachments/assets/971604bb-5462-42f2-91cb-3cda474ab7e9)

![image](https://github.com/user-attachments/assets/8896f95c-0c96-42b6-b51c-53c5dac07bee)

•	Practice vi command by navigating the file content and remove some lines, edit or undo
this can be done with use of insert and escape command together the wq to overwrite a line , q1  not to save a recent updated line etc

![image](https://github.com/user-attachments/assets/6f565cb3-0d6f-43d2-95bd-2dfe04632d41)
![image](https://github.com/user-attachments/assets/7b768eb6-08c9-4ea6-bc68-f72eeac53c04)
![image](https://github.com/user-attachments/assets/176f15a2-bd9c-42c5-b7af-e9cd9ab1028d)
![image](https://github.com/user-attachments/assets/696b1040-236d-4aa7-bed5-d968d1a0a517)

•	Create a new group superheros (if you don't already have one)
Creating group without having the right permission wont be possible especially if not on the sudoer file example is a screenshot of creating a group with the right permission 

![image](https://github.com/user-attachments/assets/c8ef42d3-e47e-4bca-bdcb-f89c1a2a11c9)

To create or add a group successfuly on linux can be done by adding the group creator to the sudoer file or member or wrap file or better create the group at the root level, in this homework , i logged in as aroot user using the command su and creating the group succesfully

![image](https://github.com/user-attachments/assets/eba4f57e-6e5d-44eb-b99b-b8b06e43ceb0)


•	Create a new user hulk and make sure its group should be superheros and its userid should be 2000
To create a new user , the permission must have been met Ie a root or sudoer and the command to solve the task is 
````useradd -u 2000 -m -G superheros hulk```` the command -u 2000 is setting the user to id=2000 and the -m is creating the home directory and the command -G is adding the user to group=superheros and the name of the user specifiied or to be created is = hulk

![image](https://github.com/user-attachments/assets/7b9ca798-5a3c-40fa-9ff4-8a555b133b90)


•	Once the user hulk is create then change the password for hulk and then login as hulk
![image](https://github.com/user-attachments/assets/7907cb31-c9d8-4ab6-92d8-e27b7d395abe)

![image](https://github.com/user-attachments/assets/5fb33ddb-fdca-4f8c-8691-5e649d0e6ade)

•	Under hulk home directory create a file Skaar

![image](https://github.com/user-attachments/assets/dcb0a4a7-c82f-4fc6-ae72-cef0a3cb8260)

•	Change group ownership of Skaar from superheros to root

![image](https://github.com/user-attachments/assets/32ef2d03-1025-4b0f-952c-2b6f33754991)

•	Then create a new group continents

![image](https://github.com/user-attachments/assets/787d11ec-4e45-4c11-beb9-6ff7dd7e6069)

•	Create a new users namerica, samerica, asia, europe, australia, africa and antartica
![image](https://github.com/user-attachments/assets/23aef430-1742-458a-9760-7add05aef61a)


•	Make sure all these users groups is continents
•	Change password for every user, then switch into each user one by one using su - username command and create one file in each user account (e.g. england file in europe, usa in namerica, japan in asia and so on)
•	Also add user namerica to wheel group to allow it to run root commands as root and then test it
•	Run last command and find out the number of users logged in.  (Do not count duplicate users)
•	Run id command on africa and australia users to verify their user id

