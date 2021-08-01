<!-- Title -->

# Women's Football website

<!-- Headline -->

## For visibility, worship and API practice

<!-- Body -->

### Why have I built it

Team work, strategy, and a clear objective. The way these aspects can apply both to football itself and to this project is almost a coincidence, but I thought this could be a good way to start talking about the Women's Football website.

Although I was still coding on my own at the time, for this project I wanted to explore having a predifined and more ambitious end-goal, and then also committing to organize my work using a [Trello board](https://trello.com/b/rYfBu3Yf/wf-website-revamp).

### The concept

<!--Use React to create a website that would engage visitors into wanting to learn more about a relevant women's football event. -->

As this was a project I started after learning React, one of the first requirements I set was that it had to have interactive content.

The 2019 FIFA Women's World Cup had just been on and with more and more people (finally) giving the women's game a bit of attention I thought it could be a cool idea to let visitors search for different countries and learn how they did on the tournament.

I was also dreaming high in terms of maybe being able to set up a simple database to pull this information from; and in terms of API, having curated news and displaying live game scores.

Basically an all-in-one website with everything you needed to know about women's football.

### Down to code

<!--Using API and an online JSON storage to display curated content about the women's game. -->

After searching for database and API options and documenting the information on Trello cards, I soon noticed I would have to change the approach for some of the intended features. The API for live scores was paid, so this one was removed, and what I implemented in the end was only the curated news and the FIFA World Cup interactive search.

To fetch specific info depending on the country, I used an online JSON storage that supported http calls. This has allowed me to manage the content directly on the JSON object and continue to use Axios to get the data. As soon as the response is received from the storage, a piece of code maps its values to the object properties and pass them to be displayed on the SearchedTeam Reach component.
