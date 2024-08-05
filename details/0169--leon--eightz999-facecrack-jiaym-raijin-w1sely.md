### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
<br />
Final Rank Value:  666.9<br />
<br />
Final Rank Value (666.9) = Starting Rank Value (697.9) + Head To Head Adjustments (-31.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 697.9
- 400 + ( ( 0.144 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 697.9


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
|           18 |      479 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.48 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           17 |      537 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.27 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |      895 | 2024-06-15 | Preasy            | L   | 0.890      | -            | -                | -                | -         |    -9.89 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |      926 | 2024-06-14 | RUBY              | L   | 0.885      | -            | -                | -                | -         |    -6.55 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |      988 | 2024-06-12 | CYBERSHOKE        | L   | 0.872      | -            | -                | -                | -         |    -7.03 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1015 | 2024-06-11 | MASONIC           | W   | 0.864      | 0.143        | 0.009 (0.001)    | 0.087 (0.011)    | 0 (0.000) |    16.58 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1390 | 2024-06-03 | Verdant           | L   | 0.813      | -            | -                | -                | -         |    -5.80 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1453 | 2024-06-01 | Aurora Young Blud | L   | 0.798      | -            | -                | -                | -         |    -9.13 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1476 | 2024-05-31 | VP.Prodigy        | W   | 0.793      | 0.372        | 0.026 (0.008)    | 0.406 (0.120)    | 0 (0.000) |    19.56 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1526 | 2024-05-29 | HOTU              | L   | 0.780      | -            | -                | -                | -         |   -12.71 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     1833 | 2024-05-18 | Rhyno             | L   | 0.704      | -            | -                | -                | -         |    -3.55 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     1859 | 2024-05-17 | WOPA              | W   | 0.698      | 0.143        | 0.001 (0.000)    | 0.127 (0.013)    | 0 (0.000) |     8.87 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     1992 | 2024-05-14 | VP.Prodigy        | L   | 0.679      | -            | -                | -                | -         |    -5.65 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2017 | 2024-05-13 | Secret            | W   | 0.673      | 0.143        | 0.000 (0.000)    | 0.061 (0.006)    | 0 (0.000) |     6.59 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2329 | 2024-04-29 | Nexus             | L   | 0.577      | -            | -                | -                | -         |    -5.46 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2345 | 2024-04-28 | VP.Prodigy        | L   | 0.571      | -            | -                | -                | -         |    -4.94 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2633 | 2024-04-18 | BIG               | L   | 0.504      | -            | -                | -                | -         |    -0.76 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3110 | 2024-04-01 | Lazer Cats        | W   | 0.392      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.57 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,244.18)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
