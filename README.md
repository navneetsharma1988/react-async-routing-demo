# react-async-routing-demo
This is a sample app to implement  asynchronous routing with Suspense, defer, and Await

We are using React router v6 for this demo and the code is in the client folder. The api folder is just a dummy server to serve the data. 

We are also using React suspense to show a fallback component, which is not a loader but skeleton of the actual component to offer the best UX as per inudstry standards, while the data is being fetched


## The problem -
Please go through this article on React router document - https://reactrouter.com/en/main/guides/deferred

## Solution -


## How to run the app
1. Clone the repo
2. Go inside the api folder and run `npm install`
3. Go inside the client folder and run `npm install`
4. Run `npm run dev` in both the folders
