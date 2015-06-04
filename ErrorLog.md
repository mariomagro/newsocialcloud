To log a new exception, make an authenticated POST request.

**URL:**

http://login.newsocialcloud.com/api/v2/error_log.json

**HTTP Methods:**

POST

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>message: The error message.</p>
<p>stacktrace: A dump of the stack trace and any other useful debug information.</p>
<p>source: The source of the error. E.g. web, android, ios.</p>
<p>type: The type of error. E.g. login, contact etc</p>

**Success Response:**

{
> <p>"source": "web",</p>
> <p>"message": "test",</p>
> <p>"stacktrace": "test",</p>
> <p>"id": 990860,</p>
> <p>"created_at": "2014/04/06 16:59:59 +0000",</p>
> <p>"user_id": 5031</p>
}