To retrieve a list of the user's mentions for a given term, make a GET call using basic authentication.


**URL:**

http://newsocialcloud.com/api/v1/mentions.format


**Formats:**

Replace format with either xml or json


**HTTP Methods:**

GET


**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>term_id: Optional. The mention term, retrieved using the GetMentionTerms call. If no term_id is provided, mentions for all terms will be returned.</p>
<p>sentiment: Optional. Retrieve mentions with neutral, positive or negative sentiment. Valid values are 0, 1 or -1.</p>
<p>type: Optional. The type of mentions to retrieve. Valid values are blogs, microblogs, bookmarks, comments, events, images, news, videos, audio, questions, networks.</p>
<p>filter: Optional. Filter mentions by keyword.</p>
<p>per_page: Optional. The number of mentions to return per page.</p>
<p>page: Optional. The page number to return.</p>


**Authentication:**

Basic authentication with username and password or remote API key belonging to the newsocialcloud user.


**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;mentions type="array"&gt;


> 

&lt;mention&gt;


> > 

&lt;content&gt;


> > > <a href='\http://shine.yahoo.com/photos/<b><b>DISNEY</b></b>-princesses-were-real-sequel-slideshow/snow-white-photo-2298504-190600838.html\'><a href='http://shine.yahoo.com/photos/'>http://shine.yahoo.com/photos/</a><b><b>DISNEY</b></b>-princesses-were-real-sequel-slideshow/snow-white-photo-2298504-190600838.html</a><br /><br /> <a href='http://shine.yahoo.com/photos/<b><b>DISNEY</b></b>-princesses-were-real-sequel-slideshow/snow-white-photo-2298504-190600838.html'><b>If <b>Disney</b> Princesses Were Real: The Sequel</b></a><br />View the If <b>Disney</b> Princesses Were Real: The Sequel photo gallery on Yahoo! Shine. Find more news related pictures in our photo galleries.<br /><br /> <a href='https://plus.google.com/104739022522671686030/posts/WsDxbQFLW5z'><img src='http://images0-focus-opensocial.googleusercontent.com/gadgets/proxy?container=focus&gadget=a&resize_h=100&url=http%3A%2F%2Fl.yimg.com%2Fbt%2Fapi%2Fres%2F1.2%2F.rrudzwc6_4_NErfcheVrQ--%2FYXBwaWQ9eW5ld3M7Zmk9ZmlsbDtoPTE1MDtxPTg1O3c9MTUw%2Fhttp%3A%2F%2Fmedia.zenfs.com%2Fen-US%2Fblogs%2Fpartner%2F2298504.0.cf.png' /></a>

> > 

&lt;/content&gt;


> > 

&lt;created-at-client type="datetime"&gt;

2012-03-22T10:12:53Z

&lt;/created-at-client&gt;


> > 

&lt;description&gt;


> > > <a href='\http://shine.yahoo.com/photos/<b><b>DISNEY</b></b>-princesses-were-real-sequel-slideshow/snow-white-photo-2298504-190600838.html\'><a href='http://shine.yahoo.com/photos/'>http://shine.yahoo.com/photos/</a><b><b>DISNEY</b></b>-princesses-were-real-sequel-slideshow/snow-white-photo-2298504-190600838.html</a>

> > 

&lt;/description&gt;


> > 

&lt;domain&gt;

Google+

&lt;/domain&gt;


> > 

&lt;favicon&gt;


> > > http://www.google.com/s2/favicons?domain=plus.google.com

> > 

&lt;/favicon&gt;


> > 

&lt;link&gt;


> > > https://plus.google.com/104739022522671686030/posts/WsDxbQFLW5z

> > 

&lt;/link&gt;


> > 

&lt;sentiment type="integer"&gt;

0

&lt;/sentiment&gt;


> > 

&lt;source&gt;

google+

&lt;/source&gt;


> > 

&lt;title&gt;


> > > Reshared post from Marquis Crumpton\n \n\nhttp://shine.yahoo.com/photos/disney-princesses-were-real-...

> > 

&lt;/title&gt;


> > 

&lt;userimage&gt;


> > > https://lh4.googleusercontent.com/-ndWnrdb1jIo/AAAAAAAAAAI/AAAAAAAAAAA/GGnra1PYJIg/photo.jpg?sz=50

> > 

&lt;/userimage&gt;


> > 

&lt;userlink&gt;

https://plus.google.com/104739022522671686030

&lt;/userlink&gt;


> > 

&lt;username&gt;

Jeremy Zano

&lt;/username&gt;


> > 

&lt;type&gt;

networks

&lt;/type&gt;


> > 

&lt;term&gt;

Disney

&lt;/term&gt;



> 

&lt;/mention&gt;


> 

&lt;mention&gt;


> > 

&lt;content/&gt;


> > 

&lt;created-at-client type="datetime"&gt;

2012-03-22T10:11:31Z

&lt;/created-at-client&gt;


> > 

&lt;description/&gt;


> > 

&lt;domain&gt;

facebook.com

&lt;/domain&gt;


> > 

&lt;favicon&gt;


> > > http://www.google.com/s2/favicons?domain=facebook.com

> > 

&lt;/favicon&gt;


> > 

&lt;link&gt;


> > > http://www.facebook.com/100001126359005/posts/325545447502443

> > 

&lt;/link&gt;


> > 

&lt;sentiment type="integer"&gt;

0

&lt;/sentiment&gt;


> > 

&lt;source&gt;

facebook

&lt;/source&gt;


> > 

&lt;title&gt;


> > > ?? DISNEY EYES LENS??? DPTKAN NEW ARRIVAL LENS HARI INI JUGA... Buy 1-RM38~FREE POSTAGE Buy 2-RM70~FREE POSTAGE Buy 3-RM90~FREE POSTAGE Buy 4-RM130FREE POSTAGE Buy 5-RM150FREE POSTAGE --->IF NAK TAMBAH LENS CASE,ADD RM1/PCS

> > 

&lt;/title&gt;


> > 

&lt;userimage&gt;

http://graph.facebook.com/100001126359005/picture

&lt;/userimage&gt;


> > 

&lt;userlink&gt;


> > > http://www.facebook.com/100001126359005/posts/325545447502443

> > 

&lt;/userlink&gt;


> > 

&lt;username&gt;

Asma Rozi

&lt;/username&gt;


> > 

&lt;type&gt;

networks

&lt;/type&gt;


> > 

&lt;term&gt;

Disney

&lt;/term&gt;



> 

&lt;/mention&gt;




&lt;/mentions&gt;




**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

