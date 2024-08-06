### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1315.1<br />
<br />
Final Rank Value (1315.1) = Starting Rank Value (1310.7) + Head To Head Adjustments (4.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.571[<sup>2</sup>](#table1)

The average of these factors is 0.443<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1310.7
- 400 + ( ( 0.443 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1310.7


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
|           34 |      106 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.97 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |      143 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.498 (0.290)    | 0.309 (0.179)    | 1 (1.000) |    27.81 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      201 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1085 | 2024-06-15 | Permitta      | L   | 0.852      | -            | -                | -                | -         |   -23.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1113 | 2024-06-14 | Space         | W   | 0.847      | 0.435        | -                | 0.429 (0.158)    | 0 (0.000) |     2.28 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1432 | 2024-06-06 | fnatic        | L   | 0.795      | -            | -                | -                | -         |    -7.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1471 | 2024-06-06 | Eternal Fire  | L   | 0.793      | -            | -                | -                | -         |    -3.55 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1495 | 2024-06-05 | BetBoom       | L   | 0.788      | -            | -                | -                | -         |   -10.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1517 | 2024-06-05 | Complexity    | L   | 0.787      | -            | -                | -                | -         |    -3.35 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1527 | 2024-06-05 | FURIA         | W   | 0.786      | 0.715        | 0.284 (0.160)    | 0.469 (0.264)    | 1 (0.786) |    19.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1709 | 2024-05-29 | HEROIC        | L   | 0.743      | -            | -                | -                | -         |    -4.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1720 | 2024-05-29 | Virtus.pro    | W   | 0.741      | 0.624        | 0.498 (0.231)    | 0.309 (0.143)    | 1 (0.741) |    20.41 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1736 | 2024-05-28 | FlyQuest      | W   | 0.735      | 0.624        | 0.104 (0.048)    | 0.278 (0.127)    | 1 (0.735) |     8.67 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1760 | 2024-05-27 | Natus Vincere | L   | 0.729      | -            | -                | -                | -         |    -0.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1956 | 2024-05-20 | MIBR          | L   | 0.680      | -            | -                | -                | -         |    -6.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1971 | 2024-05-19 | Astralis      | L   | 0.675      | -            | -                | -                | -         |    -1.63 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2349 | 2024-05-07 | G2            | L   | 0.594      | -            | -                | -                | -         |    -0.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2413 | 2024-05-03 | HEROIC        | W   | 0.568      | 0.889        | 0.224 (0.113)    | 0.355 (0.179)    | 1 (0.568) |    14.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2423 | 2024-05-03 | PERA          | W   | 0.566      | 0.889        | 0.048 (0.024)    | 0.435 (0.219)    | 1 (0.566) |     2.09 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2450 | 2024-05-02 | Natus Vincere | L   | 0.560      | -            | -                | -                | -         |    -0.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2472 | 2024-05-01 | BOSS          | W   | 0.553      | 0.889        | -                | 0.319 (0.157)    | 1 (0.553) |     1.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2685 | 2024-04-21 | BLEED         | L   | 0.486      | -            | -                | -                | -         |   -12.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2711 | 2024-04-20 | GamerLegion   | W   | 0.480      | 0.384        | 0.173 (0.032)    | -                | 0 (0.000) |     4.06 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2821 | 2024-04-18 | LEON          | W   | 0.466      | -            | -                | -                | 0 (0.000) |     0.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2930 | 2024-04-13 | OG            | L   | 0.433      | -            | -                | -                | -         |   -11.20 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2939 | 2024-04-12 | FORZE         | W   | 0.428      | 0.684        | 0.057 (0.017)    | -                | -         |     1.53 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     3010 | 2024-04-10 | Gods Reign    | W   | 0.415      | 0.684        | 0.040 (0.011)    | 0.195 (0.055)    | -         |     0.70 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3072 | 2024-04-09 | BetBoom       | L   | 0.407      | -            | -                | -                | -         |    -4.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3247 | 2024-04-03 | EYEBALLERS    | W   | 0.367      | 0.384        | -                | 0.488 (0.069)    | -         |     1.11 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3729 | 2024-03-09 | Spirit        | L   | 0.202      | -            | -                | -                | -         |    -0.21 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3760 | 2024-03-08 | GamerLegion   | W   | 0.194      | -            | -                | -                | -         |     0.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3890 | 2024-03-03 | Young Ninjas  | L   | 0.162      | -            | -                | -                | -         |    -4.87 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3950 | 2024-03-01 | AMKAL         | W   | 0.146      | 0.500        | 0.130 (0.009)    | -                | -         |     1.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3977 | 2024-02-28 | BLEED         | L   | 0.133      | -            | -                | -                | -         |    -3.68 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($49,309.18)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.861 | $2,000.00      | $1,722.04       |
| 2024-06-09 |      0.814 | $8,000.00      | $6,512.59       |
| 2024-06-02 |      0.768 | $6,000.00      | $4,609.44       |
| 2024-05-12 |      0.627 | $17,500.00     | $10,979.63      |
| 2024-04-14 |      0.441 | $35,000.00     | $15,421.06      |
| 2024-03-10 |      0.209 | $7,500.00      | $1,564.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
