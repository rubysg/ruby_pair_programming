# Ruby Pair Programming

## What is it?

- “Pair programming is an agile software development technique in which *two programmers work together at one workstation*.”
- “One, the driver, writes code while the other...reviews each line of code as it is typed in.”
- “*The two programmers switch roles frequently.*” (Wikipedia)

## Today's Session

- 3 hours long (10 am to 1 pm)
- Suitable for all levels of experience
- Objective is to learn during the process
- Ruby as primary language
- Not just Rails: script, Sinatra, gem, etc

## Pair Programming Styles

### Driver-Navigator

- Person A has control and writes some tests and the code to make them pass
- Person B observes and makes helpful comments and suggestions when appropriate
- At some stage, Person A hands control over to Person B.

### Ping Pong

- Person A writes a failing test
- Person B makes the test pass and writes another failing test
- Hands back to Person A to make that test pass and write another test, *ad infinitum*.

### Deciding

- Decide with your pair which style you would like to use beforehand
- Don't be afraid to suggest trying another style if you're not comfortable with the one you are using, or if you think it's not going anywhere.
- If all else fails and you think it's not really working with your pair, please let us know.

More on [pair programming styles](http://articles.coreyhaines.com/posts/thoughts-on-pair-programming/).

## Pairing Etiquette

- The Golden Rule: "Do unto your pair as you would have them do unto you"
- Remember you're part of a pair
- Be nice
- Don't hog the keyboard
- Please don't work on the code when your pair is not around (e.g., taking a break)
- When it's your turn, remember that no-one can read your mind
- It's often helpful to describe what you're doing to your pair, even if it might be obvious
- Communication is key!
- When it's your pair's turn, give them time and let them work at their own pace
- Don't grab the keyboard
- Sit on your hands if you need to
- Take small steps
- Write just enough code to let the tests pass
- No voodoo!

## Test Driven Development (TDD)
- Write a failing test
- Write the minimum amount of code that allows the test to pass
- Refactor code already written
- Red, green, refactor
- Encourages simple designs and inspires confidence

## Things to Work On

### Real-World Code

- a script to do something useful (or not)
- a new gem
- a project you've already started
- refactoring some existing code

### Simple Programming Problems

There are some advantages of working on a simple programming problem instead of working on "real world" code (simplicity, "purity", likelihood of success). Feel free to try any of these:

- a simple calculator that takes two numbers and outputs their sum
- a simple calculator that takes any number of numbers and outputs their sum
- (as above, but without using Enumerable#inject)
- [Project Euler](https://projecteuler.net)
- [Ruby Quiz](http://rubyquiz.com)
- [Code Kata](http://codekata.com)
- [Ruby Programming Challenge for Newbies](http://ruby-challenge.rubylearning.org)
- [14 Ways To Have Fun Coding Ruby](http://rubylearning.com/blog/2010/09/22/14-ways-to-have-fun-coding-ruby/)
- [The Gilded Rose Kata](https://github.com/jimweirich/gilded_rose_kata)
