To retrieve an existing user, make a GET call using basic authentication.

**URL:**

http://newsocialcloud.com/api/v2/user.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>The following parameters are optional. If they are not provided, then the authenticated user's details are used.</p>

<p>user_id: The ID of the user to retrieve.</p>
<p>user_api_key: The API key of the user to retrieve.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

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
> "email": "infobbbaaa123@newsocialcloud.com",
> "permission\_profile":{"profile\_name":"Default","id":2}
}

**Error Responses:**

{"error": {"type": "NotFound", "message": "The user could not be found."} }