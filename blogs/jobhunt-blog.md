# Jobhunting Bloghunting

This blog is probably more of a tracker/todo list for my progress looking for my first developer role. I'll list what I want to achieve each week and my goals for each day. I'll also add any thoughts/observations/ephemera plus articles I've read.
There's some larger topics I'll want to write about as well which I'll create separate blogs for and link to them from here.

## Overview

  * [Week 1](#Week-1)
  * [Week 2](#Week-2)
  * [Week 3](#Week-3)

## Week 1

### Tasks for week 1

- [x] Attend Careers Fair
- [ ] Update CV
- [ ] Update LinkedIn
- [x] Apply for Careers Fair jobs
- [x] Decide on what coding project I want to work on this week
- [ ] Write a blog about why I chose to move into coding

### Daily expectations

* Do an hour of coding each day - start with Gilded Rose design project
* Meditate for 10 minutes
* Do 20 minutes of exercise

### Day 1 - 19th August

- [ ] Do an hour of Gilded Rose design project
- [x] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [ ] Update CV
- [ ] Update pinned repos on Github
- [x] Set up Huntr, list a job on it
- [x] Read jobhunting pills
- [x] Attend process review workshop
- [x] Ask Becks what to include in this blog (how open should I be?)


* Fairly admin and preparatory work heavy day today, finding out what to expect and getting as many ducks in a row as possible.
* Huntr looks really cool, should help a lot tracking job applications. I can easily lose track of these things, so having it in one place should help.
* I also need to establish a daily rhythm/routine for this jobhunt so that I'm staying focussed and give myself the best chance of success.
* I have a review tomorrow, so attending the process review workshop should give me a sharpener on coding skills. Especially as I have written in Ruby :gem: for a couple of weeks now. Here's hoping it comes flooding back 🤞
* I missed meditation with Dana, which annoyed me a bit as it's good to hear her mini talks about open and focussed attention. Also at the start she asks the older cohorts what advice they'd share with their day one self and I wanted to share some advice about taking time to reflect each day about what you've learnt (which would be hypocritical as it's something I didn't manage, but if anyone else there started doing it, it would be hugely beneficial).
* Helpful chat with Becks, I've got some areas to work on:
  * Have a clear story about what took me into coding
    * Focus on how moving back to London gave me a chance to get back to a more logical/problem solving line of work
  * Improv has given me a lot of chances to be a leader
  * I've done well in retail/trainign field and improv field, p
  * Ask employers what they're looking for in junior devs and use that to find 3 key skills they're looking for to evidence
* Attended process review workshop and attempted the Echo kata. I could have spent more time planning how the app would work. I struggled with stubbing user input, with more time I feel I could have got there. I feel like I could give more time to planning, but also don't want all of my time to be spent planning. I need to look into how you TDD an app that prints to STDOUT and takes arguments from STDIN.

##### Setting expectations for the jobhunt

At the start of the course I had a good habit of setting daily goals but didn't do this towards the end of the course as the syllabus became less structured/prescribed and I think my learning suffered as a result. I still learnt, but it wasn't as focussed or as deep as it could have been. Daily goals should correct that and keeping track of whether I've achieved them or not on here should keep me honest.
Putting exercise and meditation on there reminds me to look after my general wellbeing too.

##### Articles I've read today

* [From Codeschool to Candidate](https://medium.com/@perrysetgo/making-the-jump-from-codeschool-to-candidate-8881ad3563bd)
  * Food for thought about establishing your own niche within the code community and how that benefits you in the long term
  * Made good points about going to conferences, as you have a deeper engagement with a subject that way and on how to leverage your previous experience for the skills you've demonstrated.

### Day 2 - 20th August

- [ ] Do an hour of Gilded Rose design project
- [ ] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [x] Sit a Review
- [ ] Add Projects section to CV
- [ ] Research 2 of the companies at the Careers Fair
- [ ] Write a blog about why I chose to move into coding


* Good review. Glad I practiced setting up a couple of projects beforehand to get that part down, even tho it's only a small part of the project. I took on board the feedback from my previous one about asking for edge cases and refactoring my spec file to include a `before(:each)` block.
  * The reviewer said my process was 95% of the way there which is encouraging. Hopefully his more detailed feedback can shine a light on that final 5%.
  * His point about using the `it` statements as commit messages when committing straight after making a test green was helpful.

##### Articles I've read today
* [The Agile Sweatshop](https://www.forbes.com/sites/stevedenning/2019/08/18/another-form-of-fake-agile-the-agile-sweatshop/amp/)
  * Article about how Amazon's Fulfillment Centers are not Agile while other parts of the company are.
  * Makes a good point about how if a whole firm is not run in an Agile way and there are parts of a company that are run with bureaucratic mindsets, the company will likely fairly soon slide back into bureaucracy. Teams will stop being self-organising and the firm is more focussed on maximising shareholder value than delivering value to the customer.
  * Counter to this though, as was discussed at the XTC meeting on Dark Agile two weeks ago, the Agile methodology is laid out in the Agile Manifesto for Software Development. That may have an impact on how transferable the ideas in it are to other parts of a company such as HR, strategy and finance, thus making it harder to make a company wholly Agile.

### Day 3 - 21st August

- [ ] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [ ] Add Projects section to CV
- [x] Research companies at the Careers Fair
- [x] Attend Careers Fair


* Good to hear that other people are feeling nervous about the Careers Fair. Someone made an interesting point about how other people saw it as we're going from collaborating for 12 weeks to now competing.
* My expectation is to have at least 1 interesting conversation with an employer (other people wanted to have a meaningful conversation but I'm happy to stick with interesting).

##### Careers Fair

* I was really surprised by a couple of the companies at the Careers Fair. Alfa I already knew about after Brannan's talk last week, but PensionBee was one that on paper I thought would be a fairly dry place to work. However I really liked what Johnathan (the CTO) and Bat (a former Maker who has been there for a couple of years) had to say about their onboarding process and culture.


##### Articles I've read today
* [The N+1 Query](https://www.sitepoint.com/silver-bullet-n1-problem/)
  * Database queries that need to load the children of a parent-child relationship encounter this problem.
  * Each query you make to a database takes time, so the more you make, the longer it takes to return all the data. Rather than making 100 queries each returning 1 piece of information, it's preferable to make 1 query that returns 100 pieces of information.
    * Say you have a blog app, and you're using an ORM to display the 5 (the *n* in this example) most recent articles, so you send a query (the *+1*) to return those 5 articles and then for each of the 5 articles a query is sent to return the author of the article.
    * A more efficient way is to eager load associations, so your initial query (using a Rails ORM) `includes` the authors. This way you're making 2 queries, 1 to retrieve the articles and then querying the authors of those articles within what gets returned.

### Day 4 - 22nd August

- [x] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [ ] Add Projects section to CV
- [x] Attend Strategy coaching session
- [x] Meet Laurie at Spotify for lunch
- [x] Prep application for Alfa
- [ ] Complete Profile section of Jobs Hub

##### Strategy Coaching

Max gave me these goal setting prompts:
  1. Investigate the job specs for your dream job (thinking 3-5 years ahead). Suggest a min sample size of 10 job specs.
  2. Identify the type of job that you can apply to and use as a stepping stone towards your goal
  3. Investigate the job specs for the entry level roles that will act as a stepping stone towards your dream job. Suggest a min sample size of 10 job specs.
  4. Start working on a project that demonstrates your grasp of the most relevant technologies, processes and behaviours.

### Day 5 - 23rd August

- [x] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [ ] Add Projects section to CV
- [x] Complete Profile section of Jobs Hub
- [x] Submit application for Alfa
- [ ] Submit application for PensionBee
- [ ] Submit application for yu life

##### Articles I've read today
* [The End of Agile](https://www.forbes.com/sites/cognitiveworld/2019/08/23/the-end-of-agile/amp/)

## Week 2

### Tasks for week 2

- [ ] Update CV
- [ ] Update LinkedIn
- [x] Decide on what coding project I want to work on this week
- [ ] Write a blog about why I chose to move into coding

### Daily expectations

* Do an hour of coding each day - work on a React project
* Meditate for 10 minutes
* Do 20 minutes of exercise

### Day 9 - 27th August

- [x] Start React tutorial
- [ ] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [x] Add Projects section to CV


* Working on the React tutorial today, building a tic-tac-toe game, with a view to completing it on Thursday and then starting my own project in React which will run into next week.
  * Jake Napper, a former Maker, shared [this tutorial](https://www.youtube.com/watch?v=Ke90Tje7VS0) that he found helpful.
* Added Acebook and Guilt Tripper projects to CV

### Day 10 - 28th August

- [ ] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [x] Attend lunchtime talk on tech interviews
- [x] Attend Mock interview with Max
- [x] Pair with Rachel on adding feature tests to our Makers final project


* There's a fair bit of interview prep today, hopefully gain some insight into how to go about answering questions from the lunchtime talk.
* Not looking forward to the mock interview, almost didn't book it but grateful to Becks for getting me to do it. That apprehension is exactly the reason I need to do it!
   * Also good to get some feedback on my CV. I've added a projects section but need more projects to add to it and also more skills, hopefully Max can give me some pointers for that.
* Tech interview talk was really helpful, got greater insight
into how to get a foot in the door and approach companies.
* Mock interview went better than I thought. Need to work on my story about how I got into coding and not go up at the end of my sentences.

### Day 11 - 29th August

- [x] Meditate for 10 minutes
- [x] Do 20 minutes of exercise
- [x] Pair with Rachel on updating README and tidying up our Makers final project


* Rachel and I finished working on the feature tests we'd been working on yesterday. We decided to fork the initial repo so that the other teammates weren't surprised in an interview (or when prepping for one) by any new features/files.
  * I removed the Kingfisher pod, which was straight forward, running `pod install` after removing `pod Kingfisher` from the `Podfile`
  * [gitignore.io](https://www.gitignore.io/) was really helpful for generating a `.gitignore` - something we should have done when we first set up the repo. All the `xcuserdata` files were not needed. I removed them from the current codebase by running `git rm -r --cached .` to remove all files from the file index and then `git add .` to restore all the files except the ignored ones - much simpler than manually removing the unwanted files.
      * Ran `git rm -rn --cached .` first just to do a dry run (with `-n` flag)

## Week 3

### Tasks for week 3

- [ ] Update CV
- [ ] Update LinkedIn
- [x] Decide on what coding project I want to work this week
- [ ] Research job I want to have in 5 years, reverse engineer how to get there and look at what jobs I should get now are looking for.

### Daily expectations

* Do an hour of coding each day - work on a React project
* Meditate for 10 minutes

### Day 15 - 2nd September

- [x] Finish React tutorial
- [ ] Meditate for 10 minutes
- [x] Do 20 minutes of exercise


* Completed the [React tutorial](https://reactjs.org/tutorial/tutorial.html#what-is-react), [repo here](https://github.com/rhysco8/react-tic-tac-toe). Feels like ages since I did any work in JavaScript so this project was a nice way to ease back into general JS syntax, plus then learning React on top of that.
  * I'm building up notes about how to use React in Bear so that I have my own glossary and documentation on how to use it.
