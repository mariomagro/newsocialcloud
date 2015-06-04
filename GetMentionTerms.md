To retrieve a list of the user's social media mention terms, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/mention-terms.format

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


&lt;keywords&gt;


> 

&lt;keyword&gt;


> > 

<term\_id>

238873

</term\_id>


> > 

&lt;description&gt;

newsocialcloud

&lt;/description&gt;


> > 

&lt;type&gt;

mention

&lt;/type&gt;


> > 

<last\_checked\_gmt>

Thu Mar 22 08:30:27 UTC 2012

</last\_checked\_gmt>



> 

&lt;/keyword&gt;


> 

&lt;keyword&gt;


> > 

<term\_id>

312289

</term\_id>


> > 

&lt;description&gt;

Disney

&lt;/description&gt;


> > 

&lt;type&gt;

mention

&lt;/type&gt;


> > 

<last\_checked\_gmt>

Thu Mar 22 08:14:17 UTC 2012

</last\_checked\_gmt>



> 

&lt;/keyword&gt;


> 

&lt;keyword&gt;


> > 

<term\_id>

175851

</term\_id>


> > 

&lt;description&gt;

Mc Donalds

&lt;/description&gt;


> > 

&lt;type&gt;

review

&lt;/type&gt;


> > 

<last\_checked\_gmt>

Wed Mar 21 12:03:58 UTC 2012

</last\_checked\_gmt>



> 

&lt;/keyword&gt;




&lt;/keywords&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

