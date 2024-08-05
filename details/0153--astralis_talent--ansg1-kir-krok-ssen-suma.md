### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  707.2<br />
<br />
Final Rank Value (707.2) = Starting Rank Value (786.0) + Head To Head Adjustments (-78.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 786.0
- 400 + ( ( 0.188 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 786.0


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
|           23 |      114 | 2024-08-02 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |    -6.59 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |      308 | 2024-07-28 | GUN5              | L   | 1.000      | -            | -                | -                | -         |    -9.79 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |      361 | 2024-07-26 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.22 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |      414 | 2024-07-24 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -7.34 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |      486 | 2024-07-22 | GenOne            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.078 (0.011)    | 0 (0.000) |     7.75 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |      641 | 2024-07-18 | GL Academy        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.098 (0.014)    | 0 (0.000) |    16.33 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |      689 | 2024-07-17 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -7.59 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1105 | 2024-06-14 | Revenant          | L   | 0.852      | -            | -                | -                | -         |   -10.56 | alexsomfan, ANSG1, kiR, sSen, suma |
|           15 |     1123 | 2024-06-13 | Aurora Young Blud | L   | 0.847      | -            | -                | -                | -         |    -8.10 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     1163 | 2024-06-12 | Sashi             | L   | 0.839      | -            | -                | -                | -         |    -1.83 | ANSG1, kiR, kroK, sSen, suma       |
|           13 |     1180 | 2024-06-11 | Sampi             | L   | 0.833      | -            | -                | -                | -         |    -8.30 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     1336 | 2024-06-08 | M1X KS            | L   | 0.811      | -            | -                | -                | -         |    -9.29 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     1375 | 2024-06-07 | Nexus             | L   | 0.806      | -            | -                | -                | -         |   -12.90 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     1390 | 2024-06-07 | 618 KS            | W   | 0.805      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.805) |     2.86 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     1439 | 2024-06-06 | Gaimin Gladiators | L   | 0.799      | -            | -                | -                | -         |    -5.79 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2669 | 2024-04-21 | MASONIC           | L   | 0.492      | -            | -                | -                | -         |    -7.83 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            7 |     2675 | 2024-04-21 | Preasy            | W   | 0.491      | 0.318        | 0.008 (0.001)    | 0.221 (0.034)    | 1 (0.491) |     7.92 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     2688 | 2024-04-20 | Kronjyllands      | W   | 0.487      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.487) |     1.71 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     2891 | 2024-04-15 | ECLOT             | L   | 0.451      | -            | -                | -                | -         |    -1.29 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     3068 | 2024-04-09 | Alliance          | L   | 0.411      | -            | -                | -                | -         |    -5.13 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     3391 | 2024-03-25 | Sashi             | L   | 0.314      | -            | -                | -                | -         |    -6.32 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     3394 | 2024-03-25 | XI                | W   | 0.313      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.82 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     3735 | 2024-03-09 | NOM               | L   | 0.205      | -            | -                | -                | -         |    -5.39 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,818.03)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.847 | $545.00        | $461.69         |
| 2024-06-12 |      0.840 | $360.00        | $302.43         |
| 2024-06-08 |      0.814 | $1,087.00      | $884.37         |
| 2024-04-21 |      0.492 | $1,426.00      | $701.61         |
| 2024-03-25 |      0.314 | $1,490.00      | $467.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
