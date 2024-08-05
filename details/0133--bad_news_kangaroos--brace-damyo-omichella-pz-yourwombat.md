### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: BRACE, damyo, Omichella, pz, yourwombat<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  773.7<br />
<br />
Final Rank Value (773.7) = Starting Rank Value (776.5) + Head To Head Adjustments (-2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.098[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.5
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 776.5


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
|           35 |       23 | 2024-08-04 | Lynn Vision | L   | 1.000      | -            | -                | -                | -         |    -5.63 | BRACE, damyo, Omichella, pz, yourwombat      |
|           34 |      448 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.17 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           33 |      452 | 2024-07-23 | MANTRA      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           32 |      629 | 2024-07-18 | Arcade      | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    10.67 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           31 |      633 | 2024-07-18 | Arcade      | L   | 1.000      | -            | -                | -                | -         |   -21.26 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           30 |      747 | 2024-07-16 | DXA         | L   | 1.000      | -            | -                | -                | -         |   -21.59 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           29 |      749 | 2024-07-16 | DXA         | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |     9.48 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           28 |     1375 | 2024-06-07 | Mindfreak   | L   | 0.809      | -            | -                | -                | -         |   -15.10 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           27 |     1444 | 2024-06-06 | Rooster     | L   | 0.802      | -            | -                | -                | -         |   -12.11 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           26 |     1847 | 2024-05-22 | KZG         | W   | 0.702      | 0.333        | 0.005 (0.001)    | 0.111 (0.026)    | 0 (0.000) |     6.68 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           25 |     1852 | 2024-05-22 | KZG         | W   | 0.702      | 0.333        | 0.005 (0.001)    | 0.111 (0.026)    | 0 (0.000) |     7.04 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           24 |     2105 | 2024-05-15 | Arcade      | W   | 0.656      | 0.333        | 0.002 (0.001)    | 0.136 (0.030)    | 0 (0.000) |     5.77 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           23 |     2110 | 2024-05-15 | Arcade      | W   | 0.656      | 0.333        | 0.002 (0.001)    | 0.136 (0.030)    | -         |     6.05 | ADDICT, BRACE, damyo, hazr, yourwombat       |
|           22 |     2383 | 2024-05-03 | FURIA       | L   | 0.577      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz               |
|           21 |     2430 | 2024-05-01 | ENCE        | L   | 0.564      | -            | -                | -                | -         |    -0.58 | ADDICT, BRACE, damyo, hazr, pz               |
|           20 |     2462 | 2024-04-30 | MOUZ        | L   | 0.556      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, damyo, hazr, pz               |
|           19 |     2685 | 2024-04-20 | FlyQuest    | L   | 0.489      | -            | -                | -                | -         |    -1.68 | ADDICT, BRACE, damyo, hazr, pz               |
|           18 |     2689 | 2024-04-19 | Rooster     | W   | 0.488      | 0.143        | 0.010 (0.001)    | -                | -         |     7.88 | ADDICT, BRACE, damyo, hazr, pz               |
|           17 |     2732 | 2024-04-19 | Mindfreak   | W   | 0.483      | -            | -                | -                | -         |     5.83 | ADDICT, BRACE, damyo, hazr, pz               |
|           16 |     2737 | 2024-04-18 | Rooster     | L   | 0.482      | -            | -                | -                | -         |    -7.39 | ADDICT, BRACE, damyo, hazr, pz               |
|           15 |     2986 | 2024-04-10 | Rooster     | W   | 0.422      | 0.333        | 0.010 (0.001)    | 0.251 (0.035)    | -         |     6.82 | ADDICT, BRACE, damyo, hazr, pz               |
|           14 |     2993 | 2024-04-10 | Rooster     | L   | 0.422      | -            | -                | -                | -         |    -6.62 | ADDICT, BRACE, damyo, hazr, pz               |
|           13 |     3219 | 2024-04-03 | DXA         | W   | 0.376      | 0.333        | 0.002 (0.000)    | 0.226 (0.028)    | -         |     4.19 | ADDICT, BRACE, damyo, hazr, pz               |
|           12 |     3224 | 2024-04-03 | DXA         | W   | 0.376      | 0.333        | -                | 0.226 (0.028)    | -         |     4.32 | ADDICT, BRACE, damyo, hazr, pz               |
|           11 |     3347 | 2024-03-27 | Mindfreak   | L   | 0.329      | -            | -                | -                | -         |    -6.97 | ADDICT, BRACE, damyo, hazr, pz               |
|           10 |     3352 | 2024-03-27 | Mindfreak   | W   | 0.329      | 0.333        | 0.004 (0.000)    | -                | -         |     3.45 | ADDICT, BRACE, damyo, hazr, pz               |
|            9 |     3395 | 2024-03-23 | DXA         | W   | 0.302      | 0.315        | -                | 0.226 (0.022)    | 1 (0.302) |     3.59 | ADDICT, BRACE, damyo, hazr, pz               |
|            8 |     3398 | 2024-03-23 | Arcade      | W   | 0.302      | -            | -                | -                | 1 (0.302) |     3.52 | ADDICT, BRACE, damyo, hazr, pz               |
|            7 |     3456 | 2024-03-20 | Canon Event | W   | 0.282      | -            | -                | -                | -         |     1.59 | ADDICT, BRACE, damyo, hazr, pz               |
|            6 |     3457 | 2024-03-20 | Canon Event | W   | 0.282      | -            | -                | -                | -         |     1.62 | ADDICT, BRACE, damyo, hazr, pz               |
|            5 |     3527 | 2024-03-15 | Gods Reign  | L   | 0.255      | -            | -                | -                | -         |    -4.10 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            4 |     3548 | 2024-03-14 | GRDX        | W   | 0.248      | -            | -                | -                | 1 (0.248) |     1.59 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            3 |     3581 | 2024-03-14 | Aurora      | L   | 0.242      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat          |
|            2 |     3794 | 2024-03-06 | Vantage     | W   | 0.189      | -            | -                | -                | -         |     1.94 | ADDICT, BRACE, damyo, hazr, pz               |
|            1 |     3796 | 2024-03-06 | Vantage     | W   | 0.189      | -            | -                | -                | -         |     1.97 | ADDICT, BRACE, damyo, hazr, pz               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,374.66)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.821 | $1,050.00      | $862.46         |
| 2024-05-12 |      0.637 | $3,500.00      | $2,230.28       |
| 2024-03-23 |      0.302 | $3,308.00      | $999.98         |
| 2024-03-16 |      0.256 | $5,000.00      | $1,281.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
