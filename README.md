# start

Create a file .env and add `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET`

Lastly, fill out the form with the following information:

Go to github settings -> developer setings -> OAuth and fill out the details

Application Name: OAuth Project (or any name for your project)
Homepage URL: http://localhost:3000
Authorization Callback URL: http://localhost:3000/auth/github/callback
Click “Register application”.

```
npm start
```
