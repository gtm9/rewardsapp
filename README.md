# Steps to clone and run locally

> git clone https://github.com/gtm9/rewardsapp.git

> cd local-json-react

> local-json-react> npm i

> local-json-react> npm start

# Used a local json file for the list of customers
  {
    "id": 1,
    "name": "NAME",
    "transactions": [<list of transactions for 3 months>]
  },

  #The app design
  I have utilized a json file for the transaction data. It contains the appropriate information required to demonstrate a rewards application to be simple and functional.
  I implemented a rewards.js file to showcase the reusable component developemnt startegy widely prevalent in reactjs. The customer data can be passed down as props to any created component and rendered as demanded. The data.json is accessed using a simple fetch library axios, which can be used in case of making actual API calls aswell.
  
  #Future imporvements
  1. Depeneding on the APIs, which send in the individual customer data, rewards can be calculated as required by this app.
  2. If the raw data has Date Time information, the code can be modified to add up all the transactions for each month and then feed it to the same app to calculate for every 3 months.
