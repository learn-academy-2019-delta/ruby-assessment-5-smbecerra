# ASSESSMENT 4: INTRO TO RUBY
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own there is always something more to learn.   

1. In what ways are JavaScript and Ruby similar? In what ways are they different?

  Your answer: They are both object oriented. 

  Researched answer: Both languagues are object-oriented, but in Ruby, everything is an object. JS is primarily a front-end language, while Ruby is primarily a back-end one.



2. What is a hash?

  Your answer: A collection of key-value pairs. 

  Researched answer: Hashes are a way of looking up data by assigning value to a key. Whenever that value needs to be referenced, the key is used to look it up. 



3. What is the testing framework used in Ruby? Describe the process of setting up the testing environment.

  Your answer: Behavior Driven Testing

  Researched answer: 
    - Determine a behavior to implement
    - Set up the describe and it blocks pertaining to that behavior. There can be more than one it block, set in pending in the blocks.
    - Put in an "expect" in one it block to assert the expected behavior. 
    - Run the tests and expect them to fail at first. 
    - Now implement enough software to make them pass. 
    - Add more expects as the process continues. Repeat the process as the  software is built out. 



4. Name three possible relationships between objects?

  Your answer: is-a, has-a, part-of. 


  Researched answer: 
  is-a: Where one class is a sub-class of another. 
  has-a: One object belongs to another. 
  part-of: 




5. What is an instance variable? How is it different from other variables in Ruby?

  Your answer: A variable beginning with @ and that refers to an object within it's scope.

  Researched answer: An instance variable is assigned with the value of a local variable (name) to an instance variable under (name). 
  The local variable will then be accessible via the instance of a class. 
  





6. Ruby has a great community and tons of free resources to help you learn. [Here](https://www.ruby-lang.org/en/documentation/)is a list of great resources. Below are a few popular ones:
- [Interactive Ruby Tutorial](http://tryruby.org/levels/1/challenges/0)
- [Why's (poigniant) Guide to Ruby](http://poignant.guide/book/chapter-1.html): comics, anecdotes, and microscopic canaries
- [Ruby in 20 Min](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Ruby Style Guide](https://rubystyle.guide/)

Choose one of these resources and look through the material for 10-15 min. List three new things you learned about Ruby:

1) One of Ruby's guiding principles is : "Programs must be written for people to read, and only incidentally for machines to execute."
  While I am still very new at writing code in Ruby and don't feel very comfortable with it yet, it is easy to see this guiding principle in place. 
  Ruby is easy to look at and it's helpful error messages are very usefu for getting pointed in the right direction. 
  

2) Double negation and avoiding  the use of !!. !! converts a value to boolean, while I have never run into something like !! in any coding language,
  This is a nifty trick to know. 
  

3) Use one expression per line. Keeps things clean. 



7. Stretch: What are blocks, procs, and lambdas?

  Your answer:

  Researched answer:
