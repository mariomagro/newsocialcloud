To reply to a priority post, make a POST call using basic authentication.

**URL:**

http://newsocialcloud.com/api/v1/priority-post-reply.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>priority_post_id: The ID of the priority post that you are responding to, retrieved using the GetPriorityPosts call.</p>
<p>message: The message text to respond with.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;msg&gt;


> 

&lt;status&gt;

Pending

&lt;/status&gt;


> 

&lt;subject /&gt;


> 

&lt;tags /&gt;


> 

&lt;user-id type="integer"&gt;

52231

&lt;/user-id&gt;


> 

&lt;recurs /&gt;


> 

&lt;recurs-until-gmt type="datetime"&gt;

2012-04-03T12:52:52Z

&lt;/recurs-until-gmt&gt;


> 

&lt;recurs-until-client type="datetime"&gt;

2012-04-03T13:52:52Z

&lt;/recurs-until-client&gt;


> 

&lt;message-id type="integer"&gt;

8882304

&lt;/message-id&gt;


> 

&lt;message-text&gt;

@MattAster Yes, we do. Take a look at this post: http://goo.gl/XJgwf

&lt;/message-text&gt;


> 

&lt;message-rich-text&gt;

@MattAster Yes, we do. Take a look at this post: http://goo.gl/XJgwf

&lt;/message-rich-text&gt;


> 

&lt;notify-me type="integer"&gt;

0

&lt;/notify-me&gt;


> 

&lt;send-date-gmt type="datetime"&gt;

2012-04-03T11:52:52Z

&lt;/send-date-gmt&gt;


> 

&lt;send-date-client type="datetime"&gt;

2012-04-03T12:52:52Z

&lt;/send-date-client&gt;


> 

&lt;send-to&gt;

P1451603

&lt;/send-to&gt;


> 

&lt;timezone-offset-client type="integer"&gt;

-60

&lt;/timezone-offset-client&gt;


> 

&lt;photos type="array" /&gt;




&lt;/msg&gt;



**Error Responses:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

UnableToSaveError

&lt;/type&gt;




&lt;message&gt;

>This post reply could not be created.

&lt;/message&gt;




&lt;/error&gt;




&lt;error&gt;




&lt;type&gt;

PostNotFoundError

&lt;/type&gt;




&lt;message&gt;

>This post could not be found.

&lt;/message&gt;




&lt;/error&gt;

