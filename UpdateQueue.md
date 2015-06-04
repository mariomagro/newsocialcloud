To create or NewSocialCloud SmartQueue for a given user, make a POST call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/queue.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>queue_id: The id of the queue to update.</p>
<p>queue_name: Optional. The name of the queue.</p>
<p>queue_times: Optional. The comma separated list of queue times. These will replace the existing ones on the queue. In the format, day_index|hour|minute,day_index|hour|minute,....,day_index|hour|minute<br>
day_index of 0 represents Monday. day_index of 6 is Sunday. For example: 0|11|30,2|14|44<br>
<p>represents: Monday at 11.30, Wednesday at 2.44pm.</p>
<p>contributors: Optional. A comma separated lists of user IDs representing users that can contribute to this queue.</p>
<p>can_repeat: Please use 1 if messages can repeat, otherwise 1.</p>

<b>Authentication:</b>

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.<br>
<br>
<b>Success Response:</b>

{<br>
<blockquote>"queue_times": [<br>
<blockquote>{<br>
<blockquote>"minute": 30,<br>
"hour": 11,<br>
"id": 284406,<br>
"weekday": 0<br>
</blockquote>},<br>
{<br>
<blockquote>"minute": 44,<br>
"hour": 14,<br>
"id": 284407,<br>
"weekday": 2<br>
</blockquote>}<br>
</blockquote>],<br>
"can_repeat": 0,<br>
"queue_name": "My Queue",<br>
"id": 9004,<br>
"user_id": 5131,<br>
"auto_detect": 0<br>
}