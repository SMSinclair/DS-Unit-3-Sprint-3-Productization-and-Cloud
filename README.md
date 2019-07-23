# DS-Unit-3-Sprint-3-Productization-and-Cloud
Building a real deployed full-stack application, backed by Data Science
--------------------

*Note* - assignments this week are all steps in a larger week-long project. They
are to be worked on in a repo you make with your own account, as instructed in
the first day. You should still fork this repo, and open a PR where you add a
`work_notes.md` file that includes a link to your project repo. You should then
update `work_notes.md` each day with the following:

- What went well (in the context of working on the assignment) today?
- What was particularly interesting or surprising about the topic(s) today?
- What was the most challenging part of the
 work today, and why?

Class notes

weatherbit.io/open-notify
- import requests and json
- create variable and assign requests.get()
- response.status_code
  200 - A OK
  300 - redirected to a different endpoint
  401 - authentication error
  400 - bad request
  403 - access is forbidden
  404 - resource not found
- can set up parameters as a simple dictionary


weather
- import datetime and pytz as well
utc_now = pytz.utc.localize(datetime.datetime.utcnow())
currentDT = utc_now.astimezone(ptyz.timezone("America/New York")
Hour = currentDT.hour #same for month and date
-try and throw it in a json linter, better format

bring notebook with simple model and ~4 features (e.g. iris)