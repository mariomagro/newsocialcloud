To create a new user, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/user.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>fullname: The name of the user.</p>
<p>email: The email address of the user.</p>
<p>login: The username of the user.</p>
<p>password: The password of the user.</p>
<p>profile: Either administrator, team member or client.</p>
<p>timezone: Optional. The user's timezone offset from GMT in minutes. Default: The admin user's timezone will be used. In Javascript, this is the value of getTimezoneOffset.</p>
<p>managed_by_id: Optional. The user ID of the user that manages this user. Default: None.</p>
<p>approval_from_ids: Optional. A comma-separated list of user ID's that need to approve this user's content before it is published.</p>
<p>permission_profile_id: Optional. The permission profile ID to set for the user.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "profile": "Team Member",
> "lineage": "122068",
> "is\_active": true,
> "fullname": "Test User",
> "api\_key": "c48c7db283e1d1b57f1449d1c02d6083b0e1e6a2",
> "last\_login": "2013/09/25 13:59:13 +0000",
> "id": 122068,
> "color": "#000000",
> "avatar": "![http://www.gravatar.com/avatar/4b13c1a4f17c731280e51faead7bc1f3?s=55&d=http://newsocialcloud.com/images/silhouette.png](http://www.gravatar.com/avatar/4b13c1a4f17c731280e51faead7bc1f3?s=55&d=http://newsocialcloud.com/images/silhouette.png)",
> "user\_status": "Active (Premium)",
> "parent\_user\_id": null,
> "login": "xpxaaaaaa",
> "email": "infobbbaaa123@newsocialcloud.com"
}

**Error Responses:**

{"error": {"type": "MissingParameter", "message": "The profile parameter is missing."} }
{"error": {"type": "InvalidUsername", "message": "This username is already in use."} }
{"error": {"type": "InvalidUsername", "message": "This email is already in use."} }
{"error": {"type": "InvalidUsername", "message": "Username must be longer than 3 characters."} }