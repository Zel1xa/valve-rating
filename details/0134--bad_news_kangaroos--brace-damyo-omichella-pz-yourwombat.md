### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  772.7<br />
<br />
Final Rank Value (772.7) = Starting Rank Value (775.1) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.1
- 400 + ( ( 0.183 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 775.1


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
|           35 |       51 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.42 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      476 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.19 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      480 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      657 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.133 (0.044)    | 0 (0.000) |    10.72 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      661 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.20 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      775 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.50 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      777 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |     9.56 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1403 | 2024-06-07 | Mindfreak   | L   | 0.799      | -            | -                | -                | -         |   -14.90 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1472 | 2024-06-06 | Rooster     | L   | 0.793      | -            | -                | -                | -         |   -11.96 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1875 | 2024-05-22 | KZG         | W   | 0.693      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     6.66 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1880 | 2024-05-22 | KZG         | W   | 0.693      | 0.333        | 0.005 (0.001)    | 0.109 (0.025)    | 0 (0.000) |     7.02 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2133 | 2024-05-15 | Arcade      | W   | 0.647      | 0.333        | 0.002 (0.001)    | 0.133 (0.029)    | 0 (0.000) |     5.74 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2138 | 2024-05-15 | Arcade      | W   | 0.646      | 0.333        | 0.002 (0.001)    | 0.133 (0.029)    | -         |     6.01 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2411 | 2024-05-03 | FURIA       | L   | 0.568      | -            | -                | -                | -         |    -0.16 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2458 | 2024-05-01 | ENCE        | L   | 0.555      | -            | -                | -                | -         |    -0.55 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2490 | 2024-04-30 | MOUZ        | L   | 0.547      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2713 | 2024-04-20 | FlyQuest    | L   | 0.480      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2717 | 2024-04-19 | Rooster     | W   | 0.479      | 0.143        | 0.010 (0.001)    | -                | -         |     7.74 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2760 | 2024-04-19 | Mindfreak   | W   | 0.473      | -            | -                | -                | -         |     5.74 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2765 | 2024-04-18 | Rooster     | L   | 0.472      | -            | -                | -                | -         |    -7.24 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     3014 | 2024-04-10 | Rooster     | W   | 0.413      | 0.333        | 0.010 (0.001)    | 0.246 (0.034)    | -         |     6.69 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3021 | 2024-04-10 | Rooster     | L   | 0.413      | -            | -                | -                | -         |    -6.47 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3247 | 2024-04-03 | DXA         | W   | 0.367      | 0.333        | 0.002 (0.000)    | 0.222 (0.027)    | -         |     4.12 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3252 | 2024-04-03 | DXA         | W   | 0.366      | 0.333        | -                | 0.222 (0.027)    | -         |     4.25 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3375 | 2024-03-27 | Mindfreak   | L   | 0.320      | -            | -                | -                | -         |    -6.75 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3380 | 2024-03-27 | Mindfreak   | W   | 0.320      | 0.333        | 0.004 (0.000)    | -                | -         |     3.37 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3423 | 2024-03-23 | DXA         | W   | 0.293      | 0.315        | -                | 0.222 (0.020)    | 1 (0.293) |     3.51 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3426 | 2024-03-23 | Arcade      | W   | 0.292      | -            | -                | -                | 1 (0.292) |     3.42 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3484 | 2024-03-20 | Canon Event | W   | 0.273      | -            | -                | -                | -         |     1.56 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3485 | 2024-03-20 | Canon Event | W   | 0.273      | -            | -                | -                | -         |     1.58 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3555 | 2024-03-15 | Gods Reign  | L   | 0.246      | -            | -                | -                | -         |    -3.95 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3576 | 2024-03-14 | GRDX        | W   | 0.239      | -            | -                | -                | 1 (0.239) |     1.54 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3609 | 2024-03-14 | Aurora      | L   | 0.233      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3822 | 2024-03-06 | Vantage     | W   | 0.180      | -            | -                | -                | -         |     1.86 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3824 | 2024-03-06 | Vantage     | W   | 0.180      | -            | -                | -                | -         |     1.89 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,256.80)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.812 | $1,050.00      | $852.83         |
| 2024-05-12 |      0.628 | $3,500.00      | $2,198.19       |
| 2024-03-23 |      0.293 | $3,308.00      | $969.66         |
| 2024-03-16 |      0.247 | $5,000.00      | $1,236.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
