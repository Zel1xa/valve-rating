### Roster Details<br />
Team Name: Yawara<br />
Roster: j0w, lash, revoltz, ritz, stAx<br />
Global Rank: [206](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
<br />
Final Rank Value:  494.5<br />
<br />
Final Rank Value (494.5) = Starting Rank Value (515.3) + Head To Head Adjustments (-20.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 515.3
- 400 + ( ( 0.056 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 515.3


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
|           18 |      102 | 2024-08-01 | Bounty Hunters | L   | 1.000      | -            | -                | -                | -         |    -2.45 | j0w, lash, revoltz, ritz, stAx  |
|           17 |      350 | 2024-07-25 | Imperial       | L   | 1.000      | -            | -                | -                | -         |    -0.70 | j0w, lash, revoltz, ritz, stAx  |
|           16 |      395 | 2024-07-24 | W7M            | L   | 1.000      | -            | -                | -                | -         |    -4.85 | j0w, lash, revoltz, ritz, stAx  |
|           15 |      401 | 2024-07-24 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -2.00 | j0w, lash, revoltz, ritz, stAx  |
|           14 |      481 | 2024-07-21 | Galorys        | L   | 1.000      | -            | -                | -                | -         |    -5.06 | j0w, lash, revoltz, ritz, stAx  |
|           13 |      566 | 2024-07-19 | SPORT          | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.115 (0.042)    | 0 (0.000) |    23.01 | j0w, lash, revoltz, ritz, stAx  |
|           12 |      689 | 2024-07-17 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |    -3.27 | j0w, lash, revoltz, ritz, stAx  |
|           11 |      787 | 2024-07-15 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -1.30 | j0w, lash, revoltz, ritz, stAx  |
|           10 |     1638 | 2024-05-31 | 9z Academy     | L   | 0.764      | -            | -                | -                | -         |   -12.00 | j0w, lash, ritz, stAx, Straafer |
|            9 |     1672 | 2024-05-29 | Vikings KR     | L   | 0.753      | -            | -                | -                | -         |    -3.67 | j0w, lash, perez, ritz, stAx    |
|            8 |     1699 | 2024-05-28 | W7M            | L   | 0.745      | -            | -                | -                | -         |    -4.25 | j0w, lash, perez, ritz, stAx    |
|            7 |     2044 | 2024-05-16 | Case           | L   | 0.664      | -            | -                | -                | -         |    -2.18 | j0w, lash, perez, ritz, stAx    |
|            6 |     2172 | 2024-05-13 | Galorys        | L   | 0.645      | -            | -                | -                | -         |    -2.00 | j0w, lash, perez, ritz, stAx    |
|            5 |     2297 | 2024-05-08 | Intense        | L   | 0.610      | -            | -                | -                | -         |    -4.13 | j0w, lash, perez, ritz, stAx    |
|            4 |     2326 | 2024-05-06 | Solid          | L   | 0.599      | -            | -                | -                | -         |    -2.19 | j0w, lash, perez, ritz, stAx    |
|            3 |     3589 | 2024-03-13 | Sharks         | L   | 0.239      | -            | -                | -                | -         |    -0.55 | j0w, lash, leleo, perez, stAx   |
|            2 |     3600 | 2024-03-13 | Case           | W   | 0.238      | 0.143        | 0.029 (0.001)    | 0.806 (0.027)    | 0 (0.000) |     6.84 | j0w, lash, leleo, perez, stAx   |
|            1 |     4268 | 2024-02-14 | Imperial       | L   | 0.053      | -            | -                | -                | -         |    -0.03 | j0w, lash, leleo, perez, stAx   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
