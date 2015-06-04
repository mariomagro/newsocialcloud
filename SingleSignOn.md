Log the user in to their NewSocialCloud account and direct to the default page or a page you specify.

**URL:**

http://login.newsocialcloud.com/api/v1/single-sign-on

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html
redirect\_to: Optional. The URL to direct users to after signing in. If you leave this out, the user will be redirected to the NewSocialCloud or White Label homepage.

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

