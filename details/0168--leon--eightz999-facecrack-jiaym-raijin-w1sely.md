### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
<br />
Final Rank Value:  670.6<br />
<br />
Final Rank Value (670.6) = Starting Rank Value (695.1) + Head To Head Adjustments (-24.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 695.1
- 400 + ( ( 0.144 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 695.1


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
|           17 |      570 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.49 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |      627 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.50 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |      965 | 2024-06-15 | Preasy            | L   | 0.871      | -            | -                | -                | -         |    -9.90 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |      989 | 2024-06-14 | RUBY              | L   | 0.866      | -            | -                | -                | -         |    -6.57 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1074 | 2024-06-11 | MASONIC           | W   | 0.844      | 0.143        | 0.009 (0.001)    | 0.088 (0.011)    | 0 (0.000) |    16.02 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1443 | 2024-06-03 | Verdant           | L   | 0.794      | -            | -                | -                | -         |    -5.71 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1503 | 2024-06-01 | Aurora Young Blud | L   | 0.779      | -            | -                | -                | -         |    -8.84 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1526 | 2024-05-31 | VP.Prodigy        | W   | 0.774      | 0.372        | 0.026 (0.007)    | 0.416 (0.120)    | 0 (0.000) |    19.09 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1576 | 2024-05-29 | HOTU              | L   | 0.761      | -            | -                | -                | -         |   -12.41 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     1881 | 2024-05-18 | Rhyno             | L   | 0.684      | -            | -                | -                | -         |    -3.59 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     1907 | 2024-05-17 | WOPA              | W   | 0.679      | 0.143        | 0.001 (0.000)    | 0.131 (0.013)    | 0 (0.000) |     8.65 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     2040 | 2024-05-14 | VP.Prodigy        | L   | 0.660      | -            | -                | -                | -         |    -5.51 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2065 | 2024-05-13 | Secret            | W   | 0.654      | 0.143        | 0.000 (0.000)    | 0.061 (0.006)    | 0 (0.000) |     6.40 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2376 | 2024-04-29 | Nexus             | L   | 0.558      | -            | -                | -                | -         |    -5.27 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2392 | 2024-04-28 | VP.Prodigy        | L   | 0.552      | -            | -                | -                | -         |    -4.78 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2679 | 2024-04-18 | BIG               | L   | 0.485      | -            | -                | -                | -         |    -0.52 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3156 | 2024-04-01 | Lazer Cats        | W   | 0.373      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.42 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,196.64)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
