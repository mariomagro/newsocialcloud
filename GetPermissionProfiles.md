To retrieve all available permission profiles make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/permission_profiles.json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > "profile\_name": "Default",
> > "id": 2

> },
> {
> > "profile\_name": "Default 2",
> > "id": 3

> }
]