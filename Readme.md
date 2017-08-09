Tip Calculator
# Pre-work - *Tip Calculator iOS app*

***Tip Calculator or Calculadora de propinas* is a tip calculator application for iOS.

Submitted by: **Rosa Perez**

Time spent: around **25** hours spent in total

## User Stories

The following **required** functionality is complete:

* [ x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [ x] Settings page to change the default tip percentage.

The following **optional** features are implemented:
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1**: "What are your reactions to the iOS app development platform so far? How would you describe outlets and actions to another developer? Bonus: any idea how they are being implemented under the hood? (It might give you some ideas if you right-click on the Storyboard and click Open As->Source Code")

**Answer:** [Enter your answer here in a paragraph or two].

My reactions to the iOS app development platform so far is that it was so easy to use.  I enjoyed working on the app & appreciate the easy to follow video tutorial.  This is my first iOS application.

Outlets - adds a connection from the UI file to a label in the code.  This enables code to send a message to the UI object.

Actions - example when the user clicks a button, the buttons sends an action message.  Its the developers responsibility to write the code to implement the action.





Question 2: "Swift uses [Automatic Reference Counting](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AutomaticReferenceCounting.html#//apple_ref/doc/uid/TP40014097-CH20-ID49) (ARC), which is not a garbage collector, to manage memory. Can you explain how you can get a strong reference cycle for closures? (There's a section explaining this concept in the link, how would you summarize as simply as possible?)"

**Answer:** [Enter your answer here in a paragraph or two].


Understanding what a closure may help to prevent memory leaks on your iOS app by avoiding retrain cycles in closures.  Memory leaks can cause the app to crash so it needs to be a strong reference cycle.   

  An example of a strong reference cycle for closures is that it's dependent to one another (human & heart) to live.  The heart and human have a strong reference to eachother. 

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
