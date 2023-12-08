# Races

In general, try not to join races you won't be able to finish, especially team formats. Formats here are organised by length. Time estimates given don't include setup time, which is usually between 10 and 30 minutes.

Unless mentioned otherwise, using the spoiler log in a race of any format not in the [spoiler format](#spoiler-formats) section **_is cheating_**.

Board generators:

- [ByngoSink](https://byngosink.manicjamie.com/) - Allows synced Exploration and Get To The Other Side boards. Still in open beta, so may be unstable.
- [Bingosync](https://www.bingosync.com) - only includes standard 5x5 formats, but more polished than ByngoSink.
- [Exploration Generator](https://butchie1331.github.io/hk-exploration-bingo/) - A generator without goal syncing, but the only one to currently support Roguelike.

## Solo Formats (non-spoiler)

### 3 Lines: _45 - 90 minutes_

First person to mark 3 lines of goals (rows, columns or diagonals) wins.

### Get To The Other Side: _1 - 2 hours_

Played on a 13x13 board with goals hidden until an adjacent goal is marked. Players start with only goals in the left column visible. First to mark a goal in the rightmost column wins.

### Lockout: _1 - 2 hours_

2-player format. Marking a goal prevents your opponent from marking it. First to 13 (the majority) wins. You may hold off marking goals you have completed in this format, but if your opponent marks it they get the mark instead.

### Chaos Lockout: _1 - 2 hours_

Lockout for more than 2 people - you are only locked out from marking a goal once half the players have marked the goal (rounded up). First to 13 wins.

### Invasion: _1- 2 hours_

2-player format. See [here](https://imgur.com/2WPnvHQ).

### Time Attack: _45 mins - 1 hour_

Time restricted format; mark the most goals in a given time period. Each goal is worth 1 point, and completing a line is worth an additional 2.

### Battleship

2-player format. Secretly place 3 battleships (diagonals allowed), one each of length 2, 3 and 4. Whenever your opponent completes a goal, tell them if it hit or missed your battleship. Winner is the one to sink all their opponent's battleships.

### Roguelike

Players must make it from one side of the board to the other. Marking a goal will reveal the 3 closest goal in the next row, but you may only mark 1 goal per row, meaning you're stuck with the 3 goals you revealed.

## Team Formats (non-spoiler)

Please be considerate to your teammate when joining team formats - formats requiring beating Radiance are marked below.

### Blackout True Ending / BOTE (Requires Radiance): _1 - 2 hours_

Mark all goals on the board then beat Radiance. Only one person on each team needs to complete the goals, but all members of the team must beat Radiance after all goals are marked.

### Exploration: _1 - 2 hours, depending on number of corners_

Played on a 13x13 board with goals hidden until an adjacent goal is marked. The center goal is marked as a free goal, and the goal is to mark some number of corners (usually 3 or 4). May also be played solo, but is usually 2v..v2.

### All Majors (Requires Radiance): _1 - 2 hours_

Semi spoiler format using `MajorItemByAreaTracker`, which shows a count of unobtained major items in each area.

## Spoiler Formats

Spoiler formats have you read your seed's `ItemSpoilerLog.json`. These formats are often made easier by `CondensedSpoilerViewer`, which creates an easier to read `CondensedSpoilerLog.txt`.

Time estimates are given with a prep time, time you are allowed to read the spoiler log but not play. You may still read the spoiler log after prep time has ended & gameplay has begun.

### Compass% - _5 mins + 10-30 mins_

1v...v1 format. First to pick up Wayward Compass wins.

### Double Anti Bingo / DAB - _10 mins + 45 mins_

1v...v1 format. At the end of preparation time, each player selects a line to force their opponent to complete. To finish, you must complete your forced line and one other line of your choice.

### Hand & Brain - _No prep time + 30min - 1:30 hours (depending on goal)_

2v...v2 format, where only one player on each team plays (and cannot access the spoiler log). The other player has the spoiler log and relays information for the runner to use. Any goal may be used (3 lines, True Ending or others).
