To retrieve a list of the mentions for each day in the last two weeks for a one or more mentions. Includes a breakdown of negative and positive sentiment. To get neutral sentiment subtract negative and positive sentiment from the total. Make a GET call using basic authentication.

**URL:**

http://login.newsocialcloud.com/api/v2/buzzOverTime

**HTTP Methods:**

GET

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>account_id: One or more mention terms ID, retrieved using the GetMentionTerms call. Can have more than one mention by separating the mentions by commas.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
"result" : [
> {
> > "negative" : "18",
> > "created\_date\_str" : "28 May",
> > "created\_date" : "2014-05-28",
> > "positive" : "24",
> > "total" : "136"

> },
> {
> > "negative" : "26",
> > "created\_date\_str" : "27 May",
> > "created\_date" : "2014-05-27",
> > "positive" : "61",
> > "total" : "407"

> },
> {
> > "negative" : "14",
> > "created\_date\_str" : "26 May",
> > "created\_date" : "2014-05-26",
> > "positive" : "57",
> > "total" : "339"

> },
> {
> > "negative" : "31",
> > "created\_date\_str" : "25 May",
> > "created\_date" : "2014-05-25",
> > "positive" : "58",
> > "total" : "307"

> },
> {
> > "negative" : "30",
> > "created\_date\_str" : "24 May",
> > "created\_date" : "2014-05-24",
> > "positive" : "43",
> > "total" : "262"

> },
> {
> > "negative" : "20",
> > "created\_date\_str" : "23 May",
> > "created\_date" : "2014-05-23",
> > "positive" : "55",
> > "total" : "354"

> },
> {
> > "negative" : "39",
> > "created\_date\_str" : "22 May",
> > "created\_date" : "2014-05-22",
> > "positive" : "97",
> > "total" : "452"

> },
> {
> > "negative" : "34",
> > "created\_date\_str" : "21 May",
> > "created\_date" : "2014-05-21",
> > "positive" : "88",
> > "total" : "458"

> },
> {
> > "negative" : "16",
> > "created\_date\_str" : "20 May",
> > "created\_date" : "2014-05-20",
> > "positive" : "119",
> > "total" : "404"

> },
> {
> > "negative" : "51",
> > "created\_date\_str" : "19 May",
> > "created\_date" : "2014-05-19",
> > "positive" : "53",
> > "total" : "413"

> },
> {
> > "negative" : "17",
> > "created\_date\_str" : "18 May",
> > "created\_date" : "2014-05-18",
> > "positive" : "54",
> > "total" : "315"

> },
> {
> > "negative" : "22",
> > "created\_date\_str" : "17 May",
> > "created\_date" : "2014-05-17",
> > "positive" : "61",
> > "total" : "350"

> },
> {
> > "negative" : "20",
> > "created\_date\_str" : "16 May",
> > "created\_date" : "2014-05-16",
> > "positive" : "71",
> > "total" : "375"

> },
> {
> > "negative" : "70",
> > "created\_date\_str" : "15 May",
> > "created\_date" : "2014-05-15",
> > "positive" : "106",
> > "total" : "768"

> }
]
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

