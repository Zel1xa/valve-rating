### Roster Details<br />
Team Name: LEON<br />
Roster: eightz999, facecrack, JIaYm, Raijin, w1sely<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
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
- 400 + ( ( 0.144 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 694.4


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
|           18 |      604 | 2024-07-18 | TSM               | L   | 1.000      | -            | -                | -                | -         |    -3.41 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           17 |      662 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -11.28 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           16 |     1020 | 2024-06-15 | Preasy            | L   | 0.866      | -            | -                | -                | -         |    -9.65 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           15 |     1051 | 2024-06-14 | RUBY              | L   | 0.860      | -            | -                | -                | -         |    -6.38 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           14 |     1113 | 2024-06-12 | CYBERSHOKE        | L   | 0.847      | -            | -                | -                | -         |    -6.86 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           13 |     1140 | 2024-06-11 | MASONIC           | W   | 0.839      | 0.143        | 0.009 (0.001)    | 0.085 (0.010)    | 0 (0.000) |    15.92 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           12 |     1515 | 2024-06-03 | Verdant           | L   | 0.788      | -            | -                | -                | -         |    -5.68 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           11 |     1578 | 2024-06-01 | Aurora Young Blud | L   | 0.774      | -            | -                | -                | -         |    -8.12 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|           10 |     1601 | 2024-05-31 | VP.Prodigy        | W   | 0.768      | 0.372        | 0.025 (0.007)    | 0.401 (0.115)    | 0 (0.000) |    18.93 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            9 |     1651 | 2024-05-29 | HOTU              | L   | 0.755      | -            | -                | -                | -         |   -12.31 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            8 |     1958 | 2024-05-18 | Rhyno             | L   | 0.679      | -            | -                | -                | -         |    -3.58 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            7 |     1984 | 2024-05-17 | WOPA              | W   | 0.673      | 0.143        | 0.001 (0.000)    | 0.127 (0.012)    | 0 (0.000) |     8.59 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            6 |     2117 | 2024-05-14 | VP.Prodigy        | L   | 0.655      | -            | -                | -                | -         |    -5.48 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            5 |     2142 | 2024-05-13 | Secret            | W   | 0.648      | 0.143        | 0.000 (0.000)    | 0.058 (0.005)    | 0 (0.000) |     6.34 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            4 |     2454 | 2024-04-29 | Nexus             | L   | 0.553      | -            | -                | -                | -         |    -5.27 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            3 |     2470 | 2024-04-28 | VP.Prodigy        | L   | 0.547      | -            | -                | -                | -         |    -4.76 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            2 |     2758 | 2024-04-18 | BIG               | L   | 0.479      | -            | -                | -                | -         |    -0.52 | eightz999, facecrack, JIaYm, Raijin, w1sely |
|            1 |     3235 | 2024-04-01 | Lazer Cats        | W   | 0.367      | 0.384        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.38 | eightz999, facecrack, JIaYm, Raijin, w1sely |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,182.93)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
