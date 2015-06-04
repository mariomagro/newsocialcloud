To create a support ticket on behalf of the authenticated user, make a POST request.

**URL:**

http://login.newsocialcloud.com/api/v2/support_ticket.json

**HTTP Methods:**

POST

**Parameters:**

<p>application_id: Your application id from <a href='http://newsocialcloud.com/developers.html'>http://newsocialcloud.com/developers.html</a></p>
<p>subject: This is the ticket title/subject.</p>
<p>message: This is the ticket description.</p>
<p>mode: Optional. Use test if in development or live to store tickets in the live support system.</p>

**Authentication:**

Basic authentication with username and password or remote API key belonging to the NewSocialCloud user.

**Success Response:**

{
> "ticket": {
> > "url": "https://mysite.zendesk.com/api/v2/tickets/8.json",
> > "id": 8,
> > "external\_id": null,
> > "via": {
> > > "channel": "api",
> > > "source": {
> > > > "from": {


> },
> "to": {

> },
> "rel": null
> }
> },
> "created\_at": "2013-10-29T17:07:39Z",
> "updated\_at": "2013-10-29T17:07:39Z",
> "type": null,
> "subject": "Hi",
> "description": "test",
> "priority": null,
> "status": "open",
> "recipient": null,
> "requester\_id": 527109896,
> "submitter\_id": 527109896,
> "assignee\_id": 521231896,
> "organization\_id": null,
> "group\_id": 21395086,
> "collaborator\_ids": [

> ],
> "forum\_topic\_id": null,
> "problem\_id": null,
> "has\_incidents": false,
> "due\_at": null,
> "tags": [

> ],
> "custom\_fields": [

> ],
> "satisfaction\_rating": null,
> "sharing\_agreement\_ids": [

> ],
> "fields": [

> ]
> },
> "audit": {
> > "id": 19529650186,
> > "ticket\_id": 8,
> > "created\_at": "2013-10-29T17:07:39Z",
> > "author\_id": 521231896,
> > "via": {
> > > "channel": "api",
> > > "source": {
> > > > "from": {


> },
> "to": {

> },
> "rel": null
> }
> },
> "metadata": {
> > "system": {
> > > "ip\_address": "174.129.96.109",
> > > "location": "Madrid, Ma, Spain",
> > > "latitude": XX.XXX,
> > > "longitude": -XX.XXX

> > },
> > "custom": {


> }
> },
> "events": [
> > {
> > > "id": 19529650206,
> > > "type": "Comment",
> > > "author\_id": 527109896,
> > > "body": "test",
> > > "html\_body": "
test

",

> "public": true,
> "trusted": true,
> "attachments": [

> ]
> },
> {
> > "id": 19529650216,
> > "type": "Create",
> > "value": "Hi",
> > "field\_name": "subject"

> },
> {
> > "id": 19529650226,
> > "type": "Create",
> > "value": "open",
> > "field\_name": "status"

> },
> {
> > "id": 19529650236,
> > "type": "Create",
> > "value": null,
> > "field\_name": "priority"

> },
> {
> > "id": 19529650246,
> > "type": "Create",
> > "value": null,
> > "field\_name": "type"

> },
> {
> > "id": 19529650256,
> > "type": "Create",
> > "value": "521231896",
> > "field\_name": "assignee\_id"

> },
> {
> > "id": 19529650266,
> > "type": "Create",
> > "value": "21395086",
> > "field\_name": "group\_id"

> },
> {
> > "id": 19529650276,
> > "type": "Create",
> > "value": "527109896",
> > "field\_name": "requester\_id"

> },
> {
> > "id": 19529650286,
> > "type": "Notification",
> > "via": {
> > > "channel": "rule",
> > > "source": {
> > > > "to": {


> },
> "from": {
> > "id": 40732486,
> > "title": "Notify requester of received request"

> },
> "rel": "trigger"
> }
> },
> "subject": "Request received: {{ticket.title}}",
> "body": "Your request ({{ticket.id}}) has been received and is being reviewed by our support staff.\n\nTo add additional comments, reply to this email.\n
{{ticket.comments\_formatted}}]",
> "recipients": [
> > 527109896

> ]
> }
> ]
> }
}