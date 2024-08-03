### Roster Details<br />
Team Name: SPORT<br />
Roster: DANVIET, PremiuM, timid, voltera, xns<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [49]( ../standings_americas.md)<br />
<br />
Final Rank Value:  660.5<br />
<br />
Final Rank Value (660.5) = Starting Rank Value (711.5) + Head To Head Adjustments (-51.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.5
- 400 + ( ( 0.152 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 711.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      504 | 2024-07-19 | Yawara         | L   | 1.000      | -            | -                | -                | -         |   -22.91 | DANVIET, PremiuM, timid, voltera, xns  |
|           10 |      532 | 2024-07-18 | 9z Academy     | L   | 1.000      | -            | -                | -                | -         |   -23.55 | DANVIET, PremiuM, timid, voltera, xns  |
|            9 |      604 | 2024-07-17 | W7M            | L   | 1.000      | -            | -                | -                | -         |   -12.04 | DANVIET, PremiuM, timid, voltera, xns  |
|            8 |      616 | 2024-07-17 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |    -8.91 | DANVIET, PremiuM, timid, voltera, xns  |
|            7 |      668 | 2024-07-16 | Hype           | L   | 1.000      | -            | -                | -                | -         |   -10.10 | DANVIET, PremiuM, timid, voltera, xns  |
|            6 |      759 | 2024-07-12 | BESTIA         | W   | 1.000      | 0.333        | 0.091 (0.030)    | 0.756 (0.252)    | 0 (0.000) |    25.65 | DANVIET, PremiuM, timid, voltera, xns  |
|            5 |      779 | 2024-07-11 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.64 | DANVIET, PremiuM, timid, voltera, xns  |
|            4 |      817 | 2024-07-09 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -4.83 | DANVIET, PremiuM, timid, voltera, xns  |
|            3 |      833 | 2024-07-08 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.25 | DANVIET, PremiuM, timid, voltera, xns  |
|            2 |      905 | 2024-06-20 | ex-Corinthians | W   | 0.907      | 0.270        | 0.004 (0.001)    | 0.000 (0.000)    | 0 (0.000) |     7.53 | DANVIET, farias, PremiuM, voltera, xns |
|            1 |     2725 | 2024-04-16 | ODDIK          | L   | 0.475      | -            | -                | -                | -         |    -3.21 | DANVIET, farias, PremiuM, voltera, xns |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,451.63)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
