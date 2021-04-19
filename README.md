# SpaceMonopoly

https://www.youtube.com/watch?v=_dDJ5DGYu6U&feature=emb_title

Welcome to Space Monopoly! We are glad to have you aboard.

Our inspiration came from our brainstorming session when we came upon an app showing live feed of space objects orbiting Earth! This app is called, Stuff in Space (linked below). Our goal was to then find a way to gamify the app, making it achieve every space voyager's entrepreneurial dream! To own the final frontier. Space Monopoly was born.

We built it by splitting our team and work into a front-end duo and back-end duo. Once we split up, the front-end team focused on setting up the main UI displaying the game. The back-end team focused on setting up REST APIs for players, pieces, and satellites. The back-end team also worked to implement real-time features that allow the web server to send updates to clients.

Like any project, we ran into a few challenges along the way. The team was not experienced with the Celestrak 100 API, Amsat API, Three.js graphics programming, web-socket programming using Phoenix, and a new programming language Elixir. This slowed our process due to our pursuit to learn something new and ambitious, but we trekked on.

We are proud of our application's usage of web-socket connections and web-gl visualizations. These made for a beautiful and interesting project we are excited to work on after the hackathon ends. Overall, we are looking forward to using both Three.js and elixir in the future for real time applications.

In our near future, we are planning on releasing this game for online users to play. We hope to also implement multiple game rooms so that more than 8 users can play concurrently.

Inspirational Resources: http://stuffin.space/ https://github.com/jeyoder/StuffInSpace

Built With: css3, docker, elixir, html5, javascript, phoenix, postgresql, react

<br>

How to Run:

Before starting your Phoenix server, you have to create a postgres database

Run `docker-compose create`
then `docker-compose up`
This will create your database with the default login credentials


To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Install Node.js dependencies with `npm install` inside the `assets` directory
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
