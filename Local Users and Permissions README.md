# Simulated Windows Workstation Administration & User Management
## Creating New Users
To make a new user, I go to `Settings>Accounts>Other Users` 
<img width="1080" height="910" alt="image" src="https://github.com/user-attachments/assets/2fe0a491-0416-4558-8280-167f36b631ba" />
<br>
In "Other Users" Select "Add Account" 
It will prompt you to add a Microsoft account but I am adding a local user so I will select "I don't have this person's sign-in information" 
<br>
<img width="585" height="563" alt="image" src="https://github.com/user-attachments/assets/b24f00e3-9858-41f1-bc80-a1375e2f5403" />
<br>
Then select "Add User without a Microsoft Account" 
<br>
<img width="582" height="564" alt="image" src="https://github.com/user-attachments/assets/94d12efd-5ba1-4532-80cc-972e2d414ebb" />
<br>
Which would then prompt you to make a user name and set a password and security questions. 
<br>
After the account is made I log onto it.
<img width="1089" height="492" alt="image" src="https://github.com/user-attachments/assets/b4e1fab5-d9ef-4657-b186-9e2a303a061f" />
<br>
Now to test the permissions of the new user account. 
<br>
I go to `Settings>System>Operational Features` 
<img width="948" height="729" alt="image" src="https://github.com/user-attachments/assets/488f6751-398e-49c7-b41c-d5e1cdecf277" />
<br>
Which confirms that this account does not have admin permissions. 
<br>
Back on the admin account, I go to explorer and create a new folder named `Windows Admin Lab`
<img width="1023" height="480" alt="image" src="https://github.com/user-attachments/assets/de146c82-8c41-4bb1-b597-500d78a70fc8" />
<br>
Inside the folder I make a .txt file to where I can add and restrict permissions to the new user. 
<img width="1278" height="574" alt="image" src="https://github.com/user-attachments/assets/39e52197-ecdb-4802-945d-662be817b959" />
<br>
Now I select the folder and will set permissions for it. 
<br>
I open `Properties>Security` then select `edit` to add "User 1". 
<img width="688" height="485" alt="image" src="https://github.com/user-attachments/assets/213d1113-d1e6-4545-a6bd-c295e1f08030" />
<br>
After selecting "edit", there is a box of groups and user names, below that there is a button "add" select that.
<img width="546" height="328" alt="image" src="https://github.com/user-attachments/assets/85ecc748-a0e4-4e8f-99c7-079af9e3fafb" />
<br>
After that I see another page where I can select users to add or remove access. 
<br>
On the right select "Find Now", which shows a list of the available users and groups. Where I can find User 1
<img width="621" height="607" alt="image" src="https://github.com/user-attachments/assets/b0dab742-0be9-41cc-94fa-2a7a0e7dbc76" />
<br>
For now, I give User 1 basic permissions. `Read and Execute, List Folder Contents, Read`
<br>
Select "Apply" and "OK" and the "OK" again to close the window. 
<br> 
I switch to User 1 and open the file.
<br>
As User 1, I open the .txt file and I find that I am still able to edit and save. Which is supposed to be restricted. 
<img width="1429" height="744" alt="image" src="https://github.com/user-attachments/assets/ae54e7c5-89b0-409b-b826-7dbd931e09b2" />
I right click `Windows Admin Lab` folder and go to `Properties>Security>Advanced`
<br>
In `Advanced` go into the "Effective Access" tab, then select "Select a user"
<img width="915" height="606" alt="image" src="https://github.com/user-attachments/assets/cea03a9e-912b-4494-8066-833266b43c07" />
<br>
<br>
Select "Advanced"
<br>
<img width="543" height="293" alt="image" src="https://github.com/user-attachments/assets/46b13679-94e0-44c9-900c-1f462a5bb540" />
<br>
In "Advanced" select "Find Now"
<br>
<img width="612" height="691" alt="image" src="https://github.com/user-attachments/assets/911e4db2-8f82-498c-9f59-44f2902afa0a" />
<br>
Select "OK" to close the window and then I'm back on the "Effective Access" Tab
