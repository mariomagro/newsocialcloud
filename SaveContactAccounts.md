To add contact account information to a contact make a PUT request.

**URL:**

http://login.newsocialcloud.com/api/v2/contact_account.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>contact_id: The contact id.</p>
<p>type: The type of the account. This could be one of Facebook, Twitter, Linkedin, Instagram.</p>
<p>account_id: The account id used in the SocialProfileSearch call.</p>
<p>profile_id: The profile id returned by SocialProfileSearch.</p>
<p>profile_url: The profile url returned by SocialProfileSearch.</p>
<p>profile_picture: The profile picture returned by SocialProfileSearch.</p>
<p>full_name: The fullname of the contact's account returned by SocialProfileSearch.</p>
<p>profile_name: The username of the contact's account returned by SocialProfileSearch.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> <p>"id": 3134097,</p>
> <p>"contact_id": 12722250,</p>
> <p>"full_name": "newsocialcloud",</p>
> <p>"profile_id": "15473781",</p>
> <p>"profile_name": "newsocialcloud",</p>
> <p>"profile_url": "<a href='http://twitter.com/newsocialcloud/'>http://twitter.com/newsocialcloud/</a>",</p>
> <p>"profile_picture": "<img src='http://pbs.twimg.com/profile_images/3667750807/0d1114cb36f85b8b49e45bacf9bcc485_normal.png' />",</p>
> <p>"type": "twitter",</p>
> <p>"icon": "<img src='http://snd-assets.s3.amazonaws.com/icons/somicro/twitter.png' />",</p>
> <p>"account_id": 557734</p>
}