To update a permission profile, make a PUT call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/permission_profile.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>profile_id: The ID of the profile to update.</p>
<p>profile_name: The name of the profile to update.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"profile_name": "Default 3",</p>
> <p>"id": 4,</p>
> <p>"permissions": <a href='.md'>.md</a></p>
}

**Error Responses:**

{"error": {"type": "MissingParameter", "message": "The profile\_id parameter is missing."} }
{"error": {"type": "MissingParameter", "message": "The profile\_name parameter is missing."} }