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

### Day 7: Sep 15, 2020

**Today's Progress**: Tried to add Unit Testing to Stack, new, make, pointer and &. Tiring

**Thoughts**:
Found the going hard. [Tweet-for-the-day](https://twitter.com/zero2null/status/1305921633916301312?s=20)

Spent some time struggling with the Unit Testing for the code Stac done yesterday. Was fairly frustrated with it.
I guess I need to learn more about type initialization, etc. So left it half done.

Then moved on to next chapter of Learning Go: Chapter 5. Beyond the Basics
And I found myself being rushed through several key concepts, in short one or two lines. I could not wrap my head around so many at once.
Lack of hands-on examples for each one of the concepts also hurt. So I need to go over the stuff again tomorrow.

The day had left me weary. Did it affect my comprehension?


### Day 8: Sep 16, 2020

**Today's Progress**: No success with unit testing, but did hands on new, make, pointers and address

I was so upset with yesterday's unsatisfactory performance, that I got on to the task early in the morning!

Got down to trying each concept once again through writing a program, and trying it out by hand.

And then it was a very useful journey of discovery.

Once again did some slices, some pass-by-value and pass-by-reference

Came across a few problems, roadblocks, and learnt from each one of them.


**Thoughts**:
Not as frustrated with life as yesterday ;) [Tweet-for-the-day](https://twitter.com/zero2null/status/1306294462293839873?s=20)
The progress is laborious. I think I need another 10 days of focus on basics.


### Day 9: Sep 17, 2020

**Today's Progress**:

And I found that I have already covered a number of things in Structures in my Stack Example only.
A bonus realization is: Go is not a object oriented language. It does not support inheritance, but works on composition. Need to check this out.  However, with no constructor being the official position, I can still do some such things anyway.  However, I need to change my outlook to suit the native Go coding paradigm. What is that? Need more examples [Tweet-for-the-day](https://twitter.com/zero2null/status/1306633218850914310?s=20)

Ha! the opinionated language -> type conversions are strictly controlled.
I spent some time on going through teh git workflow. It was essential. One of the goals of my endeavor is Learn Git. And so spending time today was absolutely essential. [This](https://gist.github.com/blackfalcon/8428401) is now my bible!

**Thoughts**:
It is proving truly to be a challenge.
The progress is still slow. But I keep on finding stuff that says I learn everyday.
Here is the thing: Learning a language is a daunting task. Add to it the tooling challenge. And that makes it tougher. But picking up the gauntlet publically keeps you going!


### Day 10: Sep 18, 2020

**Today's Progress**:

In the morning read a very important but very minute difference between a pointer to a type passed as an argument versus the object. Remember pass-by-value and pass-by-reference!

30 years ago I wrote my first implementation of Doubly Linked list in C. I doubt whether I have had a chance to do it over again, till today! It was fun. And I came out with a very clean implementation.
Only the nomenclature could have been better. But overall, I liked the complexity, and my clean solution.
[Tweet-for-the-day](https://twitter.com/zero2null/status/1307022384818397184?s=20)

**Thoughts**
Today is Sat Sep 17. I have completed 10 days of this challenge. I feel happy. I feel invigorated. I also thank my family for giving me the time it is required to spare for this activity. There is a long way to go. Along with Golang, I am making slow but deliberate progress on git, too. And building a bit of confidence in it.




### Day 11: Sep 19, 2020

**Today's Progress**:

I did not do coding by hand, so as to say. But I studied the cat program that Learning Go had given as assignment. And I learnt a lot from it. [Tweet-for-the-day](https://twitter.com/zero2null/status/1307389936262246400?s=20)
Downloaded John Arundel's [book](https://bitfieldconsulting.com/).
And it immediately helped me with gofmt. Interesting.

Got introduced to package flag! Wow! I mean WOW! What I would have had many lines do, it did it for me very simply!

Very happy to learn about the flag package! Daunting to see so many methods in it. 

Also, an observation: I initialized a variable outside of main by invoking a function outside of main. So it must be getting executed... when?!

And there I saw a reference to func init() in documentation of flag. What is this? Holy Crap! https://stackoverflow.com/questions/24790175/when-is-the-init-function-run Seems a big enough topic by itself.

There is such a rigmarole to go through, while opening a file. Why is not a simple fopen there? Or is it there, and just that I do not know?
* os
* bufio
* io


I think, I checked out the branch afer doing git commit. Hence today, it did not ask me to check it out first.

**Thoughts**

Hmm, the list of packages left me dumbstruck. To master the language is going to be a long trudge.

And side by side the TDD also is going to pose a number of challenges. 100 more like 1000! :)


### Day 12: Sep 20, 2020

**Today's Progress**:

So there are interfaces, which are overloaded, and there types implementing interfaces, but not declaring it.I mean what! And on top of all this something called duck Typing!

*If it walks like a duck and it quacks like a duck, then it must be a duck*: Never thought this syllogism will make it to programming, Arrgh!

.(type) syntax is only valid within a switch statement! Arent we jumping through hoops?!

Here is a chanllenge - can I use the understand of interfaces to easily implement the Stack for int or string?
Let us figure out what is the question here.

Actually my use case is - I want to put anything on the stack - int or string

But let us water the usecase sdown to rto say that I will tell you whether I want to use int or String stack.
So New function will take the parameter to say int or String. And then we should validate 

So I was able to get the code strung up like the user of my package does not see any implementation details. But when it comes to the package itself, I failed to get the structure allocated dynamically - array of int or array of string.

That is pathetic.

[Tweet-for-the-day](https://twitter.com/zero2null/status/1307690510295859206?s=20)


**Thoughts**:
Today being Sunday, I was able to spend somewhat more time with Golang. However, I am getting strange vibes with the seemingly weird stuff. This interface thingee seems to have been much more complicated than necessary. And the book says it is powerful!


### Day 13: Sep 21, 2020

**Today's Progress**:
Jon @bitfield requested access to my code, which I was so dejected about. Will see if he responds with any comments.

Today I learn goroutines and concurrency. Also some kind of concurrency control using chan.

Doing the one example was useful. But I do not still know whether it has given me wherewithal for any useful goroutine use cases. Need to find som, may be in other documentation, and get some more insights into it.

[Tweet-of-the-day](https://twitter.com/zero2null/status/1308090971800793088?s=20)


**Thoughts**:
In my planning, this concurrency of Go was a great asset. Something I wanted to build real knowledge. I think with this I am coming close to the journey of the language. But I have yet to grasp a number of concetps here. GORM and TDD for sure!



### Day 14: Sep 22, 2020

**Today's Progress**:
I was happy to have figured out the totally generic Stack. Also figured out interface{} is a powerful concept, much more than I had earlier sensed.

In the process, I reached the end of the book Learning Go by @miekg

There are a number of points from Chapter 8-Communications, taht I read and glossed over. But I am sure I am going to come back to them in due course.

Now the next step. Started with @bitfield https://github.com/AbhijitL2020/ftl-fundamentals

This will teach me TDD. And probably cover up a big hole in my maturity as a developer.


**Thoughts**:
So here we are. Making progress on Golang. Learnign the syntax, and trying to understand the heart of the language.

Till now it is promising. I am able to learn some things, question myself, improvise on the problem, and figure out what is required to get my version of problems sorted out.

There are two directions from here. TDD is one, and building Web Applicationsis another. And we need to progress along bothe ways.

It is 15 days over. About one seventsh of the way.

My problem is Git is still as inscrutable as earlier. However, I need to be at it unsparingly. That is the only way.

And remember we have CSS3, Visual Design, Dart, Flutter on our target. We still need to figure out the whole of productive toolset for the Product development activity. 
