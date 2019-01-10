# latlng-to-zip
Convert longitude and latitude to a zipcode.  Requires use of [Google's Geocoding API](https://developers.google.com/maps/documentation/geocoding/start)

## Installation
`npm install kulbhushan-ucreate/latlng-to-zip`
     OR
 `yarn add kulbhushan-ucreate/latlng-to-zip`

## Getting Starting
```
import reverseGeocode from 'latlng-to-zip';
reverseGeocode({latitude, longitude})
  .then(zipcode => zipcode)
  .catch(err => err);
```

## Testing
`npm test`
