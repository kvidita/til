# Hello I'm Vidita. Here's my dailylogs
[projects](/til/projects)

## 10th june 2023
- TODAY'S LEARNINGS
  1. mocking some function using 'it', we can use context to mock a function.
    -function mocked can be declared as 
      const mockedFn = context.mock.fn()   :- (specifying that some function is being mocked).
  2. using done while mocking :- specifies that the assertion will be done only after the specified function is called.
  3. for setTimeout, ```the done``` and assertion shall be placed in the right place.
  4. * once code is written, just think about the work it does, internal code must not be remembered.
  5. MVC -(Model-View-Controller)
    - program logic is divided into three interconnected elements
      1. Model:- (central component) application's dynamic data structure, independent of the user interface. It directly manages the data, logic and rules of the application
      2. View:- (Any representation of information) Multiple views of the same information are possible, such as a bar chart for management and a tabular view for accountants.
      3. Controller:- Accepts input and converts it to commands for the model or view.
    example tic-tac-toe done by jayanth.

## 9th june 2023 
- TODAY'S LEARNINGS
  1. inheritance concept 
    - any class is an instance of it's parent
    - parent's public methods and fields becomes accessable to the inhereting class
    - super method refers to the parent class
    - while a derived class inherits a base class, 'super(arguments)' must be the first thing to declare in constructor
    - while inheriting a class 'extends' keyword is used
    - for eg. anything in js is an object as js internally extends everything to an object.

## 8th june 2023
- TODAY'S LEARNINGS
  1. use of documents when required

## 7th june 2023
- TODAY'S LEARNINGS
  1. process.stdin.setRawMode()  :-  a method to take input from standard input as a characters only
  2. exec :- a function used to run a child process
  3. afplay  :- used to play audio
  4. process.stdout.getWoindowSize()  :- to get the window size
  5. process.stdout.columns  :- used to get columns of the window
  6. process.stdin.rows :- used to get rows of the window
  7. process.stdin.cursorTo  :- used to place the cursor in the screen where you want
  8. process.stdout.clearScreenDown()  :- used to clear the screen below the cursor's last position
  9. "a" in obj (checks presense of a key called "a" in object obj)

##  6th june 2023
- TODAY'S LEARNINGS
  1. Set :- a class that creates a set out of given string
  2. EventEmitter
  3. process.stdin :- The process.stdin property returns a stream connected to stdin (fd 0)
  4. process.stdout :-  The process.stdout property returns a stream connected to stdout (fd 1)
  5. process.stdin.on("data")
  6. process.stdin.on("end")
  7. process.stdin.on("err")
  8. fs.createReadStream()

## 5th june 2023
- TODAY'S LEARNINGS
  1. package
    - making package and requiring package
  3. npm
    - initializing :- npm init
    - installing some package :- npm install table 
    - for eg:-
      - npm table (package)
      - npm colors (package)

## 27th may 2023
- TODAY'S LEARNINGS
  1. dependency injection 
    - to have greater control over the code
    - to make code more flexible, less coupled or decoupled
    - helpful for testing the functions that does not returns anything
  2. inversion of control
  3.  jayanth's session
    - example for inversion of control > games having options of changing themes and levels
    - session on markdown documentation
    - creating github page
    - suggestion on putting daily notes on github page collectively
   
