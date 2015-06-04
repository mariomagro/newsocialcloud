To delete a custom field, make a DELETE request.

**URL:**

http://login.newsocialcloud.com/api/v2/custom_field.json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>custom_field_id: The id of the custom field to delete.</p>

**Authentication:**
Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{"status": "OK"}

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

