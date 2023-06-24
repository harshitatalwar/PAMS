# PAMS
PAMS is a Parking Management System software developed to make the billing process during parking visits efficient and less time consuming, in community spaces such as mall parking lots and corporate firms.
- PAMS is efficient as it is structured, systematic, user-friendly and secured. 
- PAMS has been developed using MySQL as backend, Python as frontend and Tkinter for the Graphic User Interface(GUI).
# Features-OSCAR 
- Organized Customer Details:  
PAMS stores customer details in an organized fashion, asking the customer to enter them and updates the table in SQL. 
- Secure Nature:  
It ensures security and privacy of each customer, such that the records for any user are not accessible without their unique password. 
- Calculates Bill:  
PAMS uses a particular bill tariff to calculate individual bills for customers. 
- Assigns Slots, Displays Vacant Ones:  
Slots are assigned to each user according the vacancy of the parking lot. 
- Robust (Status Oriented):  
PAMS is a robust software designed intricately, and updates statuses regularly
# Working 
The software asks the customer to input user details such as Name, Password and Car Number. These details are stored into the SQL table and the entry time of the customer is noted and updated. The customer is asked to enter a unique password for security purposes. Slot assignment is done according to the first slot that is vacant at the time of the customer’s visit; an available slot is assigned to them. The code then reverts back to giving a choice to the customer, either to enter the parking lot or to exit it. In case there aren’t any vacant slots available, a message is displayed that lets the customer know that the parking is full. 

At the time of exit, the software asks the user to input the password they previously entered, and their car details. This is to check for which customer is exiting the parking lot from the given record table in SQL. The current time (exit time) is once again recorded. The software then generates a Customer Bill according to a given bill tariff which calculates the bill according to the time spent by the customer. The full Customer Bill including all details given by the user is then displayed on the screen. In the event of a customer exceeding the limit for parking which is 24 hours, the user is notified about a tow truck being called.
# Future Scope 
- All the Slots status (vacant or full) to be projected/shown to the user. Thus, giving them a choice to book the slot. 
- Slots kept fixed for staffs. 
- Maps & direction signs can be shown for parking space detection. 
- In the future it can be extended which is not only specific to mall but also to companies, societies and public parking. 
- Pre-booking of the slots can be done online, making it time efficient 

<img width="374" alt="image" src="https://github.com/harshitatalwar/PAMS/assets/134962753/329f6a4f-a2f5-46ed-9753-1d020bc1df02">

<img width="374" alt="image" src="https://github.com/harshitatalwar/PAMS/assets/134962753/134b99da-5306-4a25-816d-5288fdbd0448">

<img width="374" alt="image" src="https://github.com/harshitatalwar/PAMS/assets/134962753/a16aabe6-5f9b-44ba-b92d-dfe060f47a55">

<img width="374" alt="image" src="https://github.com/harshitatalwar/PAMS/assets/134962753/2cd3b669-51f2-4b31-9c38-852e13c4750c">

<img width="374" alt="image" src="https://github.com/harshitatalwar/PAMS/assets/134962753/b62f6342-8a50-469c-915e-b8a5ed4a98a2">

<img width="374" alt="image" src="https://github.com/harshitatalwar/PAMS/assets/134962753/58ab4bfd-277c-40f7-8d7b-d2595f700806">
