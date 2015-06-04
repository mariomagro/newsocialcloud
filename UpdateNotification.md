To update a notification for a user, make an authenticated PUT request.

**URL:**

http://login.newsocialcloud.com/api/v2/notifications.json

**HTTP Methods:**

PUT

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>notification_id: The id or id's of the notification(s) to update. To update multiple notifications at once, separate the notification_id's with commas.</p>
<p>is_read: Set to 1 if the notification has been read or 0 otherwise. Note:</p>

**Success Response:**

{
> <p>"created_at_local": "2014/04/10 21:19:27 +0000",</p>
> <p>"notification_type": "timezone",</p>
> <p>"user_id": 5131,</p>
> <p>"title": "Timezone Mismatch",</p>
> <p>"data": "{}",</p>
> <p>"language": "en",</p>
> <p>"is_read": 0,</p>
> <p>"id": 1,</p>
> <p>"message": "We noticed that your local timezone is different from the timezone on your account. ",</p>
> <p>"created_at": "2014/04/10 20:19:27 +0000",</p>
> <p>"avatar": "<img src='https://cdn1.iconfinder.com/data/icons/metro-ui-dock/128/Clock.png' />"</p>
}