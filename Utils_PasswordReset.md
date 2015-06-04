To send a password reset link to a user, make a GET call without any authentication.

**URL:**

http://login.newsocialcloud.com/api/utils/password_reset.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://login.newsocialcloud.com/developers.hmtl'>http://login.newsocialcloud.com/developers.hmtl</a></p>
<p>email: The user's registered email address. This is where them reset password link will be sent.</p>
<p>redirect_uri: This is URL-encoded URL that the user will be sent to once they click the reset password link from their email. Please note - an activation link will be appended to this URL when the user receives the email. This will be needed for authenticate the user for password reset. e.g. <a href='http://myapp.com/resetpassword#'>http://myapp.com/resetpassword#</a> - this will come through as <a href='http://myapp.com/resetpassword#xxxxxxx'>http://myapp.com/resetpassword#xxxxxxx</a> when included in the reset password email.</p>

**Authentication:**

None required.

**Success Response:**

{"status": "OK" }

**Error Response:**

{"error": {"type": "NotFound", "message": "We were unable to locate your email address."} }