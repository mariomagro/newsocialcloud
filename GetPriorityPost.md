To retrieve a single priority inbox item, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/priority-post.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>priority_post_id: The ID of the priority post.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"responder_avatar": "<img src='http://pbs.twimg.com/profile_images/1642138996/Twitter_Icon_normal.jpg' />",</p>
> <p>"original_message": null,</p>
> <p>"id": 75297956,</p>
> <p>"service_image": "<a href='http://twitter.com/phoenix/favicon.ico'>http://twitter.com/phoenix/favicon.ico</a>",</p>
> <p>"message_text": "",</p>
> <p>"account_avatar": "<img src='http://pbs.twimg.com/profile_images/3667750807/0d1114cb36f85b8b49e45bacf9bcc485_normal.png' />",</p>
> <p>"uid": "KRSConsulting",</p>
> <p>"user_id": 5131,</p>
> <p>"message_html": "",</p>
> <p>"responder_fullname": "KRS Consulting",</p>
> <p>"post_picture": null,</p>
> <p>"responder_identifier": "@KRSConsulting",</p>
> <p>"account_detail": {</p>
> > <p>"uid": "newsocialcloud",</p>
> > <p>"description": "Twitter",</p>
> > <p>"account": {</p>
> > > "service": {
> > > > <p>"icon": "<img src='http://snd-assets.s3.amazonaws.com/icons/somicro/twitter.png' />",</p>
> > > > <p>"reply_via_filter": "twitteroauth",</p>
> > > > <p>"stream_actions": [</p>
> > > > > {
> > > > > > <p>"name": "Reply",</p>
> > > > > > <p>"action": "reply",</p>
> > > > > > <p>"can_message": true,</p>
> > > > > > <p>"message_prefix": "@"</p>

> > > > > },
> > > > > {
> > > > > > <p>"name": "DM",</p>
> > > > > > <p>"action": "dm",</p>
> > > > > > <p>"can_message": true,</p>
> > > > > > <p>"message_prefix": "d "</p>

> > > > > },
> > > > > {
> > > > > > <p>"name": "Retweet",</p>
> > > > > > <p>"action": "retweet",</p>
> > > > > > <p>"can_message": true,</p>
> > > > > > <p>"message_prefix": "RT @"</p>

> > > > > },
> > > > > {
> > > > > > <p>"name": "Show%20Conversation",</p>
> > > > > > <p>"action": "sc",</p>
> > > > > > <p>"can_message": false,</p>
> > > > > > <p>"message_prefix": ""</p>

> > > > > },
> > > > > {
> > > > > > <p>"name": "Favorite",</p>
> > > > > > <p>"action": "favorite",</p>
> > > > > > <p>"can_message": false,</p>
> > > > > > <p>"message_prefix": ""</p>

> > > > > }

> > > > ]

> > > }

> > },
> > <p>"picture_url": "<img src='http://pbs.twimg.com/profile_images/4354356959669096449/rA7jKuts_normal.png' />",</p>
> > <p>"url": "<a href='http://twitter.com/newsocialcloud'>http://twitter.com/newsocialcloud</a>",</p>
> > <p>"account_name": "newsocialcloud",</p>
> > <p>"account_id": 500437</p>

> },
> <p>"url": "<a href='http://twitter.com/KRSMConsulting'>http://twitter.com/KRSMConsulting</a>",</p>
> <p>"account_name": "newsocialcloud",</p>
> <p>"relative_created_at": "1 month ago",</p>
> <p>"post_link": null,</p>
> <p>"isRead": 1,</p>
> <p>"created_at": "2014/02/13 13:03:16 +0000",</p>
> <p>"sentiment": 0,</p>
> <p>"response_type": "Mention",</p>
> <p>"post_body": "The KRS Consulting Daily is out! <a href='http://t.co/hPYZCB3pRJ'>http://t.co/hPYZCB3pRJ</a> Stories via @newsocialcloud @CharlieCure",</p>
> <p>"service_name": "twitteroauth",</p>
> <p>"message_type": "Post",</p>
> <p>"account_detail_id": 5103</p>
}