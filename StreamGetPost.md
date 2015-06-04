To post an action (e.g. like an item), make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v0/post-fetch.json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: The account ID for this stream.</p>
<p>handle: The unique identifier for this stream. This is returned by the GetStream call in the id field.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "messages": [
> > {
> > > "comments": [
> > > > {
> > > > > "id": "151591754888713\_352403964807490\_4027406",
> > > > > "editable": false,
> > > > > "commenter": "London Daily Deals",
> > > > > "commenter\_pic": "http://graph.facebook.com/151591754888713/picture",
> > > > > "uid": "151591754888713",
> > > > > "message": "Test",
> > > > > "date": "24 Apr 22:24"

> > > > }

> > > ],
> > > "comment\_count": 1,
> > > "editable": false,
> > > "likes": 0,
> > > "id": "151591754888713\_352403964807490",
> > > "profile\_id": "0",
> > > "uid": "151591754888713",
> > > "picture": "![http://platform.ak.fbcdn.net/www/app_full_proxy.php?app=26065877776&v=1&size=z&cksum=e17a38410270b4eda01bf266c3fa645c&src=http%3A%2F%2Fstatic-www.kgbdeals.co.uk%2Fdeals%2FGB%2F100411%2F100411_s287x183_3.jpg](http://platform.ak.fbcdn.net/www/app_full_proxy.php?app=26065877776&v=1&size=z&cksum=e17a38410270b4eda01bf266c3fa645c&src=http%3A%2F%2Fstatic-www.kgbdeals.co.uk%2Fdeals%2FGB%2F100411%2F100411_s287x183_3.jpg)",
> > > "link": "http://www.kgbdeals.co.uk/london/deals/101611",
> > > "account\_id": 99579,
> > > "info": {
> > > > "isRead": 0,
> > > > "id": 520412,
> > > > "isHighlighted": 0

> > > },
> > > "link\_block": "%3Ctable%20style=%22padding-top:5px;%22%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%20valign=%22top%22%3E%3Ca%20href=%22http://www.kgbdeals.co.uk/london/deals/101611%22%20target=%22\_blank%22%3E%3Cimg%20src=%22http://platform.ak.fbcdn.net/www/app\_full\_proxy.php?app=26065877776&v=1&size=z&cksum=e17a38410270b4eda01bf266c3fa645c&src=http%253A%252F%252Fstatic-www.kgbdeals.co.uk%252Fdeals%252FGB%252F100411%252F100411\_s287x183\_3.jpg%22%20style=%22max-width:90px;border:0;%22/%3E%3C/a%3E%3C/td%3E%3Ctd%20style=%22border:0;%22%20valign=%22top%22%3E%3Ctable%20%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%3E%3Ca%20href=%22http://www.kgbdeals.co.uk/london/deals/101611%22%20target=%22\_blank%22%3ETwo%20tickets%20to%20Grand%20Designs%20%E2%80%93%20Grand%20Designs%202012%20%E2%80%93%20London%20-%20kgbdeals%3C/a%3E%3C/td%3E%3C/tr%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%3E%3Cspan%20class=%22faded%22%3Ewww.kgbdeals.co.uk%3C/span%3E%3C/td%3E%3C/tr%3E%3Ctr%3E%3Ctd%20style=%22border:0;%22%3E%C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!%3C/td%3E%3C/tr%3E%3C/table%20%3E%3C/td%3E%3C/tr%3E%3C/table%3E",
> > > "message": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('151591754888713',%2099579,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3ELondon%20Daily%20Deals%3C/b%3E%3C/a%3E %C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!",
> > > "message\_unformatted": "%C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!",
> > > "message\_formatted": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('151591754888713',%2099579,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3ELondon%20Daily%20Deals%3C/b%3E%3C/a%3E %C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!",
> > > "screen\_name": "London%20Daily%20Deals",
> > > "subject": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('151591754888713',%2099579,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3ELondon%20Daily%20Deals%3C/b%3E%3C/a%3E %C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!",
> > > "subject\_formatted": "%3Ca%20href=%22%23%22%20onclick=%22new%20Streams().loadProfile('151591754888713',%2099579,%20'facebook');%20%20%20return%20false;%22%3E%3Cb%3ELondon%20Daily%20Deals%3C/b%3E%3C/a%3E %C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!",
> > > "subject\_unformatted": "%C2%A314%20for%20two%20weekend%20tickets%20to%20Grand%20Designs%20Live%202012%20in%20Docklands%20worth%20up%20to%20%C2%A331.60%20%E2%80%93%20save%20up%20to%2056%25%20for%20a%20wealth%20of%20refit%20tips!",
> > > "avatar": "https://graph.facebook.com/151591754888713/picture",
> > > "formattedClientTimeLong": "24 Apr 22:11"

> > }

> ],
> "editable": false,
> "type": "facebook"
}

**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

