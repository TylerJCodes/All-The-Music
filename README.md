# Music Lookup Site

## What is this?
Music-Artist lookup site, a website that allows you to look up different artists, albums and tracks with data provided by Last.FM, MusicBrainz and more. 

## Acknowledgements

I used various API(s) for this project; (credit can also be found within the 'About' page on the website), 
Last.FM,
MusicBrainz,
SeatGeek,
YouTube

## To-Do

Tasks I must complete,

* Important // Tasks that are needed in order for the website to function as should.

- Add something for songs (to look up, have their own page?)
- Rework site for mobile display
- Add more comments to the code
- Fix where main page might put top artists in top tracks section (Refresh 3~ times on main page)
- Finish all pages
- Add localstorage to artists pages (album tab)

** Non-important // Tasks that can be completed later without restricting much of the website.

- Make sure MusicBrainz gets the correct artist
- Figure out proper attribution, (i.e, glyphicons, logos, apis, etc.)
- Possibly add color to the 'Available on' links when the link is hovered via the keyboard (i.e, tab)
- Find the perfect margin for 'the meta-data-header' (i.e, listeners, albums), example: (https://tylerjdev.github.io/index.html?query=Boom%20Clap%20Bachelors&type=artist)
- Go back to seatgeek function call, and make sure everything is complete (i.e, make sure if there are more than '1' artist(s) at the last level, to properly handle them
- Add so if you click a different tab (i.e, 'tracks', then click back to 'artists', it'll save the page you were on
- Make sure to save data whenever it can be saved
- Only use one youtube, (or other 'available on' icons) if MusicBrainz has multiple youtube links, example : (https://tylerjdev.github.io/index.html?query=Blur&type=artist)
- Condense the search results to have less pages
- Integrate last.fm user capabilities into site
- On 'read more' btn click, scroll down to the section
- Finish Pages section
- Add something to prevent multiple calls when searching (If you press enter multiple times) [Already done, but could possibly be improved]
- Change Albums & songs to just Albums
- Finish 'photos' tab

## Errors

- Blu & Exile > https://tylerjdev.github.io/index.html?query=Blu+&+Exile&type=artist
- Gorillaz > https://tylerjdev.github.io/index.html?query=Blu+&+Exile&type=artist
- Search something twice (quickly), (i.e 'blu'), then click tracks, should get an error
- https://tylerjdev.github.io/index.html?query=Mikael%20Tariverdiev&type=artist > Why is there a 'read more' link still?
- Some albums don't load, (i.e, 'flowers while I can still smell them') <<<< Possibly add MusicBrainz as alt if can't figure out what's causing this error
- https://tylerjdev.github.io/index.html?query=Blu+&+Madlib&type=artist
- https://tylerjdev.github.io/index.html?query=Madlib&type=artist Or probably any other artist, if you click the album-songs tab too fast, it will display an error, probably because it tries to 'render' before it has the data ready via the api (?)
- Homepage (probably any page that uses localstorage) won't load on private browsers, (i.e firefox, safari (on ios)) 
- https://tylerjdev.github.io/index.html?query=Johnson&Jonson&album=Johnson%20&%20Jonson&type=album
