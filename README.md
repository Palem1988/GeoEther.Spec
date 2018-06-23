# GeoEther.Spec Abstract
The Ethereum Blockchain currently does not have a geolocation layer, as such this outlines a solution to
persist location based data.

## The Spec
The spec and therefore data stored will be broken into 4 categories:
- Geohash : 12pt precision
- Type : String Constant
- Wallet Address : String of Origin
- Unique / Reference ID : For external reference to fetch expanded data

For a working example:
- As Json 
`
{
"geohash" : "dqbvxsnr54n8",
"type" : "Traffic",
"addy" : "0x123456",
"id" : "12345"
}
`
- As GeoEther
` dqbvxsnr54n8|Traffic|0x123456|12345 `
