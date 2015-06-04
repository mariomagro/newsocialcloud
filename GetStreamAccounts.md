To retrieve a list of the user's stream account details, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/stream-accounts.json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > <p>"description": "Microsoft Corporation",</p>
> > <p>"id": 239937,</p>
> > "service": {
> > > <p>"description": "Monitor Twitter for search terms.",</p>
> > > <p>"icon": "<a href='http://twitter.com/phoenix/favicon.ico'>http://twitter.com/phoenix/favicon.ico</a>",</p>
> > > <p>"id": 1495,</p>
> > > <p>"title": "Twitter Search",<br>
<blockquote>"stream_actions": [<br>
<blockquote>{<br>
<blockquote><p>"name": "Reply",</p>
<p>"action": "reply",</p>
<p>"can_message": true,</p>
<p>"message_prefix": "@"</p>
</blockquote>},<br>
{<br>
<blockquote><p>"name": "DM",</p>
<p>"action": "dm",</p>
<p>"can_message": true,</p>
<p>"message_prefix": "d "</p>
</blockquote>},<br>
{<br>
<blockquote><p>"name": "Retweet",</p>
<p>"action": "retweet",</p>
<p>"can_message": true,</p>
<p>"message_prefix": "RT @"</p>
</blockquote>}<br>
</blockquote>]<br>
</blockquote><blockquote>}<br>
</blockquote><blockquote>}<br>
]