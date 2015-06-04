To delete a content library, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/content_library.json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a><p>
<p>id: The id of the library to be deleted.<p>

<b>Authentication:</b>

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.<br>
<br>
<b>Success Response:</b>

{<br>
<blockquote>"status": "OK"<br>
}