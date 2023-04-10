# Attempted import error: 'Map' is not exported from 'react-leaflet'.

- Use <MapContainer>

# react leaflet does not display the map
- https://stackoverflow.com/questions/40365440/react-leaflet-map-not-correctly-displayed
- https://gis.stackexchange.com/questions/348228/map-is-not-visible-at-initialization-using-react-leaflet



# Module not found: Can't resolve 'babel-loader/lib/index.js
- [*** works *** StackOverFlow](https://stackoverflow.com/questions/56098779/how-to-fix-module-build-failed-from-node-modules-babel-loader-lib-index-js)

```sh
npm install @babel/core @babel/preset-env
```


# Did you wrap <GoogleMap> component with withGoogleMap() HOC?
- https://developers.google.com/maps/gmp-get-started#enable-api-sdk
- https://developers.google.com/maps/documentation/javascript/error-messages#api-not-activated-map-error
- https://stackoverflow.com/questions/50545623/error-with-react-mapdid-you-wrap-googlemap-component-with-withgooglemap-ho
- https://stackoverflow.com/questions/35700182/apinotactivatedmaperror-for-simple-html-page-using-google-places-api

# index.js:1406 Google Maps JavaScript API error: ApiNotActivatedMapError
- https://developers.google.com/maps/documentation/javascript/get-api-key#:~:text=In%20the%20Cloud%20Console%2C%20on,to%20add%20an%20API%20Key.&text=Go%20to%20the%20APIs%20%26%20Services%20%3E%20Credentials%20page.&text=On%20the%20Credentials%20page%2C%20click,your%20newly%20created%20API%20key.
- https://developers.google.com/maps/documentation/embed/get-api-key


# AuthError - Error: Amplify has not been configured correctly.

https://stackoverflow.com/questions/63605779/autherror-error-amplify-has-not-been-configured-correctly

Add to index.js
```jsx
// AWS amplify modules
import Amplify, { Auth } from 'aws-amplify'
import awsconfig from './aws-exports'
Amplify.configure(awsconfig)
Auth.configure(awsconfig)
```