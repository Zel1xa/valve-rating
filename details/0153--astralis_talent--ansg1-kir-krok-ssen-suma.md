### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  709.5<br />
<br />
Final Rank Value (709.5) = Starting Rank Value (786.4) + Head To Head Adjustments (-76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.204[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.4
- 400 + ( ( 0.188 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 786.4


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
|           23 |      128 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.66 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      322 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.82 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      375 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.20 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      428 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -6.71 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      500 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |     7.71 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      655 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.095 (0.014)    | 0 (0.000) |    16.29 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      703 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.59 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1119 | 2024-06-14 | Revenant          | L   | 0.847      | -            | -                | -                | -         |   -10.54 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1137 | 2024-06-13 | Aurora Young Blud | L   | 0.842      | -            | -                | -                | -         |    -7.21 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1177 | 2024-06-12 | Sashi             | L   | 0.834      | -            | -                | -                | -         |    -1.83 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1194 | 2024-06-11 | Sampi             | L   | 0.827      | -            | -                | -                | -         |    -8.13 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1350 | 2024-06-08 | M1X KS            | L   | 0.806      | -            | -                | -                | -         |    -9.23 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1389 | 2024-06-07 | Nexus             | L   | 0.801      | -            | -                | -                | -         |   -12.72 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1404 | 2024-06-07 | 618 KS            | W   | 0.799      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.799) |     2.83 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1453 | 2024-06-06 | Gaimin Gladiators | L   | 0.794      | -            | -                | -                | -         |    -5.81 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2683 | 2024-04-21 | MASONIC           | L   | 0.487      | -            | -                | -                | -         |    -7.75 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2689 | 2024-04-21 | Preasy            | W   | 0.485      | 0.318        | 0.008 (0.001)    | 0.216 (0.033)    | 1 (0.485) |     7.83 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2702 | 2024-04-20 | Kronjyllands      | W   | 0.482      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.482) |     1.69 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2905 | 2024-04-15 | ECLOT             | L   | 0.445      | -            | -                | -                | -         |    -1.27 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3082 | 2024-04-09 | Alliance          | L   | 0.405      | -            | -                | -                | -         |    -5.08 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3405 | 2024-03-25 | Sashi             | L   | 0.309      | -            | -                | -                | -         |    -6.22 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3408 | 2024-03-25 | XI                | W   | 0.308      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.78 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3749 | 2024-03-09 | NOM               | L   | 0.200      | -            | -                | -                | -         |    -5.25 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,791.67)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $545.00        | $458.76         |
| 2024-06-12 |      0.835 | $360.00        | $300.49         |
| 2024-06-08 |      0.808 | $1,087.00      | $878.53         |
| 2024-04-21 |      0.487 | $1,426.00      | $693.95         |
| 2024-03-25 |      0.309 | $1,490.00      | $459.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
