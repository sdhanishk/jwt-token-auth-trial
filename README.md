# Authentication and Authorization trial

Created this project to understand authorization using JWT with nodejs.

1. To get things ready
```
npm i
```

2. To start servers
```
npm run dev
npm run auth
```

3. Routes
```
/login - To get an access token and refresh token for the provided username

/posts - To get the posts of the logged in user

/token - Currently the expiry time of the access token is set to 30 seconds, after expiry to refresh the access token use this route

/logout - Delete the refresh token of the logged in user inturn logging the user out and preventing further refreshing of token until logged in back
```