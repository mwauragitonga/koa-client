
# Project Title

Admin Dashboard for Koa Grid API Test Application.
You can use this dashboard to query the API directly and also view all the grid coordinates stored in the application's mySQL database.
The Application is a simple html dashboard using Javascript (Ajax) to make HTTP requests to the backend via the API.

## API URL

While there are no env variables required, you will need to set the API URL to your corresponding IP address. E.g http://127.0.0.1:8000/ if you are serving 

`login.html`
ln 79: url: "http://127.0.0.1:8000/auth/login",
ln 125:  url: "http://127.0.0.1:8000/api/token/",
`dashboard.html`
ln 215: var url = "http://127.0.0.1:8000/api/closest-points/";
ln 258:  var url = "http://127.0.0.1:8000/api/closest-points/";
    
## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```
Open login.html

```bash
  Remember to add your koaclient host the below arrays under settings.py in case you encounter CORS errors trying to connect to the API
   ALLOWED_HOSTS = []
   CORS_ALLOWED_ORIGINS = []

```


## Tech Stack

**Client:** HTML, Javascript, Bootstrap CSS

