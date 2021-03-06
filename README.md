# Smartphone Analysis On Tiki Website
### :wink: Description :wink:
Using Python to get data from API on Tiki, the data is about the Smartphone category, then update data to Google Sheet.<br>
Using Google Data Studio tool connect to Google Sheet and visulize data into reports.<br>
#
### :diamond_shape_with_a_dot_inside: Tech :diamond_shape_with_a_dot_inside:
- Language: Python
- Libs: pandas, spread, google.oauth2, googleapiclient.discovery, requests, json.
- Tools: Data Studio, Google Sheet, Postman.
#
### Step :one: Create service account on GG Cloud Api & Dowload key
- Access to console.developers.google.com (Google Cloud Api)
- Create a project -> click on that project -> Getting Started
- Choose Explore and enable APIs -> gg sheet api -> enable it-> credentials -> Manage service accounts
- Choose Create service account -> name it -> Basic-Editor right -> dowload key json file to the same folder with your code
### Step :two: API Authentication from Tiki website 
API on Tiki website need authentication, so we need more steps than just copy-paste the link to our code.
- After tracking network on Tiki page, copy cUrl -> import by raw text to Postman (dowload it if you don't have https://www.postman.com/downloads/)
- Paste the link API to Postman try to send -> click Code button on the right hand -> choose generate code with Python or any language on left hand tab
- Copy that code to your code (my code on my repo)
### Step :three: Code by Python
- Take a look on my code in my repo above with all the comments from there.
### Step :four: Visualize data with Google Data Studio
- The link reports here:link: https://datastudio.google.com/reporting/fd634185-7ed3-4a93-85f4-606039539623
- The link Google Sheet here :link: https://docs.google.com/spreadsheets/d/1d8v_I28CqxCnsKAgLr6AM5RAlPbI6qD8A4_-cRy9V5Q/edit?usp=sharing
