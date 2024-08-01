### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
<br />
Final Rank Value:  667.7<br />
<br />
Final Rank Value (667.7) = Starting Rank Value (697.7) + Head To Head Adjustments (-30.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 697.7
- 400 + ( ( 0.145 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 697.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      517 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.48 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           17 |      575 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.26 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |      936 | 2024-06-15 | Preasy            | L   | 0.886      | -            | -                | -                | -         |    -9.87 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |      961 | 2024-06-14 | RUBY              | L   | 0.881      | -            | -                | -                | -         |    -6.47 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |     1023 | 2024-06-12 | CYBERSHOKE        | L   | 0.868      | -            | -                | -                | -         |    -7.00 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1051 | 2024-06-11 | MASONIC           | W   | 0.859      | 0.143        | 0.009 (0.001)    | 0.086 (0.011)    | 0 (0.000) |    16.46 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1441 | 2024-06-03 | Verdant           | L   | 0.808      | -            | -                | -                | -         |    -5.72 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1505 | 2024-06-01 | Aurora Young Blud | L   | 0.794      | -            | -                | -                | -         |    -8.23 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1528 | 2024-05-31 | VP.Prodigy        | W   | 0.788      | 0.372        | 0.026 (0.008)    | 0.405 (0.119)    | 0 (0.000) |    19.48 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1578 | 2024-05-29 | HOTU              | L   | 0.775      | -            | -                | -                | -         |   -12.64 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     1913 | 2024-05-18 | Rhyno             | L   | 0.699      | -            | -                | -                | -         |    -3.50 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     1939 | 2024-05-17 | WOPA              | W   | 0.693      | 0.143        | 0.001 (0.000)    | 0.127 (0.013)    | 0 (0.000) |     8.82 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     2078 | 2024-05-14 | VP.Prodigy        | L   | 0.675      | -            | -                | -                | -         |    -5.58 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2104 | 2024-05-13 | Secret            | W   | 0.669      | 0.143        | 0.000 (0.000)    | 0.060 (0.006)    | 0 (0.000) |     6.55 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2423 | 2024-04-29 | Nexus             | L   | 0.573      | -            | -                | -                | -         |    -5.39 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2439 | 2024-04-28 | VP.Prodigy        | L   | 0.567      | -            | -                | -                | -         |    -4.87 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2735 | 2024-04-18 | BIG               | L   | 0.499      | -            | -                | -                | -         |    -0.81 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3223 | 2024-04-01 | Lazer Cats        | W   | 0.388      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.54 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,233.33)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
