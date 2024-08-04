### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  774.0<br />
<br />
Final Rank Value (774.0) = Starting Rank Value (777.0) + Head To Head Adjustments (-2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.098[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.0
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 777.0


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
|           35 |       19 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.62 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      444 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.17 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      448 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      625 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    10.65 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      629 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.28 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      743 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.61 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      745 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |     9.45 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1371 | 2024-06-07 | Mindfreak   | L   | 0.811      | -            | -                | -                | -         |   -15.15 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1440 | 2024-06-06 | Rooster     | L   | 0.804      | -            | -                | -                | -         |   -12.15 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1843 | 2024-05-22 | KZG         | W   | 0.705      | 0.333        | 0.005 (0.001)    | 0.111 (0.026)    | 0 (0.000) |     6.68 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1848 | 2024-05-22 | KZG         | W   | 0.705      | 0.333        | 0.005 (0.001)    | 0.111 (0.026)    | 0 (0.000) |     7.05 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2101 | 2024-05-15 | Arcade      | W   | 0.658      | 0.333        | 0.002 (0.001)    | 0.137 (0.030)    | 0 (0.000) |     5.78 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2106 | 2024-05-15 | Arcade      | W   | 0.658      | 0.333        | 0.002 (0.001)    | 0.137 (0.030)    | -         |     6.06 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2379 | 2024-05-03 | FURIA       | L   | 0.579      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2426 | 2024-05-01 | ENCE        | L   | 0.566      | -            | -                | -                | -         |    -0.60 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2458 | 2024-04-30 | MOUZ        | L   | 0.559      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2681 | 2024-04-20 | FlyQuest    | L   | 0.492      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2685 | 2024-04-19 | Rooster     | W   | 0.491      | 0.143        | 0.010 (0.001)    | -                | -         |     7.91 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2728 | 2024-04-19 | Mindfreak   | W   | 0.485      | -            | -                | -                | -         |     5.85 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2733 | 2024-04-18 | Rooster     | L   | 0.484      | -            | -                | -                | -         |    -7.43 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     2982 | 2024-04-10 | Rooster     | W   | 0.425      | 0.333        | 0.010 (0.001)    | 0.251 (0.036)    | -         |     6.86 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     2989 | 2024-04-10 | Rooster     | L   | 0.425      | -            | -                | -                | -         |    -6.66 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3215 | 2024-04-03 | DXA         | W   | 0.378      | 0.333        | 0.002 (0.000)    | 0.226 (0.029)    | -         |     4.21 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3220 | 2024-04-03 | DXA         | W   | 0.378      | 0.333        | -                | 0.226 (0.029)    | -         |     4.34 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3343 | 2024-03-27 | Mindfreak   | L   | 0.332      | -            | -                | -                | -         |    -7.03 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3348 | 2024-03-27 | Mindfreak   | W   | 0.332      | 0.333        | 0.004 (0.000)    | -                | -         |     3.46 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3391 | 2024-03-23 | DXA         | W   | 0.305      | 0.315        | -                | 0.226 (0.022)    | 1 (0.305) |     3.62 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3394 | 2024-03-23 | Arcade      | W   | 0.304      | -            | -                | -                | 1 (0.304) |     3.54 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3452 | 2024-03-20 | Canon Event | W   | 0.284      | -            | -                | -                | -         |     1.60 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3453 | 2024-03-20 | Canon Event | W   | 0.284      | -            | -                | -                | -         |     1.63 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3523 | 2024-03-15 | Gods Reign  | L   | 0.257      | -            | -                | -                | -         |    -4.14 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3544 | 2024-03-14 | GRDX        | W   | 0.251      | -            | -                | -                | 1 (0.251) |     1.60 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3577 | 2024-03-14 | Aurora      | L   | 0.244      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3790 | 2024-03-06 | Vantage     | W   | 0.192      | -            | -                | -                | -         |     1.96 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3792 | 2024-03-06 | Vantage     | W   | 0.192      | -            | -                | -                | -         |     1.99 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,405.32)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.824 | $1,050.00      | $864.96         |
| 2024-05-12 |      0.640 | $3,500.00      | $2,238.62       |
| 2024-03-23 |      0.305 | $3,308.00      | $1,007.87       |
| 2024-03-16 |      0.259 | $5,000.00      | $1,293.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
