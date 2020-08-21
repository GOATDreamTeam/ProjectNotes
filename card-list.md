# List form of card/tickets ideas

## Front-end:
- search component with input and button
  - post or get request makes a request to BE and returns a list of plants matching the results, and at the same time the backend stores the search results (common and scientific names) or the search term in a model in the DB.
- test search input is received in browser dev tools
- test the button
- header component to display search component
- snapshot test the header component
- add header presentational component after search bar component has been included to app.js to verify it is working in browser
- autocomplete feature for use in search bar component (could be a concern with query/rate limits on API)
  - *seed common and scientific names in DB to mitigate this risk?*
    -Seed the DB as users are searching!  (100 most commonly searched, for example).  Search gets better/feature improves as more users search. ORRR store the most commonly clicked on plants instead of the searched names.
    -Also want to pair with a fuzzy search (https://norvig.com/spell-correct.html) or check for an npm package
    - test in browser
    - test in compass

- decide if we want the splash page photo cycle to be changed daily, changed every time the app is opened, or changed every n minutes/seconds, etc.
- start with hard-coding on front-end and be sure it's working, then start implementing on the backend as tech debt.
  - cross-fade npm package?
    - https://www.npmjs.com/package/react-crossfade-image
    
- write a component for monochrome feature (save implementation for last) and add to header presentational component

- write a footer presentational component that has a link to the About Us page.
- create an about us page and link to it in the footer


## Back-end:
- *service call to deployed DB (Heroku) for autocomplete feature?*
  - write test for this service call

Tech Debt:
- find a selection of photos to cycle through on the front-end splash page. Add to an array and use a Math.random function to choose a random photo to display.
  

