### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  707.3<br />
<br />
Final Rank Value (707.3) = Starting Rank Value (788.1) + Head To Head Adjustments (-80.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 788.1
- 400 + ( ( 0.190 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 788.1


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
|           23 |      106 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.61 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      300 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.83 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      353 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.21 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      406 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -7.83 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      478 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.079 (0.011)    | 0 (0.000) |     7.73 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      633 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.099 (0.014)    | 0 (0.000) |    16.29 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      681 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.63 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1097 | 2024-06-14 | Revenant          | L   | 0.853      | -            | -                | -                | -         |   -10.65 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1115 | 2024-06-13 | Aurora Young Blud | L   | 0.848      | -            | -                | -                | -         |    -8.79 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1155 | 2024-06-12 | Sashi             | L   | 0.841      | -            | -                | -                | -         |    -1.85 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1172 | 2024-06-11 | Sampi             | L   | 0.834      | -            | -                | -                | -         |    -8.40 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1328 | 2024-06-08 | M1X KS            | L   | 0.812      | -            | -                | -                | -         |    -9.38 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1367 | 2024-06-07 | Nexus             | L   | 0.807      | -            | -                | -                | -         |   -13.00 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1382 | 2024-06-07 | 618 KS            | W   | 0.806      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.806) |     2.84 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1431 | 2024-06-06 | Gaimin Gladiators | L   | 0.801      | -            | -                | -                | -         |    -5.84 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2661 | 2024-04-21 | MASONIC           | L   | 0.493      | -            | -                | -                | -         |    -7.89 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2667 | 2024-04-21 | Preasy            | W   | 0.492      | 0.318        | 0.012 (0.002)    | 0.224 (0.035)    | 1 (0.492) |     8.07 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2680 | 2024-04-20 | Kronjyllands      | W   | 0.488      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.488) |     1.70 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2883 | 2024-04-15 | ECLOT             | L   | 0.452      | -            | -                | -                | -         |    -1.31 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3060 | 2024-04-09 | Alliance          | L   | 0.412      | -            | -                | -                | -         |    -5.19 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3383 | 2024-03-25 | Sashi             | L   | 0.315      | -            | -                | -                | -         |    -6.37 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3386 | 2024-03-25 | XI                | W   | 0.314      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.81 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3727 | 2024-03-09 | NOM               | L   | 0.206      | -            | -                | -                | -         |    -5.43 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,823.48)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.848 | $545.00        | $462.29         |
| 2024-06-12 |      0.841 | $360.00        | $302.83         |
| 2024-06-08 |      0.815 | $1,087.00      | $885.58         |
| 2024-04-21 |      0.493 | $1,426.00      | $703.20         |
| 2024-03-25 |      0.315 | $1,490.00      | $469.59         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
