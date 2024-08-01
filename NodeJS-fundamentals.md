## About NodeJS
1. free and open source
2. javascript runtime environment
3. event driven
4. blocking and non-blocking i/o model
5. uses JS and C/C++
6. i/o operation (network/file system)
7. runs on google chrome v8 engine

## Use cases of nodejs
1. less CPU intensive tasks like i/o, network calls, fetching data etc because of single threaded nature
2. used in real-time applications - like chatapps etc
3. single page applications - like bookmyshow etc
4. IoT apps
5. data streaming apps like hotstar, jio cinema etc

## advantages
1. scalable
2. consumes less memory
3. high performance

## working of any web application
client - server model with request response communication model along with a database to store the data

## nodejs architecture
1. Asynchronous model resembling event-based approach of js
2. Non-blocking i/o opertions

- Working: 
1. 1st the request comes in the app and goes to node api
2. these are queued in the `event queue`.
3. the `event loop` selects the non-blocking operation and executes them via `worker thread` and again after executing comes back to the event queue and displays the output on the app. 

- components of nodejs
1. requests
2. node.js server
3. event queue
4. event loop
5. thread pool(worker threads)
6. external resources(database interaction)

## JavaScript runtime environment
1. js library: consists of some low level api's for interacting with the operating system.
2. c/c++: execute tasks fast and interact with os
3. v8 | libuv(manage threads) | zlib : different components for doing various tasks.
