<h1>
<a></a>
NewSocialCloud API Documentation<a href='#NewSocialCloud_API_Documentation'></a>
</h1>
<p>The NewSocialCloud API enables developers to interact with the NewSocialCloud web site programmatically via simple HTTP requests.<br>
NewSocialCloud exposes its data via a <a href='http://en.wikipedia.org/wiki/Representational_State_Transfer'>REST-based Application Programming Interface (API)</a>. This document is the official reference for that functionality. </p>
<p>To get started, you'll need a NewSocialCloud user account and Application ID. Sign up at: <a href='http://login.newsocialcloud.com'><a href='http://login.newsocialcloud.com'>http://login.newsocialcloud.com</a></a></p>
<p>Once you've signed up for a NewSocialCloud account, you can request an Application ID at: <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>You'll need to use the <tt>application_id</tt> in all requests you make to the API.</p>
<h2>
<a></a>Authentication<a href='#Authentication'></a>
</h2>
<p>All API endpoints require that authentication credentials be supplied through basic HTTP authentication. </p>
<p>You can authenticate using your NewSocialCloud username and password. If you'd prefer not to use your password, you can use your remote API key, which can be found at <a href='http://login.newsocialcloud.com'><a href='http://login.newsocialcloud.com'>http://login.newsocialcloud.com</a></a></p>
<h2>
<a></a>REST API<a href='#REST_API'></a>
</h2>
<h3>
<a></a>Profile<a href='#Profile'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/Profile'>Retrieve user profile</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/SingleSignOn'>Single sign on</a> </li>
<li><a href='http://newsocialcloud.com/docs/Login%20for%20Developer%20Apps_NSC.pdf'>Single sign on (using access key)</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreateUserField'>Set custom fields for a user</a> </li>
</ul>
<h3>
<a></a>Services<a href='#Services'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/Services'>Retrieve services</a> </li>
</ul>
<h3>
<a></a>Messages<a href='#Messages'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetMessages'>Retrieve messages</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetMessage'>Retrieve a message</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/MessageRecipients'>Retrieve message recipients</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreateMessage'>Create a message</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/DeleteMessage'>Delete a message</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/UpdateMessage'>Update a message</a> </li>
</ul>
<h3>
<a></a>Media<a href='#Media'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/AttachMedia'>Add media to a message</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/DeleteMedia'>Remove media from a message</a> </li>
</ul>
<h3>
<a></a>Mentions<a href='#Mentions'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetMentionTerms'>Retrieve mention terms</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetMentions'>Retrieve mentions</a> </li>
</ul>
<h3>
<a></a>Social Inbox<a href='#Social_Inbox'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetPriorityPosts'>Retrieve priority posts</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreatePriorityPostReply'>Reply to a priority post</a> </li>
</ul>
<h3>
<a></a>Contacts<a href='#Contacts'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetContacts'>Retrieve contacts</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetContact'>Retrieve a contact</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreateContact'>Create a contact</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/UpdateContact'>Update a contact</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/DeleteContact'>Delete a contact</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreateContactField'>Set a custom field for a contact</a> </li>
</ul>
<h3>
<a></a>Groups/Lists<a href='#Groups/Lists'></a>
</h3>
<ul>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/GetLists'>Retrieve all lists belonging to a user</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/GetList'>Retrieve a specific list</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/GetListItems'>Retrieve items within a list</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/AddToList'>Add an item to a list</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/RemoveFromList'>Remove an item from a list</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/CreateList'>Create a new list</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/UpdateList'>Update a list</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/DeleteList'>Delete a list</a> </li>
</ul>
<h3>
<a></a>Url Shortening<a href='#Url_Shortening'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/ShortenUrl'>Shorten a url</a> </li>
</ul>
<h3>
<a></a>Reports<a href='#Reports'></a>
</h3>
<h4>
<a></a>Message Reports<a href='#Message_Reports'></a>
</h4>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetMessageReports'>Retrieve message reports</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetMessageReport'>Retrieve a message report</a> </li>
</ul>
<h4>
<a></a>Account Reports<a href='#Account_Reports'></a>
</h4>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetAccountDetails'>Retrieve account details</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetAccountPeriods'>Retrieve valid account reporting periods</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetAccountStatistics'>Retrieve account statistics</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetAccountPosts'>Retrieve account posts and post responses/comments</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/ExportReport'>Download a full HTML/CSV report</a> </li>
</ul>
<h3>
<a></a>White Labels<a href='#White_Labels'></a>
</h3>
<ul>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetProfiles'>Retrieve user profiles belonging to agency/white label</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/SingleSignOn'>Single sign on</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreateWhiteLabelUser'>Create a new user</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/UpdateUser'>Update a user</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/CreateUserField'>Update custom fields for a user</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/GetAccountTypes'>Get Account Types/Plans (for older white label sites)</a> </li>
</ul>
<h2>
<a></a>Subscribing To Realtime Events<a href='#Subscribing_To_Realtime_Events'></a>
</h2>
<p>Using these API methods, you can configure NewSocialCloud to send an update to a URL of your choice when specific events occur for users.<br>
<ul>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/CreateAppSubscription'>Create one or more event subscriptions for your application</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/SubscribeUserToEvent'>Subscribe to updates for specific users</a> </li>
<li><a href='http://code.google.com/p/newsocialcloud/wiki/UnsubscribeUserFromEvent'>Unsubscribe from updates for specific users</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/DeleteAppSubscription'>Delete an event subscription for your application</a> </li>
<li><a href='https://code.google.com/p/newsocialcloud/wiki/GetAppSubscriptions'>List all event subscriptions for your application.</a> </li>
</ul>
</p>