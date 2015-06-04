To update an existing user, make a PUT call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/user.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>user_id: The ID of the user to update.</p>
<p>user_api_key: The API key of the user to update.</p>
<p>fullname: The name of the user.</p>
<p>email: The email address of the user.</p>
<p>login: The username of the user.</p>
<p>password: Optional. The password of the user.</p>
<p>profile: Either administrator, team member or client.</p>

**Additional optional parameters:**

<p>managed_by_id: Optional. The user ID of the user that manages this user. Default: None.</p>
<p>approval_from_ids: Optional. A comma-separated list of user ID's that need to approve this user's content before it is published.</p>
<p>permission_profile_id: Optional. The permission profile ID to set for the user.</p>
<p>timezone: Optional. The user's timezone offset from GMT in minutes. Default: The admin user's timezone will be used. In Javascript, this is the value of getTimezoneOffset.</p>
<p>language: Optional. The user's default language, as an ISO 639-1 code. For example, English would be set as en.</p>
<p>clock_format: Optional. The user's preferred clock format, i.e. a 12 hour clock or a 24 hour clock. Values can be 12 or 24.</p>
<p>marketing: Optional. Set this to 1 if the user can receive marketing updates from newsocialcloud. Alternatively, set it to 0.</p>
<p>url_shortener: Optional. Set this to the user's default URL shortener. Values include: bit.ly, is.gd, goo.gl, awe.sm, don't shorten</p>
<p>url_shortener_login: Optional. If supported, you can provide the user's bit.ly username.</p>
<p>url_shortener_key: Optional. If supported, you can provide the user's bit.ly api key.</p>
<p>image_shortener: Optional. Provide the image shortener for posting images to Twitter. Values include: Twitter, Twitpic,Yfrog</p>
<p>preference: Optional. Set the user's publishing preference. This includes whether to always display the rich text editor or not. Values are default, rte_on, rte_off.</p>
<p>is_paused: Optional. Set this to 1 to pause this user's publishing, or 0 to unpause the user's posts.</p>
<p>security_question: Optional. Set the user's security question. This is used when a user signs from an unrecognized location.</p>
<p>security_answer: Optional. Set the user's security answer. This is used when a user signs from an unrecognized location.</p>
<p>valid_ips: Optional. A commas separated list of valid IP addresses. A user will be prompted to enter security question and answer details if signing in from a non-listed IP.</p>
<p>session_days: Optional. The number of days before the user's access_token expires.</p>
<p>photo_id: Optional. The ID of the photo returned from the UploadMedia call.</p>
<p>desktop_notifications: Optional. Set to 1 if enabled, or 0 if disabled.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"profile": "Team Member",</p>
> <p>"lineage": "122068",</p>
> <p>"is_active": true,</p>
> <p>"fullname": "Test User",</p>
> <p>"api_key": "c48c7db283e1d1b57f1449d1c02d6083b0e1e6a2",</p>
> <p>"last_login": "2014/09/25 13:59:13 +0000",</p>
> <p>"id": 122068,</p>
> <p>"color": "#000000",</p>
> <p>"avatar": "<img src='http://www.gravatar.com/avatar/4b13c1a4f17c731280e51faead7bc1f3?s=55&d=http://newsocialcloud.com/images/silhouette.png' />",</p>
> <p>"user_status": "Active (Premium)",</p>
> <p>"parent_user_id": null,</p>
> <p>"login": "xpxaaaaaa",</p>
> <p>"email": "infobbbaaa123@newsocialcloud.com"</p>
}

**Error Responses:**

{"error": {"type": "MissingParameter", "message": "The profile parameter is missing."} }
{"error": {"type": "InvalidUsername", "message": "This username is already in use."} }
{"error": {"type": "InvalidUsername", "message": "This email is already in use."} }
{"error": {"type": "InvalidUsername", "message": "Username must be longer than 3 characters."} }