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
•	Once the user hulk is create then change the password for hulk and then login as hulk
•	Under hulk home directory create a file Skaar
•	Change group ownership of Skaar from superheros to root
