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
<img 
<br />
<br />
I will open three new tickets and fill out the users information along with the technical issues:  <br/>
<img
<br />
<br />
<img 
<br />
<br />
<img 
<br />
<br />
Next, I will log in as an agent (worker) we created:  <br/>
<img 
<br />
<br />
I can now see all the open tickets I created in the "Tickets" tab:  <br/>
<img 
<br />
<br />
When clicking on a ticket I can see all the information about the ticket like its priority, SLA, creation date, and more:  <br/>
<img 
<br />
<br />
I can change the priority level on appropriate tickets by clicking the "Priority" section and can add a note for the change made:  <br/>
<img 
<br />
<br />
To assign a ticket, click on "Unassigned" next to the "Assigned To" section and select an agent to assign this ticket to:  <br/>
<img 
<br />
<br />
I can also change the tickets SLA (Service Level Aggrement) of the ticket in the "SLA Plan" section:  <br/>
<img 
<br />
<br />
Another option I have is to change the tickets department in the "Department" section:  <br/>
<img 
<br />
<br />
Looking further down I can see a thread of all of the changes made to the ticket:
<img 
<br />
<br />
At the bottom I can post replies communicating updates of the ticket:  <br/>
<img 
<br />
<br />
If I go back to see all the open tickets, I can see the changes I made to the ticket:  <br/>
<img 
<br />
<br />
To resolve a ticket, I can select "Resolved" from the "Ticket Status" menu at the bottom of the ticket:
<img 
<br />
<br />
The resolved ticket will disappear from the open tickets tab and appear in the closed tickets tab:
<img
<br />
<br />
<img 
<br />
<br />

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
