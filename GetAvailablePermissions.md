To retrieve the list of all available permissions make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/available_permissions.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>category_id: Optional. The category of permissions to retrieve. To retrieve the categories, use the permission_categories API endpoint.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > "permission\_category": {
> > > "category\_name": "Engage",
> > > "id": 1,
> > > "sorting": 1,
> > > "category\_description": "Permissions for the Engage Tab"

> > },
> > "permission\_description": "The user can compose new messages.",
> > "id": 1,
> > "permission\_name": "Compose Messages",
> > "permission\_code": "messages.create"

> }
]