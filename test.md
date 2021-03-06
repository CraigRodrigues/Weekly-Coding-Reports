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
		- ![Git Immersion](http://i.cubeupload.com/5ADNqa.png)
		- I learned about tagging individual commits. You can checkout by tag name as well.
		- Use _git reset_ to reset the staging area.
		- USe _git amend -m_ to amend to the previous commit if there was only a minor change. This would've been a very useful command at times.
		- _git checkout -b < branchname >_ is a shortcut for _git branch < branchname >_ followed by a _git checkout < branchname >_.
		- YOUTUBE SERIES: GitHub & Git Foundations: [Get Up and Running](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-)
		- [The seven rules of a great git commit message](http://chris.beams.io/posts/git-commit/#seven-rules)
		- Finished _Our Development Workflow: Git and the Command Line_
			- Missed one question in the checkpoint because I confused where the local repo was cloned from versus the original repo. My forked repo that I will clone from is the **REMOTE** and the repo I forked originally is the **UPSTREAM**.
			
### January 13, 2017
Today is my last day at work!

- Hack Reactor Precourse - **TESTBUILDER**
	- Got stuck thanks to some weird bug.
	- People seem to be solving this problem without using very very simple default JS methods for Strings and Arrays. :confused:

### January 14, 2017
Finally free to focus 100% on coding!

- Hack Reactor Precourse: TESTBUILDER
	- Reading about [http://chaijs.com/](http://chaijs.com/)
	- [Chai assertion guide](http://chaijs.com/guide/styles/#assert)
	- [Red/Green/Refactor TDD](http://www.jamesshore.com/Blog/Red-Green-Refactor.html)
	- Completed testbuilder. I tried to make every function do just ONE thing and it made it very easy to add to my function when yo break it down into doing one thing rather than having a bajillion if statements everywhere.
	- ![Finished Testbuilder!](http://i.imgur.com/vSu7R6y.png)
- [Pro Git book](https://git-scm.com/book/en/v2)
- Jennifer wrote a cool Medium post: [The Secret to Becoming a Better Programmer is Speaking](https://medium.com/@ratracegrad/the-secret-to-becoming-a-better-programmer-419cab4ad942#.l59kv7dxc)
- [Things you probably didn’t know you could do with Chrome’s Developer Console](https://medium.freecodecamp.com/10-tips-to-maximize-your-javascript-debugging-experience-b69a75859329#.kjsiwdc51)
- Hack Reactor Precourse: JavaScript Koans
	- WTF you can pass strings into Function and get a function out of it?
	- [JavaScript functions as strings as functions](http://logicmason.com/2013/javascript-functions-as-strings-as-functions/)
	- http://javascript.crockford.com/prototypal.html
	- Finished all koans except the Euler-esque bonus problems.
	- [What's the difference between assertion library, testing framework and testing environment in javascript?](http://stackoverflow.com/questions/25678063/whats-the-difference-between-assertion-library-testing-framework-and-testing-e)
	- [Unit Test Your JavaScript Using Mocha and Chai](https://www.sitepoint.com/unit-test-javascript-mocha-chai/)
- Hack Reactor Precourse: Debugging/Underbar Part 1
	- identity
	- first
	- last
	- each
	- indexOf
	- filter
	- reject
	- uniq
	- map
	- pluck

### January 15, 2017
- Hack Reactor Precourse: Underbar Part 2
	- reduce
	- contains
	- every
	- some
	- extend
	- defaults
	- once (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)
- Hack Reactor Precourse: [Explore and Master Chrome DevTools](http://discover-devtools.codeschool.com/)
	- Element and inspector.
	- Updating local source file and saving it real local source.
	- Using the debugger and catching exceptions.
	- Breakpoints.
	- Page Speed Google Chrome extensions.
	- Optimizations such as minifying your JS or loading it after the CSS asynchronously.
	- Resizing images instead of letting the browser do it. Use PNG for icons instead of JPG.

### January 16, 2017
 - Hack Reactor Precourse: Underbar
	 - memoize
	 - delay (learned more about using an anon callback)
	 - shuffle ([Fisher-Yates shuffle algorithm](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle))
 - I spent 46 hours last week coding despite it being my last week at work! Dunno how I pulled that off.
 - Feeling sick. All stuffed up and coughing. Best thing ever for first day of Precourse.
 - Installed Floobits.
 - Hack Reactor Precourse: Javascript Koans Bonus Problems
	 - Find largest palindrome of two 3 digit numbers.
	 - Wrote tests for the rest of the bonus functions (should've done this first).
	 - Finished all Extra Credit problems (all project Euler problems or very similar to them).
 - Toy Problems for the next two weeks (1-2 hours a day)
	 - I will run through Coderbyte (or similar) and use Haseeb's method to get high level with the solutions.
	 - Write out in plain english how I would solve the problem.
	 - Check solution. If my logic differs (greatly) from the optimal solution provided then I will go back and deeply understand the solution.
	 - Re-implement that solution from scratch.
	 
- Course: [Advanced Javascript](https://frontendmasters.com/courses/advanced-javascript/)
 - Scope
 - Negatives of anonymous function expressions
 - Lexical scope
 - Nested scope
 - Eval keyword & With keyword
 - IIFEs
	 
- Hack Reactor: Precourse Accept Class #1
 - Opening lecture on expectations and the assessment (only 50% pass - no second chance).
 - Advanced JavaScript II - Scope
 - Advanced JavaScript II - Execution Contexts
 - Advanced JavaScript II - Contexts & Objects (a little confusing)
 - Advanced JavaScript II - Closures (setInterval is different than setTimeout. Interval is continuously called)
 - Undefined + Number = NaN
 - Refactored detectNetwork to use objects instead of functions all over the global space.
 - Refactored underbar functions map and filter using reduce.
 - I think it's best to use the parameters accumulator and current when using reduce. I find it best to do that when it comes to understanding how reduce works. It is such a damn powerful function.
 - ``` array.reduce(function(accum, curr) { return accum.concat(curr); }, [])' ```
 - The first parameter is the accumulator unless we pass in an accumulator which can be an object like an array!
 - Actually maybe it is better to use prev & curr since you don't always have to return the accumulator, you can disregard that and return something else entirely.
 - Reduce makes my brain hurt.

### January 17, 2017
- Advanced JavaScript
	- Block scope and 'let'
	- Problems with 'let'
	- Dynamic scope
	- Hoisting (let does not hoist!)
	- The 'this' keyword
		- Implicit binding
		- Default binding
		- Explicit binding (call or apply)
		- Hard binding (using 'bind')
		- The 'new' keyword

![Advanced JavaScript - 4 rules for this](http://i.imgur.com/EDFcg1g.jpg)

- Hack Reactor Precourse: Underbar
	- invoke
	- sortBy
	- zip
	- flatten
	- intersection
	- difference
- CS50 Video: [Command Line](https://www.youtube.com/watch?v=poT5Yd0Ag8I)
- Hack Reactor Precourse: [HTML & CSS](http://learn.shayhowe.com/html-css/)
	- Building Your First Web Page
	- [CSS Terms and Definitions](https://www.impressivewebs.com/css-terms-definitions/)
	- Getting to Know HTML
![Building HTML page structure](http://learn.shayhowe.com/assets/images/courses/html-css/getting-to-know-html/building-structure.png)
	- Getting to Know CSS
	- Opening the Box Model (**Every element on a page is a rectangular box.**)
![Box Model](http://learn.shayhowe.com/assets/images/courses/html-css/opening-the-box-model/box-model.png)
- Hack Reactor: Precourse Accept Class #2
	- Readiness Assessment Expectations.
	- Implemented max and min in underbar.
	- HTML/CSS: Positioning Content
	- HTML/CSS: Working with Typography
	- Code School CSS Cross Country Level 1-4
- Code School: Regex Course

### January 18, 2017
#### Coderbyte Toy Problems
<br>
<br>
[Subset Sum Problem](https://coderbyte.com/algorithm/subset-sum-problem)

Easy to brute force, however a Dynamic Programming solution is explained in the video and it's insane.

[Second Great Low](https://coderbyte.com/solution/Second%20GreatLow)

Here I would create a set from the original array and then pass that Set object back into an array. Sort that new unique set array and from lowest to highest. Then return the 1st index and the value in the [last index - 1] (assuming there are at least two values). If there is only one value then return index [0] for both.

[Division Stringified](https://coderbyte.com/solution/Division%20Stringified)

On this problem you would take the ceiling of (num1 / num2) to get the answer in the regular format. From here you need to convert the number to a string and put that string into an array of char numbers.

Also at this point it's possible to just stringify the number to '123456' and use regex to add in commas at the correct points. Without regex I would take 12346 and make it ['1', '2', '3', '4', '6']. Reverse this array to ['6', '4', '3', '2', '1'] and then have a loop and counter than after 3 numbers have been passed it will splice in a ',' character.

Once the end has been reached we reverse the array again ['1', '2', ',', '3', '4', '6'] which we join into the final result of 12,346.

Solution Review: It looks like the solution used Math.round instead of Math.ceiling so I messed that part up. Also see [this StackOverflow post](http://stackoverflow.com/questions/18754109/regular-expression-to-insert-using-replace-method-in-javascript) about using regex to insert the commas. ```/\B(?=(\d{3})+$)/g```

#### CodeSchool: Try jQuery

1. Introduction to jQuery
2. Traversing the DOM
3. Working with the DOM
4. Listening to DOM events
5. Styling/Animation

#### Hack Reactor Precourse: Twittler
- Forked the repo and took a look. I want to get a deep understanding of how the data is generated so I will take 1-2 hours to read over that code and understand it.
- Once I understand the code I will make a list of reqs and maybe even put some tests in there if I'm really feisty.
- Only once all functionality has been completed will I being to style my page.
- My wishlist is really I want the page to:
	1. Automatically refresh the tweets and alert the user as to how many new tweets they have.
	2. The user clicks a button to see the new tweets.
	3. A user should be able to add their own tweets.
	4. A user should be able to see all the tweets for a person by clicking their profile name (user stream).
	5. Each tweet should have a timestamp.
	6. Each tweet should have a 'seconds ago' feature.
	7. Show a user profile picture and number of tweets they have created.
	8. Show a worldwide trends list depending on the hashtag counts.
	9. Have a 'refresh now' button to instantly refresh rather than waiting.
	10. I want each user to have a small avatar icon of their actual face.
	11. I want moused-over tweets to be highlighted.
	12. I want there to be "endless scroll" functionality
	13. Chocobo Icon and favicon
	14. Click hashtag and only show tweets that have that hashtag
	15. Have the title update showing the number of unread tweets. Example (50) Twittler
	16. Click a tweet to pop it out.
	17. Implement a simple search.
	18. Click a hashtag and only show tweets with those hashtags

- Helped out a fellow student for an hour or two working through some underbar problems involving reduce. I had never pair programmed before and it was fun. I tried my best to steer towards understanding why something wasn't working rather than giving out an answer.
- I got much better understanding of closures because of my pairing.
