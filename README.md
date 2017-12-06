# Introduction
We might all know already that there's *always* stuff to work on when it comes to optimizing our websites, but some of us might just be spending too much of our time optimizing the *wrong* things. 

**Less than 20%** of the end user response time is spent getting the HTML page to the web browser, but where does the rest of the time go? In order to understand this issue, we need to see what the math is *really* telling us:
 
  - **HTML:** 10-20% `// Downloading the HTML document is usually 5% of the total time. `
  - **Components:** 60-70% `// Downloading the rest of the components typically counts for 60% of the total time. `
  - **Scripts:** 100 % (HTML + Components) `// The remainder of time is spent parsing script tags or css files `
 
All this starts with **HTTP** (HyperText Transfer Protocol), a.k.a *the rules that govern how browsers and servers communicate with eachother*. The main two components of HTTP are its **requests** and its **responses**. 

The types of requests and responses are listed here: 
### Requests 
  - **POST**  
  
  - **GET**  
  
  - **Head**  
  
  - **PUT** 
  
  - **DELETE** 
  
  - **OPTIONS**
  
  - **TRACE**
 
 `/* If you are new to this, `
  `you should mainly be concerned with `
  `POST, GET, and OPTIONS for now */`
  
 The request we will be working on is the **GET** request, since it is the most common.
 
### What's a GET request?
In layman's terms, a get request is what you send to a server to ask that server for something, whether it's information, data, etc. A get request typically contains a URL and some headers, however the main focus of this is not the get request itself but the response it brings in return...

## Compression

## Sending Conditional Requests

## Expires

## Keeping Alive


# Lets Get Moving!
You have reached the end of this introduction! Now its time to really dig deep into the other chapters. 
