# cypress-testing

Follow the course of [pluralsight](https://app.pluralsight.com/library/courses/cypress-end-to-end-javascript-testing/table-of-contents) 

## Cypress integration to the project

```Javascript
npm install cypress --dev
```
After this is finish, cypress creaes an integration cypress 


Add the next script to your package.json
```Javascript
"cypress": "cypress open"
```
run with 
```Javascript
npm run cypress
```

this will generate a cypress folder the first time you run it, under it you'll find fixtures, integration, plugins and support to get you started.  

The integration folder is were new test will be placed.

- Fixtures are used as external pieces of static data that can be used by your tests.


Other references
[Add cypress to your react app](https://medium.com/swlh/add-cypress-tests-to-your-react-app-75f7a8e1f18b)
[Cypress documentation](https://docs.cypress.io/guides/getting-started/installing-cypress.html#npm-install)