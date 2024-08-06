# Dishcover
This is our website

** Do not forget to update pip, flask and create the flask environment before running the application.

To run:
1. Download this code and unzip the files
2. Open a terminal into the `dishcover` directory
2. Run server.py with the command `python server.py` in the terminal
3. Go to `localhost:4000` in the browser

Explanation of Webpages and their URL's:
1. localhost:4000/ is the Home page
2. localhost:4000/createmission is the Create Missions page
3. localhost:4000/sentmission appears after you successfully submit your mission
4. localhost:4000/currentacceptedmission shows and accepted mission
5. localhost:4000/exampleofguide shows curated categories of local restaurants
6. localhost:4000/notifications is the Notifications page
8. localhost:4000/profile is the Profile page
9. localhost:4000/publishmission is the Publish Missions page
10. localhost:4000/sentmission shows the status of a sent mission
11. localhost:4000/sentmissionsupdated shows what updated sent missions would look like
12. localhost:4000/yourmissions is the page for Your Missions

Tools We Used:
- We used Figma, TeleportHQ, and PythonAnywhere as GUIs for coding the HTML and CSS pages.
- We also used GitHub, Git, VSCode, and Flask for implementing our static version.
- JavaScript was used for the image upload buttons to work

The Directory `Sample Images for Uploading` is just that: a sample collection of pictures to upload for the purposes of testing our create missions and publish missions forms.


Directory Tree:
dishcover/
├─ Sample Images for Uploading/ (images to use when testing uploading feature)
├─ static/
│  ├─ public/
│  │  ├─ external/ (All Dishcover app images)
|  |  ├─ restaurant_images/ (All images for restaurant_database.json)
|  ├─ user_mission_images/
|  |  ├─ create_user_mission_images/ (Images that users uploaded when creating missions)
|  |  ├─ publish_user_mission_images/ (Images that users uploaded when publishing missions)
│  ├─ ALL CSS FILES HERE
├─ templates/
│  ├─ ALL HTML FILES HERE
├─ .gitignore
├─ package.json
├─ README.md
├─ restaurant_database.json
├─ server.py
├─ create_missions_database.json (created when a mission is created)
├─ publish_missions_database.json (created when a finished mission is published)
