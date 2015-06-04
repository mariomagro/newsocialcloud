To remove an item to a list, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/list_remove.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>list_id: The id of the list to remove this item from.</p>
<p>item_id: The id of the service or contact to be removed.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "status": "OK"
}