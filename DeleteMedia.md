To delete a media file for a given user, make a DELETE call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/media.json

**HTTP Methods:**

DELETE

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

file\_id: The id of the file to be deleted.

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Success Response:**

{
> "status": "OK"
}