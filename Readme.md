### Description:

This script will provide the Teams owners and members information of available teams in tenant.
     First it will get the Teams 
     For each Team it will fetch the Owner and members of the team
     output will contain Team Name, Team id, Team Owners,members
     Output.csv will store in the current folder.




### Keep the Below details in info.json file
     
   "client_Id":  "please paste your application id here",
  
   "Client_Secret":  "please paste your client secret here",
   
   "Tenantid":  "please paste your tenant id here"


Run the script it will open webpage for grant permissions.
Please login with your tenant **USER ID** and **PASSWORD**


![Image](C:/Users/v-gsaiku/Pictures/1.png)

Once you are login it will shows the 

![Image](C:/Users/v-gsaiku/Pictures/2.png)

Click accept 

If you provided correct credentials it will through success status _**admin_consent = True**_

![Image](C:/Users/v-gsaiku/Pictures/3.png)

Now press Y to proceed further in script.
Script will create 3files. 
Apps.csv is the final output file having Teams applications for each user.

**Output:**

|Teamid |	TeamDisplayname | Owner	| Member|

