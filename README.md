# ![LOGO](logo.png) MLB v3 Stats **flow**ground Connector

## Description

A generated **flow**ground connector for the MLB v3 Stats API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/mlb-v3-stats/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:33+03:00

## API Description

MLB scores, stats, and news API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Teams (All)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Are Games In Progress

> Returns <code>true</code> if there is at least one game being played at the time of the request or <code>false</code> if there are none.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Box Score

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `gameid` - _required_ - The GameID of an MLB game.  GameIDs can be found in the Games API.  Valid entries are <code>14620</code> or <code>16905</code>

### Box Scores by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Box Scores by Date Delta

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.
* `minutes` - _required_ - Only returns player statistics that have changed in the last X minutes.  You specify how many minutes in time to go back. Valid entries are:
<code>1</code>, <code>2</code> ... <code>all</code>.

### Current Season

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### DFS Slates by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the slates.
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Player Details by Free Agents

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Schedules

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018PRE</code>, <code>2018POST</code>, <code>2018STAR</code>, <code>2019</code>, etc.

### Games by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Batter vs. Pitcher Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `hitterid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000031</code>.
* `pitcherid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000618</code>.

### News

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### News by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the news.
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### News by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000507</code>.

### Player Details by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000507</code>.

### Player Game Stats by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Player Game Stats by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000507</code>.

### Player Season Away Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

### Player Season Home Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

### Player Season Split Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.
* `split` - _required_ - The desired split of stats. Currently, we support vs. Left/Right/Switch handed pitchers/hitters. Possible values are: <code>L</code>, <code>R</code> and <code>S</code>
    Possible values: L, R, S.

### Player Season Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

### Player Season Stats By Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>10000507</code>.

### Player Season Stats by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

* `team` - _required_ - The abbreviation of the requested team.
<br>Examples: <code>SF</code>, <code>NYY</code>.

### Player Season Stats Split By Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

### Player Details by Active

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Players by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `team` - _required_ - The abbreviation of the requested team.
<br>Examples: <code>SF</code>, <code>NYY</code>.

### Stadiums

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: xml, json.

### Standings

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

### Team Game Stats by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### Team Hitting vs. Starting Pitcher

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `gameid` - _required_ - The GameID of an MLB game.  GameIDs can be found in the Games API.  Valid entries are <code>14620</code> or <code>16905</code>
* `team` - _required_ - The abbreviation of the requested team.
<br>Examples: <code>SF</code>, <code>NYY</code>.

### Team Season Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.
<br>Examples: <code>2017</code>, <code>2018</code>.

### Teams (Active)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-mlb-v-3-stats-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
