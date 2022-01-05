# react-mongodb-graphQL-sample
sample mongodb graphql with react

This is a sample based on existing repo, and blog created by Nikhil
Full Stack project with React, GraphQL, MondoDB, Apollo.

https://github.com/nikhilknoldus/fullstack-react-apollo-graphql-mongodb

i have made my local changes that connects to my local mongo db instead of cloud based.

Blog followed was:
https://betterprogramming.pub/full-stack-react-graphql-mongodb-apollo-building-an-app-cb1eb647c73a

We will build two sections in this app: server and client.
On the server side, we will be building a GraphQL API with three queries and one GraphQL mutation that will interact with our hosted MongoDB database for persistency. 

On the client side, we will be utilizing React and Apollo to interact with our GraphQL API and GraphQL queries.

server side code development:
1. npm init -y
2. npm install express express-graphql mongoose
3. one can install nodemon as dev dependency to quickly start working with the changes you make. To install as dev dependency i used 
npm install --save-dev nodemon

This will add a line :
"devDependencies": {
    "nodemon": "^2.0.15"
  }
  
  to generate random data of persons, i used generatedata.com downloaded json file from the random data, and imported straight in to my local mongodb collection people.
  quickstart with people and extract data as json for this sample data.
  
  To test your graphql on server restpoint to check if it is working, use http://localhost:3001/person
  
  there are tests for both mutation and query.
  
  Our client will be on port 3000, simply trigger http://localhost:3000 you get the data directly from the mongodb endpoint magically.
  
  

