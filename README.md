# svv
Info about a vehicle from Statens vegvesen API and put it as sensors in Home Assistant

You have to exchange CarRegistrationNumber in the URL with the car you want to look up:
https://www.vegvesen.no/ws/no/vegvesen/kjoretoy/felles/datautlevering/enkeltoppslag/kjoretoydata?kjennemerke=CarRegistrationNumber eg. EV11223

You also have to create your own API-key: 
https://www.vegvesen.no/om-oss/om-organisasjonen/apne-data/et-utvalg-apne-data/api-for-tekniske-kjoretoyopplysninger/

And put it in the code here keeping Apikey:
SVV-Authorization: "Apikey YourOwnAPICode"

<img width="511" alt="lovelace-example-card" src="https://user-images.githubusercontent.com/125091134/220125079-28f7789a-820f-4121-808f-ac7422dccbcb.png">

Example lovelace card based on picture-elements.
