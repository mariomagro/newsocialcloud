To bulk import contacts make a POST request.

**URL:**

http://login.newsocialcloud.com/api/v2/import.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a><p>
<p>payload: The raw CSV data.<p>
<p>type: Set this to contacts.<p>
<p>preference: Set this to Email, SMS or Mixed.<p>
<p>list_id: Optional. Set this to the list id that these contacts will be added to.<p>

<b>Authentication:</b>

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.<br>
<br>
<b>Success Response:</b>

{"rows":2,"status":"Processing","id":34739890}