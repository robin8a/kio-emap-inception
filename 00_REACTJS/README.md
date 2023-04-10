
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


# Amplify Auth

```sh
amplify add auth
# Scanning for plugins...
# Plugin scan successful
# Using service: Cognito, provided by: awscloudformation
 
#  The current configured provider is Amazon Cognito. 
 
#  Do you want to use the default authentication and security configuration? Default configuration
#  Warning: you will not be able to edit these selections. 
#  How do you want users to be able to sign in? Username
#  Do you want to configure advanced settings? No, I am done.
# Successfully added resource kioindooremap259c6824 locally

# Some next steps:
# "amplify push" will build all your local backend resources and provision it in the cloud
# "amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud
```

# Amplify Auth

```sh
 amplify add api
# ? Please select from one of the below mentioned services: GraphQL
# ? Provide API name: kioindooremap
# ? Choose the default authorization type for the API API key
# ? Enter a description for the API key: 
# ? After how many days from now the API key should expire (1-365): 365
# ? Do you want to configure advanced settings for the GraphQL API No, I am done.
# ? Do you have an annotated GraphQL schema? No
# ? Do you want a guided schema creation? Yes
# ? What best describes your project: One-to-many relationship (e.g., “Blogs” with “Posts” and “Comments”)
# ? Do you want to edit the schema now? (Y/n) 

```
## Result

