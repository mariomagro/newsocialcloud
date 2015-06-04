To authenticate against the API and retrieve an access token, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/auth

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>redirect_uri: The URI to send the user to after authenticating. newsocialcloud will redirect the user back to this URL with either #error_type= or #access_token= appended to the URL. You will need to store the access_token for any subsequent API requests.</p>
<p>site: Optional. For white label sites, pass the site code when you authenticate.</p>
<p>source: Optional. Specify client or server as the source. If client is set, the response is sent in the following format:#/success/access_token or #/error/error_message If server is set, the response is sent in the following format: ?error_type=errorType&error_message=errorMessage ?access_token=access_token</p>

**Authentication:**

Basic authentication with username and password belonging to the newsocialcloud user.

**Success Response:**

User is redirected to redirect\_uri with #access\_token= appended to the URL.

**Error Responses:**

User is redirected to redirect\_uri with #error\_type= appended to the URL.