### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  667.7<br />
<br />
Final Rank Value (667.7) = Starting Rank Value (695.3) + Head To Head Adjustments (-27.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 695.3
- 400 + ( ( 0.144 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 695.3


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
|           18 |      672 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.25 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           17 |      730 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.07 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |     1088 | 2024-06-15 | Preasy            | L   | 0.852      | -            | -                | -                | -         |    -9.60 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |     1119 | 2024-06-14 | RUBY              | L   | 0.847      | -            | -                | -                | -         |    -6.11 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |     1181 | 2024-06-12 | CYBERSHOKE        | L   | 0.834      | -            | -                | -                | -         |    -6.78 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1208 | 2024-06-11 | MASONIC           | W   | 0.825      | 0.143        | 0.009 (0.001)    | 0.081 (0.010)    | 0 (0.000) |    15.56 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1583 | 2024-06-03 | Verdant           | L   | 0.774      | -            | -                | -                | -         |    -5.57 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1646 | 2024-06-01 | Aurora Young Blud | L   | 0.760      | -            | -                | -                | -         |    -6.16 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1669 | 2024-05-31 | VP.Prodigy        | W   | 0.754      | 0.372        | 0.025 (0.007)    | 0.383 (0.108)    | 0 (0.000) |    18.62 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1719 | 2024-05-29 | HOTU              | L   | 0.741      | -            | -                | -                | -         |   -12.09 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     2026 | 2024-05-18 | Rhyno             | L   | 0.665      | -            | -                | -                | -         |    -3.52 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     2052 | 2024-05-17 | WOPA              | W   | 0.659      | 0.143        | 0.001 (0.000)    | 0.121 (0.011)    | 0 (0.000) |     8.42 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     2185 | 2024-05-14 | VP.Prodigy        | L   | 0.641      | -            | -                | -                | -         |    -5.35 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2210 | 2024-05-13 | Secret            | W   | 0.635      | 0.143        | 0.000 (0.000)    | 0.055 (0.005)    | 0 (0.000) |     6.18 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2522 | 2024-04-29 | Nexus             | L   | 0.539      | -            | -                | -                | -         |    -5.07 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2538 | 2024-04-28 | VP.Prodigy        | L   | 0.533      | -            | -                | -                | -         |    -4.62 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2826 | 2024-04-18 | BIG               | L   | 0.465      | -            | -                | -                | -         |    -0.51 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3303 | 2024-04-01 | Lazer Cats        | W   | 0.354      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.25 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,148.38)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />