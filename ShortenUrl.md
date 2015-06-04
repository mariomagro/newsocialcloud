To shorten a given url, make a GET call using basic authentication. Where available, newsocialcloud will use the authenticated user's link shortening preferences.

**URL:**

http://login.newsocialcloud.com/api/v1/shorten.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>url: The long url to shorten.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**



&lt;result&gt;


> 

&lt;status&gt;

success

&lt;/status&gt;


> 

&lt;url&gt;

http://is.gd/WbezIX

&lt;/url&gt;




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

