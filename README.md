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

![image](https://github.com/user-attachments/assets/4fad16a4-ad87-4b6d-88b4-fb4ce2141484)

•	Change password for every user, then switch into each user one by one using su - username command and create one file in each user account (e.g. england file in europe, usa in namerica, japan in asia and so on)

 ![image](https://github.com/user-attachments/assets/3e8b0496-af89-4aab-8099-2901c81c6f17)
 
to switch into each user is done with su <username> and enter with the passwd and create the file with touch command 

![image](https://github.com/user-attachments/assets/29d31d9a-8b3a-4f2e-ad0b-646635499363)![image](https://github.com/user-attachments/assets/3ea8bbee-6212-44c3-bb30-e6eaf2716d8d)


•	Also add user namerica to wheel group to allow it to run root commands as root and then test it

![image](https://github.com/user-attachments/assets/af4e4753-3322-4f4e-9b48-4df63cd70213)

•	Run last command and find out the number of users logged in.  (Do not count duplicate users)


![image](https://github.com/user-attachments/assets/264ec626-8d06-4d4a-97f7-b9c9f5b501d6) ![image](https://github.com/user-attachments/assets/7210b144-cf00-48ec-ae98-df108f1b9704)


•	Run id command on africa and australia users to verify their user id

![image](https://github.com/user-attachments/assets/e158ef3b-3e61-4ad1-a94b-ebc750c8d3f2)
![image](https://github.com/user-attachments/assets/1281923f-4ae4-469b-a77c-672db380237a)

•	Change the date of your system to Aug 22 1998 at 1pm and verify

![image](https://github.com/user-attachments/assets/33fe364b-9f72-4f49-a232-e4196d5a8157)


•	Check system uptime

![image](https://github.com/user-attachments/assets/051e2563-029f-4345-a521-f41ab776ff38)

•	List 1999 calendar 

![image](https://github.com/user-attachments/assets/933ab557-ef27-4205-92ab-76b4fb3ec466)

•	List everything with uname command and find out where the system architecture information is located

![image](https://github.com/user-attachments/assets/429cf67d-99dd-41e7-8952-c977c0528431)

•	Become yourself "your username" and run df -h command.  Output the df -h command to another file name it systemdiskinfo

![image](https://github.com/user-attachments/assets/156f1e66-d5a0-4315-8d7f-f3d2427cea56)

•	vi systemdiskinfo file and remove the first and second line and save the file

![image](https://github.com/user-attachments/assets/63e7546b-55d4-4bab-a824-139f04711a2d)
![image](https://github.com/user-attachments/assets/d1ba6c35-e445-4748-a9f2-e7554c6c710d)
![image](https://github.com/user-attachments/assets/737fedb4-9e83-46a5-b143-950e7b952320)


•	Run dmesg command and output to dm-file 
![image](https://github.com/user-attachments/assets/454491ed-c401-44e8-be32-37eb6743589c)

•	vi dm-file and remove the last 5-7 lines
![image](https://github.com/user-attachments/assets/8a9253d2-d614-4ee2-b109-1f5b9d46cd5a)
![image](https://github.com/user-attachments/assets/0ac40b4d-d7f9-4705-92cb-1fa99b1f2495)

•	Add text in the end of file dm-file using vi.  Text = This is the end of the file.  Then save the file
![image](https://github.com/user-attachments/assets/706b8381-908f-4ea8-a741-b845c3795bf9)![image](https://github.com/user-attachments/assets/27fbb6ac-1608-4108-973b-2e3ee71bf31e)


•	Reboot the system using init command
![image](https://github.com/user-attachments/assets/62863fdc-a2a5-44c7-8abe-adefbe4bf001)
![image](https://github.com/user-attachments/assets/5b6a314c-ba1d-48d1-a049-522ae6df92e8)



