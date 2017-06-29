# NDCOslo2017FPTrack

[![Join the chat at https://gitter.im/NDCOslo2017FPTrack/Lobby](https://badges.gitter.im/NDCOslo2017FPTrack/Lobby.svg)](https://gitter.im/NDCOslo2017FPTrack/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Links to all FP talks at NDC Oslo 2017.

## Wednesday

### F# for C# programmers - Scott Wlashin (10:20-11:20)

Curious about F# and want to understand how is it different from C#?

In this talk, we'll look at the basics of coding in F#, and how functional programming differs from object-oriented programming. Along the way, there will be many examples showing the same code written in C# and F# so that you can see for yourself how the two languages differ in style and approach.

### Suave – zero to hero of HTTP APIs - Henrik Feldt (11:40-12:40)

Software should just work! Suave gives you HTTP super powers by letting YOU decide how you want your API to respond. Libraries should be competent at what they do and then get out of your way.

In this talk I'll show you how to program F# with Suave to create smooth HTTP APIs from scratch and how to leverage functional composition and functional programming in a sweet symphony to quickly and effortlessly deploy a service. We'll go behind the scenes and discover the thought patterns behind the hugely popular suave.io web server and web library written in all F#.

Henrik has programmed for the web since the late nineties; take this opportunity to learn about how to write server-side software for the web by a true web development expert and coauthor of the Suave web server, a cross-platform, functional-first library for building HTTP APIs.

### Inviting everyone to the party - Andrea Magnorsky (15:00-16:00)

Most of today's popular general-purpose programming languages incorporate various aspects of the imperative, object and functional programming paradigms. In some cases, these languages provide clear guidelines as to what style is preferred, and why.

As programmers, we have a choice to make about which paradigm(s) to use and to what extent, even if the language provides clear guidelines. How should we think about those choices? Where are the sweet spots to make trade-offs, and what do they depend on? Let's wear the hats of history and science, thinking about the past and looking to the future, examining these apparent conflicts. Paradigm change is not a new thing - perhaps we can learn something from the history books? Wear Some(hat) and party like it's a hat party. With hats.

### Beyond JavaScript Frameworks: Writing Reliable Web Apps With Elm - Erik Wendel (16:20-17:20)

In times where a jungle of JavaScript frameworks wants to solve every conceivable problem in web app development, creating headaches and javascript fatigue in the process, Elm offers a different approach.

Elm is a functional programming language that you can use instead of JavaScript — or alongside it. It builds on the concepts virtual dom and unidirectional data flow popularized by React and Redux, but with a sound typesystem, built-in immutability, and an amazing compiler that catches errors before you even run your code. Simply put, Elm is a great language that will make your backend team jealous (unless they're already on the very similar F#).

In this talk you'll see how Elm works and learn how to use it to build a web app. I will emphasize the advantages and disadvantages it brings compared to the traditional JavaScript tech stack used at my most recent project.

This talk is not aimed at experienced functional programmers coming from languages such as Haskell, but rather JavaScript developers seeking a more functional approach in their daily work. It serves both as a introduction to Elm and typed, ML-style functional programming.

### Domain Modeling Made Functional - Scott Wlashin (17:40-18:40)

Statically typed functional programming languages encourage a very different way of thinking about types. The type system is your friend, not an annoyance, and can be used in many ways that might not be familiar to OO programmers.

Types can be used to represent the domain in a fine-grained, self documenting way. And in many cases, types can even be used to encode business rules so that you literally cannot create incorrect code. You can then use the static type checking almost as an instant unit test — making sure that your code is correct at compile time.

In this talk, we'll look at some of the ways you can use types as part of a domain driven design process, with some simple real world examples in F#. No jargon, no maths, and no prior F# experience necessary.

## Thursday

### Live Lambda Calculus - Einar W. Høst, Jonas Winje (9:00-10:00)

You might know that the lambda calculus is the theoretical foundation for all functional programming languages - but what is it really, and how does it work?

In this talk, we'll bring the theory to life! Using F# and the fparsec library, we will write a working lambda calculus interpreter from scratch. We'll even have time left to demonstrate how we can use it to do something useful, like adding numbers!

### What To Expect When You Are Elixiring - Johnny Winn (10:20-11:20)

Congratulations, you are expecting! Well, expecting to use Elixir that is. I’m sure you are flooded with questions including, “what is Elixir?” Don’t worry, I have you covered.

Starting from Day 1 all the way to “Oh my, it’s OTP” we’ll cover all you need to know to get ready for your new app. This new stage of development will begin with your new syntax and tools. Then on to common frameworks, and finally an intro to Open Telecom Platform (OTP). It can be scary at times and you may get nervous but never fear. You’ll get through this and it’s all part of learning something new.

### Using F# on Azure Functions in Production - Nikolai Andersen (11:40-12:40)

In this talk I'll show a real world example of running F# on Azure Functions. By consuming several APIs in a deployment pipeline we have created a service that generates informative changelogs between environments. I want to show you how easily you can do the same.

Using the power of F# Type Providers we'll create a new project, integrate with three external systems and deploy to Azure Functions in under an hour. We'll go all the way from the drawing board to running in production. Be prepared for some live coding.

The presentation does not assume any prior familiarity with F#, Type Providers or Azure Functions.

### Develop Your Development Automation - Jessica Kerr (15:00-16:00)

Is your work ever boring?
Programming is exciting and challenging when we’re adding features and making the computer do stuff, like serious business work. Programming is boring when we’re getting yet another service up and running and configured in CI. Adding the same methods to matching classes, again. Creating an issue, linking the PR, waiting for the build. Then there are the tasks so tedious we deny their importance and skip them, like upgrading existing services to the latest coding standards and keeping library versions up to date everywhere. What if you could replace every boring task with a few lines of carefully-considered code?

In this session, you’ll see a live demo of how I can automate coordination and code with Rug and Atomist. I can’t get you out of boring meetings, but I can help you stick to the serious business in your coding time.

### Conquer the JavaScript ecosystem with F# and Fable! - Alfonso Garcia-Caro (16:20-17:20)

Let's acknowledge it, Javascript has conquered the world. You've it on the web, on the server, on the desktop, on mobile... everywhere! Like the language or not, the truth is JS developers have built an incredible ecosystem with libraries and tools to do almost anything. If you want to enjoy all these development opportunities, does it mean there's no choice but dealing with duck typing, cryptic equality rules and undefined everywhere?

No! Fable (http://fable.io) is an open source compiler that brings all the power of F# to the JS world: the functional paradigm, static typing with type inference, pattern matching, type providers and more. Together with a comprehensive library to handle collections, text and observables among others.

Fable doesn't add any runtime overhead and generates clean JS code in conformance with new ES6 patterns, like modules or iterables, making it compatible with modern development tools, including Github Electron or React Native to let you develop not only web, but also cross platform desktop and mobile apps.

In its short life Fable already has several projects in production like the amazing thegamma.net, and is very close to 1.0 release. In this talk you will learn about the coolest and newest features of Fable and the vast number of possibilities it opens for F# developers.

### Modern app development with Fable and React Native - Steffen Forkmann (17:40-18:40)

React Native is a JavaScript framework for mobile apps by Facebook and allows developers to create “native apps” on iOS and Android.

This talks shows how functional programmers can leverage the full power of React Native in a functional and typed way by using modern tools like Fable and elmish. Fable is a powerful F# to JavaScript compiler and allows to write the React Native app in F#. Elmish on the other hand is library that brings the popular “Elm architecture” to F#. Together these tools build an excellent foundation for modern app development.

## Friday

### Programming is writing is programming - Felienne (09:00-10:00)

Writing and programming are often seen as different. Writing a creative profession, programming a technical one. Below the surface however, there is one large similarity. Both writing and programming are, ultimately, the translation of a high-level idea into low level sentences or statements.

So, there should be something we can learn from each other, right? In this talk, Felienne will compare the activities of writing and programming, with a focus on learning to read and write, versus learning to program.

### Taming the Web with Cowboy & Coyote - Johnny Winn (10:20-11:20)

What if I told you we could simplify web development with OTP over MVC. At first glance you might think anything with “simplifying with OTP” sounds complicated.

I mean have you built an OTP application? We’re talking supervision, transient processes, crashes, recoveries, that’s not even including distributing applications across multiple nodes. Can’t we just use a framework for that? Don’t worry we’ve all been there but it’s actually really simple and exceptionally fun to build pure OTP applications to run on the web. In this talk, we cover how coyote was built to manage distributed OTP applications servicing web requests via cowboy. We’ll see the code used to manage node connections, message relays, and of course all the goodness that is OTP. Some call it thinking outside the box but we could say that we're taming the Web with Cowboy & Coyote!

### Scaling Serverless F# with Azure Functions - Mathias Brandewinder (11:40-12:40)

In essence, Azure Functions give you the ability to take a small piece of code, and painlessly deploy and run it in the cloud. Not surprisingly, then, Functions shine for "programming in the small", for instance scripting automated tasks. But what if you wanted to build a serious application, Serverless style?

Unless you are careful, you will probably quickly end up with a spaghetti of functions on your hands. Azure Functions make some problems disappear, but also introduce issues of their own, without much guidance available. In this talk, we'll explore what types of challenges can arise and why, and present some techniques to help you grow Serverless code that doesn't suck.

### FAKE + Paket – PowerTools for .NET developers - Steffen Forkmann (15:00-16:00)

FAKE - F# Make is a build automation system with capabilities which are similar to make and rake. It is using an easy domain-specific language (DSL) which allows you to express your build logic in F#.

Paket is a dependency manager for .NET and mono projects, which is designed to work well with NuGet packages and also enables referencing files directly from GitHub repositories. It enables precise and predictable control over what packages the projects within your application reference.

The talk will show you how to set up basic build scripts with FAKE and gives you an overview about dependency management with Paket. This talk is for every .NET developer that wants to get rid of the problems that come with XML build scripts and NuGet dependency chaos.

### Servant: Web APIs at the Type Level - Erlend Hamberg (16:20-17:20)

Servant is a Haskell library that implements a domain-specific language for web APIs at the type level. By specifying the API as types, you get a clean separation of HTTP logic and the value-level handlers. Also, since the type checker has knowledge about the various endpoints and where they live, it will be able to verify that all handlers return the correct types and headers, and that internal URIs are correct.

Implementing a server (i.e. a set of handlers for the HTTP endpoints) is just one of several uses of an API type, however. By traversing the type, Servant is also able to derive a Swagger/OpenAPI specification for the API, and even API client code in JavaScript and other languages. We will look at how Servant achieves a clean separation of HTTP and business logic – true to the core philosophy of HTTP and REST. By not just implementing a server for an API, but also deriving a JavaScript client and a Swagger/OpenAPI specification for the, we will end up with an API with strong correctness guarantees and also documentation and client code that is guaranteed to be correct and up to date.
