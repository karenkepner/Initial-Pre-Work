# TG-Pre-Work

### While we do want our developers to work smarter, not harder, please refrain from plagiarizing.  It is completely fine to reword information you have gleaned from internet sources, however, please be prepared to redo the work should you submit a directly copied/pasted answer.  If you must copy/paste, cite your sources (this citation doesn't need to be fancy - just state directly where you found the information or provide a link).  Additionally, some of the questions below are tricky.  The answers were not necessarily covered in the reading we assigned.  They are not intended to be straightforward because we expect you to do some research to discover the answers to the best of your ability.  If you cannot find an answer, explain what you do know and what you are stuck on.  

## When we hit https://www.techtonic.com/ what happens? Don’t focus too much on architecture (Monolithic, SOA, Microservices, etc.). Try to focus more on how the web functions in general terms/steps.

When you click on a link, the current page registers what element you clicked on, in this case a URL. Then the URL (uniform resource locator) information is sent to the DNS (domain name server). The DNS looks up the IP (internet protocol) address. Then the browser opens a TCP (transmission control protocol) connection to the HTTP or HTTPS server. The server finds the IP address and retrieves the HTML document to be rendered by your browser. The browser renders the HTML file and you can see the Techtonic website in your browser.

## From start to finish, how does data reach you to be rendered in the browser?

After you request data from a website the URL information is sent to the DNS. The DNS looks up the actual IP address. The server takes that IP address and retrieves the HTML component files from that IP. The files and assets are then sent to your computer as an HTTP response. The browser parses the HTML and builds the DOM (document object model) tree. This repeats until all the data is transferred to the browser. Then the CSS is parsed and applied to the DOM. Next the JavaScript is parsed and executed. The page then renders in your browser.

## What code is rendered in the browser?

HTML code is rendered in the browser. Then CSS and Javascript are added for styling and interactivity.

## What is the server-side code’s main function?

The server-side code's main function is to deliver a dynamic customized experience for each user. It is also used to limit client access to server data and proprietary code.

## What is the client-side code’s main function?

Client side code runs on the client's computer and its main function is to display information to the user.

## What is runtime?

Runtime is the time that elapses while a computer program is running.

## How many instances of the client-side assets (HTML, CSS, JS, Images, etc.) are created?

An instance of the client-side assets is created each time a user requests the set of assets. When a client opens a website, they create one instance of the assets on their local computer.

## How many instances of the server-side code are available at any given time?

The level of service the asset owner has paid for from the hosting company will determine how many instances of the server-side code are available at any given time.

## How many instances of the databases connected to the server application are created?

Many instances of the database can be connected to the server application. There are limits to the amount of instances of a database that can be created but it appears to depend on what vendor designed the database product.
