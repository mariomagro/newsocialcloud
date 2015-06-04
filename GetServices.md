To retrieve a user's accounts, make an authenticated GET request.

**URL:**

http://login.newsocialcloud.com/api/v2/accounts.json

**HTTP Methods:**

GET

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>filter: Optional. The search string used to filter results by name.</p>
<p>service_type: Optional. The type of service to search for. E.g. emailautoresponder.</p>
<p>include_properties: Optional. Set this to true to have service properties/parameters included in results.</p>
<p>per_page: Optional. The number of results to return per page.</p>
<p>page: Optional. The page number to be returned.</p>
<p>Editing an account:<br>
To edit an account, you need to open a window with the connection_url. After an account is updated, a notification is sent back to the parent window.</p>

**Success Response:**

{
> "accounts": [
> > {
> > > <p>"sender_type": "bloggerv3",</p>
> > > <p>"id": 615497,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "newsocialcloudtest",</p>
> > > <p>"service_image": "<img src='http://snd-assets.s3.amazonaws.com/icons/somicro/blogger.png' />",</p>
> > > <p>"service_description": "Blogger and Blogspot",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=11809&account_id=615497",</p>
> > > <p>"service_id": 11809,</p>
> > > <p>"description": "newsocialcloudtest"</p>

> > },
> > {
> > > <p>"sender_type": "blogspot",</p>
> > > <p>"id": 605429,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "info@newsocialcloud.com",</p>
> > > <p>"service_image": "<img src='http://snd-assets.s3.amazonaws.com/icons/somicro/blogger.png' />",</p>
> > > <p>"service_description": "Blogger and Blogspot",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=1189&account_id=60529",</p>
> > > <p>"service_id": 11809,</p>
> > > <p>"description": "<a href='http://newsocialcloud.blogspot.com'>http://newsocialcloud.blogspot.com</a>"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 740644,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "newsocialcloud Main3 Test",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=740644",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "newsocialcloud Main3 Test"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 514918,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "newsocialcloud Test",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=514918",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "newsocialcloud Test"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 573305,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "mobisquad",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=573305",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "Mobisquad"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 573307,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "entrust bankcard",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=573307",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "Entrust Bankcard"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 597642,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "apple",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=597642",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "Apple"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 597643,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "android",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=597643",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "Android"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 728022,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "london stock exchange",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=728022",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "London Stock Exchange"</p>

> > },
> > {
> > > <p>"sender_type": "brandmonitor",</p>
> > > <p>"id": 519402,</p>
> > > <p>"avatar": null,</p>
> > > <p>"username": "skin by lovely",</p>
> > > <p>"service_image": "<img src='https://d3u44nfepqqjcg.cloudfront.net/images/comment-16x16.png' />",</p>
> > > <p>"service_description": "Brand and Keyword Monitoring",</p>
> > > <p>"connection_url": "/api/v2/connect?service_id=53&account_id=519402",</p>
> > > <p>"service_id": 53,</p>
> > > <p>"description": "Skin by Lovely"</p>

> > }

> ]
}