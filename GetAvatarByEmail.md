To retrieve an avatar for a given email address, make a GETcall without any authentication.

**URL:**

http://login.newsocialcloud.com/api/utils/email_avatar.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>email: The user's email address.</p>
default: Optional. If no matching avatar is found, this URL will be refurned as default.

Unknown end tag for &lt;/p&gt;



**Authentication:**

None required.

**Success Response:**

{"avatar": ""![http://www.gravatar.com/avatar/xxxx.png](http://www.gravatar.com/avatar/xxxx.png)" }