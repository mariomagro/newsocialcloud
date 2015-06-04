To retrieve a the profile for an authenticated user, make a GET call using an access\_token.

**URL:**

http://login.newsocialcloud.com/api/v2/profile.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>timezone: Optional. Pass the timezoneOffsetClient value from the browser. This will be used to determine if the user's browser timezone differs from that in their profile preferences.</p>

**Authentication:**

Use the access\_token that's retrieved after a call to http://login.newsocialcloud.com/api/v2/auth.

**Success Response:**

{
> "permission\_profile": {
> > "profile\_name": "Default",
> > "id": 2,
> > "permissions": [
> > > {
> > > > "permission\_id": "1",
> > > > "permission\_description": "The user can compose new messages.",
> > > > "permission\_name": "Compose Messages",
> > > > "permission\_code": "messages.create",
> > > > "permission\_category": {
> > > > > "category\_name": "Engage",
> > > > > "id": 1,
> > > > > "sorting": 1

> > > > }

> > > }

> > ]

> },
> "approval\_from": [.md](.md),
> "profile": "Administrator",
> "is\_active": true,
> "lineage": "1234",
> "children\_count": 4,
> "last\_login": "2014/09/08 09:05:41 +0000",
> "user\_status": "Active (Premium)",
> "language": "en",
> "fullname": "John Smith",
> "api\_key": "xxxxxxxxxxxxxx",
> "timezone": -60,
> "id": 1234,
> "color": "#b6617c",
> "user\_properties": [
> > {
> > > "created\_at": "2013/02/26 00:00:00 +0000",
> > > "updated\_at": "2013/02/26 18:18:42 +0000",
> > > "propertyName": "google\_fonts",
> > > "id": 422,
> > > "user\_id": 5131,
> > > "propertyValue": "{\"items\":[.md](.md)}"

> > }

> ],
> "timezone\_name": "Europe - Madrid",
> "mobile": "",
> "parent\_user\_id": null,
> "login": "newsocialcloud",
> "company\_address": "",
> "avatar": "https://snd-store.s3.amazonaws.com/0/NewSocialCloud/... .png",
> "email": "info@xxxx.xxxx",
> "clock\_format": 12
}