```sh
amplify push
# ✔ Successfully pulled backend environment kioemapenv from the cloud.

# Current Environment: kioemapenv

# | Category | Resource name         | Operation | Provider plugin   |
# | -------- | --------------------- | --------- | ----------------- |
# | Auth     | kioindooremap259c6824 | Create    | awscloudformation |
# | Hosting  | amplifyhosting        | No Change |                   |
# ? Are you sure you want to continue? Yes
# ⠹ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionRole         AWS::IAM::Role             Tue Aug 03 2021 14:54:46 GMT-0500 (Colombia Standard Time)               
# UPDATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621 AWS::CloudFormation::Stack Tue Aug 03 2021 14:54:40 GMT-0500 (Colombia Standard Time) User Initiated
# ⠏ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS authkioindooremap259c6824 AWS::CloudFormation::Stack Tue Aug 03 2021 14:54:46 GMT-0500 (Colombia Standard Time) 
# UPDATE_IN_PROGRESS DeploymentBucket          AWS::S3::Bucket            Tue Aug 03 2021 14:54:46 GMT-0500 (Colombia Standard Time) 
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS authkioindooremap259c6824      AWS::CloudFormation::Stack Tue Aug 03 2021 14:54:47 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionRole AWS::IAM::Role             Tue Aug 03 2021 14:54:46 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-authkioindooremap259c6824-1JAXC0MPVXJTZ AWS::CloudFormation::Stack Tue Aug 03 2021 14:54:47 GMT-0500 (Colombia Standard Time) User Initiated
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS SNSRole AWS::IAM::Role Tue Aug 03 2021 14:54:54 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS SNSRole AWS::IAM::Role Tue Aug 03 2021 14:54:53 GMT-0500 (Colombia Standard Time)                            
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE UpdateRolesWithIDPFunctionRole AWS::IAM::Role Tue Aug 03 2021 14:55:02 GMT-0500 (Colombia Standard Time) 
# ⠋ Updating resources in the cloud. This may take a few minutes...

# UPDATE_COMPLETE DeploymentBucket AWS::S3::Bucket Tue Aug 03 2021 14:55:06 GMT-0500 (Colombia Standard Time) 
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE SNSRole AWS::IAM::Role Tue Aug 03 2021 14:55:10 GMT-0500 (Colombia Standard Time) 
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UserPool AWS::Cognito::UserPool Tue Aug 03 2021 14:55:16 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UserPool AWS::Cognito::UserPool Tue Aug 03 2021 14:55:14 GMT-0500 (Colombia Standard Time)                            
# ⠴ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE UserPool AWS::Cognito::UserPool Tue Aug 03 2021 14:55:16 GMT-0500 (Colombia Standard Time) 
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UserPoolClientWeb AWS::Cognito::UserPoolClient Tue Aug 03 2021 14:55:21 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UserPoolClient    AWS::Cognito::UserPoolClient Tue Aug 03 2021 14:55:19 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UserPoolClientWeb AWS::Cognito::UserPoolClient Tue Aug 03 2021 14:55:19 GMT-0500 (Colombia Standard Time)                            
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    UserPoolClient    AWS::Cognito::UserPoolClient Tue Aug 03 2021 14:55:21 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UserPoolClient    AWS::Cognito::UserPoolClient Tue Aug 03 2021 14:55:21 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    UserPoolClientWeb AWS::Cognito::UserPoolClient Tue Aug 03 2021 14:55:21 GMT-0500 (Colombia Standard Time)                            
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UserPoolClientRole AWS::IAM::Role Tue Aug 03 2021 14:55:25 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UserPoolClientRole AWS::IAM::Role Tue Aug 03 2021 14:55:24 GMT-0500 (Colombia Standard Time)                            
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE UserPoolClientRole AWS::IAM::Role Tue Aug 03 2021 14:55:40 GMT-0500 (Colombia Standard Time) 
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    UserPoolClientLambda AWS::Lambda::Function Tue Aug 03 2021 14:55:46 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UserPoolClientLambda AWS::Lambda::Function Tue Aug 03 2021 14:55:46 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UserPoolClientLambda AWS::Lambda::Function Tue Aug 03 2021 14:55:43 GMT-0500 (Colombia Standard Time)                            
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UserPoolClientLambdaPolicy AWS::IAM::Policy Tue Aug 03 2021 14:55:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UserPoolClientLambdaPolicy AWS::IAM::Policy Tue Aug 03 2021 14:55:50 GMT-0500 (Colombia Standard Time)                            
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE UserPoolClientLambdaPolicy AWS::IAM::Policy Tue Aug 03 2021 14:56:05 GMT-0500 (Colombia Standard Time) 
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UserPoolClientLogPolicy AWS::IAM::Policy Tue Aug 03 2021 14:56:09 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UserPoolClientLogPolicy AWS::IAM::Policy Tue Aug 03 2021 14:56:08 GMT-0500 (Colombia Standard Time)                            
# ⠴ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE UserPoolClientLogPolicy AWS::IAM::Policy Tue Aug 03 2021 14:56:23 GMT-0500 (Colombia Standard Time) 
# ⠹ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UserPoolClientInputs Custom::LambdaCallout Tue Aug 03 2021 14:56:27 GMT-0500 (Colombia Standard Time) 
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    UserPoolClientInputs Custom::LambdaCallout Tue Aug 03 2021 14:56:31 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UserPoolClientInputs Custom::LambdaCallout Tue Aug 03 2021 14:56:31 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS IdentityPool AWS::Cognito::IdentityPool Tue Aug 03 2021 14:56:36 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS IdentityPool AWS::Cognito::IdentityPool Tue Aug 03 2021 14:56:34 GMT-0500 (Colombia Standard Time)                            
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS IdentityPoolRoleMap AWS::Cognito::IdentityPoolRoleAttachment Tue Aug 03 2021 14:56:40 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE    IdentityPool        AWS::Cognito::IdentityPool               Tue Aug 03 2021 14:56:37 GMT-0500 (Colombia Standard Time) 
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    amplify-kioindooremap-kioemapenv-92621-authkioindooremap259c6824-1JAXC0MPVXJTZ AWS::CloudFormation::Stack               Tue Aug 03 2021 14:56:46 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    IdentityPoolRoleMap                                                            AWS::Cognito::IdentityPoolRoleAttachment Tue Aug 03 2021 14:56:42 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS IdentityPoolRoleMap                                                            AWS::Cognito::IdentityPoolRoleAttachment Tue Aug 03 2021 14:56:42 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UpdateRolesWithIDPFunction AWS::Lambda::Function      Tue Aug 03 2021 14:57:04 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE    authkioindooremap259c6824  AWS::CloudFormation::Stack Tue Aug 03 2021 14:57:02 GMT-0500 (Colombia Standard Time) 
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    UpdateRolesWithIDPFunction AWS::Lambda::Function Tue Aug 03 2021 14:57:07 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateRolesWithIDPFunction AWS::Lambda::Function Tue Aug 03 2021 14:57:07 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionOutputs Custom::LambdaCallout Tue Aug 03 2021 14:57:11 GMT-0500 (Colombia Standard Time) 
# ⠏ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    UpdateRolesWithIDPFunctionOutputs Custom::LambdaCallout Tue Aug 03 2021 14:57:15 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionOutputs Custom::LambdaCallout Tue Aug 03 2021 14:57:15 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠹ Updating resources in the cloud. This may take a few minutes...

# UPDATE_COMPLETE                     amplify-kioindooremap-kioemapenv-92621 AWS::CloudFormation::Stack Tue Aug 03 2021 14:57:19 GMT-0500 (Colombia Standard Time) 
# UPDATE_COMPLETE_CLEANUP_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621 AWS::CloudFormation::Stack Tue Aug 03 2021 14:57:18 GMT-0500 (Colombia Standard Time) 
# ✔ All resources are updated in the cloud


# ➜  kio-indoor-emap git:(development) ✗ amplify add api
# ? Please select from one of the below mentioned services: GraphQL
# ? Provide API name: kioindooremap
# ? Choose the default authorization type for the API API key
# ? Enter a description for the API key: 
# ? After how many days from now the API key should expire (1-365): 365
# ? Do you want to configure advanced settings for the GraphQL API No, I am done.
# ? Do you have an annotated GraphQL schema? No
# ? Do you want a guided schema creation? Yes
# ? What best describes your project: One-to-many relationship (e.g., “Blogs” with “Posts” and “Comments”)
# ? Do you want to edit the schema now? Yes
# Please edit the file in your editor: /Users/robin8a/Documents/react_ws/kio-indoor-emap/amplify/backend/api/kioindooremap/schema.graphql
# ? Press enter to continue 

# The following types do not have '@auth' enabled. Consider using @auth with @model
#          - Brand
#          - Mall
#          - Store
#          - Deal
# Learn more about @auth here: https://aws-amplify.github.io/docs/cli-toolchain/graphql#auth 

# Failed compiling GraphQL schema:
# You cannot specify a non-existant field 'content' in @key 'byStore' on type 'Deal'.
# ? Correct the errors in schema.graphql and press Enter to re-compile.

# Path to schema.graphql:
# /Users/robin8a/Documents/react_ws/kio-indoor-emap/amplify/backend/api/kioindooremap/schema.graphql 

# The following types do not have '@auth' enabled. Consider using @auth with @model
#          - Brand
#          - Mall
#          - Store
#          - Deal
# Learn more about @auth here: https://aws-amplify.github.io/docs/cli-toolchain/graphql#auth 


# GraphQL schema compiled successfully.

# Edit your schema at /Users/robin8a/Documents/react_ws/kio-indoor-emap/amplify/backend/api/kioindooremap/schema.graphql or place .graphql files in a directory at /Users/robin8a/Documents/react_ws/kio-indoor-emap/amplify/backend/api/kioindooremap/schema
# Successfully added resource kioindooremap locally

# Some next steps:
# "amplify push" will build all your local backend resources and provision it in the cloud
# "amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud

# ➜  kio-indoor-emap git:(development) ✗ amplify push
# ✔ Successfully pulled backend environment kioemapenv from the cloud.

# Current Environment: kioemapenv

# | Category | Resource name         | Operation | Provider plugin   |
# | -------- | --------------------- | --------- | ----------------- |
# | Api      | kioindooremap         | Create    | awscloudformation |
# | Hosting  | amplifyhosting        | No Change |                   |
# | Auth     | kioindooremap259c6824 | No Change | awscloudformation |
# ? Are you sure you want to continue? Yes

# The following types do not have '@auth' enabled. Consider using @auth with @model
#          - Brand
#          - Mall
#          - Store
#          - Deal
# Learn more about @auth here: https://aws-amplify.github.io/docs/cli-toolchain/graphql#auth 


# GraphQL schema compiled successfully.

# Edit your schema at /Users/robin8a/Documents/react_ws/kio-indoor-emap/amplify/backend/api/kioindooremap/schema.graphql or place .graphql files in a directory at /Users/robin8a/Documents/react_ws/kio-indoor-emap/amplify/backend/api/kioindooremap/schema
# ? Do you want to generate code for your newly created GraphQL API Yes
# ? Choose the code generation language target javascript
# ? Enter the file name pattern of graphql queries, mutations and subscriptions src/graphql/**/*.js
# ? Do you want to generate/update all possible GraphQL operations - queries, mutations and subscriptions Yes
# ? Enter maximum statement depth [increase from default if your schema is deeply nested] 2
# ⠼ Updating resources in the cloud. This may take a few minutes...

# UPDATE_IN_PROGRESS authkioindooremap259c6824              AWS::CloudFormation::Stack Tue Aug 03 2021 18:41:53 GMT-0500 (Colombia Standard Time)               
# CREATE_IN_PROGRESS apikioindooremap                       AWS::CloudFormation::Stack Tue Aug 03 2021 18:41:52 GMT-0500 (Colombia Standard Time)               
# UPDATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621 AWS::CloudFormation::Stack Tue Aug 03 2021 18:41:48 GMT-0500 (Colombia Standard Time) User Initiated
# ⠼ Updating resources in the cloud. This may take a few minutes...

# UPDATE_COMPLETE    authkioindooremap259c6824 AWS::CloudFormation::Stack Tue Aug 03 2021 18:41:54 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS apikioindooremap          AWS::CloudFormation::Stack Tue Aug 03 2021 18:41:53 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ AWS::CloudFormation::Stack Tue Aug 03 2021 18:41:53 GMT-0500 (Colombia Standard Time) User Initiated
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS GraphQLAPI AWS::AppSync::GraphQLApi Tue Aug 03 2021 18:41:58 GMT-0500 (Colombia Standard Time) 
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS GraphQLSchema AWS::AppSync::GraphQLSchema Tue Aug 03 2021 18:42:13 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    GraphQLAPI    AWS::AppSync::GraphQLApi    Tue Aug 03 2021 18:42:11 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GraphQLAPI    AWS::AppSync::GraphQLApi    Tue Aug 03 2021 18:42:11 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS GraphQLAPIKey AWS::AppSync::ApiKey Tue Aug 03 2021 18:42:14 GMT-0500 (Colombia Standard Time) 
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS GraphQLSchema AWS::AppSync::GraphQLSchema Tue Aug 03 2021 18:42:16 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    GraphQLAPIKey AWS::AppSync::ApiKey Tue Aug 03 2021 18:42:27 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GraphQLAPIKey AWS::AppSync::ApiKey Tue Aug 03 2021 18:42:27 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE GraphQLSchema AWS::AppSync::GraphQLSchema Tue Aug 03 2021 18:43:17 GMT-0500 (Colombia Standard Time) 
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS Deal  AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:19 GMT-0500 (Colombia Standard Time) 
# CREATE_IN_PROGRESS Mall  AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:19 GMT-0500 (Colombia Standard Time) 
# CREATE_IN_PROGRESS Brand AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:19 GMT-0500 (Colombia Standard Time) 
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS Store AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:21 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS Deal  AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS Brand AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS Mall  AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS Store AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time)                            
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Store-1TQY3A8IWYFCU AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) User Initiated


# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Deal-KFS5ASTFTPDJ AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) User Initiated
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Brand-SXVB6V6AY0LB AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) User Initiated
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Mall-1468GMFG4947B AWS::CloudFormation::Stack Tue Aug 03 2021 18:43:20 GMT-0500 (Colombia Standard Time) User Initiated
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS StoreTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:28 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS StoreIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS StoreTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS StoreIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time)                            


# CREATE_IN_PROGRESS DealTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:28 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS DealIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:28 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS DealTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DealIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time)                            
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS BrandIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS BrandTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS BrandTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:26 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS BrandIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:26 GMT-0500 (Colombia Standard Time)                            
# ⠸ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS MallIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS MallTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS MallIAMRole AWS::IAM::Role       Tue Aug 03 2021 18:43:27 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS MallTable   AWS::DynamoDB::Table Tue Aug 03 2021 18:43:26 GMT-0500 (Colombia Standard Time)                            
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS StoreDataSource AWS::AppSync::DataSource Tue Aug 03 2021 18:43:44 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE    StoreIAMRole    AWS::IAM::Role           Tue Aug 03 2021 18:43:42 GMT-0500 (Colombia Standard Time) 
# ⠏ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE DealIAMRole AWS::IAM::Role Tue Aug 03 2021 18:43:43 GMT-0500 (Colombia Standard Time) 
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS BrandDataSource AWS::AppSync::DataSource Tue Aug 03 2021 18:43:44 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE    BrandIAMRole    AWS::IAM::Role           Tue Aug 03 2021 18:43:41 GMT-0500 (Colombia Standard Time) 
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS MallDataSource AWS::AppSync::DataSource Tue Aug 03 2021 18:43:45 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE    MallIAMRole    AWS::IAM::Role           Tue Aug 03 2021 18:43:43 GMT-0500 (Colombia Standard Time) 
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS DealDataSource AWS::AppSync::DataSource Tue Aug 03 2021 18:43:45 GMT-0500 (Colombia Standard Time) 
# ⠏ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS GetStoreResolver    AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListStoreResolver   AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateStoreResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DeleteStoreResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateStoreResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    StoreDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:46 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS StoreDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:46 GMT-0500 (Colombia Standard Time) Resource creation Initiated


# CREATE_IN_PROGRESS GetDealResolver    AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateDealResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListDealResolver   AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    DealDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:47 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DealDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:47 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS DeleteBrandResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListBrandResolver   AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateBrandResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateBrandResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GetBrandResolver    AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    BrandDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:47 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS BrandDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:46 GMT-0500 (Colombia Standard Time) Resource creation Initiated


# CREATE_IN_PROGRESS GetMallResolver    AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:50 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListMallResolver   AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateMallResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateMallResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DeleteMallResolver AWS::AppSync::Resolver   Tue Aug 03 2021 18:43:49 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    MallDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:47 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS MallDataSource     AWS::AppSync::DataSource Tue Aug 03 2021 18:43:47 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠹ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS UpdateDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:50 GMT-0500 (Colombia Standard Time) 
# CREATE_IN_PROGRESS DeleteDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:50 GMT-0500 (Colombia Standard Time) 
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    UpdateStoreResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateStoreResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    DeleteStoreResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DeleteStoreResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    ListStoreResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListStoreResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    GetStoreResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GetStoreResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    CreateStoreResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateStoreResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    CreateDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:53 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    GetDealResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GetDealResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    UpdateDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    DeleteDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS DeleteDealResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    ListDealResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListDealResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠹ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    DeleteBrandResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    CreateBrandResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DeleteBrandResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS CreateBrandResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    ListBrandResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    UpdateBrandResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS ListBrandResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS UpdateBrandResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    GetBrandResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GetBrandResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠸ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    CreateMallResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:53 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS CreateMallResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:53 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    GetMallResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS GetMallResolver    AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    UpdateMallResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:52 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    ListMallResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    DeleteMallResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS UpdateMallResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS ListMallResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS DeleteMallResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:43:51 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠙ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE DealTable AWS::DynamoDB::Table Tue Aug 03 2021 18:43:59 GMT-0500 (Colombia Standard Time) 
# ⠹ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE MallTable AWS::DynamoDB::Table Tue Aug 03 2021 18:43:58 GMT-0500 (Colombia Standard Time) 
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE StoreTable AWS::DynamoDB::Table Tue Aug 03 2021 18:43:59 GMT-0500 (Colombia Standard Time) 
# ⠸ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Brand-SXVB6V6AY0LB AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:00 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE BrandTable                                                                               AWS::DynamoDB::Table       Tue Aug 03 2021 18:43:58 GMT-0500 (Colombia Standard Time) 
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Store-1TQY3A8IWYFCU AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:01 GMT-0500 (Colombia Standard Time) 
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Deal-KFS5ASTFTPDJ AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:02 GMT-0500 (Colombia Standard Time) 
# ⠇ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-Mall-1468GMFG4947B AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:01 GMT-0500 (Colombia Standard Time) 
# ⠴ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE Deal  AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:08 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE Store AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:08 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE Brand AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:08 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE Mall  AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:07 GMT-0500 (Colombia Standard Time) 
# ⠏ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS ConnectionStack AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:11 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS ConnectionStack AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:10 GMT-0500 (Colombia Standard Time)                            
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-ConnectionStack-1O72UIY1OH3V0 AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:11 GMT-0500 (Colombia Standard Time) User Initiated
# ⠸ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    MallstoresResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:19 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS MallstoresResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:19 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    DealstoreResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:44:19 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    StoredealsResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:19 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    StorebrandResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:19 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS DealstoreResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:44:19 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS StoredealsResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:18 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS StorebrandResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:18 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_COMPLETE    StoremallResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:44:18 GMT-0500 (Colombia Standard Time)                            
# CREATE_COMPLETE    BrandstoresResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:44:18 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS BrandstoresResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:44:18 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS StoremallResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:44:18 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# CREATE_IN_PROGRESS DealstoreResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:44:16 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS BrandstoresResolver AWS::AppSync::Resolver Tue Aug 03 2021 18:44:16 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS StorebrandResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:16 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS MallstoresResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:16 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS StoredealsResolver  AWS::AppSync::Resolver Tue Aug 03 2021 18:44:16 GMT-0500 (Colombia Standard Time)                            
# CREATE_IN_PROGRESS StoremallResolver   AWS::AppSync::Resolver Tue Aug 03 2021 18:44:16 GMT-0500 (Colombia Standard Time)                            
# ⠦ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ-ConnectionStack-1O72UIY1OH3V0 AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:21 GMT-0500 (Colombia Standard Time) 
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE ConnectionStack AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:22 GMT-0500 (Colombia Standard Time) 
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS CustomResourcesjson AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:24 GMT-0500 (Colombia Standard Time) 
# ⠼ Updating resources in the cloud. This may take a few minutes...

# CREATE_IN_PROGRESS CustomResourcesjson AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:25 GMT-0500 (Colombia Standard Time) Resource creation Initiated
# ⠋ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE    amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSX-CustomResourcesjson-NVA55IRKPIFL AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:29 GMT-0500 (Colombia Standard Time)               
# CREATE_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSX-CustomResourcesjson-NVA55IRKPIFL AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:25 GMT-0500 (Colombia Standard Time) User Initiated
# ⠧ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE amplify-kioindooremap-kioemapenv-92621-apikioindooremap-1XLN6EHUSXROQ AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:38 GMT-0500 (Colombia Standard Time) 
# CREATE_COMPLETE CustomResourcesjson                                                   AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:36 GMT-0500 (Colombia Standard Time) 
# ⠏ Updating resources in the cloud. This may take a few minutes...

# CREATE_COMPLETE apikioindooremap AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:57 GMT-0500 (Colombia Standard Time) 
# ⠇ Updating resources in the cloud. This may take a few minutes...

# UPDATE_COMPLETE                     amplify-kioindooremap-kioemapenv-92621 AWS::CloudFormation::Stack Tue Aug 03 2021 18:45:02 GMT-0500 (Colombia Standard Time) 
# UPDATE_COMPLETE                     authkioindooremap259c6824              AWS::CloudFormation::Stack Tue Aug 03 2021 18:45:01 GMT-0500 (Colombia Standard Time) 
# UPDATE_COMPLETE_CLEANUP_IN_PROGRESS amplify-kioindooremap-kioemapenv-92621 AWS::CloudFormation::Stack Tue Aug 03 2021 18:44:59 GMT-0500 (Colombia Standard Time) 
# ✔ Generated GraphQL operations successfully and saved at src/graphql
# ✔ All resources are updated in the cloud

# GraphQL endpoint: https://phmqvtw4pfbdndpg4mf4wcdjim.appsync-api.us-east-1.amazonaws.com/graphql
# GraphQL API KEY: da2-s7igsi7eabbetndgxfx7yzhg2u
```

# Design
- [Install Docs: Paper Kit React is a freeby Bootstrap 4, React and Reactstrap UI Kit.](https://demos.creative-tim.com/paper-kit-react/?_ga=2.4090992.1346301165.1628078989-743588370.1626883218#/documentation/introduction)


## Libraries (Depends the template)
```sh
npm i nouislider \
npm i react-datetime \
npm i moment \
npm i reactstrap
```


# Status
- Ver pivot tracker: https://www.pivotaltracker.com/n/projects/2549185
- https://www.fceia.unr.edu.ar/estruc/2005/graffund.htm
- https://disi.unal.edu.co/~lctorress/estructuras/pdf/EInf28.pdf


# GraphQL Auth
- https://docs.amplify.aws/cli-legacy/graphql-transformer/auth/#definition


# Using Material UI v4 theme variable in React Function and Class Components
- Example working
```js
export default withStyles(styles, { withTheme: true })(
  GoogleApiWrapper({apiKey: ("AIzaSyCGDQSnXKQDzedzzwPpe07tRgY9My2Cz0U")})(SimpleMapTwo))
```
- https://medium.com/swlh/using-material-ui-theme-variable-in-react-function-and-class-components-56f4b8164a00


# amplify storage
```sh
amplify add storage
```