# LocateMe System

About Project :
- This is a application to access current location user using the latitude and longitude of any places on earth.

Language Use :
- JavaScript
- HTML

Platform Use :
- Any Text Editor

API Use :
 Google Maps
 - Maps JavaScript API
   - The functions in the Places Library, Maps JavaScript API enable your application to search for places (defined in this API as
   establishments, geographic locations, or prominent points of interest) contained within a defined area, such as the bounds of a map, 
   or around a fixed point.
   The Places SDK offers an autocomplete feature which you can use to give your applications the type-ahead-search behavior of the
   Google Maps search field. When a user starts typing an address, autocomplete will fill in the rest.
   
 - Geolocation API
   - The Geolocation API returns a location and accuracy radius based on information about cell towers and WiFi nodes that the mobile
     client can detect. This document describes the protocol used to send this data to the server and to return a response to the
     client.
   - Communication is done over HTTPS using POST. Both request and response are formatted as JSON, and the content type of both is
     application/json.
     
 - Geocoding API
   - Geocoding is the process of converting addresses (like a street address) into geographic coordinates (like latitude and longitude),
     which you can use to place markers on a map, or position the map.
   - Reverse geocoding is the process of converting geographic coordinates into a human-readable address.

How to use :
- Just open the app and the application will detect your current location.
- Click the Marker to see your latitude and longitude

The parameter that the API able to receive :
 By 

The responses that the API return (the JSON values) :
{
   "results" : [
      {
         "address_components" : [
            {
               "long_name" : "102",
               "short_name" : "102",
               "types" : [ "street_number" ]
            },
            {
               "long_name" : "Jalan TU 3",
               "short_name" : "Jalan TU 3",
               "types" : [ "route" ]
            },
            {
               "long_name" : "Melaka",
               "short_name" : "Melaka",
               "types" : [ "locality", "political" ]
            },
            {
               "long_name" : "Melaka",
               "short_name" : "Melaka",
               "types" : [ "administrative_area_level_1", "political" ]
            },
            {
               "long_name" : "Malaysia",
               "short_name" : "MY",
               "types" : [ "country", "political" ]
            },
            {
               "long_name" : "75350",
               "short_name" : "75350",
               "types" : [ "postal_code" ]
            }
         ],
         "formatted_address" : "102, Jalan TU 3, 75350 Melaka, Malaysia",
   "status" : "OK"
}
