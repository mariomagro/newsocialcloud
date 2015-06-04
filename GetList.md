To retrieve an existing list, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/list.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>list_id: The id of the list to retrieve.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"consumers": <a href='.md'>.md</a>,</p>
> <p>"contributors": <a href='.md'>.md</a>,</p>
> <p>"id": 630,</p>
> <p>"user_id": 5131,</p>
> <p>"list_type": "Social",</p>
> <p>"list_name": "NewSocialCloud Twitter"</p>
}