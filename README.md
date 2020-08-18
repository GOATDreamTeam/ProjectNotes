# ProjectNotes
Notes, planning, collab, and agreements

# Final Project

## Working in groups with git

* Make an org.
* make 2 repos. one for back-end and one for front-end
  * deploy the be to heroku and fe to netlify
* Keep the PRs small with many commits
  * features/CARD-NUMBER-NAME_OF_FEATURE (features/card-1-create-people-route)
  * fix/CARD_NUMBER-NAME_OF_FIX (fix/card-2-buttons-should-be-red)
  * **WONT NEED FOR THIS SCOPE** hotfix/CARD_NUMBUER-NAME_OF_HOTFIX (hotfix/broke-prod-oops)
  * The maker of the PR is the one who merges!
  * add a useful title and description (changelog, screenshots, use humble language 
    information for review and maybe employers) to the PR
    * Fix: Buttons should be red
* on github
  * default branch dev
  * add rules to force reviews and passing tests
  * only allow squash merges

### CI/CD

* two envs (two heroku apps and two netlify apps) (my-app-staging and my-app)
  * staging - deployed from dev
  * production - deployed from main
* setup auto deploy

## Flow of the week

* Begin everyday with a team standup
  * blocked
  * explain what you did yesterday
  * explain what you will do today
  * surface if you don't know what to work on
  * surface if you think things aren't following the plan
* Instructional staff will meet with each team every day
  * we will want to see code
  * instructional staff will present a daily digest detailing areas you should refactor,
    areas you are not following your plan, and areas you are doing well in
* At 5pm each day teams will present 5-10 minutes demos of their progress to the cohort
  * during this time all teams should pause any coding activities

### Day 0 -Monday

* create team agreement
* brainstorm ideas
  * what do you want to get out of final project?
    * do you want to work with new tech?
    * do you want to work on something that benefits the community?
    * do you want to work on developer tools?
  * research your ideas: explore documentation and APIs
* **DEMO**: show us something your learned while researching ideas

### Day 1 -Tuesday

* pitch idea
* research libraries and APIs you may need
  * test the libraries and APIs to make sure they work
  * make proof of concepts
* **DEMO**: present your proposed idea and show us some API or library you may use

### Day 2 -Wednesday

* setup repos and workflow tooling
* continue research and exploration
* begin to plan and test your plan with proof of concept code
  * what technologies will you use (redux?, react?, monogodb?, postgres?, etc...)
  * user stories
  * models
  * routes (you may not need all CRUD routes for every model)
  * wireframe
  * component hierarchy
  * define an MVP
  * start breaking up work into small pieces
* **DEMO**: present your final idea

## Day 3 -Thursday

* solidify wireframe and data models
* begin coding application architecture
  * where are you going to put your code?
  * what services will you need?
  * what routes will you need?
  * what components will you need?
  * what hooks will you need?
**DEMO**: wireframe

### Day 4 -Friday

* Start implementing plan (working on cards)
* move slow
* by end of day. You should have **some** features finished
* **DEMO**: demo a complete and deployed feature

### Day 5 -Monday

* Continue working
* continue moving slow
* by the end of the day have MVP in sight
* **DEMO**: demo a complete and **deployed** feature

### Day 6 (MVP) -Tuesday

* push to main and production envs
* if your not close to MVP maybe reconsider what MVP is
* **DEMO**: demo MVP

### Day 7 (really really have MVP) -Wednesday

* Polish MVP functionality
* **DEMO**: demo polished MVP

### Day 10 (Style) -Thursday

* Stretch goals
* DON'T BREAK STUFF
* Make sure things look good
  * on the hardware you will use (projector)
* plan presentations
* Practice presentations in the afternoon
  * TAs would love to see the presentations and give you feedback

### Day 11 -Friday!!!

* continue to practice presentation on the hardware that you will use
* you should be done coding
* eat lunch
* meditate

## Preparing for presentations

### Keep a diary of what you did each day

* what did you do
* why was it easy/hard/interesting?
* 30 minute presentation
  * spend some time talking about the product
  * spend some time talking about the tech
  * spend some time talking about yourself as a developer
