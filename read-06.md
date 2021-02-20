# Node, Express, and APIs

![node](imgs/Node-js-Logo.png)

**Node. js**

    - Node Is Built on Google Chrome’s V8 JavaScript Engine : This means that Node.js is a program we can use to execute JavaScript on our computers. In other words, it’s a JavaScript runtime.

    - You can check that Node is installed on your system by opening a terminal and typing node -v. If all has gone well, you should see something like v12.14.1 displayed. This is the current LTS version at the time of writing.

**Introducing npm, the JavaScript Package Manager**

    1- Installing a Package Globally :This will install the jshint package globally on your system. We can use it to lint the index.js

    2- Installing a Package Locally: We can also install packages locally to a project, as opposed to globally, on our system. Create a test folder and open a terminal in that directory.

    3- Working with the package.json File : If you open the package.json file, you’ll see lodash listed under the dependencies field. By specifying your project’s dependencies in this way, you allow any developer anywhere to clone your project and use npm to install whatever packages it needs to run.


**Are There Any Downsides?**

    The fact that Node runs in a single thread does impose some limitations.Some developers also dislike the callback-based style of coding that JavaScript imposes (so much so that there’s even a site dedicated to the horrors of writing asynchronous JavaScript). But with the arrival of native Promises, followed closely by async await, flow control in modern JavaScript has become easier than it ever was.


**What Are the Advantages of Node.js?**

- that your brain no longer needs to switch modes.

- Node’s big pluses is that it speaks JSON. JSON is probably the most important data exchange format on the Web, and the lingua franca for interacting with object databases (such as MongoDB).

- it makes other languages seem cumbersome.

# The End