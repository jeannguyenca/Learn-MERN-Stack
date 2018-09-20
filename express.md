# Understand Express.js by comparing with restaurant operation

Express is a popular framework run on top of Node.js. Node is a platform for building server-side application using JavaScript and Express is built based on Node. It adds more features so that writing a server is easier. There are four stages of an Express server: require statements, middleware, routing and listener or starting the server.

A very interesting metaphor of how Express work is presented by Kevin(*). He described Express works like a restaurant manager that help you with creating and managing a place to run smoothly and serve customers.

![Express vs Restaurant](https://cdn-images-1.medium.com/max/2000/1*gWVqib20b1NNzB6vrM-U6w.png)

## Require statements
In this part, you are a restaurant owner, who is looking for a manager. You specify Express as the manager, which has expertise in managing a restaurant. Like any NPM package, you need to install the express module and use require statement to load it. You also need this:
        ```
        const app = express()
        ```
.A variable need to be defined to hold Express app because it is not a part of Node.

## Middleware
The next step is defining regular routines and rules in the restaurant, somethings like ID checking if anyone want to sit in the bar or order alcohol. Likewise, you would need to check requests to the server in certain areas like account and password before processing to the next step. 

## Routing
After validating the customers, we will seat them. We need to make sure that our restaurant serves customers’ requests. For example, some customers want to sit indoor and some wants to sit outside. In Express, this is done by route. Routes allow specific actions based on the path. There are four options: GET, POST, PUT and DELETE. After receiving a request, the server process it and send a respond back to the customer.

## Listening
In the first three stages, we have hired a manager, defining how to check-in and seating, now we need to finally open the restaurant. We need a specific place to open it. Use a port is as specific address for a server just like a restaurant’s address. 


### References
(*)Kevin K. Going out to eat and understanding the basics of Express.js. Retrieved September 19, 2018, from [https://medium.freecodecamp.org/going-out-to-eat-and-understanding-the-basics-of-express-js-f034a029fb66]( https://medium.freecodecamp.org/going-out-to-eat-and-understanding-the-basics-of-express-js-f034a029fb66)

### [Go back home](index.md)
### [See my next post](prototype-idea.md)
