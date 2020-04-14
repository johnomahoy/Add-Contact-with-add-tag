# Add-Contact-with-add-tag

This script will check and update if contact exist or create if none it will also find the tag id using the SearchTag data.

These are the expected data from the user: newcontactname  
	newcontactemail  
	newcontactjob  
	company  
	tagID  
	SearchTag  
	eventabbrevation  
	eventname

	(1) Check for duplicate
		The script will check if a contact with the email has been already created, if a
		contact has already been created with the email
		the script will return an error, ELSE it will create the contact and return the id of the contact
   

	(2) Get the user ID
		The script will get the user ID using the email of the contact   


	(3) Loop and get the user id in $data   


	(4) Add tag id to the contact
		 The script will add the tag id to the contact by using grpAssign($user_id, $tagID);   

	(5) Insert Event name and Event abbrevation into the contact  


	(6) Find the tag id using the data in $searchtag  


	(7) Apply the tag into the contact  


  Developed by: Benjie
  Check the script for more info.
