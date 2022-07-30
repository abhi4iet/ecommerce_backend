# Mock JSON server

A mock json server for basic e-commerce PSC. You can easily deploy the API to services like Heroku by simply pushing the repository there.


```sh
step 1 :- Create an account on Heroku
```
Go to [Heroku](https://www.heroku.com/)

```sh
step 2 :- Grab this project setup
```

```sh
step 3 :- Modify endpoints and data in db.json according to your choice
```

## Installation

Run npm to install all dependencies:

```sh
npm install
```

Now you are ready to deploy to Heroku:

```sh
# Login with your Heroku account
heroku login

# Create the project
heroku create your-api-project-name

# Deploy to Heroku
git push heroku master
```

Test your API by running:

```sh
heroku open
```

## Editing the initial data

The database is in the file **[db.json](db.json)**. You can edit the JSON information there.

## HTTP Requests & Endpoints

Refer to the [json-server documentation](https://github.com/typicode/json-server) for how to use your API.