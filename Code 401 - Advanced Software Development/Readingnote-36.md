[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-36 Application State with Redux


### Review, Research, and Discussion

1- What are the advantages of storing tokens in “Cookies” vs “Local Storage”

   - If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
   - It's automatically sent in every HTTP request to your server.

2- Explain 3rd party cookies.

  - Third-party cookies are created by domains that are not the website (or domain) that you are visiting. These are usually used for online-advertising purposes and placed on a website through adding scripts or tags. A third-party cookie is accessible on any website that loads the third-party server's code

3- How do pixel tags work?

 - A tracking pixel (also called 1x1 pixel or pixel tag) is a graphic with dimensions of 1x1 pixels that is loaded when a user visits a webpage or opens an email. ... The tracking pixel URL is the memory location on the server. When the user visits a website, the image with the tag is loaded from this server.

###  Document the following Vocabulary Terms
### Term
- cookies
   - Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network. Specific cookies known as HTTP cookies are used to identify specific users and improve your web browsing experience.

- authorization
  - he HTTP Authorization request header contains the credentials to authenticate a user agent with a server, usually, but not necessarily, after the server has responded with a 401 Unauthorized status and the WWW-Authenticate header.

- access control
   - What is "Access Control"? In information security, Access Control is selective restriction of access to a resource. AccessControl.js ... defines act of accessing by "actions". provides an abstract layer between the application logic and the requested resource and action.

- conditional rendering

  - Conditional rendering is a term to describe the ability to render different user interface (UI) markup if a condition is true or false. In React, it allows us to render different elements or components based on a condition. This concept is applied often in the following scenarios: Rendering external data from an API.