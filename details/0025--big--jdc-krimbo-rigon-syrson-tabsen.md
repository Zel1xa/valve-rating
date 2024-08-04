### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1315.4<br />
<br />
Final Rank Value (1315.4) = Starting Rank Value (1313.1) + Head To Head Adjustments (2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.164[<sup>2</sup>](#table1)
- LAN Wins: 0.576[<sup>2</sup>](#table1)

The average of these factors is 0.447<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1313.1
- 400 + ( ( 0.447 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1313.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       37 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.99 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |       74 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.188)    | 1 (1.000) |    27.73 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      130 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.74 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1014 | 2024-06-15 | Permitta      | L   | 0.866      | -            | -                | -                | -         |   -24.15 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1042 | 2024-06-14 | Space         | W   | 0.861      | 0.435        | -                | 0.406 (0.152)    | 0 (0.000) |     2.26 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1361 | 2024-06-06 | fnatic        | L   | 0.809      | -            | -                | -                | -         |    -7.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1400 | 2024-06-06 | Eternal Fire  | L   | 0.807      | -            | -                | -                | -         |    -3.70 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1424 | 2024-06-05 | BetBoom       | L   | 0.802      | -            | -                | -                | -         |   -10.97 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1446 | 2024-06-05 | Complexity    | L   | 0.801      | -            | -                | -                | -         |    -3.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1456 | 2024-06-05 | FURIA         | W   | 0.800      | 0.715        | 0.284 (0.163)    | 0.491 (0.281)    | 1 (0.800) |    19.94 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1638 | 2024-05-29 | HEROIC        | L   | 0.757      | -            | -                | -                | -         |    -4.64 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1649 | 2024-05-29 | Virtus.pro    | W   | 0.755      | 0.624        | 0.497 (0.234)    | 0.323 (0.152)    | 1 (0.755) |    20.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1665 | 2024-05-28 | FlyQuest      | W   | 0.749      | 0.624        | 0.104 (0.049)    | 0.290 (0.136)    | 1 (0.749) |     8.92 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1689 | 2024-05-27 | Natus Vincere | L   | 0.743      | -            | -                | -                | -         |    -0.60 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1885 | 2024-05-20 | MIBR          | L   | 0.694      | -            | -                | -                | -         |    -6.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1900 | 2024-05-19 | Astralis      | L   | 0.689      | -            | -                | -                | -         |    -2.02 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2278 | 2024-05-07 | G2            | L   | 0.608      | -            | -                | -                | -         |    -0.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2342 | 2024-05-03 | HEROIC        | W   | 0.582      | 0.889        | 0.229 (0.118)    | 0.374 (0.193)    | 1 (0.582) |    15.07 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2352 | 2024-05-03 | PERA          | W   | 0.580      | 0.889        | 0.048 (0.025)    | 0.453 (0.233)    | 1 (0.580) |     2.10 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2379 | 2024-05-02 | Natus Vincere | L   | 0.574      | -            | -                | -                | -         |    -0.38 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2401 | 2024-05-01 | BOSS          | W   | 0.567      | 0.889        | -                | 0.333 (0.168)    | 1 (0.567) |     1.24 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2614 | 2024-04-21 | BLEED         | L   | 0.500      | -            | -                | -                | -         |   -12.83 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2640 | 2024-04-20 | GamerLegion   | W   | 0.494      | 0.384        | 0.174 (0.033)    | -                | 0 (0.000) |     4.20 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2750 | 2024-04-18 | LEON          | W   | 0.480      | -            | -                | -                | 0 (0.000) |     0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2859 | 2024-04-13 | OG            | L   | 0.447      | -            | -                | -                | -         |   -11.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2868 | 2024-04-12 | FORZE         | W   | 0.442      | 0.684        | 0.058 (0.018)    | -                | -         |     1.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2939 | 2024-04-10 | Gods Reign    | W   | 0.429      | 0.684        | 0.041 (0.012)    | 0.204 (0.060)    | -         |     0.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3001 | 2024-04-09 | BetBoom       | L   | 0.421      | -            | -                | -                | -         |    -4.88 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3176 | 2024-04-03 | EYEBALLERS    | W   | 0.381      | 0.384        | -                | 0.510 (0.075)    | -         |     1.14 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3658 | 2024-03-09 | Spirit        | L   | 0.216      | -            | -                | -                | -         |    -0.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3689 | 2024-03-08 | GamerLegion   | W   | 0.208      | -            | -                | -                | -         |     0.34 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3819 | 2024-03-03 | Young Ninjas  | L   | 0.176      | -            | -                | -                | -         |    -5.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3879 | 2024-03-01 | AMKAL         | W   | 0.160      | 0.500        | 0.130 (0.010)    | -                | -         |     1.43 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3906 | 2024-02-28 | BLEED         | L   | 0.147      | -            | -                | -                | -         |    -4.07 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,371.77)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.875 | $2,000.00      | $1,750.00       |
| 2024-06-09 |      0.828 | $8,000.00      | $6,624.44       |
| 2024-06-02 |      0.782 | $6,000.00      | $4,693.33       |
| 2024-05-12 |      0.641 | $17,500.00     | $11,224.31      |
| 2024-04-14 |      0.455 | $35,000.00     | $15,910.42      |
| 2024-03-10 |      0.223 | $7,500.00      | $1,669.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
