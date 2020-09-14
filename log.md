# 100 Days Of Code - Log

### Day 0: Sep 8, 2020

**Today's Progress**:  Set up Windows Terminal, WSL2, AND created an account and used GitHub!

**Thoughts:** Oh shit! I just read that it has to be CODE only, not the other things like tutorial and so on. That is going to complicate my quest. I want to learn Go Flutter and Dart. But I thought I will do it as I go. I want to build a toolset along with it. For example, if I were to plan the Error Message management system as a project, then I need to plan. Which is a good tool to plan? And I need to design. Which is the good tool to Design? All these questions, and answers to them is also a part of my 100DoC quest. I want to build an ecosystem around the project in which I will be improving my knowledge of modern day development paradigm. So...

**Link to work:** [I think I found something that is not documented in WSL2 setup](https://twitter.com/zero2null/status/1303180547049496577)

### Day 1: Sep 9, 2020

**Today's Progress**:  Installed GoLang, neovim, and plugins for auto-complete and delve, the debugger

**Thoughts**: I spent a considerable amount of time in getting the neovim installed and configured. It was my bullheadedness that I would not use VS Code. I first used vi in 1990 or 91. And I have come to love it. I remember the fun I had when my fingers remembered the commands, but not my brain!
So I wanted to do it with vi/vim. But then a reference pushed me to neovim. I thought it is an opportunity to improve myself. And I did. I touched some of the configuration files for the first time in the life.
I was always intrigued with the plugin based architecture, and could not let by the chance to do debugging through vi/neovim. So here we are.

I came across the book Learning Go through the reference 

I had fun writing my first program hello.go, and try out some tweaks based on the info there. 

However my struggles with git/github continue. This thing is hard to learn!

### Day 2: Sep 10, 2020

**Today's Progress**: Writing m first few programs in Go, esp to try out slice, and then the firs exercise 

**Thoughts**: It was interesting to try out the concepts read yesterday, and combine them with the new stuff from today. THen I put it into a scrap program. Ensureed that I got run time errors, and also completions. The topics are going deeper.
Coming from a lengthy C heritage, I fee at times, that the Golang has been made to overcome the shortcomings. However, at times it sounds too clever?!
Today, I had a little trouble to find free time to do the daily hour! Just a taste of things to come, I guess?!

### Day 3: Sep 11, 2020

**Today's Progress**: Not in terms of the Chapters in LearningGo, but tried out what I had learnt till yesterday

**Thoughts**: 
Just leaned into the code from yesterday, and tried to build understanding of different language features

* used maps
* used constants
* used a separate function to print
* optimized the algo
* used different form of for "post" condition.
* Did some string conversion, concatenation

Added a rather audacious [tweet-for-the-day](https://twitter.com/zero2null/status/1304468009562509312?s=20)
iBy the way, if I can concatenate strings using a +, is it not operator overloading? No, I am not complaining, just want to get my head cleared.

### Day 4: Sep 12, 2020

**Today's Progress**: Started wtih Functions in Go, and did some recursion, call backs and other funcy stuff!

**Thoughts**:
The language retains so many similarities to C, and yet veers away from it in a dizzing fashion.

defer? That is a nice touch! Is it used much? Shades of that something called AOP?
So defer needs a function call ONLY! Not a statement. This is something restrictive, and instructive too!
Variadic? What a toungue-twister!
Boy, with so many concepts to digest, learning Go is going to be a long process. When will I get to trial out all these concepts and variations?
No exceptions?! Panic? Yes, I am already panicking. Hope to recover soon! :)

This is the [tweet for the day](https://twitter.com/zero2null/status/1304822870619516931?s=20)
Callback is also a novel concept. I have read it in JS, but never used it. And here also I am not too convinced. But we shall see.

Before I proceed far, I need to understand the concept of a callback and a closure clearly.


### Day 5: Sep 13, 2020

**Today's Progress**: Read a ORM+REST etc app, created a package, documented it, and added Unit Testing!

**Thoughts**:
Package is a namespace
The nuances: A function name starting with a Capital letter is exported, i.e. can be used outside the package.
If function name starts with small case, it is a private function. BTW, it applies to Type, Global variables, etc

The convention in Go is to use CamelCase rather than underscores to write multi-word names.

And we hit up on the (unit) testing part, which is what I was looking forward to!

This package thing though: How is this thing going to be organized. It needs to be under $GOPATH/src/even ?
And I have not understood how it compiles,what is its intermediate code, etc

Did the documentation. Looks a bit less structured than JavaDoc. Why?
And Unit Testing also, but not the Example part

Here is the [tweet_for_the_day](https://twitter.com/zero2null/status/1305200879373410304?s=20)


### Day 6: Sep 14, 2020

**Today's Progress**: Read a OAuth2.0 using Go app, created second package, documented it, and had fun

**Thoughts**:
Gad! I had blast today...

I wrote a package. A simple Stack, nothing much, but went way beyond what the book expected me to do.

In it used Const. Package name same as the file name. Defined a type using struct, made it public, I guess. "Stack"

Created Push and Pop functions (well, methods), then made sure that they get passing-by-reference values. Not passing-by-value

So I had to allocate the variable using new() in my calling /main function. And whats that? Not mentioned anywhere yet!

Added error handlign that not more than 10 values can be added. And cannot pop out of an empty stack.And used the comma ok format.

A bit late, so did not add the unit testing today. Thats left for tomorrow.

And it worked, man! So the multiple return values and the multi-assignment, though I did not like it first, I did use it, happily :)

Here is the [twee-for-the-day](https://twitter.com/zero2null/status/1305569818389573632?s=20)
But I am still not very convinced about some of the choices. Why not a constructor?

I eschewed writing bubble sort yesterday. But I need to see it as just an opportunity to build the muscle memory.

