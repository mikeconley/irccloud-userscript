# mconley's IRCCloud user script

Shamelessly forked from [luser's irccloud-gifcommand](https://github.com/luser/irccloud-gifcommand)

I use [the IRCCloud desktop client](https://github.com/irccloud/irccloud-desktop), and that client lets me inject my own user script into its
execution scope.

This is the script I've added. It adds the following commands:

## Usage

Open your IRCCloud Desktop client, and choose File > Reveal User Script. The place that's revealed is where the script needs to go. Either copy it in there, or you can symlink it there (that's what I do).

## Commands

### /gif <search query>

This will search [giphy](https://giphy.com) for your query, and insert the first result that it returns. Pretty high risk, but sometimes hilarious.

### /shrug

Inserts

    ¯\_(ツ)_/¯

into the current channel.

### /tableflip

Inserts

    (╯°□°）╯︵ ┻━┻

into the current channel.


