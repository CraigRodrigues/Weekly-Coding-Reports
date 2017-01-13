## CHANGE IS HARD
### Weekly Coding Report #99
### January 07, 2017

Reorganized my _Coding Personal Curriculum_ for work I want to complete before PCA and Hack Reactor onsite.

Hack Reactor Prep
 - Outlining and stubbing
 - Testing/Assertio
 - TDD
 - TDD Exercises
 - Quick simple testing assert PASS/FAIL message template using ES6 template literals:
 
   ```javascript
   return `PASSED [${testName}]`;
   return `FAILED [${testName}] - Expected "${expected}", but got "${actual}"`;
   ```
 - Should a test be made that is meant to not pass or is negative?

Asked someone on Slack who went to Dev Bootcamp for good resources for Hack Reactor. She said:

> Hey! Here are some additional resources that should aid you in being successful during and after bootcamp:

> HTML & CSS:

> [Learn to Code HTML & CSS by Shay Howe](http://learn.shayhowe.com/html-css/)

> Javascript:

> [Head First Javascript Programming](https://www.amazon.com/Head-First-JavaScript-Programming-Brain-Friendly/dp/144934013X)

> [You Don’t Know JS Book Series](https://github.com/getify/You-Dont-Know-JS)

> SQL:

> [Head First SQL](https://www.amazon.com/dp/B006QNDJZI/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1)

> Node:

> I’m making an assumption here that this is probably the server side language they will teach you since Hack Reactor is a JS bootcamp, but I would fact check that first.
http://javascriptissexy.com/learn-node-js-completely-and-with-confidence/

> Coding Problems:

> [Free Code Camp](www.freecodecamp.com) - The site has several basic, intermediate, and advance algorithm scripting problems

> [Hacker Rank](www.hackerrank.com):
This site also has several algorithmic type problems you can work on

> Blogs:

> I would also look up blogs written by Hack Reactor students. They generally have very detailed information about what they learned during the project. Which can help you get a leg in terms of preparing. I liked [this blog]( http://rebootjeff.github.io/blog/archives/).

> However, it was written in 2013 so I would look up a more updated one also.

> Frameworks:

> **I would first get really comfortable with understanding Javascript fundamentals, then become literate in a JS framework.** I’m not that crazy about these resources, but it’s a starting point. If you find better one’s please let me know.

> Angular:

> https://thinkster.io/a-better-way-to-learn-angularjs

> React:

> https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/

> Good luck!

Testing a change to my writing flow
  - Completed this [Markdown Tutorial](www.markdowntutorial.com)
  - [Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
  - Proposed Blogging Flow
    
    Me :arrow_right: GitHub Markdown :arrow_right: Wordpress HTML or Ghost :arrow_right: Medium (one day) :arrow_right: Twitter!

Free Code Camp Toy Problems

- Hack Reactor prep site went down so I switched to FCC algorithm 'Wherefore Art Thou'
- I am weak at Objects and completely understanding how to search for their keys/props.
- I understand the solution and my logic was exactly correct.
- I am trying to never use a for loop like this again:
```javascript
for(let i = 0; i < arr.length; i++)
```
- Now that I think I understand it, I have to recall and do it again FROM SCRATCH. It's the **only** way to really beat something into my skull and learn.

### January 08, 2017

Hack Reactor Prep
 - Module 2 Exercises
  - Average integers
  - Decorate student list with ages
  - Is it an isogram?
  - Find first word with most repeated characters
  
      Their solution split out finding the max value in a hash map  
      My tests are more rigourous. Theirs will fail if a character is uppercase.  
      I should strive to have each function I write do **ONE THING ONLY**!
    
  - Render phone number
  - Find longest palindrome
 - Here's a quick checklist of how I should approach each problem.
  - [ ] Understand the problem first
  - [ ] Outline and skeleton
  - [ ] Think of test cases
  - [ ] Write assert for those tests
  - [ ] Create tests ==RED==
  - [ ] Develop main function(s)
  - [ ] Make tests pass ==GREEN==
 - I still need more work on Objects, Prototypes and Constructors. I must understand them deeply.

Free Code Camp Intermediate Algorithms - **COMPLETED**

- DNA Pairing (switch statements ever worth using?)
- Wherefore Art Thou
- Sum All Odd Fibonacci Numbers
- Sum All Odd Primes (learned how to implement Sieve of Eratosthenes!)
- Smallest Common Multiple (damn math research for GCD and LCM)
- Finders Keepers
- Drop it!
- Steamroller
- Binary Agents
- Everything Be True
- Arguments Optional

### January 09, 2017

- Finishing up a lot of stuff in my last week of work so I didn't get much done today since I was in at 7AM and reached home at 8PM.

- My copy of [Professional JavaScript for Web Developers](https://www.amazon.com/Professional-JavaScript-Developers-Nicholas-Zakas/dp/1118026691) arrived!
 
![Professional JavaScript for Web Developers Book](https://images-na.ssl-images-amazon.com/images/I/518NO3X1X2L._SX394_BO1,204,203,200_.jpg)

- Hack Reactor Pre-course Slack channel was opened and I joined in. Exciting!
	- This useful tool was already shared by instructor Albrey: [http://explainshell.com/](http://explainshell.com/)
	- Google Calendar also all setup and ready to go.

- Another cool article shared with me about engineers and notebooks: [Software Engineers Should Keep Lab Notebooks](https://blog.nelhage.com/2010/05/software-and-lab-notebooks/)

- Few good posts on Deep Work:

	1. [Deep Work: A welcome kick in the butt.](https://cpbotha.net/2017/01/09/deep-work-a-welcome-kick-in-the-butt/)
	2. [Quantifying and Visualizing “Deep Work”](https://medium.com/@FILWD/quantifying-and-visualizing-deep-work-af4689a62423#.3h2xlvpy7)

- I bought [iA Writer](https://ia.net/writer) and it's a great Markdown editor and I like writing in it much more than Google Docs, however it's not easily accessible across all computers/devices.
- Worked on toy problem _Character Frequency_ for 30 minutes.
	- It was very quick until I ran into trying to sort my array alphabetically when frequencies match.
	- Solved it two minutes later after getting a deeper understanding of using a callback function in sort().
	- I ran two sort functions. I feel like it can be done in one most likely.
	- Total time 33 minutes.
	- I want to write some quick assert tests as well to get more practice with writing and composing tests.

### January 10, 2017

This morning I spent 90 minutes working on the toy problems Jennifer gave me (finally). I was able to get through two of them fairly easily, but ran up against trying to computer all anagrams of a string.

I solved it later at work, but the recursion is intense!

- Hack Reactor Prep
	- Completed Fashion Inventory A
	- Completed Fashion Inventory B
		- Getting reduce to work with objects is a PITA
		- Looking at the solution theirs is easier to read because they broke down the functions EVEN FURTHER than what I thought of doing.
		- They had maybe twice as many. Each doing ONE TINY THING.
		- My skeletoning needs work!

### January 11, 2017

- Hack Reactor Prep
	- Completed Fashion Inventory C
		- Tried to break my functions down even more.
		- I had 4 functions in the end. All worked well.
		- Used simple regex to match for BLACK shoes.
		- Got stuck on the first map, oops. Got unstuck quickly.
		- The solution also had 4 functions, but was still slightly cleaner and more readable.
	- Completed Fashion Inventory D
		- I admit it took me a lot longer than I wanted.
		- It is hard to break everything down to the finest functions.
		- A good outline helps a lot and testing each function as you go.
		- My solution was slightly different than HR's but mine is almost just as clean.
	- [A Recipe for Solving Toy Problems](https://docs.google.com/document/d/1KlU7nxRKiicGSsMN89mog06GozqfYlyh0L3DRC3WYFk/edit)
	- [We Are Typists First, Programmers Second](https://blog.codinghorror.com/we-are-typists-first-programmers-second/)
	- Completed interview videos for 4 problems, did the rest without recording.
		- Flipper
		- Big Flipper
		- Outliers
		- Transpose
		- Find the Pair
		- Oh yeah? Rotate this!

### January 12, 2017
Getting closer and closer to Hack Reactor PCA.

- Hack Reactor Prep
	- Completed the final problem "Divide and Conquer" which is just Binary Search. I did it recursively, however using a while loop is much more efficient and I will try to do that again later while at work.
	- I got really lazy and didn't map out my solution, so I ended up thrashing about missing a +1. Just goes to show that you cannot skip the process and expect good results!
	- **HACK REACTOR PREP COMPLETED**
	- ![Hack Reactor Prep 100%](http://i.imgur.com/yV2ZFv3.png)
- Hack Reactor Precourse
	- First checkpoint (5/6) - I messed up the CSS border question thinking it was TLBR, but it's TRBL.
	- Going through the slides for _Prerequisite Studies: Basic JavaScript, CSS, and HTML_ I just realized that Array properties can be accessed via dot notation and the length PROPERTY is just array.length. **How the fuck did I not make this connection before?**
	- Finished all slides for _Prerequisite Studies: Basic JavaScript, CSS, and HTML_
	- READ: [How to Use Terminal: The Basics](http://mac.appstorm.net/how-to/utilities-how-to/how-to-use-terminal-the-basics/)
	- COMPLETED: [Git Immersion](http://gitimmersion.com/) Labs 1 - 30
		- ![Git Immersion](![Git Immersion](http://i.cubeupload.com/5ADNqa.png))
		- I learned about tagging individual commits. You can checkout by tag name as well.
		- Use _git reset_ to reset the staging area.
		- USe _git amend -m_ to amend to the previous commit if there was only a minor change. This would've been a very useful command at times.
		- _git checkout -b < branchname >_ is a shortcut for _git branch < branchname >_ followed by a _git checkout < branchname >_.
		- YOUTUBE SERIES: GitHub & Git Foundations: [Get Up and Running](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-)
		- [The seven rules of a great git commit message](http://chris.beams.io/posts/git-commit/#seven-rules)
		- Finished _Our Development Workflow: Git and the Command Line_
			- Missed one question in the checkpoint because I confused where the local repo was cloned from versus the original repo. My forked repo that I will clone from is the **REMOTE** and the repo I forked originally is the **UPSTREAM**.
