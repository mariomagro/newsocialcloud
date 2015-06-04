To create a new custom field, make a POST request.

**URL:**

http://login.newsocialcloud.com/api/v2/custom_field.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
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
> > "created\_at": "2012/04/27 16:03:02 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/04/27 16:03:02 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 1,
> > "id": 32772,
> > "user\_id": 5131,
> > "field\_options": "New York\nLos Angeles",
> > "field\_type": "list",
> > "field\_name": "city",
> > "field\_title": "City"

> },
> {
> > "created\_at": "2012/04/19 12:35:03 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/04/19 12:35:03 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 1,
> > "id": 31660,
> > "user\_id": 59119,
> > "field\_options": "",
> > "field\_type": "text",
> > "field\_name": "field3",
> > "field\_title": "Field3"

> },
> {
> > "created\_at": "2012/04/19 07:51:35 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/04/19 07:51:35 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 1,
> > "id": 31656,
> > "user\_id": 5131,
> > "field\_options": "Madrid\nBarcelona",
> > "field\_type": "list",
> > "field\_name": "location",
> > "field\_title": "Location"

> },
> {
> > "created\_at": "2012/05/11 15:24:27 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/05/11 15:24:27 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 1,
> > "id": 33554,
> > "user\_id": 5131,
> > "field\_options": "",
> > "field\_type": "text",
> > "field\_name": "neighbourhood",
> > "field\_title": "neighbourhood"

> },
> {
> > "created\_at": "2012/10/24 10:56:38 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/10/24 10:56:38 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 0,
> > "id": 51348,
> > "user\_id": 77515,
> > "field\_options": "",
> > "field\_type": "text",
> > "field\_name": "signature",
> > "field\_title": "Signature"

> },
> {
> > "created\_at": "2012/04/25 15:12:02 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/04/25 15:12:02 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 1,
> > "id": 32184,
> > "user\_id": 5131,
> > "field\_options": "Store 1\nStore 2\n",
> > "field\_type": "list",
> > "field\_name": "store\_name",
> > "field\_title": "store name"

> },
> {
> > "created\_at": "2012/10/16 17:00:58 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/10/16 17:00:58 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 0,
> > "id": 50968,
> > "user\_id": 5131,
> > "field\_options": "",
> > "field\_type": "text",
> > "field\_name": "twitter\_hashtag",
> > "field\_title": "Twitter Hashtag"

> },
> {
> > "created\_at": "2012/10/16 16:58:16 +0000",
> > "category": "user",
> > "whitelabel": "NewSocialCloud Team",
> > "updated\_at": "2012/10/16 16:58:16 +0000",
> > "field\_value": "",
> > "sort\_order": 1,
> > "mandatory": 0,
> > "id": 50967,
> > "user\_id": 5131,
> > "field\_options": "",
> > "field\_type": "password",
> > "field\_name": "twitter\_password",
> > "field\_title": "Twitter Password"

> }
]

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

