# Learn About Application Programming Interfaces

## Defining Interface

- Interface is just an abstraction that hides the implementation detail
- These interfaces might become so useful that they need a GUI (Graphical User Interface)
- Developers of interfaces potentially also need to use other interfaces
- Ex: Media player
  - Requires the mediaPlayer API from the operating system
  - Buttons API that controls what happens when it is clicked

## Defining APIs

- API is used for the application programmer
- API is a contract of sorts, and used to make your life easier
- Nowadays, the term API is almost entirely used to talk about web-based APIs
- However, there are also other different types of APIs
  - Ex: Every programming language has some method for converting a string to uppercase
  - Ex: Different web browsers, but your scripts run in all of them. This works because each browser needs to implement a set of web APIs
- Most frameworks are larger interfaces for websites

## Remote APIs

- Remote APIs are ones that are executed locally on our machines
- Oftentimes, we don't have enough space locally to run everything
  - Ex: Playing songs from an interface
  - APIs remove limitation on your device and takes that computation to somewhere else
- Writing Remote APIs is a very real challenge; however, overtime, REST APIs eventually won out all of them, REST stands for Representational State Transfer
- When APIs use the REST style, they are called Restful APIs

## How the Web Works

- On a computer, you open up a web broswer, and this web browser is a client, which connects to the server
- You do this by connecting to the server through an address, a Universal Resource Locator (URL), or a superset term Universal Resource Identifier (URI)
- The URL has a schema portion
  - Ex: http
    - Hypertext Transfer Protocol
    - The browser creates an HTTP request for you along with the URI and a specific HTTP verb (get, post, etc.)
    - The server then sends the response back, and the most important part of the response is the body, which contains HTML, or Hyper Text Markup Language
    - Hyper Text is text that can link to other language
    - HTTP is a Stateless protocol, once the request recevies a response, everything is over
    - To include more information:
      - You can pass in query string parameters, the information after the question mark
      - You can also pass with specific key and value pairs, called headers. Both request and responses have headers, and they're used to further communicate information
        - This technique allows for caching
- A protocol is often likened to a contract, a little lower level than an API, or the expectations of how we communication

  - I tell you how you should respond to my specific request

- Checkpoint [YouTube](https://youtu.be/GZvSYJDk-us?t=1323)
