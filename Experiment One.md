Experiment One:
This experiment focused on the HTML Geolocation API as well as the Google Maps API. Overall, the Geolocation API was relatively easy to use. We were able to access a user�s location information such as their latitude, longitude, and the time stamp of when this location was recorded. Additionally, the API gives us access to additional information such as the accuracy of the position, the altitude, which direction they are heading in, and at what speed they are heading. Of these remaining fields, the most useful ones will likely be the direction someone is heading and the accuracy of the position. We could potentially use someone�s heading to figure out study spots in that direction. Something interesting to note about the position is that it seems to be less accurate when using wifi as opposed to cellular data, but this is probably okay since we assume that most people using this site will be on their phones.
On the other hand, the Google Maps API was a good bit more difficult to get the hang of. Google�s Maps API required an account and API key. There seems to be some limit on how frequently we can use Google�s Maps API for free, but for our purposes and volume, we think we will be fine. The primary issue with getting this API functioning is that we were unable to access it directly, so we needed to use a library. Of the libraries we tried so far, one called google-map-react seemed to work relatively well. We were able to get an interactive map to show up on a webpage, with the map centered at our current location. However, we were unable to place a marker for our location working correctly while using this library, which would be helpful for easily scanning a map to find study locations. So we may have to do some further experimentation with other Google Maps React libraries to try and get the desired behavior. However, overall, this experiment appears to have been successful. 