# Day 03 

## Canvas Submission Guidelines 
### Wireframes 
- provide an image of your wireframe to your project


## GamePlan / Process for today

### Individual/Group Priorities

Rachel:
- wireframing (plan to narrow D3 experimentation)
- maybe split into groups?
    - D3 learning 

Breeann:
- whatever is the most time consuming 
    - breaking into D3, if it's a failed attempt then changing to graphql
- backup plan suggestion:
    - under distributions, introduced, species count 
    - get graphql and get species count and representing in a pie graph the different distribution of counts 
    - even though its nested, it could be an approachable display of data 

Langston:
- learn about D3 before wireframing / graphQL might be faster 
    - recommends everyone take time to learn about D3 before we can think about what will be displayed 


Nikki:
- autocomplete problem domain(with search bar?) 
- wireframing
    - what if we could break out the visions we have for how something should look 


Briseida:
- whoever spends time with D3, should spend some time with backup options just in case 
- divide ourselves into groups
    - D3 / data visualization options /  chooose one to implement, even if its using dummy data 
    - a group/person that writes the shape of what we want to return 


Notes:
- we can filter out null values from the API
- Ryan's Feedback:
    - user stories 
    - list of questions on day 3, begin the work, some of these q's dont have answers yet but we should start thinking about the architecture of this app
        - could be as small as taking our wireframe and drawing boxes around components 
        - what is the user expecting to see, therefore the utility of user stories 
    - at what point should we have tickets?
        - as you start answering questions, start cards 
        - start creating cards this afternoon based on wireframe 
        - user stories: who will use our app? what needs will our app fulfill for them?
        - cards: breaking into smaller pieces
        - we are amazing, never compare yourself, you are brilliant 
        - don't stress about it

-------

- Check API for edible boolean and veg boolean
    - play with this on postman to see how many objects the API returns
    - make sure there's useable values in the "growth" object in the API
    - it might be easier to store edible/veg boolean in mongodb // something we can be asked to be walked through later on 
- D3
    - will we be able to render something in D3?
    - returning some kind of data to visualize in whatever graph/pie/map form
        - Map (?)
            - research map graphics
            - vector map graphic saved as an svg in which we would be able to import into D3
- General
    - animation library : https://www.framer.com/api/motion/
    - make time to individually draw out our visions/ideas for the site, then reconvene to bring them together in one place 
    - spend some time with dribble 
    - send code to Ryan for review/feedback 
- Big questions
    - What if we started building with mobile first?

## Group Priority  / Plan

- user stories - group ? 
    - jump off Breeann's og user story
        - "As a new plant lover, this app will allow you to search through different plants and the entire plant kingdom, to gain more information on a specific plant and view images of their different phases."
            - Rachel would add: "I would love to search for a plant by its common name."
        - "As a seasoned plant lover, this app will allow you to search through different plants and the entire plant kingdom, to gain more information on a specific plant and view images of their different phases and perhaps record specific detail for future use."
            - Rachel would add: "As a seasoned plant lover, it would be nice to see how many diff species of Plant there are within a specific area"
- graphQL / D3
    - Nikki demo's graphQL / some learned key points, what stood out, valuable info
    - 45 min to individually explore graphQL/D3

- 2:15/2:30
    - mob getting data viz rendering on a page (Nikki can branch off here to:)
    
- search input
    - autocomplete feature 

3:45, come back together 
- wireframe
    - dribble for inspo (since we're maybe leading with mobile first)
    - placeholder images 
    - does not to be super complete or set in stone, but build out the shell as fully as possible
- start cards (no need to get super detailed with it because new cards will emerge as we keep building out app)
    - do this alongside wireframe to make it more approachable 




### User Stories 
[Code Fellows Outline Requirements](https://alchemycodelab.github.io/common_curriculum/projects/UserStories)
1. Title: 
2. User Story Sentence 
3. Feature Tasks
4. Acceptance Tests 


### Software Requirements 
[Software Requirements Document](https://alchemycodelab.github.io/common_curriculum/projects/SoftwareReqs)
- Create a new file called requirements.md and include your software reqs for the project.  

### Domain Modeling 
- Draw out entities for reach component of your project and how they are related to each other. Determine the relationships between the functions/methods and required components of your app.
- Include in your domain model, include the names and data types of your entities.
- Helpful Resources: 
    - [Brief introduction to Domain Modeling](https://medium.com/@olegchursin/a-brief-introduction-to-domain-modeling-862a30b38353)
    - [Domain Modeling](https://www.scaledagileframework.com/domain-modeling/)
    - [Domain driven architecture diagram](https://medium.com/nick-tune-tech-strategy-blog/domain-driven-architecture-diagrams-139a75acb578)
- Include this domain model in your README.md file located in your project GitHub repo

## Rubric Submission Guidelines 
- solidify wireframe and data models
- begin coding application architecture
    - where are you going to put your code?
    - what services will you need?
    - what routes will you need?
    - what components will you need?
    - what hooks will you need? DEMO: wireframe
