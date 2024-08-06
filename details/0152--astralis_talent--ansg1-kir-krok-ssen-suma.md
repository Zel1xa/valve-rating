### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [152](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  708.1<br />
<br />
Final Rank Value (708.1) = Starting Rank Value (786.4) + Head To Head Adjustments (-78.4)<br />

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
|           23 |      125 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.62 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      319 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.78 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      372 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.20 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      425 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -7.34 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      497 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |     7.74 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      652 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.095 (0.014)    | 0 (0.000) |    16.29 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      700 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.59 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1116 | 2024-06-14 | Revenant          | L   | 0.847      | -            | -                | -                | -         |   -10.51 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1134 | 2024-06-13 | Aurora Young Blud | L   | 0.842      | -            | -                | -                | -         |    -8.07 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1174 | 2024-06-12 | Sashi             | L   | 0.834      | -            | -                | -                | -         |    -1.83 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1191 | 2024-06-11 | Sampi             | L   | 0.828      | -            | -                | -                | -         |    -8.25 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1347 | 2024-06-08 | M1X KS            | L   | 0.806      | -            | -                | -                | -         |    -9.24 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1386 | 2024-06-07 | Nexus             | L   | 0.801      | -            | -                | -                | -         |   -12.73 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1401 | 2024-06-07 | 618 KS            | W   | 0.800      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.800) |     2.84 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1450 | 2024-06-06 | Gaimin Gladiators | L   | 0.794      | -            | -                | -                | -         |    -5.80 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2680 | 2024-04-21 | MASONIC           | L   | 0.487      | -            | -                | -                | -         |    -7.76 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2686 | 2024-04-21 | Preasy            | W   | 0.486      | 0.318        | 0.008 (0.001)    | 0.216 (0.033)    | 1 (0.486) |     7.83 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2699 | 2024-04-20 | Kronjyllands      | W   | 0.482      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.482) |     1.69 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2902 | 2024-04-15 | ECLOT             | L   | 0.446      | -            | -                | -                | -         |    -1.27 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3079 | 2024-04-09 | Alliance          | L   | 0.406      | -            | -                | -                | -         |    -5.09 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3402 | 2024-03-25 | Sashi             | L   | 0.309      | -            | -                | -                | -         |    -6.22 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3405 | 2024-03-25 | XI                | W   | 0.308      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.79 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3746 | 2024-03-09 | NOM               | L   | 0.200      | -            | -                | -                | -         |    -5.26 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,793.49)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $545.00        | $458.96         |
| 2024-06-12 |      0.835 | $360.00        | $300.63         |
| 2024-06-08 |      0.809 | $1,087.00      | $878.94         |
| 2024-04-21 |      0.487 | $1,426.00      | $694.48         |
| 2024-03-25 |      0.309 | $1,490.00      | $460.49         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
