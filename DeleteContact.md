To delete a contact, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/contact.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>


&lt;P&gt;

contact\_id: The id of the contact to be deleted.

Unknown end tag for &lt;/p&gt;



**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;result&gt;


> 

&lt;status&gt;

success

&lt;/status&gt;




&lt;/result&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

ContactNotFound

&lt;/type&gt;




&lt;message&gt;

Contact could not be found.

&lt;/message&gt;




&lt;/error&gt;

