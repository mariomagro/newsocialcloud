To retrieve a list of message recipients for a given NewSocialCloud message, make a GET call using basic authentication with the user's NewSocialCloud username and password

**URL:**

http://login.newsocialcloud.com/api/v1/message-recipients.format?type=type

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html
message\_id: The message id.

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;user-services type="array"&gt;


> 

&lt;user-service&gt;


> > 

&lt;account-name&gt;

Twitter - oauth - NewSocialCloud

&lt;/account-name&gt;


> > 

&lt;account-type&gt;

Twitteroauth

&lt;/account-type&gt;


> > 

&lt;icon-url&gt;

http://www.google.com/s2/favicons?domain=twitter.com

&lt;/icon-url&gt;


> > 

&lt;recipient-id&gt;

6300

&lt;/recipient-id&gt;



> 

&lt;/user-service&gt;


> 

&lt;user-service&gt;


> > 

&lt;account-name&gt;

Ping.fm - info@newsocialcloud.com

&lt;/account-name&gt;


> > 

&lt;account-type&gt;

Pingfm

&lt;/account-type&gt;


> > 

&lt;icon-url&gt;

http://www.google.com/s2/favicons?domain=ping.fm

&lt;/icon-url&gt;


> > 

&lt;recipient-id&gt;

6307

&lt;/recipient-id&gt;



> 

&lt;/user-service&gt;




&lt;/user-services&gt;



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

MessageNotFoundError\

&lt;/type&gt;




&lt;message&gt;

Message could not be found.

&lt;/message&gt;




&lt;/error&gt;

