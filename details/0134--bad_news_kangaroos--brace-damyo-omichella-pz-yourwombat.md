### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [134](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.0<br />
<br />
Final Rank Value (773.0) = Starting Rank Value (775.5) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.5
- 400 + ( ( 0.183 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 775.5


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
|           35 |       55 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.41 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      480 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.18 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      484 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      661 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    10.72 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      665 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.20 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      779 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.50 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      781 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |     9.56 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1407 | 2024-06-07 | Mindfreak   | L   | 0.799      | -            | -                | -                | -         |   -14.90 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1476 | 2024-06-06 | Rooster     | L   | 0.792      | -            | -                | -                | -         |   -11.96 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1879 | 2024-05-22 | KZG         | W   | 0.693      | 0.333        | 0.005 (0.001)    | 0.106 (0.025)    | 0 (0.000) |     6.65 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1884 | 2024-05-22 | KZG         | W   | 0.693      | 0.333        | 0.005 (0.001)    | 0.106 (0.025)    | 0 (0.000) |     7.01 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2137 | 2024-05-15 | Arcade      | W   | 0.646      | 0.333        | 0.002 (0.001)    | 0.130 (0.028)    | 0 (0.000) |     5.74 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2142 | 2024-05-15 | Arcade      | W   | 0.646      | 0.333        | 0.002 (0.001)    | 0.130 (0.028)    | -         |     6.01 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2415 | 2024-05-03 | FURIA       | L   | 0.568      | -            | -                | -                | -         |    -0.16 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2462 | 2024-05-01 | ENCE        | L   | 0.554      | -            | -                | -                | -         |    -0.54 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2494 | 2024-04-30 | MOUZ        | L   | 0.547      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2717 | 2024-04-20 | FlyQuest    | L   | 0.480      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2721 | 2024-04-19 | Rooster     | W   | 0.479      | 0.143        | 0.010 (0.001)    | -                | -         |     7.73 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2764 | 2024-04-19 | Mindfreak   | W   | 0.473      | -            | -                | -                | -         |     5.74 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2769 | 2024-04-18 | Rooster     | L   | 0.472      | -            | -                | -                | -         |    -7.24 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     3018 | 2024-04-10 | Rooster     | W   | 0.413      | 0.333        | 0.010 (0.001)    | 0.241 (0.033)    | -         |     6.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     3025 | 2024-04-10 | Rooster     | L   | 0.413      | -            | -                | -                | -         |    -6.46 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3251 | 2024-04-03 | DXA         | W   | 0.366      | 0.333        | 0.002 (0.000)    | 0.217 (0.026)    | -         |     4.12 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3256 | 2024-04-03 | DXA         | W   | 0.366      | 0.333        | -                | 0.217 (0.026)    | -         |     4.25 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3379 | 2024-03-27 | Mindfreak   | L   | 0.320      | -            | -                | -                | -         |    -6.75 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3384 | 2024-03-27 | Mindfreak   | W   | 0.320      | 0.333        | 0.004 (0.000)    | -                | -         |     3.37 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3427 | 2024-03-23 | DXA         | W   | 0.293      | 0.315        | -                | 0.217 (0.020)    | 1 (0.293) |     3.50 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3430 | 2024-03-23 | Arcade      | W   | 0.292      | -            | -                | -                | 1 (0.292) |     3.42 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3488 | 2024-03-20 | Canon Event | W   | 0.272      | -            | -                | -                | -         |     1.56 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3489 | 2024-03-20 | Canon Event | W   | 0.272      | -            | -                | -                | -         |     1.58 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3559 | 2024-03-15 | Gods Reign  | L   | 0.245      | -            | -                | -                | -         |    -3.95 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3580 | 2024-03-14 | GRDX        | W   | 0.239      | -            | -                | -                | 1 (0.239) |     1.54 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3613 | 2024-03-14 | Aurora      | L   | 0.232      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3826 | 2024-03-06 | Vantage     | W   | 0.180      | -            | -                | -                | -         |     1.86 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3828 | 2024-03-06 | Vantage     | W   | 0.180      | -            | -                | -                | -         |     1.88 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,253.22)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.812 | $1,050.00      | $852.54         |
| 2024-05-12 |      0.628 | $3,500.00      | $2,197.22       |
| 2024-03-23 |      0.293 | $3,308.00      | $968.74         |
| 2024-03-16 |      0.247 | $5,000.00      | $1,234.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
