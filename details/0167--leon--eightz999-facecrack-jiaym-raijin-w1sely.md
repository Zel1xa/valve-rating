### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
<br />
Final Rank Value:  666.6<br />
<br />
Final Rank Value (666.6) = Starting Rank Value (695.3) + Head To Head Adjustments (-28.7)<br />

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
|           18 |      664 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.24 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           17 |      722 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.07 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |     1080 | 2024-06-15 | Preasy            | L   | 0.853      | -            | -                | -                | -         |    -9.58 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |     1111 | 2024-06-14 | RUBY              | L   | 0.848      | -            | -                | -                | -         |    -6.14 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |     1173 | 2024-06-12 | CYBERSHOKE        | L   | 0.834      | -            | -                | -                | -         |    -6.79 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1200 | 2024-06-11 | MASONIC           | W   | 0.826      | 0.143        | 0.009 (0.001)    | 0.081 (0.010)    | 0 (0.000) |    15.62 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1575 | 2024-06-03 | Verdant           | L   | 0.775      | -            | -                | -                | -         |    -5.56 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1638 | 2024-06-01 | Aurora Young Blud | L   | 0.761      | -            | -                | -                | -         |    -7.20 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1661 | 2024-05-31 | VP.Prodigy        | W   | 0.755      | 0.372        | 0.025 (0.007)    | 0.383 (0.108)    | 0 (0.000) |    18.63 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1711 | 2024-05-29 | HOTU              | L   | 0.742      | -            | -                | -                | -         |   -12.10 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     2018 | 2024-05-18 | Rhyno             | L   | 0.666      | -            | -                | -                | -         |    -3.55 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     2044 | 2024-05-17 | WOPA              | W   | 0.660      | 0.143        | 0.001 (0.000)    | 0.121 (0.011)    | 0 (0.000) |     8.43 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     2177 | 2024-05-14 | VP.Prodigy        | L   | 0.642      | -            | -                | -                | -         |    -5.38 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2202 | 2024-05-13 | Secret            | W   | 0.636      | 0.143        | 0.000 (0.000)    | 0.055 (0.005)    | 0 (0.000) |     6.18 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2514 | 2024-04-29 | Nexus             | L   | 0.540      | -            | -                | -                | -         |    -5.11 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2530 | 2024-04-28 | VP.Prodigy        | L   | 0.534      | -            | -                | -                | -         |    -4.64 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2818 | 2024-04-18 | BIG               | L   | 0.466      | -            | -                | -                | -         |    -0.51 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3295 | 2024-04-01 | Lazer Cats        | W   | 0.355      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.26 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,150.69)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
