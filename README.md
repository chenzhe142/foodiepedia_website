A website based on Google App Engine, webapp2 and Jinja2.
Foodiepedia
===================
http://foodie-pedia.appspot.com/



2014.12.30
- Testing user authentication function.

2015.1.3
- Finish building user authentication system.

2015.1.4
- Begin writing item post and search function 
- Modify UI design

2015.1.4
- 'Find' page now can do a simple search on Datastore Item. Modification need to be done.
- Available now: user can signup, login, and then post new items when user is maintaining login status.
- Homepage UI and coloring need re-design.

2015.1.5
- When doing search on 'Find' page, if there's a result, redirect to item page. If empty input, redirect to homepage.
  (Upcoming modification: if no result or empty input, show popular item page.)
- Wrote part of the CSS code of show_item.html page, using flat design. Color will need to be re-considered.
- Fixed small bugs of BaseHandler.dispatch, stop showing 'None' on the bottom of every page.
- In home page, I added links for every item's name, and it can jump to the item page.
  (There's a small bug appears when item name contains 'whitespace', I need to figure it out on linking and redirecting.)

2015.1.6
- Fixed: links contain 'whitespace', replacing whitespace with '-'. 

