To retrieve a list of the user's message reports, make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v1/message-reports.format

**Formats:**

Replace format with either xml or json

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>filter: Optional. Filter reports by keyword.</p>
<p>per_page: Optional. The number of messages to return per page.</p>
<p>page: Optional. The page number to return.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

<?xml version="1.0" encoding="UTF-8"?>


&lt;message-reports type="array"&gt;


> 

&lt;message-report&gt;


> > 

&lt;clientTime type="datetime"&gt;

2010-09-13T12:13:57Z

&lt;/clientTime&gt;


> > 

&lt;id type="integer"&gt;

1071280

&lt;/id&gt;


> > 

&lt;message-html&gt;

Squeak the baby killer whale was moved out of Clacton Pier because of storm damage... what was the year on the Lunchtime Rewind?

&lt;/message-html&gt;


> > 

&lt;message-text&gt;

Squeak the baby killer whale was moved out of Clacton Pier because of storm damage... what was the year on the Lunchtime Rewind?

&lt;/message-text&gt;


> > 

&lt;message-id type="integer"&gt;

1872924

&lt;/message-id&gt;


> > 

&lt;stat-chart&gt;

http://chart.apis.google.com/chart?chtt=Message Statistics&amp;chds=0,1&amp;chxl=0:|Comments|Recipients&amp;cht=bvs&amp;chd=t:1,1&amp;chs=350x160&amp;chco=1166BB|377EC6|5D97D1|83AFDC|A9C8E7|CFE0F1&amp;chbh=a&amp;chxt=x&amp;chdl=Comments (1)|Recipients (1)

&lt;/stat-chart&gt;


> > 

&lt;subject&gt;



&lt;/subject&gt;


> > 

&lt;score type="decimal"&gt;

1.0

&lt;/score&gt;


> > 

&lt;messages-photos type="array"/&gt;



> 

&lt;/message-report&gt;


> 

&lt;message-report&gt;


> > 

&lt;clientTime type="datetime"&gt;

2010-09-13T10:09:33Z

&lt;/clientTime&gt;


> > 

&lt;id type="integer"&gt;

1071002

&lt;/id&gt;


> > 

&lt;message-html&gt;

Hi, Joff here with Easy at 11 - a nice way to spend 10mins during a busy Monday! Do you have an 'easy' favourite song? Let me know!

&lt;/message-html&gt;


> > 

&lt;message-text&gt;

Hi, Joff here with Easy at 11 - a nice way to spend 10mins during a busy Monday! Do you have an 'easy' favourite song? Let me know!

&lt;/message-text&gt;


> > 

&lt;message-id type="integer"&gt;

1872588

&lt;/message-id&gt;


> > 

&lt;stat-chart&gt;

http://chart.apis.google.com/chart?chtt=Message Statistics&amp;chds=0,3&amp;chxl=0:|Comments|Recipients&amp;cht=bvs&amp;chd=t:3,1&amp;chs=350x160&amp;chco=1166BB|377EC6|5D97D1|83AFDC|A9C8E7|CFE0F1&amp;chbh=a&amp;chxt=x&amp;chdl=Comments (3)|Recipients (1)

&lt;/stat-chart&gt;


> > 

&lt;subject&gt;



&lt;/subject&gt;


> > 

&lt;score type="decimal"&gt;

3.0

&lt;/score&gt;


> > 

&lt;messages-photos type="array"/&gt;



> 

&lt;/message-report&gt;




&lt;/message-reports&gt;



**Error Response:**



&lt;error&gt;




&lt;type&gt;

InvalidUsernamePassword

&lt;/type&gt;




&lt;message&gt;

Username/password is invalid.

&lt;/message&gt;




&lt;/error&gt;

