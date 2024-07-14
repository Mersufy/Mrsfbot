**Bot Commands:**
**Prefix: %**
| Command     | Aliases  | Usage                                   | Description                                             | Cooldown        | Access   |
|-------------|----------|-----------------------------------------|---------------------------------------------------------|-----------------|----------|
| ping        |          |        ping                             | Returns various information about the bot's status.     |      3s           |   ✅      |
| commands    |cmds, help|       commands                          |                                                         |       3s          |      ✅    |
| prefix      |          | prefix <new_prefix>                      |        Changes the bot's prefix.                                                 |     10s            |     ⛔     |
| user           |     u     |             user <username>            | Get information about a specific Twitch user, if none specified it will default to yourself.|   3s              |    ✅      |
| username          |         |         username <user_id>             |          Gets the username of a given id                          |         3s        |     ✅     |
| team          |          |             team <team_name>          |                Retrieves the list of users in a specified Twitch team.         |      3s           |    ✅      |
| subage          |     sa     |          sa <username> <channel>                               |                                                         |       3s          |    ✅     |
| followage        |   fa     |        fa <username> <channel>                                |          Get the follow age of a user on Twitch.                   |       3s          |    ✅      |
| chatters       |    ch    |          chatters <username>                   |                Displays information about chatters in the channel                    |      3s           |    ✅      |
| badge          |   badges     |         badge <username>                |                 global vanity chat badge                            |    3s             |   ✅       |
| founders          |   founder    |           founders <channel>                   |             Get all available founders for a channel.                       |      3s           |     ✅     |
| uid           |     id     |        uid <user>                                 |    Retrieves the user ID of a specified user.    |       3s          |     ✅     |
| color           |          |      color <username>                                   |        Gets user's chat color, or defaults to your own if not specified.                                                 |    3s             |   ✅       |
| preview    |     prev     |          preview <channel>    |Get a preview image of specified Twitch stream. If no channel is provided, it will default to the current channel.         |        3s         |    ✅      |
| pfp           |   avatar       |          %pfp <username>                               |      Get the profile picture of a user.           |      3s           |   ✅       |
| streaminfo      |   si     |    si <channel>                          |         Shows current stream information.             |       3s          |    ✅      |
| team         |          |             team <team_name>                            |                 Retrieves the list of users in a specified Twitch team.                                        |     3s            |    ✅      |
| accage          |  age       |        accage <username>                         |                 Shows how old an account is.                                        |      3s           |     ✅     |
| StreamElements         |          |     streamelements <channel>                                    |           StreamElements commands                   |     3s            |     ✅     |
| fossabot          |          |           fossabot <channel>                             |              Fossabot commands                                           |      3s           |     ✅     |
| chatstats          |   stats     |       chatstats <channel>                            |             Shows chat statistics.                                            |        3s         |     ✅     |
| vanity       |          |          vanity <username>           |             Shows vanity information.                                    |     3s            |    ✅      |
| math          |  calc        |        %math <expression>                          |              Performs a math calculation.                   |          3s       |       ✅   |
| coin          |          |                  coin                       |                 Flips a coin.                                |        3s         |    ✅      |
| dice          |          |              dice                       |            Rolls a 6 sided die              |     3s            |    ✅      |
| pick          |          |          pick <word1> <word2>                         |             Randomly picks one of the provided options.                    |      3s           |      ✅    |
| follows          |          |           follows <channel>             |                Displays the followers of the specified channel.                   |     3s            |   ✅       |
|  afk     |          |          afk <message>                          |                    Sets AFK status with a message.                     |        3s         |    ✅      |
|  rafk     |          |         rafk                        |                Resumes AFK status within 5 minutes of returning.         |        3s         |      ✅    |
|  lastseen |          |      lastseen <username>                        |                Shows the last message of a specified user.                         |         3s        |     ✅     |
|    say      |          |           say <message>             |      Sends a message from the bot to the specified or current channel.        |        3s         |    ⛔      |
|   spam     |     sp     |     spam <count> <message>          |             Spam the chat.                                |       7s         |     ⛔     |
|    fill    |          |       fill <message to fill>       |       Fills message with maximum repitions of specified text.                    |        5s         |    ⛔      |
|    pyramid      |   py       |    pyramid <text>                   |      Creates a text pyramid with the given word.               |     10s          |     ⛔     |
|    split      |          |     split <text> <delimiter>         |          Splits text based on specified delimiter.                     |     5s            |    ⛔      |
|   ambassador      |          |      ambassador add/remove <username>              | Allow a moderator to perform actions on behalf of the broadcaster. Permissions only available if user remains a moderator. |      10s           |   ⛔       |
|    join    |          |       join <channel>                          |                Join a channel                     |        10s         |     ⛔     |
|   part       |          |      part <channel>                       |              Leave a channel'                           |        10s         |     ⛔    |
