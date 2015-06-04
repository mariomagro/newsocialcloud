Allows you to attach photos and files to a specific NewSocialCloud message.

**URL:**

http://login.newsocialcloud.com/api/v1/media.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

POST

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

message\_id: The message's id.

media: Optional. A comma separated list of files or images to attach to the message. Each item in the list must contain the file name with extension and a URL-encoded base64 string representing the data.

Format: file\_name\_1|base64string\_1,file\_name\_2|base64string\_2. e.g. logo1w.png|iVBORw0KGgoAAAANSUhEUgAAARMAAABfCAMAAAD8mtMpAAADAFBMVEUAcwsOcRojZitLflOWBR...


**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;msg&gt;


> 

&lt;status&gt;

Pending

&lt;/status&gt;


> 

&lt;subject&gt;



&lt;/subject&gt;


> 

&lt;tags nil="true"&gt;



&lt;/tags&gt;


> 

&lt;user-id type="integer"&gt;

1

&lt;/user-id&gt;


> 

&lt;recurs&gt;

Once

&lt;/recurs&gt;


> 

&lt;recurs-until-gmt type="datetime"&gt;

2009-11-12T10:26:55Z

&lt;/recurs-until-gmt&gt;


> 

&lt;recurs-until-client type="datetime"&gt;

2009-11-12T12:26:55Z

&lt;/recurs-until-client&gt;


> 

&lt;message-id type="integer"&gt;

5

&lt;/message-id&gt;


> 

&lt;message-text&gt;

test to FF.

&lt;/message-text&gt;


> 

&lt;message-rich-text&gt;

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">


&lt;html&gt;




&lt;head&gt;




&lt;title&gt;



&lt;/title&gt;




&lt;/head&gt;




&lt;body&gt;


<p>test to FF.</p>


&lt;/body&gt;




&lt;/html&gt;



&lt;/message-rich-text&gt;


> 

&lt;notify-me type="integer"&gt;

0

&lt;/notify-me&gt;


> 

&lt;send-date-gmt type="datetime"&gt;

2009-11-12T10:26:55Z

&lt;/send-date-gmt&gt;


> 

&lt;send-date-client type="datetime"&gt;

2009-11-12T12:26:55Z

&lt;/send-date-client&gt;


> 

&lt;send-to&gt;

"Friendfeed - hamgav"

&lt;/send-to&gt;


> 

&lt;timezone-offset-client type="integer"&gt;

-120

&lt;/timezone-offset-client&gt;


> 

&lt;photos type="array"&gt;


> > 

&lt;photo&gt;


> > > 

&lt;id type="integer"&gt;

484

&lt;/id&gt;


> > > 

&lt;name&gt;

logo1w.png

&lt;/name&gt;


> > > 

<file\_url>

http://newsocialcloud.com/imagenes/logo1w.pnng

</file\_url>



> > 

&lt;/photo&gt;


> > 

&lt;photo&gt;


> > > 

&lt;id type="integer"&gt;

485

&lt;/id&gt;


> > > 

&lt;name&gt;

n1727389556\_1512.jpg

&lt;/name&gt;


> > > 

<file\_url>

http://newsocialcloud.com/imagenes/n1727389556_1512.jppg

</file\_url>



> > 

&lt;/photo&gt;




&lt;/photos&gt;



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

