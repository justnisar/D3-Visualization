### Requirements ###
- A webserver. (We used XAMMP server).
- Javascript enabled on browser.
- D3.js on server side.

### Installation ###

- Download and install XAMMP server.
- Go to XAMMP installation folder -> htdocs
- Copy paste the files.
- Go to your localserver (example: http://localhost:80/index.html)

You're all set!

#Issues#
- Experienced CORS issue due to reading CSV file from Chrome. 
- Since chrome blocks all unsecure access for local files through XMLHTTPRequests, I needed to adopt server way of handling requests.

#FUTURE SCOPE#
- Can be made even more dynamic by adding Animations.
- Dropdown can be a view and can be rendered when a "Change" event is emmitted.
- Maybe a custom url to read and parse the data