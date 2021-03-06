
# Starting React App
```sh
source ~/.bash_profile
npx create-react-app kio-sl-emap
```
## Install Amplify libraries

# Bootstrap
https://create-react-app.dev/docs/adding-bootstrap/
https://react-bootstrap.github.io/getting-started/introduction/


# git

```sh
ssh-keygen

/Users/robin8a/.ssh/kio_sl_emap_rsa

cat ~/.ssh/kio_sl_emap_rsa.pub


```


```sh
cd ~/.ssh
ls
nano config

# Add

# CodeCommit hosts
Host su_amazing_leads_inception_rsa
   HostName git-codecommit.us-east-1.amazonaws.com
   User APKASWPUM4U3QFO7WQG2
   IdentityFile ~/.ssh/su_amazing_leads_inception_rsa

```

```sh
# git clone ssh://git-codecommit.us-east-1.amazonaws.com/v1/repos/kio-sl-emap

git remote add origin ssh://git-codecommit.us-east-1.amazonaws.com/v1/repos/kio-sl-emap

git push --set-upstream origin master

```

# Amplify
- https://docs.amplify.aws/cli/start/install#option-2-follow-the-instructions
- [Getting started Auth with style](https://github.com/aws-amplify/amplify-js/tree/e56aba642acc7eb3482f0e69454a530409d1b3ac)

```sh
amplify configure

```

## Init

```sh
amplify init
? Enter a name for the project su-amazing-leads
? Enter a name for the environment suamaleapi
? Choose your default editor: Visual Studio Code
? Choose the type of app that you're building javascript
Please tell us about your project
? What javascript framework are you using react
? Source Directory Path:  src
? Distribution Directory Path: build
? Build Command:  npm run-script build
? Start Command: npm run-script start
Using default provider  awscloudformation
```

```sh
amplify add hosting

kio-sl-lms robin8a$ amplify add hosting
? Select the plugin module to execute Amazon CloudFront and S3
? Select the environment setup: DEV (S3 only with HTTP)
? hosting bucket name kio-sl-lms-20200907192030-hostingbucket
? index doc for the website index.html
? error doc for the website index.html


https://master.ds3q4dungfi7s.amplifyapp.com

```

```sh
amplify publish

```


# Navegation

```sh
yarn add react-router-dom

```

# Cloud 9 config

https://github.com/dowjones/react-tutorial/blob/master/AWS.Cloud9.Instructions.md


# Leaflet Zoom 
- [Zoom further in than level 19 with leaflet javascript API?](https://gis.stackexchange.com/questions/78843/zoom-further-in-than-level-19-with-leaflet-javascript-api)
- https://leafletjs.com/reference-1.2.0.html#gridlayer-maxnativezoom


# Leaflet 3D


# UI
```sh
npm i react-select
npm i react-router-dom
npm i bootstrap
npm i holderjs
npm i jquery
npm install popper.js --save
npm audit fix
npm i geolib
```


# 
- [Share variables between components](https://medium.com/@nipunadilhara/passing-data-between-different-components-using-react-c8e27319ee69)
- https://reactrouter.com/web/guides/quick-start
- https://www.freecodecamp.org/news/react-router-tutorial/

# GPS

- [ *** works *** How to Use Geolocation Call in ReactJS](https://www.pluralsight.com/guides/how-to-use-geolocation-call-in-reactjs)

## Calculate distance
- [Geolib](https://github.com/manuelbieh/geolib)

# Redirect
- [Stack Over Flow](https://stackoverflow.com/questions/45089386/what-is-the-best-way-to-redirect-a-page-using-react-router)
- [Code redirect](https://dev.to/projectescape/programmatic-navigation-in-react-3p1l)

# React Images
- [Examples](https://reactnative.dev/docs/image-style-props)
- [W3](https://www.w3schools.com/css/css3_images.asp)

# Map drawer
http://sns.lv/tools/googletools.html
https://www.scribblemaps.com/
https://geojson.io/

# JSON Formatter

https://jsonformatter.curiousconcept.com/

# Polygon

https://developers.google.com/maps/documentation/javascript/reference/polygon

# Icon Change Color
https://onlinepngtools.com/change-png-color

# Overlay Polylines <=> Polygone

- [Toggle between google map polyline and polygon](https://stackoverflow.com/questions/32930184/toggle-between-google-map-polyline-and-polygon)
- [Groups](https://groups.google.com/g/google-maps-js-api-v3/c/WEdCSNejvbw)
- [Polyline zIndex](https://groups.google.com/g/google-maps-js-api-v3/c/WEdCSNejvbw)

# how to pass a function react router dom

- [React-router-dom v.4 BrowseRouter pass function to child](https://stackoverflow.com/questions/43385871/react-router-dom-v-4-browserouter-pass-function-to-child)
- https://stackoverflow.com/questions/50235503/pass-function-by-props-in-react-router
- https://learnwithparam.com/blog/how-to-pass-props-in-react-router/

# Card Clickable
- [Making whole card clickable in Reactstrap](https://stackoverflow.com/questions/53973644/making-whole-card-clickable-in-reactstrap)

# Redirect
- [How to redirect from one page to another page in React Router](https://reactgo.com/react-router-redirection/)
- https://codesource.io/how-to-use-this-props-history-push-on-your-react-project/

# Pass variables on Link
- [How to Pass props using Link and NavLink in React Router v4](https://medium.com/@bopaiahmd.mca/how-to-pass-props-using-link-and-navlink-in-react-router-v4-75dc1d9507b4)

# Coupon / Promos Templates
- https://venngage.com/templates/coupons?vap=couponLP