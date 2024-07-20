## API Testing Using Postman@
Welcome to API Testing using Postman. This testing is handler request and assert the response from assert time to data body.


## Framework and How to Install
- clone the repo

### Run with Postman
- Import json to postman
- Or click documentation in evidence

### Run with Newman
- npm install newman 
- newman run [collection.json] -e [environment.json]

### Run with Html Reporter
- npm install -g newman-reporter-html
- newman run [collection.json] -e [environment.json] -r html

## API / Features
Features tested includes:
- uploads an image
- Add a new pet to the store
- Update an existing pet
- Finds Pets by status
- Find pet by ID
- Updates a pet in the store with form data
- Deletes a pet
- Returns pet inventories by status
- Place an order for a pet
- Find purchase order by ID
- Delete purchase order by ID
- Creates list of users with given input array
- Get user by user name
- Updated user
- Delete user
- Logs user into the system
- Logs out current logged in user session
- Creates list of users with given input array
- Create user

## Evidence

**Html Report**

[https://hema-kun.github.io/API-Postman-PetStore/]

**documentation**

[https://documenter.getpostman.com/view/20672644/2sA3kPoj9J]
