### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  719.7<br />
<br />
Final Rank Value (719.7) = Starting Rank Value (800.8) + Head To Head Adjustments (-81.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.215[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 800.8
- 400 + ( ( 0.195 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 800.8


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
|           24 |      167 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.97 | ANSG1, kiR, kroK, sSen, suma       |
|           23 |      220 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.41 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      273 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -7.66 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      346 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |     7.55 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      368 | 2024-07-21 | K10               | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.133 (0.019)    | 0 (0.000) |    14.85 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      509 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.102 (0.015)    | 0 (0.000) |    16.91 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      557 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -6.37 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      970 | 2024-06-14 | Revenant          | L   | 0.879      | -            | -                | -                | -         |   -10.58 | alexsomfan, ANSG1, kiR, sSen, suma |
|           16 |      988 | 2024-06-13 | Aurora Young Blud | L   | 0.874      | -            | -                | -                | -         |    -7.89 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1028 | 2024-06-12 | Sashi             | L   | 0.866      | -            | -                | -                | -         |    -1.80 | ANSG1, kiR, kroK, sSen, suma       |
|           14 |     1046 | 2024-06-11 | Sampi             | L   | 0.859      | -            | -                | -                | -         |    -8.53 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1206 | 2024-06-08 | M1X KS            | L   | 0.838      | -            | -                | -                | -         |    -8.99 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1209 | 2024-06-08 | GhoulsW           | L   | 0.838      | -            | -                | -                | -         |   -20.75 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1251 | 2024-06-07 | Nexus             | L   | 0.833      | -            | -                | -                | -         |   -13.67 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1266 | 2024-06-07 | 618 KS            | W   | 0.831      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.831) |     2.79 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1317 | 2024-06-06 | Gaimin Gladiators | L   | 0.826      | -            | -                | -                | -         |    -5.97 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2597 | 2024-04-21 | MASONIC           | L   | 0.519      | -            | -                | -                | -         |    -8.32 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2603 | 2024-04-21 | Preasy            | W   | 0.517      | 0.318        | 0.012 (0.002)    | 0.222 (0.037)    | 1 (0.517) |     8.33 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2618 | 2024-04-20 | Kronjyllands      | W   | 0.514      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.514) |     1.70 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2825 | 2024-04-15 | ECLOT             | L   | 0.477      | -            | -                | -                | -         |    -2.37 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3003 | 2024-04-09 | Alliance          | L   | 0.438      | -            | -                | -                | -         |    -5.65 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3339 | 2024-03-25 | Sashi             | L   | 0.341      | -            | -                | -                | -         |    -6.99 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3342 | 2024-03-25 | XI                | W   | 0.340      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.86 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3689 | 2024-03-09 | NOM               | L   | 0.232      | -            | -                | -                | -         |    -6.16 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,948.91)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.874 | $545.00        | $476.22         |
| 2024-06-12 |      0.867 | $360.00        | $312.03         |
| 2024-06-08 |      0.840 | $1,087.00      | $913.36         |
| 2024-04-21 |      0.519 | $1,426.00      | $739.64         |
| 2024-03-25 |      0.341 | $1,490.00      | $507.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
