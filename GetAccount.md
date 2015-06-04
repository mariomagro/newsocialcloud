To retrieve an account, make an authenticated GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/account.json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The ID belonging to the account.</p>

**Editing an account:**

To edit an account, you need to open a window with the connection\_url. After an account is updated, a notification is sent back to the parent window.

**Success Response:**

{
> "properties": {
> > "message": "Thanks for opting in.",
> > "mapresponse": "none",
> > "number": "+3411223344",
> > "group\_id": "36395",
> > "smskeyword": "newsocialcloud"

> },
> "id": 603003,
> "propertyOverride": "smskeyword=newsocialcloud,number=+3411223344,group\_id=36395,mapresponse=none,message=Thanks for opting in.",
> "service": {
> > "parameters": [
> > > {
> > > > "parameter\_description": "Opt-In  keyword",
> > > > "parameter\_type": "keyword",
> > > > "id": 3477,
> > > > "category": "config",
> > > > "parameter\_name": "smskeyword",
> > > > "options": null,
> > > > "post\_description": "This is the keyword that contacts need to include in their text messages to opt in."

> > > },
> > > {
> > > > "parameter\_description": "Pick a number",
> > > > "parameter\_type": "valuelist",
> > > > "id": 8761,
> > > > "category": "config",
> > > > "parameter\_name": "number",
> > > > "options": "|Available inbound numbers...,|United States (+1),+14411223344|&nbsp;&nbsp;-&nbsp;&nbsp;(442) 333-SEND,+11223344|&nbsp;&nbsp;-&nbsp;&nbsp;(917) 7-GOSAVE,+11223344|&nbsp;&nbsp;-&nbsp;&nbsp;(717) 96-START,+11223344|&nbsp;&nbsp;-&nbsp;&nbsp;(315) 820-2559,|United Kingdom (+44),+4411223344|&nbsp;&nbsp;-&nbsp;&nbsp;(203) 32-ADDME,+4411223344|&nbsp;&nbsp;-&nbsp;&nbsp;(203) 322-INFO",
> > > > "post\_description": "Select an opt-in number from the list and share this with your customers. <br />Want your own number? Contact us about getting a

> <a href='mailto:$email?subject=Custom Number'>custom number-shortcode</a> for your company."
> > },
> > {
> > > "parameter\_description": "Add contacts to this group",
> > > "parameter\_type": "group",
> > > "id": 3479,
> > > "category": "config",
> > > "parameter\_name": "group\_id",
> > > "options": null,
> > > "post\_description": "Add contacts who have opted in via SMS to this group."

> > },
> > {
> > > "parameter\_description": "Map response to",
> > > "parameter\_type": "contact\_field",
> > > "id": 8731,
> > > "category": "config",
> > > "parameter\_name": "mapresponse",
> > > "options": null,
> > > "post\_description": "The mobile number will be captured automatically but you can define which contact field should store the response."

> > },
> > {
> > > "parameter\_description": "Automatic response",
> > > "parameter\_type": "message\_maxlength",
> > > "id": 3481,
> > > "category": "config",
> > > "parameter\_name": "message",
> > > "options": "160",
> > > "post\_description": "Enter a message that will be sent out to new contacts."

> > }
> > ],
> > "compose\_parameters": [.md](.md),
> > "id": 2319,
> > "reply\_via\_filter": null,
> > "category": {
> > > "is\_rich\_text": false,
> > > "category\_name": "Email and SMS Services"

> > },
> > "stream\_actions": [.md](.md)

> },
> "username": "newsocialcloud",
> "sender\_type": "smsgroup"
}