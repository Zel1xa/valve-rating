### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  707.0<br />
<br />
Final Rank Value (707.0) = Starting Rank Value (788.5) + Head To Head Adjustments (-81.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 788.5
- 400 + ( ( 0.190 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 788.5


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
|           23 |       88 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.59 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      282 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.74 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      335 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.25 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      388 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -7.85 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      460 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.079 (0.011)    | 0 (0.000) |     7.73 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      615 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.100 (0.014)    | 0 (0.000) |    16.33 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      663 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.63 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1079 | 2024-06-14 | Revenant          | L   | 0.859      | -            | -                | -                | -         |   -10.75 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1097 | 2024-06-13 | Aurora Young Blud | L   | 0.854      | -            | -                | -                | -         |    -8.88 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1137 | 2024-06-12 | Sashi             | L   | 0.847      | -            | -                | -                | -         |    -1.86 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1154 | 2024-06-11 | Sampi             | L   | 0.840      | -            | -                | -                | -         |    -8.55 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1310 | 2024-06-08 | M1X KS            | L   | 0.818      | -            | -                | -                | -         |    -9.44 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1349 | 2024-06-07 | Nexus             | L   | 0.813      | -            | -                | -                | -         |   -13.13 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1364 | 2024-06-07 | 618 KS            | W   | 0.812      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.812) |     2.86 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1413 | 2024-06-06 | Gaimin Gladiators | L   | 0.807      | -            | -                | -                | -         |    -5.83 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2643 | 2024-04-21 | MASONIC           | L   | 0.499      | -            | -                | -                | -         |    -7.98 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2649 | 2024-04-21 | Preasy            | W   | 0.498      | 0.318        | 0.012 (0.002)    | 0.224 (0.035)    | 1 (0.498) |     8.16 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2662 | 2024-04-20 | Kronjyllands      | W   | 0.494      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.494) |     1.72 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2865 | 2024-04-15 | ECLOT             | L   | 0.458      | -            | -                | -                | -         |    -1.33 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3042 | 2024-04-09 | Alliance          | L   | 0.418      | -            | -                | -                | -         |    -5.26 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3365 | 2024-03-25 | Sashi             | L   | 0.321      | -            | -                | -                | -         |    -6.49 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3368 | 2024-03-25 | XI                | W   | 0.320      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.84 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3709 | 2024-03-09 | NOM               | L   | 0.212      | -            | -                | -                | -         |    -5.59 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,853.02)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.854 | $545.00        | $465.57         |
| 2024-06-12 |      0.847 | $360.00        | $304.99         |
| 2024-06-08 |      0.821 | $1,087.00      | $892.12         |
| 2024-04-21 |      0.499 | $1,426.00      | $711.78         |
| 2024-03-25 |      0.321 | $1,490.00      | $478.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
