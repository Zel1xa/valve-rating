### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1315.9<br />
<br />
Final Rank Value (1315.9) = Starting Rank Value (1312.1) + Head To Head Adjustments (3.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.494[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.574[<sup>2</sup>](#table1)

The average of these factors is 0.446<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1312.1
- 400 + ( ( 0.446 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1312.1


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
|           34 |       71 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.97 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |      108 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.187)    | 1 (1.000) |    27.84 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      166 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1050 | 2024-06-15 | Permitta      | L   | 0.862      | -            | -                | -                | -         |   -24.01 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1078 | 2024-06-14 | Space         | W   | 0.857      | 0.435        | -                | 0.406 (0.151)    | 0 (0.000) |     2.18 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1397 | 2024-06-06 | fnatic        | L   | 0.805      | -            | -                | -                | -         |    -7.64 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1436 | 2024-06-06 | Eternal Fire  | L   | 0.803      | -            | -                | -                | -         |    -3.62 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1460 | 2024-06-05 | BetBoom       | L   | 0.798      | -            | -                | -                | -         |   -10.93 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1482 | 2024-06-05 | Complexity    | L   | 0.797      | -            | -                | -                | -         |    -3.37 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1492 | 2024-06-05 | FURIA         | W   | 0.796      | 0.715        | 0.284 (0.162)    | 0.490 (0.279)    | 1 (0.796) |    19.95 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1674 | 2024-05-29 | HEROIC        | L   | 0.753      | -            | -                | -                | -         |    -4.55 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1685 | 2024-05-29 | Virtus.pro    | W   | 0.751      | 0.624        | 0.497 (0.233)    | 0.323 (0.151)    | 1 (0.751) |    20.70 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1701 | 2024-05-28 | FlyQuest      | W   | 0.745      | 0.624        | 0.104 (0.048)    | 0.293 (0.136)    | 1 (0.745) |     8.91 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1725 | 2024-05-27 | Natus Vincere | L   | 0.739      | -            | -                | -                | -         |    -0.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1921 | 2024-05-20 | MIBR          | L   | 0.690      | -            | -                | -                | -         |    -6.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1936 | 2024-05-19 | Astralis      | L   | 0.685      | -            | -                | -                | -         |    -1.63 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2314 | 2024-05-07 | G2            | L   | 0.604      | -            | -                | -                | -         |    -0.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2378 | 2024-05-03 | HEROIC        | W   | 0.578      | 0.889        | 0.226 (0.116)    | 0.372 (0.191)    | 1 (0.578) |    15.02 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2388 | 2024-05-03 | PERA          | W   | 0.576      | 0.889        | 0.048 (0.024)    | 0.453 (0.232)    | 1 (0.576) |     2.12 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2415 | 2024-05-02 | Natus Vincere | L   | 0.570      | -            | -                | -                | -         |    -0.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2437 | 2024-05-01 | BOSS          | W   | 0.563      | 0.889        | -                | 0.332 (0.166)    | 1 (0.563) |     1.24 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2650 | 2024-04-21 | BLEED         | L   | 0.496      | -            | -                | -                | -         |   -12.71 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2676 | 2024-04-20 | GamerLegion   | W   | 0.490      | 0.384        | 0.173 (0.033)    | -                | 0 (0.000) |     4.19 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2786 | 2024-04-18 | LEON          | W   | 0.476      | -            | -                | -                | 0 (0.000) |     0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2895 | 2024-04-13 | OG            | L   | 0.443      | -            | -                | -                | -         |   -11.42 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2904 | 2024-04-12 | FORZE         | W   | 0.438      | 0.684        | 0.058 (0.017)    | -                | -         |     1.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2975 | 2024-04-10 | Gods Reign    | W   | 0.425      | 0.684        | 0.040 (0.012)    | 0.203 (0.059)    | -         |     0.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3037 | 2024-04-09 | BetBoom       | L   | 0.417      | -            | -                | -                | -         |    -4.84 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3212 | 2024-04-03 | EYEBALLERS    | W   | 0.377      | 0.384        | -                | 0.509 (0.074)    | -         |     1.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3694 | 2024-03-09 | Spirit        | L   | 0.212      | -            | -                | -                | -         |    -0.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3725 | 2024-03-08 | GamerLegion   | W   | 0.204      | -            | -                | -                | -         |     0.32 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3855 | 2024-03-03 | Young Ninjas  | L   | 0.172      | -            | -                | -                | -         |    -5.18 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3915 | 2024-03-01 | AMKAL         | W   | 0.156      | 0.500        | 0.130 (0.010)    | -                | -         |     1.39 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3942 | 2024-02-28 | BLEED         | L   | 0.142      | -            | -                | -                | -         |    -3.95 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,055.10)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.871 | $2,000.00      | $1,741.67       |
| 2024-06-09 |      0.824 | $8,000.00      | $6,591.11       |
| 2024-06-02 |      0.778 | $6,000.00      | $4,668.33       |
| 2024-05-12 |      0.637 | $17,500.00     | $11,151.39      |
| 2024-04-14 |      0.450 | $35,000.00     | $15,764.58      |
| 2024-03-10 |      0.218 | $7,500.00      | $1,638.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
