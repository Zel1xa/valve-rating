### Roster Details<br />
Team Name: Yawara<br />
Roster: j0w, lash, revoltz, ritz, stAx<br />
Global Rank: [206](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
<br />
Final Rank Value:  494.6<br />
<br />
Final Rank Value (494.6) = Starting Rank Value (515.6) + Head To Head Adjustments (-21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 515.6
- 400 + ( ( 0.056 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 515.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      132 | 2024-08-01 | Bounty Hunters | L   | 1.000      | -            | -                | -                | -         |    -2.48 | j0w, lash, revoltz, ritz, stAx  |
|           17 |      380 | 2024-07-25 | Imperial       | L   | 1.000      | -            | -                | -                | -         |    -0.72 | j0w, lash, revoltz, ritz, stAx  |
|           16 |      425 | 2024-07-24 | W7M            | L   | 1.000      | -            | -                | -                | -         |    -4.89 | j0w, lash, revoltz, ritz, stAx  |
|           15 |      431 | 2024-07-24 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -2.04 | j0w, lash, revoltz, ritz, stAx  |
|           14 |      511 | 2024-07-21 | Galorys        | L   | 1.000      | -            | -                | -                | -         |    -5.10 | j0w, lash, revoltz, ritz, stAx  |
|           13 |      596 | 2024-07-19 | SPORT          | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.111 (0.041)    | 0 (0.000) |    23.02 | j0w, lash, revoltz, ritz, stAx  |
|           12 |      719 | 2024-07-17 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |    -3.31 | j0w, lash, revoltz, ritz, stAx  |
|           11 |      817 | 2024-07-15 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -1.33 | j0w, lash, revoltz, ritz, stAx  |
|           10 |     1668 | 2024-05-31 | 9z Academy     | L   | 0.754      | -            | -                | -                | -         |   -11.83 | j0w, lash, ritz, stAx, Straafer |
|            9 |     1702 | 2024-05-29 | Vikings KR     | L   | 0.743      | -            | -                | -                | -         |    -3.65 | j0w, lash, perez, ritz, stAx    |
|            8 |     1729 | 2024-05-28 | W7M            | L   | 0.735      | -            | -                | -                | -         |    -4.22 | j0w, lash, perez, ritz, stAx    |
|            7 |     2074 | 2024-05-16 | Case           | L   | 0.654      | -            | -                | -                | -         |    -2.17 | j0w, lash, perez, ritz, stAx    |
|            6 |     2202 | 2024-05-13 | Galorys        | L   | 0.635      | -            | -                | -                | -         |    -2.00 | j0w, lash, perez, ritz, stAx    |
|            5 |     2327 | 2024-05-08 | Intense        | L   | 0.600      | -            | -                | -                | -         |    -4.07 | j0w, lash, perez, ritz, stAx    |
|            4 |     2356 | 2024-05-06 | Solid          | L   | 0.589      | -            | -                | -                | -         |    -2.18 | j0w, lash, perez, ritz, stAx    |
|            3 |     3619 | 2024-03-13 | Sharks         | L   | 0.229      | -            | -                | -                | -         |    -0.53 | j0w, lash, leleo, perez, stAx   |
|            2 |     3630 | 2024-03-13 | Case           | W   | 0.228      | 0.143        | 0.029 (0.001)    | 0.778 (0.025)    | 0 (0.000) |     6.54 | j0w, lash, leleo, perez, stAx   |
|            1 |     4298 | 2024-02-14 | Imperial       | L   | 0.043      | -            | -                | -                | -         |    -0.02 | j0w, lash, leleo, perez, stAx   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
