To store a search term so that it's added to the list of previous social searches for the authenticated user, make a POST request using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/search_term

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>search_term:. The search term (query) to be stored.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

> {
> > "id": 26576,
> > "search\_term": "burger king"

> }

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

