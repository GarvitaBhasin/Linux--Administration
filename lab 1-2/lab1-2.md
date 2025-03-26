🚀 LAB 1 - 2 🚀
1. Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well.

2. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.


   
Solution :

Lab 1:
 1. Open the terminal and type:

    sudo useradd operator1

    <img width="194" alt="image" src="https://github.com/user-attachments/assets/ce192391-d413-4f50-b9ba-7e0955ac67c0" />


2. To check whether or not the user is added:

   sudo cat /etc/passwd
3. To add the password:

   sudo passwd operator1

    <img width="382" alt="image" src="https://github.com/user-attachments/assets/2d2bee3b-144b-4717-8e2f-68df3fd591d5" />



4. Follow the same steps for operator2 and operator3 as well:


   <img width="382" alt="image" src="https://github.com/user-attachments/assets/fd9488dd-dd44-4f01-815b-fe18644ddc15" />


Lab 2:
1. To add comments to a particular user, type:

    sudo usermod -c "Operator1's comment" operator1

    <img width="283" alt="image" src="https://github.com/user-attachments/assets/80da2470-7c8a-478e-9a97-d1f644d1e7eb" />


2. To delete the user:

   sudo userdel -r operator
   <img width="354" alt="image" src="https://github.com/user-attachments/assets/00789a93-4ae9-4774-87ca-e9a4fb215f69" />


Creating Practice Files and Directories:
Use the touch command to create sets of empty practice files:

  touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi
  Use a single command to create all three subdirectories:

  mkdir friends family work
  <img width="365" alt="image" src="https://github.com/user-attachments/assets/67b78d67-1f86-4b04-b667-5f67e3eb7cc6" />
