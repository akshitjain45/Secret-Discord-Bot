# SECRET Discord Bot πΎ

We created a Discord multi-purpose bot named βSECRETβ using python as our central programming language.

SECRET can perform a wide range of tasks that include some responsive **test functions** π, an **8-Ball trivia game** π±, performing **admin rights functions** π, a fully functioning **music player** π΅ that uses YouTube as its search platform, a **token-rank feature** π based on user activity, an **interactive AI chatbot** π¬ feature, **Wikipedia search** π and some **developer functions** π₯ for better performance.

> P.S. Our bot hasn't been deployed yet but you can still fork this repository, download and run the code as and when you feel like enjoying all the cool features of the bot! π

# Installation

Install all dependencies:

```shell
pip install -r requirements.txt
```
Then put your Discord token that can be found in the Discord's developers portal inside `bot.py`.

Finally, host the bot and invite it to your own server.

# Features 
## Test Functions π
Feature | Command
-------- | --------
**SECRET says "Hi"** | \*Hi
**Replies "Boop"** | \*Beep
**Returns the username** | \*user
**Return the bot's response time** | \*ping

## 8 Ball Trivia π±
Feature | Command
-------- | --------
**Magic 8Ball Trivia** | \*8ball \<_write your question here_>
  
## AI Chat Bot π¬
Feature | Command
-------- | --------
**AI Chat Bot** | \*ask \<_write your question here_>
  
## Admin Rights π
Feature | Command
-------- | --------
**Ban members from the server** | \*ban \@\<_tag the member_>
**Delete specified number of messages** | \*clear\<_add the number of messages_>
**Kick members from the server** | \*kick\@\<_tag the member_>
**Unban banned members from the server** | \*unban @<_tag the member_>

## Wikipedia Search π
  Feature | Command
-------- | --------
**Wikipedia search** | \*define\<_enter the keyword_>

## Music Player π΅
Feature | Command
-------- | --------
**Joins the Voice Channel** | \*join
**Disconnect from the voice channel** | \*leave
**Pause the playing audio** | \*pause
**Play YouTube audio** | \*play\<_YouTube URL_>
**Resume the paused audio** | \*resume
**Stop the playing audio** | \*stop

## Token Rank Feature π
Feature | Command
-------- | --------
**Displays the score and rank based on points system** | \*leaderboard
**Add points** | \*points add @<_tag the member_> <_points to be added_>
**Remove points** | \*points remove @<_tag the member_> <_points to be removed_>
**Reset the points database** | \*reset

## Developer Functions π₯
Feature | Command
-------- | --------
**Load the mentioned cogs file** | \*load<_name of the cogs file_>
**Reaload the mentioned cogs file** | \*reload<_name of the cogs file_>
**Unload the mentioned cogs file** | \*unload<_name of the cogs file_>

# Contributing π

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
