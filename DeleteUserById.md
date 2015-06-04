To delete an existing user, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/user.json

**HTTP Methods:**

DELETE

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>user_id: The ID of the user to update.</p>
<p>user_api_key: The API key of the user to update.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "status": "OK",
}

**Error Responses:**

{"error": {"type": "NotFound", "message": The user could not be found."} }