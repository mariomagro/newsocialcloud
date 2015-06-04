To retrieve a list of the user's social media account details, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/account-details.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

application\_id: Your application id from http://newsocialcloud.com/developers.html

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;account-details type="array"&gt;


> 

&lt;account-detail&gt;


> > 

&lt;account-name&gt;

Resources

&lt;/account-name&gt;


> > 

&lt;description&gt;

Facebook Fan Page

&lt;/description&gt;


> > 

&lt;id type="integer"&gt;

198918

&lt;/id&gt;


> > 

&lt;url&gt;


> > > http://www.facebook.com/pages/Resources/198906483514676

> > 

&lt;/url&gt;


> > 

&lt;avatar&gt;

http://graph.facebook.com/198906483514676/picture

&lt;/avatar&gt;




&lt;/account-detail&gt;




&lt;account-detail&gt;



> 

&lt;account-name&gt;

Test Page 3

&lt;/account-name&gt;


> > 

&lt;description&gt;

Facebook Fan Page

&lt;/description&gt;


> > 

&lt;id type="integer"&gt;

1150841

&lt;/id&gt;


> > 

&lt;url&gt;


> > > http://www.facebook.com/pages/Test-Page-3/158776710828095

> > 

&lt;/url&gt;


> > 

&lt;avatar&gt;

http://graph.facebook.com/158776710828095/picture

&lt;/avatar&gt;



> 

&lt;/account-detail&gt;




&lt;/account-details&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

