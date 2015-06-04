To retrieve the details for a specific contact, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/contact.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>contact_id: The contact id.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;contact&gt;


> 

&lt;addressline1 nil="true"&gt;



&lt;/addressline1&gt;


> 

&lt;addressline2 nil="true"&gt;



&lt;/addressline2&gt;


> 

&lt;birthday type="date"&gt;

1990-05-01

&lt;/birthday&gt;


> 

&lt;cellphone nil="true"&gt;



&lt;/cellphone&gt;


> 

&lt;city nil="true"&gt;



&lt;/city&gt;


> 

&lt;company nil="true"&gt;



&lt;/company&gt;


> 

&lt;country nil="true"&gt;



&lt;/country&gt;


> 

&lt;email&gt;

info@newsocialcloud.com

&lt;/email&gt;


> 

&lt;fax nil="true"&gt;



&lt;/fax&gt;


> 

&lt;firstName&gt;

John

&lt;/firstName&gt;


> 

&lt;id type="integer"&gt;

3568

&lt;/id&gt;


> 

&lt;lastName&gt;

Smith

&lt;/lastName&gt;


> 

&lt;occupation nil="true"&gt;



&lt;/occupation&gt;


> 

&lt;sex nil="true"&gt;



&lt;/sex&gt;


> 

&lt;state nil="true"&gt;



&lt;/state&gt;


> 

&lt;tel nil="true"&gt;



&lt;/tel&gt;


> 

&lt;unsubscribed type="integer"&gt;

0

&lt;/unsubscribed&gt;


> 

&lt;zip nil="true"&gt;



&lt;/zip&gt;


> 

&lt;contact-accounts type="array"/&gt;




&lt;/contact&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;



OR



&lt;error&gt;




&lt;type&gt;

ContactNotFoundError

&lt;/type&gt;




&lt;message&gt;

Contact could not be found.

&lt;/message&gt;




&lt;/error&gt;

