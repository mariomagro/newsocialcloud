To retrieve the list of all available permission categories make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/permission_categories.json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > "category\_name": "Engage",
> > "id": 1,
> > "sorting": 1,
> > "category\_description": "Permissions for the Engage Tab"

> }
]