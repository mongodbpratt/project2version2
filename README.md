PropertyBookProject
-  by: Will Pratt
- link: project2version2.heroku.com
- Given the DOD's desire to account for almost every dollar of government owned property and junior leaders requirement to execute that accountability, this app is meant to enable those junior leaders to access and edit their property from thair phone and not carry around a phone book sized binder of property records.
---

Technology Used:
-   Mongoose, Node, mongoDB, EJS, Express, HTML, CSS
---

Challenges:
-   Authorization was my biggest blocker. I tried to build that before the actual MVP and took up a lot of time that I should have used to build that or more functionality later.
---

Model
- name: String
- serialnumber: String
- picture: String
- location: String
- primaryhandreceiptholder: String  
- subhandreceiptholder: String
- quantity: String
---

Next Steps
- Add Authorization
- Add ability to add photos and geotags from you phone
- Add abilty to filter and sort by subhandreceipt holder
