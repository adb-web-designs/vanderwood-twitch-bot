# Battle of Midgard Twitch Bot Documentation

The Battle of Midgard Twitch Bot is a bot that has been built for the [VanderwoodTV](https://www.twitch.tv/vanderwoodtv) Twitch channel.
The bot is built mainly using the [TwitchIO](https://github.com/TwitchIO/TwitchIO) and the [tortoise-orm](https://github.com/tortoise/tortoise-orm) libraries.

The bot has been built and coded by [Adam Birds](https://github.com/adambirds/) of [ADB Web Designs](https://adbwebdesigns.co.uk/).

The documentation for the bot has been created using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Commands

The bot has a number of commands that are available to the streamer, moderators, subscribers and normal viewers.

### Streamer Commands
* **[?registerchannel](docs/commands/streamer-commands/registerchannel.md)** - Registers the channel for the Battle of Midgard game.

### Moderator Commands

* **[?createclan](docs/commands/moderator-commands/createclan.md)** - Creates a clan which viewers can join in the Battle of Midgard game.
* **[?add](docs/commands/moderator-commands/add.md)** - Adds a viewer to a clan in the Battle of Midgard game.
* **[?remove](docs/commands/moderator-commands/remove.md)** - Removes a viewer from a clan in the Battle of Midgard game.
* **[?startseason](docs/commands/moderator-commands/startseason.md)** - Starts a new season of the Battle of Midgard game.
* **[?endseason](docs/commands/moderator-commands/endseason.md)** - Ends the current season of the Battle of Midgard game.
* **[?startsession](docs/commands/moderator-commands/startsession.md)** - Starts a new session of the Battle of Midgard game.
* **[?endsession](docs/commands/moderator-commands/endsession.md)** - Ends the current session of the Battle of Midgard game.
* **[?setdate](docs/commands/moderator-commands/setdate.md)** - Sets the end date of the current season of the Battle of Midgard game.
* **[?addpoints](docs/commands/moderator-commands/addpoints.md)** - Adds points to the viewer for the current season of the Battle of Midgard game.
* **[?removepoints](docs/commands/moderator-commands/removepoints.md)** - Removes points from the viewer for the current season of the Battle of Midgard game.

### Subscriber Commands

* **[?join](docs/commands/subscriber-commands/join.md)** - Joins the Battle of Midgard game and get randomly assigned to a clan.

### Viewer Commands

* **[?rank](docs/commands/viewer-commands/rank.md)** - Displays the Top 10 players in the clan for the current season of the Battle of Midgard game.
* **[?standings](docs/commands/viewer-commands/standings.md)** - Displays the current clan standings for the current season of the Battle of Midgard game.
* **[?overallrank](docs/commands/viewer-commands/overallrank.md)** - Displays the top 10 players across all clans for the current season of the Battle of Midgard game.
* **[?myrank](docs/commands/viewer-commands/myrank.md)** - Displays the current season points, lifetime points, clan rank and overall rank for the viewer.
* **[?dates](docs/commands/viewer-commands/dates.md)** - Displays the start and end dates for the current season of the Battle of Midgard game.
* **[?mvp](docs/commands/viewer-commands/mvp.md)** - Displays the MVP from the previous season of the Battle of Midgard game.
* **[?checkin](docs/commands/viewer-commands/checkin.md)** - Checks the viewer into the current session of the Battle of Midgard game.
* **[?help](docs/commands/viewer-commands/help.md)** - Displays a link to this documentation.
