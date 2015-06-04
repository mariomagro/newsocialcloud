Retrieves all the user profiles belonging to the authenticated user. If the authenticated is a white label or agency administrator, then all users belonging to the white label/agency will be returned.

**URL:**

http://login.newsocialcloud.com/api/v1/profiles.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Success Response:**



&lt;users type="array"&gt;


> 

&lt;user&gt;


> > 

&lt;api-key&gt;

xxxx

&lt;/api-key&gt;


> > 

&lt;email&gt;

user@newsocialcloud.com

&lt;/email&gt;


> > 

&lt;fullname&gt;

Admin

&lt;/fullname&gt;


> > 

&lt;id type="integer"&gt;

1

&lt;/id&gt;


> > 

&lt;login&gt;

username

&lt;/login&gt;


> > 

&lt;is-pro type="boolean"&gt;

true

&lt;/is-pro&gt;


> > 

&lt;account-type-name&gt;

Marketer

&lt;/account-type-name&gt;


> > 

&lt;total-credits-available type="decimal"&gt;

2222.0

&lt;/total-credits-available&gt;


> > 

<api\_key>

ABCD1234

</api\_key>



> 

&lt;/user&gt;




&lt;/users&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

