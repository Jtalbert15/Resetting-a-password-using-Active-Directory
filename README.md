# Resetting-a-password-using-Active-Directory

<h1>Summary</h1>

In this lab we will reset a password with Active Directory. We will also go over a way to seach for a user if our domain contains many users.

<h1>Step 1) Finding a User and Resetting their Password</h1>
To begin this lab we need to start up our Windows 2019 server and log in.

<img width="635" alt="Screenshot 2024-05-21 at 6 22 42 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/1fb1dbbe-7e1e-4917-8e4f-8624e231b679">

Now that we're in we are going to navigate to the top right of the screen and click on Tools

<img width="633" alt="Screenshot 2024-05-21 at 6 23 45 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/23452fc9-a567-46d2-8cb5-0a97236ca7d6">

From there we are going to click on the domain we have created for ourselves

<img width="635" alt="Screenshot 2024-05-21 at 6 24 30 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/6ab320ec-86e3-485c-b7be-23257381ddc0">

We want to change the password for our users so we are going to double click on Users

<img width="636" alt="Screenshot 2024-05-21 at 6 25 50 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/018da60e-e9b3-4bfe-8444-02bdaf134a1a">

Now we need to find the account we created in the last lab. For me its my name but for you it is whatever name you gave the user 

<img width="634" alt="Screenshot 2024-05-21 at 6 30 12 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/c023caaa-0252-4f65-bd54-0a4b308b77e6">

 Left click on the user and then right click on the user
 <img width="636" alt="Screenshot 2024-05-21 at 6 31 52 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/2c4c26a7-1733-4d01-92c1-da7857f93ba3">

 From here we are going to click Reset Password...
 
<img width="629" alt="Screenshot 2024-05-21 at 6 34 44 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/1d8a6fba-107c-4c85-a38d-f03b417859a7">

And there we have it we can now reset a users password. Since we have only one person in our domain our user was easy to find. What if you had hundreds or thousands of users? Well luckily there is an easier way to find a user so let's give that a try.

<h1>Step 2) Searching for a User and Resetting their Password</h1>
<img width="635" alt="Screenshot 2024-05-21 at 6 37 59 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/820b3f89-a198-403a-bdef-23d2ef416602">

All we have to do is right click on our domain. In my case that is ITLab.org

<img width="633" alt="Screenshot 2024-05-21 at 6 42 52 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/8c96e2d5-c5fe-48c7-ad4a-1e3f2ed2b5de">

Click on Find...

<img width="637" alt="Screenshot 2024-05-21 at 6 43 34 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/cac315c8-b3b5-4f48-bca1-b17403508a83">

Search for the user and then click Find Now

<img width="633" alt="Screenshot 2024-05-21 at 6 47 31 PM" src="https://github.com/Jtalbert15/Resetting-a-password-using-Active-Directory/assets/66844406/6afc67f3-5e54-4656-9978-10227938748a">

And there it is. From here we can right click on the user and reset their password.


