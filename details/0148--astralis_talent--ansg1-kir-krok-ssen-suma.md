### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  716.1<br />
<br />
Final Rank Value (716.1) = Starting Rank Value (797.8) + Head To Head Adjustments (-81.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.216[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 797.8
- 400 + ( ( 0.193 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 797.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      134 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -10.47 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      187 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.38 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      240 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -8.54 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      312 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |     7.63 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      467 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.102 (0.015)    | 0 (0.000) |    16.45 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      515 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.61 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |      931 | 2024-06-14 | Revenant          | L   | 0.884      | -            | -                | -                | -         |   -11.19 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |      949 | 2024-06-13 | Aurora Young Blud | L   | 0.879      | -            | -                | -                | -         |    -9.76 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |      989 | 2024-06-12 | Sashi             | L   | 0.872      | -            | -                | -                | -         |    -1.90 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1006 | 2024-06-11 | Sampi             | L   | 0.865      | -            | -                | -                | -         |    -9.10 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1162 | 2024-06-08 | M1X KS            | L   | 0.844      | -            | -                | -                | -         |    -9.61 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1201 | 2024-06-07 | Nexus             | L   | 0.839      | -            | -                | -                | -         |   -13.68 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1216 | 2024-06-07 | 618 KS            | W   | 0.837      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.837) |     2.85 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1265 | 2024-06-06 | Gaimin Gladiators | L   | 0.832      | -            | -                | -                | -         |    -5.87 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2495 | 2024-04-21 | MASONIC           | L   | 0.524      | -            | -                | -                | -         |    -8.32 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2501 | 2024-04-21 | Preasy            | W   | 0.523      | 0.318        | 0.012 (0.002)    | 0.222 (0.037)    | 1 (0.523) |     8.51 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2514 | 2024-04-20 | Kronjyllands      | W   | 0.519      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.519) |     1.75 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2717 | 2024-04-15 | ECLOT             | L   | 0.483      | -            | -                | -                | -         |    -2.34 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     2894 | 2024-04-09 | Alliance          | L   | 0.443      | -            | -                | -                | -         |    -5.71 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3217 | 2024-03-25 | Sashi             | L   | 0.346      | -            | -                | -                | -         |    -7.05 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3220 | 2024-03-25 | XI                | W   | 0.346      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.92 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3561 | 2024-03-09 | NOM               | L   | 0.238      | -            | -                | -                | -         |    -6.29 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,977.02)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.880 | $545.00        | $479.34         |
| 2024-06-12 |      0.872 | $360.00        | $314.09         |
| 2024-06-08 |      0.846 | $1,087.00      | $919.58         |
| 2024-04-21 |      0.524 | $1,426.00      | $747.80         |
| 2024-03-25 |      0.346 | $1,490.00      | $516.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
