# Technical Assignment

Our team here at Nedap Healthcare is playing a fantasy role-playing game. Every time the
heroes they play arrive at a town, they don't know the local population and what they can do
to help them on their adventures.
This is one of these times, our heroes just arrived at a Gnome town called Brastlewark. To
facilitate trade with the local population they need an easy way to browse all the inhabitants'
details. We've found a server providing all the census data of Brastlewark (see data.json).

Gnomes in this town are not really social because they have too much work to do. That's the
reason they can have more than one job and might have few or even no friends at all. They
also appreciate their privacy so they've used some random images from the internet for their
profiles, not particularly optimised to be used as such. They are very modern in some
aspects, as they even have smartphones and access to the internet.

Please write an application to help our team browse and see the details of those
inhabitants. Keep in mind that we want to improve and extend this application in the
future. Don't forget to commit your changes to a new branch in this repository.

## Specifications:
- Retrieve data from the URL provided.
- Our heroes will be quite busy dealing with Orcs, so the web application has to be
really simple and easy to use. It should at least be possible to find inhabitants based
on their professions, but also to just browse the inhabitants and see the details of each
one.
- The services of Comzass - which hosts the census data - can be unreliable, so the data
should be stored locally once it has been retrieved.
- Our heroes are using the most modern of modern devices, so the newest web
technologies are always supported.
- At least one automated test.

## Bonus:
- React with Redux Saga for state management with TypeScript.
- Our heroes want to rate the skill level of each profession of each inhabitant. This will
make repeat visits to the town much faster, leaving more time for Orc slaying.
- Filter inhabitants in other ways, like by whom they have befriended.
- Error handling.
- Any addition that demonstrates your way of working or shows a neat way to do
something would be nice if time permits it.
