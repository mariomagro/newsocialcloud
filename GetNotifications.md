To retrieve notifications for a user, make an authenticated GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/notifications.json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>language: Optional. Set this to the user's language code. E.g. en, es etc.</p>
<p>page: Optional. Set this to the page number you would like to retrieve.</p>
<p>per_page: Optional. Set this to the number of results to return per page. Default is 20.</p>

**Success Response:**

<p>Currently, we have 3 types of notification:</p>

<p>reconnect: Shown when the user needs to reconnect a broken service. (e.g. Facebook after a password change)</p>
<p>message: Shown for general messages/alerts.</p>
<p>timezone: Shown if the user's browser timezone does not match what's stored on the server.</p>
[
> {
> > <p>"created_at_local": "2014/04/10 21:23:23 +0000",</p>
> > <p>"notification_type": "reconnect",</p>
> > <p>"user_id": 5131,</p>
> > <p>"title": "Facebook Reconnection Issue",</p>
> > <p>"data": "{\"reconnection_url\": \"/services/edit/53?aid=747547&src=api\"}",</p>
> > <p>"language": "en",</p>
> > <p>"is_read": 0,</p>
> > <p>"id": 3,</p>
> > <p>"message": "We noticed that you recently changed your Facebook password. Please click here to reconnect.",</p>
> > <p>"created_at": "2014/04/10 20:23:23 +0000",</p>
> > <p>"avatar": "<img src='https://cdn2.iconfinder.com/data/icons/metro-ui-dock/128/Facebook_alt_1.png' />"</p>

> },
> {
> > <p>"created_at_local": "2014/04/10 21:21:03 +0000",</p>
> > <p>"notification_type": "message",</p>
> > <p>"user_id": 5131,</p>
> > <p>"title": "Discount Code",</p>
> > <p>"data": "{\"url\": \"/upgrade?discount_code=x\"}",</p>
> > <p>"language": "en",</p>
> > <p>"is_read": 0,</p>
> > <p>"id": 2,</p>
> > <p>"message": "Use this discount code and save 15%!",</p>
> > <p>"created_at": "2014/04/10 20:21:03 +0000",</p>
> > <p>"avatar": "<img src='https://cdn2.iconfinder.com/data/icons/metro-ui-dock/128/Email_Chat.png' />"</p>

> },
> {
> > <p>"created_at_local": "2014/04/10 21:19:27 +0000",</p>
> > <p>"notification_type": "timezone",</p>
> > <p>"user_id": 5131,</p>
> > <p>"title": "Timezone Mismatch",</p>
> > <p>"data": "{}",</p>
> > <p>"language": "en",</p>
> > <p>"is_read": 0,</p>
> > <p>"id": 1,</p>
> > <p>"message": "We noticed that your local timezone is different from the timezone on your account. ",</p>
> > <p>"created_at": "2014/04/10 20:19:27 +0000",</p>
> > <p>"avatar": "<img src='https://cdn1.iconfinder.com/data/icons/metro-ui-dock/128/Clock.png' />"</p>

> }
]