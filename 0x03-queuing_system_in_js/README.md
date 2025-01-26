# 0x03. Queuing System in JS

A queuing system refers to a software architecture that allows you to manage and process tasks or jobs in an organized and asynchronous manner. It involves the use of queues, which are data structures that store tasks or jobs until they can be processed by one or more worker processes. These tasks can range from background jobs, data processing, to asynchronous operations like sending emails or handling user requests.

Queuing systems provide a way to offload time-consuming or resource-intensive tasks from the main application thread, ensuring that the application remains responsive and efficient. These systems often offer features like job prioritization, retries, delays, and monitoring tools. They are particularly useful in scenarios where tasks need to be executed independently of the main application flow or where tasks may be time-consuming and should not block other operations.

Kue package is a popular Node.js package for creating and managing background jobs, tasks, and queues. It's commonly used for managing asynchronous tasks in web applications, such as sending emails, processing data, generating reports, and other time-consuming processes that should not block the main thread of your application.

Kue provides a simple and powerful API for creating, scheduling, and processing jobs.

By utilizing queuing systems in JavaScript, developers can create more robust and scalable applications that handle various types of workloads effectively, enhancing the overall performance and user experience.

### Learning Objectives

- How to run a Redis server on your machine
- How to run simple operations with the Redis client
- How to use a Redis client with Node JS for basic operations
- How to store hash values in Redis
- How to deal with async operations with Redis
- How to use Kue as a queue system
- How to build a basic Express app interacting with a Redis server
- How to the build a basic Express app interacting with a Redis server and queue
