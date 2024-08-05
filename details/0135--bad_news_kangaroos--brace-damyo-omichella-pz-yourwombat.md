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
Final Rank Value (773.4) = Starting Rank Value (775.9) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.096[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.9
- 400 + ( ( 0.183 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 775.9


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
|           35 |       45 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.41 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      470 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      474 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.28 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      651 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    10.70 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      655 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.23 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      769 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.54 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      771 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     9.52 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1397 | 2024-06-07 | Mindfreak   | L   | 0.804      | -            | -                | -                | -         |   -14.99 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1466 | 2024-06-06 | Rooster     | L   | 0.797      | -            | -                | -                | -         |   -12.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1869 | 2024-05-22 | KZG         | W   | 0.698      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     6.67 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1874 | 2024-05-22 | KZG         | W   | 0.697      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     7.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2127 | 2024-05-15 | Arcade      | W   | 0.651      | 0.333        | 0.002 (0.001)    | 0.134 (0.029)    | 0 (0.000) |     5.75 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2132 | 2024-05-15 | Arcade      | W   | 0.651      | 0.333        | 0.002 (0.001)    | 0.134 (0.029)    | -         |     6.03 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2405 | 2024-05-03 | FURIA       | L   | 0.572      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2452 | 2024-05-01 | ENCE        | L   | 0.559      | -            | -                | -                | -         |    -0.56 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2484 | 2024-04-30 | MOUZ        | L   | 0.551      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2707 | 2024-04-20 | FlyQuest    | L   | 0.484      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2711 | 2024-04-19 | Rooster     | W   | 0.483      | 0.143        | 0.010 (0.001)    | -                | -         |     7.80 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2754 | 2024-04-19 | Mindfreak   | W   | 0.478      | -            | -                | -                | -         |     5.78 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2759 | 2024-04-18 | Rooster     | L   | 0.477      | -            | -                | -                | -         |    -7.32 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     3008 | 2024-04-10 | Rooster     | W   | 0.418      | 0.333        | 0.010 (0.001)    | 0.247 (0.034)    | -         |     6.75 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3015 | 2024-04-10 | Rooster     | L   | 0.417      | -            | -                | -                | -         |    -6.54 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3241 | 2024-04-03 | DXA         | W   | 0.371      | 0.333        | 0.002 (0.000)    | 0.222 (0.027)    | -         |     4.16 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3246 | 2024-04-03 | DXA         | W   | 0.371      | 0.333        | -                | 0.222 (0.027)    | -         |     4.28 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3369 | 2024-03-27 | Mindfreak   | L   | 0.324      | -            | -                | -                | -         |    -6.86 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3374 | 2024-03-27 | Mindfreak   | W   | 0.324      | 0.333        | 0.004 (0.000)    | -                | -         |     3.41 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3417 | 2024-03-23 | DXA         | W   | 0.297      | 0.315        | -                | 0.222 (0.021)    | 1 (0.297) |     3.55 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3420 | 2024-03-23 | Arcade      | W   | 0.297      | -            | -                | -                | 1 (0.297) |     3.46 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3478 | 2024-03-20 | Canon Event | W   | 0.277      | -            | -                | -                | -         |     1.57 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3479 | 2024-03-20 | Canon Event | W   | 0.277      | -            | -                | -                | -         |     1.60 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3549 | 2024-03-15 | Gods Reign  | L   | 0.250      | -            | -                | -                | -         |    -4.02 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3570 | 2024-03-14 | GRDX        | W   | 0.243      | -            | -                | -                | 1 (0.243) |     1.56 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3603 | 2024-03-14 | Aurora      | L   | 0.237      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3816 | 2024-03-06 | Vantage     | W   | 0.185      | -            | -                | -                | -         |     1.90 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3818 | 2024-03-06 | Vantage     | W   | 0.184      | -            | -                | -                | -         |     1.93 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,312.16)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.817 | $1,050.00      | $857.35         |
| 2024-05-12 |      0.632 | $3,500.00      | $2,213.26       |
| 2024-03-23 |      0.297 | $3,308.00      | $983.90         |
| 2024-03-16 |      0.252 | $5,000.00      | $1,257.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
