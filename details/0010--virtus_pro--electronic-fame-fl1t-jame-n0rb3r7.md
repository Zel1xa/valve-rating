### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1649.0<br />
<br />
Final Rank Value (1649.0) = Starting Rank Value (1701.6) + Head To Head Adjustments (-52.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.640[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.846[<sup>2</sup>](#table1)

The average of these factors is 0.635<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1701.6
- 400 + ( ( 0.635 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1701.6


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
|           38 |      129 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.83 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      181 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      550 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.80 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      592 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.648 (0.648)    | 0.376 (0.376)    | 1 (1.000) |    22.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      694 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.373 (0.373)    | 1 (1.000) |    13.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1046 | 2024-06-15 | Natus Vincere | L   | 0.861      | -            | -                | -                | -         |    -5.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1083 | 2024-06-14 | Astralis      | W   | 0.854      | 0.729        | 0.389 (0.242)    | 0.413 (0.257)    | 1 (0.854) |    15.28 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1120 | 2024-06-13 | Spirit        | L   | 0.847      | -            | -                | -                | -         |    -5.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1160 | 2024-06-12 | Vitality      | W   | 0.840      | 0.729        | 0.648 (0.396)    | 0.376 (0.230)    | 1 (0.840) |    20.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1706 | 2024-05-29 | BIG           | L   | 0.747      | -            | -                | -                | -         |   -20.57 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1721 | 2024-05-28 | FaZe          | L   | 0.741      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1742 | 2024-05-27 | HEROIC        | W   | 0.735      | 0.624        | 0.225 (0.103)    | 0.365 (0.167)    | 1 (0.735) |     8.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2034 | 2024-05-17 | Falcons       | L   | 0.665      | -            | -                | -                | -         |   -17.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2073 | 2024-05-16 | MOUZ          | L   | 0.658      | -            | -                | -                | -         |    -5.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2172 | 2024-05-14 | Falcons       | W   | 0.647      | 0.769        | 0.221 (0.110)    | -                | 1 (0.647) |     3.49 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2294 | 2024-05-09 | Complexity    | L   | 0.613      | -            | -                | -                | -         |   -10.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2313 | 2024-05-08 | The MongolZ   | W   | 0.607      | 0.889        | 1.000 (0.540)    | 0.710 (0.383)    | 1 (0.607) |    14.83 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2329 | 2024-05-07 | GamerLegion   | W   | 0.600      | 0.889        | 0.173 (0.092)    | -                | 1 (0.600) |     0.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2517 | 2024-04-28 | SAW           | W   | 0.539      | 0.889        | -                | 0.530 (0.254)    | 1 (0.539) |     1.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2548 | 2024-04-27 | fnatic        | W   | 0.532      | 0.889        | 0.371 (0.175)    | 0.697 (0.329)    | 1 (0.532) |     5.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2591 | 2024-04-25 | FaZe          | L   | 0.520      | -            | -                | -                | -         |    -7.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2614 | 2024-04-24 | SAW           | W   | 0.513      | 0.889        | -                | 0.530 (0.242)    | -         |     0.87 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2637 | 2024-04-23 | fnatic        | L   | 0.505      | -            | -                | -                | -         |   -11.34 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2933 | 2024-04-12 | G2            | L   | 0.431      | -            | -                | -                | -         |    -2.26 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     3017 | 2024-04-10 | Astralis      | L   | 0.418      | -            | -                | -                | -         |    -5.96 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3069 | 2024-04-08 | FlyQuest      | W   | 0.410      | -            | -                | -                | -         |     0.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3099 | 2024-04-08 | Wildcard      | W   | 0.404      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3399 | 2024-03-24 | G2            | L   | 0.306      | -            | -                | -                | -         |    -1.58 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3413 | 2024-03-23 | Eternal Fire  | L   | 0.299      | -            | -                | -                | -         |    -4.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3430 | 2024-03-22 | HEROIC        | W   | 0.292      | -            | -                | -                | -         |     2.97 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3444 | 2024-03-21 | paiN          | W   | 0.287      | 1.000        | 0.325 (0.093)    | 0.856 (0.246)    | -         |     1.48 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3454 | 2024-03-21 | Imperial      | L   | 0.286      | -            | -                | -                | -         |    -8.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3656 | 2024-03-12 | HEROIC        | W   | 0.227      | -            | -                | -                | -         |     2.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3672 | 2024-03-11 | Apeks         | W   | 0.221      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3683 | 2024-03-11 | B8            | W   | 0.219      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4265 | 2024-02-15 | Natus Vincere | W   | 0.053      | -            | -                | -                | -         |     1.37 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4297 | 2024-02-14 | fnatic        | W   | 0.047      | -            | -                | -                | -         |     0.46 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4316 | 2024-02-14 | SAW           | W   | 0.045      | -            | -                | -                | -         |     0.07 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($160,271.34)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.866 | $40,000.00     | $34,633.33      |
| 2024-06-02 |      0.774 | $5,000.00      | $3,868.06       |
| 2024-05-12 |      0.633 | $32,000.00     | $20,248.89      |
| 2024-04-14 |      0.445 | $10,000.00     | $4,448.84       |
| 2024-03-31 |      0.354 | $20,000.00     | $7,072.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
