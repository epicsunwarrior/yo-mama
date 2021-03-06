# Yo Momma Generator

![image](https://farm8.staticflickr.com/7055/6899344713_a3f7f44921.jpg)

[Attribution](https://www.flickr.com/photos/gammaman/6899344713/in/photolist-bvEWPc-6e3ddD-6VPfbU-b3QsG4-6be4Dm-59aqWm-6b9QvT-5Hn9TB-6b9Xpc-6bdhSs-6bdzqS-6be2Vm-6bdqNm-6be1cb-6be5c7-6b9iRc-6be49J-6b9PGg-6bdt8d-6bdVcN-6bdpP3-6b9NhD-6b97Av-6b9ftp-6b9Fmz-6b9SJV-6b9HFi-6b9cEx-6b96ZZ-6bdkEj-6bdr2W-6b9hYF-6bdjwS-6b9ecp-6b9M2r-6bdXX3-6be1PU-6b9eHZ-6b9GXB-6b9WRF-6b9rEX-6bdiF1-kDPp7-5iNYSG-5YZWBT-7m1cNx-5jxxLW-5jteQH-5jt8ep-5jt7AK)

##Scope
To capitalize on the viral fury of the underground 'Yo Momma' battle scene, you have been tasked with designing and creating a webapp to help users find the best 'Yo Momma' joke to help them to become victorious.

##Project Description
Your Manager has laid out the following requirements for the project: 

* Implement a mock API to retreive the jokes
* Allow users to interact with the application to get a new joke
* Implement the ability to convert the joke to a voice text

##Learning Objectives
By the end of this project the employee will be able to...

* Understand the difference between a GET and POST requests (HTTP Methods)
* Interpret the supplied API documentation and use the API for the application (APIs)
* Understand the role of the client and the role of the server (Client-Service Interaction)
* Understand how the client and the server interact (Client-Server Interaction)
* Analyze and interpret the supplied documentation to their project (Reading Comprehension)
* Ability to explain and discuss projects in terms of APIs and HTTP requests (Technical Vocabulary)

##References/Tools

* Get/Post Request: http://www.w3schools.com/tags/ref_httpmethods.asp
* API: http://money.howstuffworks.com/business-communications/how-to-leverage-an-api-for-conferencing1.htm
* Web Speech API Documentation: https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html
* Web Speech Overview: http://stiltsoft.com/blog/2013/05/google-chrome-how-to-use-the-web-speech-api/

##Instructions
You are given a stripped-down project to add the required functionality, which must be cloned into your own workspace.  And make sure to read the comments!

###1) API Creation

####Why do I need this:

As a developer, you will rely on components created by other people or other teams. One way to interact with other components is through a systematic interface - known as the API (Application Programming Interface).  An API provides a set of specific format for the interaction between the callee and the caller - such as specifying the required inputs, the expected outputs, and possible error cases.  Some APIs return information about products and recommended products (Amazon), post updates to social networks (Twitter or Facebook), or send money to your friend (Paypal, Venmo, etc.).

####What am I going to do:

In this step, you will step into the role of an architect and create an API used by your website to retreive jokes from the service.  The API will need to specify the inputs and the output, as well as mocking the expecting output (pretending to be the server and returning an output).

###2) Adding Interactivity

####Why do I need this: 
If you look at Facebook, you notice that users can submit comments or like a post without requiring the page to reload.  This ability to get information or perform an action without a page reload provides a better, more seamless experience for users.

####What am I going to do: 

You will implement the ability to show a new joke to the user without the need of reloading the entire page

###3) Speech Implementation

####Why do I need this: 

This is a natural extention of the previous two steps.  You will be add another method of interaction by providing the user the ability to hear the joke, instead of reading the joke.  To avoid the need to build out an entire system to convert text to speech, this functionality will use the Web Speech's API to convert text to audio.

####What am I going to do:

You will implement a method to use Web Speech's API based on their documentation (with assistance from the web) to voice out the text.

##Vocabulary

* Application Program Interface (API) - A set of interfaces to interact another web-based resource.
* GET Requests - A request to retreive data from another resource
* POST Requests - A request to submit data to another resoure for processing
* AJAX Requests - A technique to provide interactivity between the client and server without reloading the page
* Client - The program that requests another service to perform an action 
* Server - The program that performs the action requested by the client's request

##How to Submit
This project must be pushed back up to your repo on GitHub. Then you will share your link with the instructor

##Homework
Instructor will assign homework based on progress in class.
