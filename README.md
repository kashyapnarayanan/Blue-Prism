# Blue-Prism
Robotic Process Automation. 
Here i had automated a process for generating hashcode, which is a web based application. 
Hashcode is generated from personal information of various client entities. 
Basically we get the client information in a table form and there is different catagories of client present in that table, hashcode is generated for a particular catagory of work item(WI5). 
So first i launched the application from a URL and sign up using the credentials. 
 then fetched all the table data and store it into the data collection. Then i filterded the required data only using collection manipulation,
and populated those data onto work queue named ACME POC Work Queue. Hashcode is generated from another webpage, so i used different VBO for this. 
Then input required information and generated the hashcode and stored it into the collection. 
Now i added this hashcode into correspondinmg client details and updated the status as Completed. 
Marked the corresponding workqueue item as completed and repeated the process for all items.
