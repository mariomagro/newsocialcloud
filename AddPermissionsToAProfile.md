To specify all permissions for a permission profile, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/permissions.json


**HTTP Methods:**

POST

**Parameters:**

application\_id: Your Application ID from http://newsocialcloud.com/developers.
profile\_id: The ID of the profile to retrieve.
permissions: A comma separated list of permission IDs. This list can be retrieved using the available\_permissions API call.

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "profile\_name": "Default",
> "id": 2,
> "permissions": [
> > {
> > > "permission\_category": {
> > > > "category\_name": "Engage",
> > > > "id": 1,
> > > > "sorting": 1

> > > },
> > > "permission\_description": "The user can compose new messages.",
> > > "id": 2,
> > > "permission\_name": "Compose Messages",
> > > "permission\_code": "messages.create"

> > }

> ]
}

**Error Responses:**

{"error": {"type": "MissingParameter", "message": "The profile\_id parameter is missing."} }
{"error": {"type": "MissingParameter", "message": "The permissions parameter is missing."} }