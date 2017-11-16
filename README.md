# Teaching Javascript (the hard way) to my brother John

This is heavily influenced by Zed Shaw's "Learn Ruby the Hard Way" (https://learnrubythehardway.org/book/) and kmcrayton7's javascript version (https://github.com/kmcrayton7/javascript)


## Setup

* Clone this repository
* Check the version of nodejs you have installed

```
  node --version
```

## Exercise 1: A Good First Program

Type the following text into a single file named ex1.js. Javascript works best with files ending in .js.

```javascript
  console.log("Hello World!");
  console.log("Hello Again");
  console.log("I like typing this.");
  console.log("This is fun.");
  console.log("Yay! Printing");
  console.log("I'd much rather you 'not'.");
  console.log('I "said" do not touch this.');
```

In your terminal run the file by typing:

```bash
  node ex1.js
```

### What You Should See

```
Hello World!
Hello Again
I like typing this.
This is fun.
Yay! Printing
I'd much rather you 'not'.
I "said" do not touch this.
```

### Study Drills

The Study Drills contain things you should try to do. If you can't, skip it and come back later.

For this exercise, try these things:

* Make your script print another line.
* Make your script print only one of the lines.
* Put a //  at the beginning of a line. What did it do? Try to find out what this character does.

## Exercise 2: Comments and Pound Characters

Comments are very important in your programs. They are used to tell you what something does in English, and they are used to disable parts of your program if you need to remove them temporarily. Here's how you use comments in Javascript:

```javascript
  // A comment, this is so you can read your program later.
  // Anything after the // is ignored by javascript.
  console.log("I could have code like this."); // and the comment after is ignored

  // You can also use a comment to "disable" or comment out a piece of code:
  // console.log("This won't run.");

  console.log("This will run.");
```

From now on, I'm going to write code like this. It is important for you to understand that everything does not have to be literal. Your screen and program may visually look different, but what's important is the text you type into the file you're writing in your text editor. In fact, I could work with any text editor and the results would be the same.

### What You Should See

```bash
$ node ex2.js
I could have code like this.
This will run.
```

Again, I'm not going to show you screenshots of all the terminals possible. You should understand that the preceding is not a literal translation of what your output should look like visually, but the text between the first $ node ... and last $ lines will be what you focus on.

### Study Drills

* Find out if you were right about what the // character does
* Take your ex2.js file and review each line going backward. Start at the last line, and check each word in reverse against what you should have typed.
* Did you find more mistakes? Fix them.
* Read what you typed above out loud, including saying each character by its name. Did you find more mistakes? Fix them.
