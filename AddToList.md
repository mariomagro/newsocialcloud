To add an item to a list, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/list_add.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>list_id: The id of the list to add this item to.</p>
<p>item_id: The recipient_id of the service retrieved from the Services call or the contact_id of a contact.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

{
> "status": "OK"
}