# ticket-lifecycle
<p align="center">
<img src="https://i.imgur.com/tUnlhRz.jpeg" height="80%" width="80%" alt="Setting Up in Azure"/>
 
<br />

<h1>osTicket: Ticket and lifecycling Tickets</h1>



<h2>Description</h2>
In this last section of the osTicket project, I go through the life cycle of a ticket from creation, to resolution. I make changes to the tickets when necessary like assigning the tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication. 
<br/>
<br/>

This is a continuation of the [osTicket: Post-Installation Configuration](https://github.com/AH1791/post-install-config) project.
<br />


<h2>Environments and Utilities Used</h2>

- <b>osTicket</b>

<h2>Project Walk-through:</h2>

<p align="center">
First, I will navigate to the end user site of osTicket to be able to create a new ticket: <br/>
<p align="center"> 
 
![image](https://github.com/user-attachments/assets/92eb2f18-560b-4eb3-b7f7-86679f02bca8)

<br />
<br />
<p align="center">
I will open three new tickets and fill out the users information along with the technical issues:  <br/>

![image](https://github.com/user-attachments/assets/e61fcf31-4471-463d-b620-f3ecbfec96d0)
![image](https://github.com/user-attachments/assets/edb4e581-c01f-4dc2-9614-62aa772995a1)
![image](https://github.com/user-attachments/assets/9a26d7bc-8597-48db-874b-d5e807ce906c)
 
<br />
<br />

<br />
<br />
<p align="center">
Next, I will log in as an agent (worker) we created:  <br/>

![image](https://github.com/user-attachments/assets/35e54657-78dc-4e15-aaec-18ae829e1194)

<br />
<br />
<p align="center">
I can now see all the open tickets I created in the "Tickets" tab:  <br/>

![image](https://github.com/user-attachments/assets/2c46aa4d-1db3-40e3-89cb-f2033df97bb6)

<br />
<br />
<p align="center">
When clicking on a ticket I can see all the information about the ticket like its priority, SLA, creation date, and more:  <br/>

 ![image](https://github.com/user-attachments/assets/641131a0-7f08-4c1e-8c64-719c164ec7e6)

<br />
<br />
<p align="center">
I can change the priority level on appropriate tickets by clicking the "Priority" section and can add a note for the change made:  <br/>

 ![image](https://github.com/user-attachments/assets/6ba6fec2-aa0c-46ff-9d08-be80c2c3c857)

<br />
<br />
<p align="center">
To assign a ticket, click on "Unassigned" next to the "Assigned To" section and select an agent to assign this ticket to:  <br/>

![image](https://github.com/user-attachments/assets/2a2a54fb-126d-4638-8026-8e41f5abf03a)

<br />
<br />
<p align="center">
I can also change the tickets SLA (Service Level Aggrement) of the ticket in the "SLA Plan" section:  <br/>
 
![image](https://github.com/user-attachments/assets/2b6e155c-6738-4d81-a2c0-ba0444d9522e)

<br />
<br />
<p align="center">
Another option I have is to change the tickets department in the "Department" section:  <br/>

![image](https://github.com/user-attachments/assets/68fce70f-8459-43fd-a28d-55fa599f7af8)

<br />
<br />
<p align="center">
Looking further down I can see a thread of all of the changes made to the ticket:

![image](https://github.com/user-attachments/assets/7d48149f-78fc-452e-843a-8bfb954cbeaf)

<br />
<br />
<p align="center">
At the bottom I can post replies communicating updates of the ticket:  <br/>

![image](https://github.com/user-attachments/assets/d0bf7755-54c6-4384-b701-70da8741de10)

<br />
<br />
<p align="center">
If I go back to see all the open tickets, I can see the changes I made to the ticket:  <br/>

![image](https://github.com/user-attachments/assets/bb161f2a-bc8b-485d-89ef-ef257927cac7)

<br />
<br />
<p align="center">
To resolve a ticket, I can select "Resolved" from the "Ticket Status" menu at the bottom of the ticket:

![image](https://github.com/user-attachments/assets/982f5740-c01d-4fe1-9d63-2345b98c7129)

<br />
<br />
<p align="center">
The resolved ticket will disappear from the open tickets tab and appear in the closed tickets tab:

![image](https://github.com/user-attachments/assets/58ea72c4-fbd8-4d34-ac3c-869f1554462e)
![image](https://github.com/user-attachments/assets/6205fe65-1807-4b0f-a8c2-b1ce848033a9)


<h2>osTicket: Creating and Working Tickets is now Complete!</h2>

<b> We've successfully gone through the life cycle of a ticket from creation to resolution, made changes to the tickets when necessary like assigning the tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication! </b>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
