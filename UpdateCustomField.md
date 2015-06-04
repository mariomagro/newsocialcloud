To update an existing custom field, make a PUT request.

**URL:**

http://login.newsocialcloud.com/api/v2/custom_field.json

**HTTP Methods:**

PUT

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>custom_field_id: Your id of the custom field to update.</p>
<p>field_title: The field title.</p>
<p>category: The custom field category. Either: user, contact or account.</p>
<p>field_type: The type of field. Either: text, textarea, password, list, date, time, url, numeric.</p>
<p>sort_order: A numeric value representing the order that this field appears in.</p>
<p>mandatory: Specifies whether this field is mandator or not. 1 or 0.</p>
<p>field_options: When field_type is list, this represents a list of options. Each option in the list is separated by a line break.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

[
> {
> > <p>"created_at": "2014/04/27 16:03:02 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/04/27 16:03:02 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 1,</p>
> > <p>"id": 32772,</p>
> > <p>"user_id": 5131,</p>
> > <p>"field_options": "New York\Los Angeles",</p>
> > <p>"field_type": "list",</p>
> > <p>"field_name": "city",</p>
> > <p>"field_title": "City"</p>

> },
> {
> > <p>"created_at": "2014/04/19 12:35:03 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/04/19 12:35:03 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 1,</p>
> > <p>"id": 31660,</p>
> > <p>"user_id": 59119,</p>
> > <p>"field_options": "",</p>
> > <p>"field_type": "text",</p>
> > <p>"field_name": "field3",</p>
> > <p>"field_title": "Field3"</p>

> },
> {
> > <p>"created_at": "2014/04/19 07:51:35 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/04/19 07:51:35 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 1,</p>
> > <p>"id": 31656,</p>
> > <p>"user_id": 5131,</p>
> > <p>"field_options": "Madrid\Barcelona",</p>
> > <p>"field_type": "list",</p>
> > <p>"field_name": "location",</p>
> > <p>"field_title": "Location"</p>

> },
> {
> > <p>"created_at": "2014/05/11 15:24:27 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/05/11 15:24:27 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 1,</p>
> > <p>"id": 33554,</p>
> > <p>"user_id": 5131,</p>
> > <p>"field_options": "",</p>
> > <p>"field_type": "text",</p>
> > <p>"field_name": "neighbourhood",</p>
> > <p>"field_title": "neighbourhood"</p>

> },
> {
> > <p>"created_at": "2014/10/24 10:56:38 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/10/24 10:56:38 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 0,</p>
> > <p>"id": 51348,</p>
> > <p>"user_id": 77515,</p>
> > <p>"field_options": "",</p>
> > <p>"field_type": "text",</p>
> > <p>"field_name": "signature",</p>
> > <p>"field_title": "Signature"</p>

> },
> {
> > <p>"created_at": "2014/04/25 15:12:02 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/04/25 15:12:02 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 1,</p>
> > <p>"id": 32184,</p>
> > <p>"user_id": 5131,</p>
> > <p>"field_options": "Store 1\nStore 2\n",</p>
> > <p>"field_type": "list",</p>
> > <p>"field_name": "store_name",</p>
> > <p>"field_title": "store name"</p>

> },
> {
> > <p>"created_at": "2014/10/16 17:00:58 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/10/16 17:00:58 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 0,</p>
> > <p>"id": 50968,</p>
> > <p>"user_id": 5131,</p>
> > <p>"field_options": "",</p>
> > <p>"field_type": "text",</p>
> > <p>"field_name": "twitter_hashtag",</p>
> > <p>"field_title": "Twitter Hashtag"</p>

> },
> {
> > <p>"created_at": "2014/10/16 16:58:16 +0000",</p>
> > <p>"category": "user",</p>
> > <p>"whitelabel": "NewSocialCloud Team",</p>
> > <p>"updated_at": "2014/10/16 16:58:16 +0000",</p>
> > <p>"field_value": "",</p>
> > <p>"sort_order": 1,</p>
> > <p>"mandatory": 0,</p>
> > <p>"id": 50967,</p>
> > <p>"user_id": 5131,</p>
> > <p>"field_options": "",</p>
> > <p>"field_type": "password",</p>
> > <p>"field_name": "twitter_password",</p>
> > <p>"field_title": "Twitter Password"</p>

> }
]
Error Response:


&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;
