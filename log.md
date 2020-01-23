# 100 Days Of Code - Log

**I want to learn**: Swift, pytorch

**I want to get more practice with** tensorflow, front end development

**I will do for fun/for a break** Advent of code, hackerrank, Project Euler 100

**possible projects**:

turn python code I have for reading in french webpage and creating a list of translations for words I don't know into an iOS app

Make a 100 days of app to track work



### R1D1: Jan 13, 2020 

**Today's Progress**: Breaking the rules already -- I worked through a Swift tutorial and am in the process of making my very first app.  Since I have no experience at all in Swift, I'm counting tutorial work for the first few days.  I'm following https://www.raywenderlich.com/4919757-your-first-ios-and-swiftui-app/ 

**Thoughts:** So far Swift is pretty easy to learn.  There's a lot in common with python and html, so that helps.  I'm making good progress

**Link to work:** https://github.com/alyshareinard/firstswiftapp

### R1D2: Jan 14, 2020 

**Today's Progress**: I completed the "bullseye" Swift tutorial put a working bullseye App on my phone! Even better, though, I created my own app.  My son was practicing his times tables and he likes to see the numbers instead of hearing them -- so I made an app that lets him do just that. Had to spend lots of time on stackoverflow and google, but managed to put it together. It's an MVP now -- barebones, but works.  He likes it and we both have ideas for improving it.  

**Thoughts:** Yay!  My first app of my very own!

**Link to work:** https://github.com/alyshareinard/timestable

### R1D3: Jan 15, 2020 

**Today's Progress**: Working through some details of the Times table app -- resizing the answer box, adjusting the layout.  Made my own numpad since the built in one doesn't have a "done" button and so permanately blocks several of my buttons.  Added ability to keep track of and display points.  Also made planning list and did a little research for a wine inventory app my sister-in-law requested. 

**Thoughts:** The Swift number pad keyboard really needs a "return" or "done" button!  WTH?  

**Link to work:** https://github.com/alyshareinard/timestable


### R1D4: Jan 16, 2020 

**Today's Progress**: My times table app had been picking numbers randomly from a given range, but this results in the user seeing some equations repeatedly and not seeing other equations -- so today I set up arrays for num1, num2 that contain the desired range of numbers to practice and then set up a 2d (shuffled) problems array of the form [ [num1, num2, num1*num2], ]  With this the code now removes problems that are answered correctly on the first try.  The problems array has to be set up when the start button is pushed and I don't have a good way to handle the end of play when there are no problems left. So that's my next job.  I'm now working through some tutorials to get a better handle on creating multiple screens for the start and finish parts of the app.  

**Thoughts:** Working through bugs/issues on my own (with the help of google and stack overflow) as I develop this app has been very helpful, but at this point it's time to go back to tutorials for a bit to pick up some more fundamentals.  

**Link to work:** https://github.com/alyshareinard/timestable

### R1D5: Jan 17, 2020 

**Today's Progress**:  Today I focused on fundamentals -- working through 100 days of SwiftUI (https://www.hackingwithswift.com/100/swiftui) -- jumping through the first few days to fill out the knowledge I have so far. Learned about ternary operators -- that's what those ?'s are for! -- got a fuller understanding of function syntax, and starting a dive into closures -- closures are a new concept for me, and are important in Swift so I'll have to spend some time on them.  More fundamentals tomorrow and hopefully I'll be able to start implementing some of my learnings into my projects.  

**Thoughts:** I'm familiar with the concept of passing functions to functions, but I haven't really done it -- closures seem like that on speed and actually important in this language, so I have some grokking to do.  

**Link to work:** https://www.hackingwithswift.com/100/swiftui completed day 1-5

### R1D6: Jan 18, 2020 

**Today's Progress**: Not much to report today.  Really had just an hour so worked through day 6 and part of day 7, really getting a handle on closures. Also read an article about making a menu in Swift.  That will be helpful for making the timestable app more customizable.  

**Thoughts:** I'm getting closures -- hopeffuly I'll have time tomorrow to finish day 7 of the tutorial and look through some code examples to get a better feel for how closures are used in practice.  

**Link to work:** https://www.hackingwithswift.com/100/swiftui completed day 6 - 7.5

### R1D7: Jan 19, 2020 

**Today's Progress**: Worked through the rest of the tutorial on closures and blew through the 2 days on Structures -- there was quite a bit in common with python structures, so it wasn't too hard. Looked through my own code examples with my new knowledge, which helped me interpret a few parts. Read up on codebase. Started playing with an implementation of a barcode reader, but I think I still need more background information about what the different files in the swiftui project folder do and how they interact.

**Thoughts:** Closures are less daunting, structure are great -- I like being able to put a function into a structure. Very powerful.   

**Link to work:** https://www.hackingwithswift.com/100/swiftui completed day 7.5-9



### R1D8: Jan 20, 2020 

**Today's Progress**: Added a timer to the Times tables app -- timer counts up and gives more points the faster the problem is solved.  It's nice to do some real project coding again.  Then on to more tutorials.  Classes, protocols, extensions, optionals.  All helping to clarify what I have seen in sample swift code.  Good stuff!  I like that on hackingwithswift they have videos and text explaining each point. I don't like to watch videos so I really appreciate the text! Then went through and created a couple of projects on the swiftui in 100 days page.  Ran into app developer limit for free account but found out how to delete apps from my phone using Window, devices and simulators, then deleting apps from my phone on there to make room for new ones.  

**Thoughts:**  The tutorials and sample projects are a big help -- I have a better udnerstanding of how the different elements in ContentView work together.  I'm looking forward to a tutorial project that uses multiple app pages and/or uses some of the other files in the main project folder.  
I wonder if I should get a developer account -- not yet, but maybe soon. 

**Link to work:** https://www.hackingwithswift.com/100/swiftui completed day 10-12, 16-22.

### R1D9: Jan 21, 2020 

**Today's Progress**: Feeling under the weather but put my hour in -- worked through hacking with swift project and looked at a few swift practice sites.  In the Hacking With Swift there was a nice overview of the grid method -- I'll add that to my tiems table app tomorrow -- I am finding that the number keys don't line up on the ipad, so a grid might help.  

**Thoughts:**  Tired, but feeling good about completing my hour of coding.  

**Link to work:** https://www.hackingwithswift.com/100/swiftui completed day 23-24.5, checked out https://edabit.com/ for code practicing -- not a bad interface, but a bit slow.  


### R1D10: Jan 22, 2020 

**Today's Progress**: Did the day 24 project (no code provided) creating a roshambo brain buster game.  Was able to put it together easily.  Then going to the next day it required core ML -- I have Apple Mojave and I'm reluctant to upgrade to Catalina, so that's causing some problems.  My Xcode 11.3 verson of core ML requires Catalina. 

**Thoughts:**  Will I have to upgrade my os?  Ugh.  

**Link to work:** https://www.hackingwithswift.com/100/swiftui day 24 project -- creating a Rock paper scissors brain builder game from scratch.   https://github.com/alyshareinard/roshambo
