To delete a message, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/message.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

DELETE

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html
message\_id: The message's id.

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

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

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;



OR



&lt;error&gt;




&lt;type&gt;

MessageNotFoundError

&lt;/type&gt;




&lt;message&gt;

Message could not be found.

&lt;/message&gt;




&lt;/error&gt;

