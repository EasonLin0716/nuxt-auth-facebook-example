# nuxt-auth-facebook-example

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev
```

## Usage

You'll need a .env file to set your configs:

```
FB_CLIENT_ID=xxxx
FB_REDIRECT_URI=xxxxx
FB_CLIENT_SECRET=xxxxxx
```

To make this work, you'll need an https site to host your app. Heroku would be a good choice.

In / page, open your devtool and click Facebook Login, after redirect from facebook, you should see your data returned from node server.
