### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.4<br />
<br />
Final Rank Value (773.4) = Starting Rank Value (776.0) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.096[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.0
- 400 + ( ( 0.183 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 776.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |       44 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.41 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      469 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      473 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.28 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      650 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    10.69 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      654 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.23 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      768 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.55 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      770 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     9.52 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1396 | 2024-06-07 | Mindfreak   | L   | 0.804      | -            | -                | -                | -         |   -15.00 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1465 | 2024-06-06 | Rooster     | L   | 0.797      | -            | -                | -                | -         |   -12.04 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1868 | 2024-05-22 | KZG         | W   | 0.698      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     6.67 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1873 | 2024-05-22 | KZG         | W   | 0.698      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     7.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2126 | 2024-05-15 | Arcade      | W   | 0.651      | 0.333        | 0.002 (0.001)    | 0.134 (0.029)    | 0 (0.000) |     5.76 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2131 | 2024-05-15 | Arcade      | W   | 0.651      | 0.333        | 0.002 (0.001)    | 0.134 (0.029)    | -         |     6.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2404 | 2024-05-03 | FURIA       | L   | 0.573      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2451 | 2024-05-01 | ENCE        | L   | 0.559      | -            | -                | -                | -         |    -0.56 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2483 | 2024-04-30 | MOUZ        | L   | 0.552      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2706 | 2024-04-20 | FlyQuest    | L   | 0.485      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2710 | 2024-04-19 | Rooster     | W   | 0.484      | 0.143        | 0.010 (0.001)    | -                | -         |     7.81 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2753 | 2024-04-19 | Mindfreak   | W   | 0.478      | -            | -                | -                | -         |     5.78 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2758 | 2024-04-18 | Rooster     | L   | 0.477      | -            | -                | -                | -         |    -7.32 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     3007 | 2024-04-10 | Rooster     | W   | 0.418      | 0.333        | 0.010 (0.001)    | 0.247 (0.034)    | -         |     6.76 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3014 | 2024-04-10 | Rooster     | L   | 0.418      | -            | -                | -                | -         |    -6.55 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3240 | 2024-04-03 | DXA         | W   | 0.371      | 0.333        | 0.002 (0.000)    | 0.222 (0.028)    | -         |     4.16 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3245 | 2024-04-03 | DXA         | W   | 0.371      | 0.333        | -                | 0.222 (0.028)    | -         |     4.29 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3368 | 2024-03-27 | Mindfreak   | L   | 0.325      | -            | -                | -                | -         |    -6.87 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3373 | 2024-03-27 | Mindfreak   | W   | 0.325      | 0.333        | 0.004 (0.000)    | -                | -         |     3.41 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3416 | 2024-03-23 | DXA         | W   | 0.298      | 0.315        | -                | 0.222 (0.021)    | 1 (0.298) |     3.55 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3419 | 2024-03-23 | Arcade      | W   | 0.297      | -            | -                | -                | 1 (0.297) |     3.47 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3477 | 2024-03-20 | Canon Event | W   | 0.277      | -            | -                | -                | -         |     1.58 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3478 | 2024-03-20 | Canon Event | W   | 0.277      | -            | -                | -                | -         |     1.60 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3548 | 2024-03-15 | Gods Reign  | L   | 0.250      | -            | -                | -                | -         |    -4.03 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3569 | 2024-03-14 | GRDX        | W   | 0.244      | -            | -                | -                | 1 (0.244) |     1.56 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3602 | 2024-03-14 | Aurora      | L   | 0.237      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3815 | 2024-03-06 | Vantage     | W   | 0.185      | -            | -                | -                | -         |     1.90 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3817 | 2024-03-06 | Vantage     | W   | 0.185      | -            | -                | -                | -         |     1.93 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,317.51)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.817 | $1,050.00      | $857.79         |
| 2024-05-12 |      0.633 | $3,500.00      | $2,214.72       |
| 2024-03-23 |      0.298 | $3,308.00      | $985.28         |
| 2024-03-16 |      0.252 | $5,000.00      | $1,259.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
