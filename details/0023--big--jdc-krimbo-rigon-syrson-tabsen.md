### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1314.5<br />
<br />
Final Rank Value (1314.5) = Starting Rank Value (1318.7) + Head To Head Adjustments (-4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.577[<sup>2</sup>](#table1)

The average of these factors is 0.449<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1318.7
- 400 + ( ( 0.449 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1318.7


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
|           34 |       28 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.97 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |       52 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.496 (0.288)    | 0.335 (0.195)    | 1 (1.000) |    27.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      105 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |      967 | 2024-06-15 | Permitta      | L   | 0.871      | -            | -                | -                | -         |   -24.40 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |      988 | 2024-06-14 | Space         | W   | 0.866      | 0.435        | -                | 0.420 (0.158)    | 0 (0.000) |     2.44 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1296 | 2024-06-06 | fnatic        | L   | 0.814      | -            | -                | -                | -         |   -12.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1336 | 2024-06-06 | Eternal Fire  | L   | 0.812      | -            | -                | -                | -         |    -3.83 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1360 | 2024-06-05 | BetBoom       | L   | 0.807      | -            | -                | -                | -         |   -11.35 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1381 | 2024-06-05 | Complexity    | L   | 0.806      | -            | -                | -                | -         |    -3.60 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1392 | 2024-06-05 | FURIA         | W   | 0.805      | 0.715        | 0.284 (0.163)    | 0.508 (0.293)    | 1 (0.805) |    19.86 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1571 | 2024-05-29 | HEROIC        | L   | 0.762      | -            | -                | -                | -         |    -4.84 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1582 | 2024-05-29 | Virtus.pro    | W   | 0.760      | 0.624        | 0.496 (0.235)    | 0.335 (0.159)    | 1 (0.760) |    20.80 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1598 | 2024-05-28 | FlyQuest      | W   | 0.754      | 0.624        | 0.104 (0.049)    | 0.302 (0.142)    | 1 (0.754) |     8.90 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1622 | 2024-05-27 | Natus Vincere | L   | 0.748      | -            | -                | -                | -         |    -0.60 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1818 | 2024-05-20 | MIBR          | L   | 0.699      | -            | -                | -                | -         |    -7.01 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1832 | 2024-05-19 | Astralis      | L   | 0.694      | -            | -                | -                | -         |    -2.00 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2208 | 2024-05-07 | G2            | L   | 0.613      | -            | -                | -                | -         |    -0.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2272 | 2024-05-03 | HEROIC        | W   | 0.587      | 0.889        | 0.230 (0.120)    | 0.388 (0.202)    | 1 (0.587) |    15.09 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2282 | 2024-05-03 | PERA          | W   | 0.585      | 0.889        | 0.048 (0.025)    | 0.468 (0.243)    | 1 (0.585) |     2.07 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2309 | 2024-05-02 | Natus Vincere | L   | 0.579      | -            | -                | -                | -         |    -0.38 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2331 | 2024-05-01 | BOSS          | W   | 0.572      | 0.889        | -                | 0.344 (0.175)    | 1 (0.572) |     1.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2543 | 2024-04-21 | BLEED         | L   | 0.505      | -            | -                | -                | -         |   -13.01 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2569 | 2024-04-20 | GamerLegion   | W   | 0.499      | 0.384        | 0.174 (0.033)    | -                | 0 (0.000) |     4.15 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2679 | 2024-04-18 | LEON          | W   | 0.485      | -            | -                | -                | 0 (0.000) |     0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2788 | 2024-04-13 | OG            | L   | 0.452      | -            | -                | -                | -         |   -11.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2797 | 2024-04-12 | FORZE         | W   | 0.446      | 0.684        | 0.059 (0.018)    | -                | -         |     1.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2868 | 2024-04-10 | Gods Reign    | W   | 0.433      | 0.684        | 0.041 (0.012)    | 0.211 (0.063)    | -         |     0.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     2930 | 2024-04-09 | BetBoom       | L   | 0.426      | -            | -                | -                | -         |    -5.03 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3105 | 2024-04-03 | EYEBALLERS    | W   | 0.386      | 0.384        | -                | 0.528 (0.078)    | -         |     1.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3579 | 2024-03-09 | Spirit        | L   | 0.221      | -            | -                | -                | -         |    -0.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3610 | 2024-03-08 | GamerLegion   | W   | 0.213      | -            | -                | -                | -         |     0.34 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3740 | 2024-03-03 | Young Ninjas  | L   | 0.181      | -            | -                | -                | -         |    -5.45 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3800 | 2024-03-01 | AMKAL         | W   | 0.165      | 0.500        | 0.130 (0.011)    | -                | -         |     1.46 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3827 | 2024-02-28 | BLEED         | L   | 0.151      | -            | -                | -                | -         |    -4.21 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,734.18)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.880 | $2,000.00      | $1,759.54       |
| 2024-06-09 |      0.833 | $8,000.00      | $6,662.59       |
| 2024-06-02 |      0.787 | $6,000.00      | $4,721.94       |
| 2024-05-12 |      0.646 | $17,500.00     | $11,307.75      |
| 2024-04-14 |      0.459 | $35,000.00     | $16,077.31      |
| 2024-03-10 |      0.227 | $7,500.00      | $1,705.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
