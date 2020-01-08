


## Prerequisites

What things you need to install the software and how to install them


| Location                                                     | Suggested Version       |
| -------------                                                |:-------------:|
| <a href="https://nodejs.org/en/">NodeJS</a>                     | >= 6.0.0 |
| <a href="https://nodejs.org/en/">npm</a>                        | >= 4.0.0 |

# Deployment with Now
Out the box, this setup supports deploying to https://zeit.co
```$xslt
npm i now -g
now
```

## Installing
```
npm i
```

## Running
**Development**

Hot reloading for client / server
```
npm run dev
```

RUN LOG :
-----------

IM-LP-681:nextjs-redux detiwari$ sudo npm i now -g
Password:

> now@16.7.1 preinstall /usr/local/lib/node_modules/now
> node ./scripts/preinstall.js

/usr/local/bin/now -> /usr/local/lib/node_modules/now/dist/index.js
+ now@16.7.1
added 1 package in 7.051s
IM-LP-681:nextjs-redux detiwari$ now
> No existing credentials found. Please log in:
> Enter your email: detiwari@innominds.com
> Error! Please sign up: https://zeit.co/signup
IM-LP-681:nextjs-redux detiwari$ now
> Error! The content of "~/Library/Application Support/now/auth.json" is invalid. No `token` property found inside. Run `now login` to authorize.
IM-LP-681:nextjs-redux detiwari$ now login
> Enter your email: detiwari@innominds.com
> Error! Please sign up: https://zeit.co/signup
IM-LP-681:nextjs-redux detiwari$ now login
> We sent an email to detiwari@innominds.com. Please follow the steps provided
  inside it and make sure the security code matches Nice Oyster.
✔ Email confirmed
> Congratulations! You are now logged in. In order to deploy something, run `now`.
IM-LP-681:nextjs-redux detiwari$ now
> Deploying ~/nextjs-redux under detiwari
> Using project nextjs-redux
> Synced 2 files [3s]
> NOTE: This is the first deployment in the nextjs-redux project. It will be promoted to production.
> NOTE: To deploy to production in the future, run `now --prod`.
> https://nextjs-redux-1w140mzlg.now.sh [11s]
> Ready! Deployment complete [1m]
- https://nextjs-redux-livid-chi.now.sh
- https://nextjs-redux.detiwari.now.sh [in clipboard]
