### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1316.4<br />
<br />
Final Rank Value (1316.4) = Starting Rank Value (1312.8) + Head To Head Adjustments (3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.575[<sup>2</sup>](#table1)

The average of these factors is 0.446<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1312.8
- 400 + ( ( 0.446 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1312.8


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
|           34 |       67 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.97 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |      104 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.188)    | 1 (1.000) |    27.84 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      162 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1046 | 2024-06-15 | Permitta      | L   | 0.864      | -            | -                | -                | -         |   -24.08 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1074 | 2024-06-14 | Space         | W   | 0.859      | 0.435        | -                | 0.406 (0.152)    | 0 (0.000) |     2.18 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1393 | 2024-06-06 | fnatic        | L   | 0.807      | -            | -                | -                | -         |    -7.69 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1432 | 2024-06-06 | Eternal Fire  | L   | 0.805      | -            | -                | -                | -         |    -3.63 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1456 | 2024-06-05 | BetBoom       | L   | 0.801      | -            | -                | -                | -         |   -10.96 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1478 | 2024-06-05 | Complexity    | L   | 0.799      | -            | -                | -                | -         |    -3.38 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1488 | 2024-06-05 | FURIA         | W   | 0.798      | 0.715        | 0.284 (0.162)    | 0.490 (0.280)    | 1 (0.798) |    19.97 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1670 | 2024-05-29 | HEROIC        | L   | 0.755      | -            | -                | -                | -         |    -4.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1681 | 2024-05-29 | Virtus.pro    | W   | 0.753      | 0.624        | 0.497 (0.234)    | 0.323 (0.152)    | 1 (0.753) |    20.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1697 | 2024-05-28 | FlyQuest      | W   | 0.748      | 0.624        | 0.104 (0.049)    | 0.294 (0.137)    | 1 (0.748) |     8.97 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1721 | 2024-05-27 | Natus Vincere | L   | 0.741      | -            | -                | -                | -         |    -0.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1917 | 2024-05-20 | MIBR          | L   | 0.692      | -            | -                | -                | -         |    -6.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1932 | 2024-05-19 | Astralis      | L   | 0.687      | -            | -                | -                | -         |    -1.64 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2310 | 2024-05-07 | G2            | L   | 0.606      | -            | -                | -                | -         |    -0.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2374 | 2024-05-03 | HEROIC        | W   | 0.580      | 0.889        | 0.229 (0.118)    | 0.373 (0.192)    | 1 (0.580) |    15.08 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2384 | 2024-05-03 | PERA          | W   | 0.579      | 0.889        | 0.048 (0.025)    | 0.453 (0.233)    | 1 (0.579) |     2.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2411 | 2024-05-02 | Natus Vincere | L   | 0.572      | -            | -                | -                | -         |    -0.37 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2433 | 2024-05-01 | BOSS          | W   | 0.565      | 0.889        | -                | 0.332 (0.167)    | 1 (0.565) |     1.24 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2646 | 2024-04-21 | BLEED         | L   | 0.498      | -            | -                | -                | -         |   -12.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2672 | 2024-04-20 | GamerLegion   | W   | 0.493      | 0.384        | 0.173 (0.033)    | -                | 0 (0.000) |     4.18 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2782 | 2024-04-18 | LEON          | W   | 0.478      | -            | -                | -                | 0 (0.000) |     0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2891 | 2024-04-13 | OG            | L   | 0.445      | -            | -                | -                | -         |   -11.48 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2900 | 2024-04-12 | FORZE         | W   | 0.440      | 0.684        | 0.058 (0.017)    | -                | -         |     1.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2971 | 2024-04-10 | Gods Reign    | W   | 0.427      | 0.684        | 0.041 (0.012)    | 0.204 (0.059)    | -         |     0.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3033 | 2024-04-09 | BetBoom       | L   | 0.419      | -            | -                | -                | -         |    -4.86 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3208 | 2024-04-03 | EYEBALLERS    | W   | 0.379      | 0.384        | -                | 0.509 (0.074)    | -         |     1.14 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3690 | 2024-03-09 | Spirit        | L   | 0.214      | -            | -                | -                | -         |    -0.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3721 | 2024-03-08 | GamerLegion   | W   | 0.207      | -            | -                | -                | -         |     0.33 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3851 | 2024-03-03 | Young Ninjas  | L   | 0.174      | -            | -                | -                | -         |    -5.25 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3911 | 2024-03-01 | AMKAL         | W   | 0.158      | 0.500        | 0.130 (0.010)    | -                | -         |     1.41 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3938 | 2024-02-28 | BLEED         | L   | 0.145      | -            | -                | -                | -         |    -4.01 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,236.31)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.873 | $2,000.00      | $1,746.44       |
| 2024-06-09 |      0.826 | $8,000.00      | $6,610.19       |
| 2024-06-02 |      0.780 | $6,000.00      | $4,682.64       |
| 2024-05-12 |      0.640 | $17,500.00     | $11,193.11      |
| 2024-04-14 |      0.453 | $35,000.00     | $15,848.03      |
| 2024-03-10 |      0.221 | $7,500.00      | $1,655.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
