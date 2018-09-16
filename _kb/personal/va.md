---
title: Virtual Assistant Tasks
---

## Setup
- Asana
- Create a new Calendar on titled "Prospective Events for Shane". Invite Shane's personal email with full edit access.
- Create a new Calendar titled "Marcus Buddaonova" (unless already exists since this is default). Invite Shane's personal email with full edit access.

## Ongoing

### Know my city
- The calendar "Shane's Location" should always be scheduled out 2 months in advance with the city Shane will be in (formatted `<CITY>, <COUNTRY>`).
- If there is a time slot that is open within 2 months, email Shane and ask him where he will be during the empty time slots
- Shane may respond via text or by inviting you to a multi-day event

### Asana
TODO

## Processes

### Create Event - createEvent(link)

Example:
- Given <list of Zouk festivals> create Google events and invite me to each. Title '<city> - Zouk - <event name>'
  - Description is the FB event. The URL if exists. The URL of the ticket prices. If you can't find the price, email the event organizers asking about the price.

### City Prep -
- Input =
  - City
  - Dates
  - Location
- Output = email with
  - Weather (in both F and C)
  - Logistics
    - Best travel method from current city (see calendar "Shane's Location") to that city (e.g. Plane, Train, Bus)
    - If (plane or train) check google flights one way and send me the URL
      - If (flight is longer than 8 hours) depart between 10pm and 2am
      - If (weekday) depart after 11am and arrive before 3pm
      - If (weekend) depart after 11am and arrive before 9pm
    - If (plane) include a link to the airport lounges for the two airports (search )
  - Training
    - Best places to run (3)
  - Social
    - Zouk
      - Zouk events - search facebook in that location for "zouk" and createEvent(zouk event link)
      - Find the names (and facebook links) of zouk instructors in that city
    - Big events - search facebook events and google for noteworthy events going on in that area during that time and createEvent()
  - Experiences
    - Search airbnb experiences for that city and those dates, include the link here
  - Things to see
    - Search google and touringbird and yelp for best things to see and list as:
      - `<NAME OF THING>` with a link to that place on google maps like [this](https://www.google.com/maps/place/Copacabana+Beach/@-22.9732698,-43.2032649,14z/data=!4m13!1m7!3m6!1s0x9bd523d20f9c53:0x693c6132635e6b0d!2sCopacabana,+Rio+de+Janeiro+-+State+of+Rio+de+Janeiro,+Brazil!3b1!8m2!3d-22.9697777!4d-43.1868592!3m4!1s0x9bd538c8832c3d:0xcb920056b5eb9082!8m2!3d-22.9738728!4d-43.1853086)
  - Nearby things (with google maps link)
    - Parks
    - Supermarket
    - Nearest public transportation


## Later
- Asana
- Airbnb homes
- Airbnb experiences
- Google flights
- Date spots / dinner reservations
- Spotify
  - Add song to my Spotify (I'll give access to this),  Spotify - new monthly playlist
- GitHub KB add via pull request
- Hubspot contact
- Nutrition
- Buffer/IG
- Personal report
- Transportation (Public)
- Haircut places that do hair designs near me
- Find a vocal teacher wherever I am
