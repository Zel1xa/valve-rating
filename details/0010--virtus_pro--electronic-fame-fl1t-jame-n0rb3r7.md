### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1648.9<br />
<br />
Final Rank Value (1648.9) = Starting Rank Value (1701.5) + Head To Head Adjustments (-52.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.640[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.846[<sup>2</sup>](#table1)

The average of these factors is 0.635<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1701.5
- 400 + ( ( 0.635 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1701.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      130 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.82 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      182 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      551 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.80 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      593 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.648 (0.648)    | 0.376 (0.376)    | 1 (1.000) |    22.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      695 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.373 (0.373)    | 1 (1.000) |    13.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1047 | 2024-06-15 | Natus Vincere | L   | 0.860      | -            | -                | -                | -         |    -5.15 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1084 | 2024-06-14 | Astralis      | W   | 0.853      | 0.729        | 0.389 (0.242)    | 0.413 (0.257)    | 1 (0.853) |    15.27 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1121 | 2024-06-13 | Spirit        | L   | 0.847      | -            | -                | -                | -         |    -5.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1161 | 2024-06-12 | Vitality      | W   | 0.839      | 0.729        | 0.648 (0.396)    | 0.376 (0.230)    | 1 (0.839) |    20.02 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1707 | 2024-05-29 | BIG           | L   | 0.746      | -            | -                | -                | -         |   -20.55 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1722 | 2024-05-28 | FaZe          | L   | 0.740      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1743 | 2024-05-27 | HEROIC        | W   | 0.734      | 0.624        | 0.225 (0.103)    | 0.365 (0.167)    | 1 (0.734) |     8.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2035 | 2024-05-17 | Falcons       | L   | 0.665      | -            | -                | -                | -         |   -17.00 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2074 | 2024-05-16 | MOUZ          | L   | 0.658      | -            | -                | -                | -         |    -5.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2173 | 2024-05-14 | Falcons       | W   | 0.646      | 0.769        | 0.221 (0.110)    | -                | 1 (0.646) |     3.48 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2295 | 2024-05-09 | Complexity    | L   | 0.612      | -            | -                | -                | -         |   -10.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2314 | 2024-05-08 | The MongolZ   | W   | 0.607      | 0.889        | 1.000 (0.539)    | 0.710 (0.383)    | 1 (0.607) |    14.82 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2330 | 2024-05-07 | GamerLegion   | W   | 0.600      | 0.889        | 0.173 (0.092)    | -                | 1 (0.600) |     0.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2518 | 2024-04-28 | SAW           | W   | 0.539      | 0.889        | -                | 0.530 (0.254)    | 1 (0.539) |     1.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2549 | 2024-04-27 | fnatic        | W   | 0.531      | 0.889        | 0.371 (0.175)    | 0.697 (0.329)    | 1 (0.531) |     5.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2592 | 2024-04-25 | FaZe          | L   | 0.520      | -            | -                | -                | -         |    -7.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2615 | 2024-04-24 | SAW           | W   | 0.512      | 0.889        | -                | 0.530 (0.241)    | -         |     0.87 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2638 | 2024-04-23 | fnatic        | L   | 0.505      | -            | -                | -                | -         |   -11.33 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2934 | 2024-04-12 | G2            | L   | 0.430      | -            | -                | -                | -         |    -2.25 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     3018 | 2024-04-10 | Astralis      | L   | 0.417      | -            | -                | -                | -         |    -5.95 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3070 | 2024-04-08 | FlyQuest      | W   | 0.410      | -            | -                | -                | -         |     0.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3100 | 2024-04-08 | Wildcard      | W   | 0.404      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3400 | 2024-03-24 | G2            | L   | 0.305      | -            | -                | -                | -         |    -1.58 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3414 | 2024-03-23 | Eternal Fire  | L   | 0.298      | -            | -                | -                | -         |    -4.63 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3431 | 2024-03-22 | HEROIC        | W   | 0.292      | -            | -                | -                | -         |     2.96 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3445 | 2024-03-21 | paiN          | W   | 0.287      | 1.000        | 0.325 (0.093)    | 0.856 (0.245)    | -         |     1.48 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3455 | 2024-03-21 | Imperial      | L   | 0.285      | -            | -                | -                | -         |    -8.29 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3657 | 2024-03-12 | HEROIC        | W   | 0.227      | -            | -                | -                | -         |     2.20 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3673 | 2024-03-11 | Apeks         | W   | 0.220      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3684 | 2024-03-11 | B8            | W   | 0.219      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4266 | 2024-02-15 | Natus Vincere | W   | 0.053      | -            | -                | -                | -         |     1.36 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4298 | 2024-02-14 | fnatic        | W   | 0.047      | -            | -                | -                | -         |     0.46 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4317 | 2024-02-14 | SAW           | W   | 0.045      | -            | -                | -                | -         |     0.07 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($160,226.76)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.865 | $40,000.00     | $34,616.67      |
| 2024-06-02 |      0.773 | $5,000.00      | $3,865.97       |
| 2024-05-12 |      0.632 | $32,000.00     | $20,235.56      |
| 2024-04-14 |      0.444 | $10,000.00     | $4,444.68       |
| 2024-03-31 |      0.353 | $20,000.00     | $7,063.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
