### Roster Details<br />
Team Name: Astralis Talent<br />
Roster: ANSG1, kiR, kroK, sSen, suma<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  649.6<br />
<br />
Final Rank Value (649.6) = Starting Rank Value (701.6) + Head To Head Adjustments (-52.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.156<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.6
- 400 + ( ( 0.156 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 701.6


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
|           24 |     1011 | 2024-08-09 | Into the Breach   | L   | 0.999      | -            | -                | -                | -         |    -7.54 | ANSG1, kiR, kroK, sSen, suma       |
|           23 |     1037 | 2024-08-08 | Enterprise        | L   | 0.993      | -            | -                | -                | -         |    -5.96 | ANSG1, kiR, kroK, sSen, suma       |
|           22 |     1253 | 2024-08-02 | RUSH B            | L   | 0.952      | -            | -                | -                | -         |    -5.86 | ANSG1, kiR, kroK, sSen, suma       |
|           21 |     1447 | 2024-07-28 | GUN5              | L   | 0.920      | -            | -                | -                | -         |    -6.83 | ANSG1, kiR, kroK, sSen, suma       |
|           20 |     1500 | 2024-07-26 | Passion UA        | L   | 0.906      | -            | -                | -                | -         |    -2.67 | ANSG1, kiR, kroK, sSen, suma       |
|           19 |     1553 | 2024-07-24 | Aurora Young Blud | L   | 0.895      | -            | -                | -                | -         |    -5.24 | ANSG1, kiR, kroK, sSen, suma       |
|           18 |     1625 | 2024-07-22 | GenOne            | W   | 0.881      | 0.143        | 0.000 (0.000)    | 0.103 (0.013)    | 0 (0.000) |     8.03 | ANSG1, kiR, kroK, sSen, suma       |
|           17 |     1780 | 2024-07-18 | GL Academy        | W   | 0.853      | 0.143        | 0.002 (0.000)    | 0.052 (0.006)    | 0 (0.000) |    13.45 | ANSG1, kiR, kroK, sSen, suma       |
|           16 |     1828 | 2024-07-17 | 9INE              | L   | 0.848      | -            | -                | -                | -         |    -5.40 | ANSG1, kiR, kroK, sSen, suma       |
|           15 |     2247 | 2024-06-14 | Revenant          | L   | 0.626      | -            | -                | -                | -         |    -4.18 | alexsomfan, ANSG1, kiR, sSen, suma |
|           14 |     2265 | 2024-06-13 | Aurora Young Blud | L   | 0.621      | -            | -                | -                | -         |    -4.21 | alexsomfan, ANSG1, kiR, sSen, suma |
|           13 |     2305 | 2024-06-12 | Sashi             | L   | 0.614      | -            | -                | -                | -         |    -1.56 | ANSG1, kiR, kroK, sSen, suma       |
|           12 |     2322 | 2024-06-11 | Sampi             | L   | 0.607      | -            | -                | -                | -         |    -4.87 | ANSG1, kiR, kroK, sSen, suma       |
|           11 |     2478 | 2024-06-08 | M1X KS            | L   | 0.586      | -            | -                | -                | -         |    -7.30 | ANSG1, kiR, kroK, sSen, suma       |
|           10 |     2517 | 2024-06-07 | Nexus             | L   | 0.581      | -            | -                | -                | -         |    -7.89 | ANSG1, kiR, kroK, sSen, suma       |
|            9 |     2532 | 2024-06-07 | 618 KS            | W   | 0.579      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.579) |     2.91 | ANSG1, kiR, kroK, sSen, suma       |
|            8 |     2581 | 2024-06-06 | Gaimin Gladiators | L   | 0.574      | -            | -                | -                | -         |    -4.46 | ANSG1, kiR, kroK, sSen, suma       |
|            7 |     3811 | 2024-04-21 | MASONIC           | L   | 0.266      | -            | -                | -                | -         |    -4.40 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            6 |     3817 | 2024-04-21 | Preasy            | W   | 0.265      | 0.318        | 0.007 (0.001)    | 0.162 (0.014)    | 1 (0.265) |     4.47 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            5 |     3830 | 2024-04-20 | Kronjyllands      | W   | 0.261      | 0.318        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.261) |     1.30 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            4 |     4033 | 2024-04-15 | ECLOT             | L   | 0.225      | -            | -                | -                | -         |    -0.80 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            3 |     4210 | 2024-04-09 | Alliance          | L   | 0.185      | -            | -                | -                | -         |    -1.93 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            2 |     4533 | 2024-03-25 | Sashi             | L   | 0.088      | -            | -                | -                | -         |    -1.70 | ANSG1, JBOEN, kiR, kroK, tOPZ      |
|            1 |     4536 | 2024-03-25 | XI                | W   | 0.088      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.67 | ANSG1, JBOEN, kiR, kroK, tOPZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,711.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.622 | $545.00        | $338.76         |
| 2024-06-12 |      0.615 | $360.00        | $221.23         |
| 2024-06-08 |      0.588 | $1,087.00      | $639.19         |
| 2024-04-21 |      0.266 | $1,426.00      | $379.97         |
| 2024-03-25 |      0.088 | $1,490.00      | $131.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
