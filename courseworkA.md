# **Software Specification Coursework Part A**
Name : Mohd Hafiz Hilmy  
Student ID : 4240176

## **Document Introduction**
The purpose of this document is to provide a detailed description of an Email Client System. It explains the features and functionality of the email system, what the system will do, the constraints of the system and how the system works in homes.

## **System Overview**
The Email System will allow users to manage and access their emails with ease while allowing users to preview, save or delete the email after viewing. The system will allow communication between different users and allow rights of an email to different users.

This system will be mostly used in homes where it will display itself on display panel monitors. A database containing data account and emails is contained in the system.


## **Functional requirements of the system**
***User	requirements***
1. **User Account Login**  
***Function*** : Allow users to login to the email client system  
***Pre-condition*** : User enters email and password correctly  
***Action*** :  User enters their email and password access their email account   
***Post-condition***: User continues and enters the email client home page    

2. **User Read Email Then Delete/Archive**    
***Function*** Allow user to read email and then either delete or archive the email
***Pre-condition***: User reads the email  
***Action*** :  1.User opens email <br/> 2. User reads the email <br/> 3. User then chooses to delete or archive email   
***Post-condition***: User deletes or archives email  

2. **User Sets Action Status To An Email**    
***Function*** User sets an action status to an email where the user will be able to mark email to the 'personal', 'immediate action', 'pending action', or 'social' status.
***Pre-condition***: User sets and marks email with an action status  
***Action*** :  1.User sets email to an action status <br/> 2. Email is marked with an action status <br/> 3. Email is sent to the specific action status mark displayed   
***Post-condition***: Email is marked with an action status and s 


***System	requirements***    
1.  **Display Manager**  
***Function*** : Finds a specific networked display monitor in the home and connect/disconnect networked display monitor to the email system
***Pre-condition***:  System locates and connects to a specific display monitor  
***Action*** :  1. System locates a display monitor <br/> 2. System connects to the display panel <br/> 3. Checks the connection status of display monitor
***Post-condition***: Display monitor is connected to email system  

2.  **Database**  
***Function*** : Store email and account data of user  
***Pre-condition***:  Email and data of user added to system  
***Action*** :  1. Data of user is added by the user <br/> 2. The system stores the data in the database  
***Post-condition***: Database receives and stores email and data of user  

3.  **Account manager**  
***Function*** : Add/delete user email accounts to the system(database) or assign email rights to a user  
***Pre-condition***:  Add/Delete email account of a new user to the system's database  
***Action*** :  1. User enters new email account <br/> 2. System adds a new user's email account to the database <br/> 3. Email account is added to database  
***Post-condition***: User email is added to database

4.  **Email Client**  
***Function*** : Retrieve email from user accounts and move and show email to display panel  
***Pre-condition***:  System locates and connects to a specific display panels  
***Action*** :  1. System locates a display panel <br/> 2. System connects to the display panel <br/> 3. Monitors the connection status of display panel until disconnected  
***Post-condition***: Display panel is connected to email system

4.  **Email Client**  
***Function*** : Retrieve email from user accounts and move and show email to display panel  
***Pre-condition***:  System locates and connects to a specific display panels  
***Action*** :  1. System locates a display panel <br/> 2. System connects to the display panel <br/> 3. Monitors the connection status of display panel until disconnected  
***Post-condition***: Display panel is connected to email system


## **Non-functional requirements of the system**
1. **Performance of the system** - System should perform at a fast response time
2. **Memory Capacity of the system** - Memory capacity of the email system should not exceed limit
3. **Internet Connectivity** - Internet connection should be active 24 hours daily and be accessed by the system
4. **Data Integrity** - Data of the user is maintained and backed up in a cloud storage
5. **System Accessibility** - System shall be available to all users 24 hours a day
6. **Ease of use** - The system should be easily
7. **Security** - A password structure is implemented and only certain users can access the email client system

## **Formal Description Of The System Behaviour**
Sequence diagram or state machine diagram
