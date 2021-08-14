# demo
Spring Boot Project Web
I used start.spring.io / spring initializr; This guide is in https://spring.io/quickstart
"You will build a classic “Hello World!” endpoint which any browser can connect to. You can even tell it your name, and it will respond in a more friendly way"
"Spring Boot is the quickest and most popular way to start Spring projects"
The hello() method we’ve added is designed to take a String parameter called name, and then combine this parameter with the word "Hello" in the code. This means that if you set your name to “Amy” in the request, the response would be “Hello Amy”.

The @RestController annotation tells Spring that this code describes an endpoint that should be made available over the web. The @GetMapping(“/hello”) tells Spring to use our hello() method to answer requests that get sent to the http://localhost:8080/hello address. Finally, the @RequestParam is telling Spring to expect a name value in the request, but if it’s not there, it will use the word “World” by default.
