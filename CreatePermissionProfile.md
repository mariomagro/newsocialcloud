To create a new permission profile, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/permission_profile.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>profile_name: The name of the profile.</p>
<p>permissions: Optional. A comma separated list of permission IDs. This list can be retrieved using the available_permissions API call.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"profile_name": "Default 3",</p>
> <p>"id": 4,</p>
> <p>"permissions": <a href='.md'>.md</a></p>
}

**Error Responses:**

{"error": {"type": "MissingParameter", "message": "The profile\_name parameter is missing."} }