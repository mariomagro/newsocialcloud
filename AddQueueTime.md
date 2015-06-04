To add a new time to a given NewSocialCloud SmartQueue, make a POST call using basic authentication.


**URL:**

http://login.newsocialcloud.com/api/v2/queue_times.json


**HTTP Methods:**

POST


**Parameters:**

application\_id: Your application ID from http://newsocialcloud.com/developers.
queue\_id: The id belonging to the SmartQueue.
weekday: The index of the weekday. 0 = Monday, 6 = Sunday
hour: The hour (military time format).
minute: The minute.

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**
{
> "queue\_times": [
> > {
> > > "minute": 0,
> > > "hour": 12,
> > > "id": 284406,
> > > "weekday": 0

> > },
> > {
> > > "minute": 0,
> > > "hour": 12,
> > > "id": 284407,
> > > "weekday": 2

> > }

> ],
> "can\_repeat": 0,
> "queue\_name": "ignore",
> "id": 9004,
> "user\_id": 5131,
> "auto\_detect": 0
> }