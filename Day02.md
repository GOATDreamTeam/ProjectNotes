# Day 2 

## Canvas Guideline
### Tasks 
-  create an organization 
    - [Github Organization](https://github.com/GOATDreamTeam)
        - [Github Backend](https://github.com/GOATDreamTeam/backend)
            - [dev branch](https://github.com/GOATDreamTeam/backend/tree/dev)
                - made public
                - changed restriction for PRs approved 
                -  changed restriction for CI
        - [Github Frontend](https://github.com/GOATDreamTeam/frontend)
            - [dev branch](https://github.com/GOATDreamTeam/frontend/pull/1) 
                - made public
                - changed restriction for PRs approved 
                -  changed restriction for CI
    - Create a basic README.md file within your repos that contains the names of all the members as well as a short description of the project.
        - done except we need to solidify our description 
    - Setup autodeploy on Heroku and Netlify.
        - [Heroku Staging](https://goatdreamteam.herokuapp.com/)
        - [Heroku Production](https://goatdreamteamproduction.herokuapp.com/)
        - [Netlify Staging](frontend-master.netlify.app)

### PM Tools 
- [Our Github Projects](https://github.com/orgs/GOATDreamTeam/projects)
    - [Frontend](https://github.com/orgs/GOATDreamTeam/projects/4)
    - [Backend](https://github.com/orgs/GOATDreamTeam/projects/3)
    - [Project Notes](https://github.com/orgs/GOATDreamTeam/projects/2)
    - [Mood Board](https://github.com/orgs/GOATDreamTeam/projects/1)

## Rubric Guideline for Day 2 
- setup repos and workflow tooling
    - done! See above for links to specific PM Tools 
- continue research and exploration
- begin to plan and test your plan with proof of concept code
    - What technologies will you use (redux?, react?, monogodb?, postgres?, etc...)
        - Frontend: 
            - D3 or GraphQL depending on our needs
            - Sass 
            - Responsive Web Design 
            - Motion Loading Screen: https://www.framer.com/api/motion/
        - Backend: 
            - Node 
            - Mongodb 
    - User stories
        - "As a new plant lover, this app will allow you to search through different plants and the entire plant kingdom, to gain more information on a specific plant and view images of their different phases."
        - "As a seasoned plant lover, this app will allow you to search through different plants and the entire plant kingdom, to gain more information on a specific plant and view images of their different phases and perhaps record specific detail for future use."
    - Models
        - User 
            - email
            - passwordHash 
        - Plant
            - scientific name
            - common name 
            - images[{flower: image_url}, {leaf: image_url}] 
    - Routes (you may not need all CRUD routes for every model)
    - Wireframe
        - draw.io link 
    - Component Hierarchy
    - Define an MVP
    - Start breaking up work into small pieces
- DEMO: present your final idea
    - Ryan says, whatever you have to show 
    - Tell us of the idea that we've chosen 
        - show the API and a request to that API and what it gives back 

