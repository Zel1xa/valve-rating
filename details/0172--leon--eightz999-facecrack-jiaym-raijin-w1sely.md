### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  664.3<br />
<br />
Final Rank Value (664.3) = Starting Rank Value (694.4) + Head To Head Adjustments (-30.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.4
- 400 + ( ( 0.144 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 694.4


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
|           18 |      628 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.39 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           17 |      686 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.26 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |     1044 | 2024-06-15 | Preasy            | L   | 0.865      | -            | -                | -                | -         |    -9.62 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |     1075 | 2024-06-14 | RUBY              | L   | 0.859      | -            | -                | -                | -         |    -6.43 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |     1137 | 2024-06-12 | CYBERSHOKE        | L   | 0.846      | -            | -                | -                | -         |    -6.84 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1164 | 2024-06-11 | MASONIC           | W   | 0.838      | 0.143        | 0.009 (0.001)    | 0.085 (0.010)    | 0 (0.000) |    15.89 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1539 | 2024-06-03 | Verdant           | L   | 0.787      | -            | -                | -                | -         |    -5.66 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1602 | 2024-06-01 | Aurora Young Blud | L   | 0.773      | -            | -                | -                | -         |    -8.11 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1625 | 2024-05-31 | VP.Prodigy        | W   | 0.767      | 0.372        | 0.025 (0.007)    | 0.401 (0.114)    | 0 (0.000) |    18.93 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1675 | 2024-05-29 | HOTU              | L   | 0.754      | -            | -                | -                | -         |   -12.29 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     1982 | 2024-05-18 | Rhyno             | L   | 0.678      | -            | -                | -                | -         |    -3.57 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     2008 | 2024-05-17 | WOPA              | W   | 0.672      | 0.143        | 0.001 (0.000)    | 0.127 (0.012)    | 0 (0.000) |     8.58 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     2141 | 2024-05-14 | VP.Prodigy        | L   | 0.654      | -            | -                | -                | -         |    -5.46 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2166 | 2024-05-13 | Secret            | W   | 0.647      | 0.143        | 0.000 (0.000)    | 0.058 (0.005)    | 0 (0.000) |     6.32 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2478 | 2024-04-29 | Nexus             | L   | 0.552      | -            | -                | -                | -         |    -5.27 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2494 | 2024-04-28 | VP.Prodigy        | L   | 0.546      | -            | -                | -                | -         |    -4.74 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2782 | 2024-04-18 | BIG               | L   | 0.478      | -            | -                | -                | -         |    -0.52 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3259 | 2024-04-01 | Lazer Cats        | W   | 0.366      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.37 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,180.27)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
