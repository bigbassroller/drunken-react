# DrunkenReact

Getting Started
---------------

The first thing you want to do is copy the `drunken-react` directory and change the name to something else (like, say, `my-awesome-app`), and then you'll need to do a three-step find and replace on the name in all the templates.

1. Search for `drunken_react` to capture the configs.
2. Search for `DrunkenReact` to capture all the function names.
3. Search for `Drunken React` to capture all static text.

OR
* Search for: `drunken-react` and replace with: `my-awesome-app`.
* Search for: `drunken_react` and replace with: `my_awesome_app`.
* Search for: `DrunkenReact` and replace with: `MyAwesomeApp`.
* Search for: `Drunken React` and replace with: `My Awesome App`.


Inside /lib folder, rename drunken_react to my_awesome_app and in the same folder rename drunken_react.ex to my_awesome_app.ex.

Next, update or delete this readme.

Now you're ready to go! May the Elixir/Phoenx and React be with you :)

Good luck!

To start your Phoenix app:

  1. Clean out artifact dependencies and install fresh dependencies `rm -rf _build deps mix.lock && mix deps.clean --unused && mix deps.get`
  2. Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  3. Install npm packages `npm install`
  4. Compile Sass and JavaScript files, launch and watch the phoenix server `npm start`.


Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix